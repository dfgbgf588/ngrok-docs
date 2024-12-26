<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-26T10:05:54Z",
			"hostport": "f9d04df620d3.ngrok.paid:443",
			"id": "ep_2qkXTUkWCufxDSqNPaLng6T3uz9",
			"name": "command_line",
			"principal": {
				"id": "usr_2qkXQwS8qJNOih9pL659xm9qwiZ",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://f9d04df620d3.ngrok.paid",
			"tunnel": {
				"id": "tn_2qkXTUkWCufxDSqNPaLng6T3uz9",
				"uri": "https://api.ngrok.com/tunnels/tn_2qkXTUkWCufxDSqNPaLng6T3uz9"
			},
			"tunnel_session": {
				"id": "ts_2qkXTYysxDPhjmGcwJDkcGu9DnH",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qkXTYysxDPhjmGcwJDkcGu9DnH"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-26T10:05:54Z",
			"upstream_url": "http://localhost:80",
			"url": "https://f9d04df620d3.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-26T10:05:51Z",
			"domain": {
				"id": "rd_2qkXT4soB54NcjVmaezRLfs23QI",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qkXT4soB54NcjVmaezRLfs23QI"
			},
			"edge": {
				"id": "edgtls_2qkXTBjWJfYBoSSmbugupIbx4SH",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qkXTBjWJfYBoSSmbugupIbx4SH"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qkXTBwVFesPeKRol2xWPYiWWEJ",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-26T10:05:51Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
