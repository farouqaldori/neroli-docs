# Neroli docs

Bare-bones Mintlify documentation for `neroli.dev/docs`.

## Local preview

Install the Mintlify CLI, then run:

```sh
mint dev
```

## Deployment

Mintlify deploys this repository automatically from `main`.

The main website proxies `/docs` to Mintlify through its Cloudflare Worker. Set
the `MINTLIFY_DOCS_HOST` Worker variable to the Mintlify host, for example
`neroli.mintlify.app`.
