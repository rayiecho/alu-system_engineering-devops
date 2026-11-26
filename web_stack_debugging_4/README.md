# Web stack debugging #4

| File | Description |
| ---- | ----------- |
| `0-the_sky_is_the_limit_not.pp` | Raises Nginx's open-file limit (ULIMIT in `/etc/default/nginx`) from 15 to 4096 and restarts Nginx, so ApacheBench gets 0 failed requests. |
