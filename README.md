# letsencrypt-nginx-config
Auto-renewing Let's Encrypt nginx config, that forces SSL for "regular" content


After all the files are in place, run letsencrypt-auto from the location you installed it.
```
./letsencrypt-auto -c /etc/letsencrypt/cli.ini certonly
```

To add new domains, just add them to cli.ini, and re-run letsencrypt-auto as above.
