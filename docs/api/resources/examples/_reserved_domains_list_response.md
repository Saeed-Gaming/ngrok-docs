<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2x2KyqCch5Hv18ih4tto5RnItgP",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2x2KyqCch5Hv18ih4tto5RnItgP"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.33fc9glvxb1nvy877.local-ngrok-cname.com",
      "created_at": "2025-05-13T10:09:45Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2x2Kyz0QjG203tOxs6Qk62AqXCH",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2x2Kyz0QjG203tOxs6Qk62AqXCH"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-05-13T10:09:46Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.33fc9glvxb1nvy877.local-ngrok-cname.com",
      "created_at": "2025-05-13T10:09:46Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2x2KyxRWxCKbIC7SyGxrBqpuJhS",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2x2KyxRWxCKbIC7SyGxrBqpuJhS"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
