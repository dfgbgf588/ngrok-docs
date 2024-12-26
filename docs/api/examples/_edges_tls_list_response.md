<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-26T10:06:02Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qkXUYWAzymeHPz0MljcUOrbfoG",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qkXUYWAzymeHPz0MljcUOrbfoG"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qkXTCJ3klcg0f1toDp2QN7CUTy",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qkXTCJ3klcg0f1toDp2QN7CUTy"
				},
				"enabled": true
			},
			"created_at": "2024-12-26T10:05:51Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qkXTBjWJfYBoSSmbugupIbx4SH",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qkXTBjWJfYBoSSmbugupIbx4SH"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
