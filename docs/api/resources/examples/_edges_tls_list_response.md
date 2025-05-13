<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-13T10:10:13Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2x2L2KGAX8rYZtao5G01fl5LIDf",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2x2L2KGAX8rYZtao5G01fl5LIDf"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2x2L13qK116g7uyOkakWofwVlXR",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2x2L13qK116g7uyOkakWofwVlXR"
        },
        "enabled": true
      },
      "created_at": "2025-05-13T10:10:02Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2x2L0zSTBQHEq0zLCgyvUzz4sAW",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2x2L0zSTBQHEq0zLCgyvUzz4sAW"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
