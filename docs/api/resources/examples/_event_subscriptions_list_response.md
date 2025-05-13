<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-05-13T10:10:09Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2x2L1vxWj3sJRlhPGI1YZdPwG4h",
          "uri": "https://api.ngrok.com/event_destinations/ed_2x2L1vxWj3sJRlhPGI1YZdPwG4h"
        }
      ],
      "id": "esb_2x2L1vxpmhno5T7ygkjnmPfPVmc",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2x2L1vxpmhno5T7ygkjnmPfPVmc/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2x2L1vxpmhno5T7ygkjnmPfPVmc"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
