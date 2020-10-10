# proxy-china-pacs

Some useful proxy pacs for proxying China.

Based on [gfw whitelist](https://github.com/breakwa11/gfw_whitelist/blob/master/whitelist.pac).

## Usage

- `http.pac`, `http_ip.pac`

  Use this if you'd like to browse Chinese websites via local http proxy listening at 8080

- `socks.pac`, `socks_ip.pac`

  Use this if you'd like to browse Chinese websites via local socks proxy listening at 1080

## Q&A

- What's the difference between `*.pac` and `*_ip.pac`?

  The IP version is smaller and makes your [cloudflare workers http proxy](https://github.com/luckypoem/gopxy) work more seamlessly without configuring certificates. The disadvantage is accuracy.

- How to change my port or proxy server?

  You have to download the pac file and modify it on your own, or fork this repository.

## Potential scenarios

1. To play with Chinese streaming services, such as Bilibili, Netease music, etc.

2. To cover my ass from China behind a proxy server.

3. To block all access to Chinese websites, for some political or technical reasons.

## License

MIT
