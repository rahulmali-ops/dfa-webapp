# Run DFA WebApp on your laptop (real localhost)

The cloud agent’s `http://127.0.0.1:8765` is **inside the remote VM**. Your browser’s `127.0.0.1` is your PC — they are different machines, so you get `ERR_CONNECTION_REFUSED (-102)`.

## 1. Download the zip
- From the tunnel: open `/dfa-webapp.zip` on the public app URL, or
- From Cursor Agent Store: `media/dfa-ui/dfa-webapp.zip`

## 2. Unzip, then in that folder run (Windows PowerShell / CMD)

```bat
python -m http.server 8765 --bind 127.0.0.1
```

If `python` is missing, try `py -m http.server 8765 --bind 127.0.0.1`.

## 3. Open on your PC

http://127.0.0.1:8765/

AMR page: http://127.0.0.1:8765/amr-requirements.html
