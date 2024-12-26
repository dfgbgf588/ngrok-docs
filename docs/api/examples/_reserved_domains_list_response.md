<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2qkXQyOGZ2V5j39RNTEifkc9Uj9",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2qkXQyOGZ2V5j39RNTEifkc9Uj9"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.4zpdk7p7wkefrwqla.local-ngrok-cname.com",
			"created_at": "2024-12-26T10:05:34Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qkXR9VON1njSzpVGO84RjlM5uv",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qkXR9VON1njSzpVGO84RjlM5uv"
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
					"started_at": "2024-12-26T10:05:35Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.4zpdk7p7wkefrwqla.local-ngrok-cname.com",
			"created_at": "2024-12-26T10:05:35Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qkXR91LefZP9Eeu0Xr4gO3Hm7o",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qkXR91LefZP9Eeu0Xr4gO3Hm7o"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
