<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"certificate_management_policy":{"authority":"letsencrypt"},"description":"point-of-sale new york #302","http_endpoint_configuration_id":"ec_2x2Kz1kmfMSBQ0XpaStLNfyBBGd","https_endpoint_configuration_id":"ec_2x2KywkBjb2BaLqnx30MNe1czKW","metadata":"{\"env\": \"staging\", \"connector_id\":\"64698fcc-5f5c-4b63-910e-8669d04bd943\"}"}' \
https://api.ngrok.com/reserved_domains/rd_2x2Kyz0QjG203tOxs6Qk62AqXCH
```
