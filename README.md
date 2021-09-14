# CORS simple setup for bypassing

- Copy index.js on a server (e.g., `http://my.server.com`).
- Run the file with `node index.js`
- If your api is at the location `http://myapi.com` make your request this way: `http://my.server.com/http://myapi.com`.
- If you have any paramter to pass to the api, you can do that directly. Example:
`http://my.server.com/http://myapi.com?myParam=value`
