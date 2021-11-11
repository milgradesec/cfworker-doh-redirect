# doh-redirect

[![Deploy to Cloudflare Workers](https://github.com/milgradesec/cfworker-doh-cache/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/milgradesec/cfworker-doh-cache/actions/workflows/deploy.yml)
![GitHub](https://img.shields.io/github/license/milgradesec/cfworker-doh-cache)

👷 `doh-cache` is a Cloudflare Worker to make DNS over HTTPS requests cacheable at edge.

🚀 Running in production at **<https://dns.paesa.es/dns-query>**

## How it Works

`doh-cache` converts a DoH POST request to a GET request and uses the Cache API to store the response in Cloudflare's cache.

## License

MIT License
