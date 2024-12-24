<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-24T10:06:26Z",
			"hostport": "7ebd58ae994f.ngrok.paid:443",
			"id": "ep_2qetIEe0YeSoKTRGhMUajg7b8QV",
			"name": "command_line",
			"principal": {
				"id": "usr_2qetFio3p5ZUMQBLXnh6WmFPmwD",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://7ebd58ae994f.ngrok.paid",
			"tunnel": {
				"id": "tn_2qetIEe0YeSoKTRGhMUajg7b8QV",
				"uri": "https://api.ngrok.com/tunnels/tn_2qetIEe0YeSoKTRGhMUajg7b8QV"
			},
			"tunnel_session": {
				"id": "ts_2qetICqCTnmF1tf0LcK2BMrRIO0",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qetICqCTnmF1tf0LcK2BMrRIO0"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-24T10:06:26Z",
			"upstream_url": "http://localhost:80",
			"url": "https://7ebd58ae994f.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-24T10:06:23Z",
			"domain": {
				"id": "rd_2qetHqmIss1YgMI77NBEkoCiUzv",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qetHqmIss1YgMI77NBEkoCiUzv"
			},
			"edge": {
				"id": "edgtls_2qetHrUXjVhE2wAk4LJxf43dsAU",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qetHrUXjVhE2wAk4LJxf43dsAU"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qetHp5sJfacRdrvKW9U58DtbhP",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-24T10:06:23Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
