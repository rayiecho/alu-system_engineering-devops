# Load balancer

| File | Description |
| ---- | ----------- |
| `0-custom_http_response_header` | Configures Nginx (web-01, web-02) with an `X-Served-By` header set to the server's hostname. |
| `1-install_load_balancer` | Installs HAProxy on lb-01, sending traffic to web-01 and web-02 with roundrobin, manageable via init script. |
