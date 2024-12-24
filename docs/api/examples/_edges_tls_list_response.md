<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-24T10:06:34Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qetJGgy2kEiPGfvZyIMtdfdEwO",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qetJGgy2kEiPGfvZyIMtdfdEwO"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qetHoocj5lZToqsat8g66E8IOO",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qetHoocj5lZToqsat8g66E8IOO"
				},
				"enabled": true
			},
			"created_at": "2024-12-24T10:06:23Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qetHrUXjVhE2wAk4LJxf43dsAU",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qetHrUXjVhE2wAk4LJxf43dsAU"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
