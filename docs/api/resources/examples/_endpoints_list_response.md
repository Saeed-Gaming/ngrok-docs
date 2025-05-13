<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-13T10:10:07Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2x2L0ywJnC1KhD1GHncibFImKg4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2x2L0ywJnC1KhD1GHncibFImKg4"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2x2L1bpY6yBk9Uhi6pVmehffda5",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-13T10:10:07Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2x2L1bpY6yBk9Uhi6pVmehffda5",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-13T10:10:05Z",
      "hostport": "066001282e82.ngrok.paid:443",
      "id": "ep_2x2L1MpLuHqWRQq7fp95X2a0BjF",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2x2KyqSjZ6rDZVTWonzyvBp33g5",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://066001282e82.ngrok.paid",
      "tunnel": {
        "id": "tn_2x2L1MpLuHqWRQq7fp95X2a0BjF",
        "uri": "https://api.ngrok.com/tunnels/tn_2x2L1MpLuHqWRQq7fp95X2a0BjF"
      },
      "tunnel_session": {
        "id": "ts_2x2L1M3UsFKV2paXoMN4IMWzZSq",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2x2L1M3UsFKV2paXoMN4IMWzZSq"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-13T10:10:05Z",
      "upstream_url": "http://localhost:80",
      "url": "https://066001282e82.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-13T10:10:03Z",
      "domain": {
        "id": "rd_2x2L0ywJnC1KhD1GHncibFImKg4",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2x2L0ywJnC1KhD1GHncibFImKg4"
      },
      "edge": {
        "id": "edgtls_2x2L0zSTBQHEq0zLCgyvUzz4sAW",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2x2L0zSTBQHEq0zLCgyvUzz4sAW"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2x2L0xXTR34JBZQ2xxFZmsr9KiO",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-13T10:10:03Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
