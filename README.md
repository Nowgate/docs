# Nowgate docs

The source of [docs.nowgate.io](https://docs.nowgate.io): Nowgate's guides, the API reference's
pages and the SDKs' pages, and the merchant API's description.

[Nowgate](https://nowgate.io) is a payment gateway for crypto: accept USDT, USDC, BTC, ETH, SOL and
more on nine networks, through hosted checkout, payment links or the API.

## What's here

- **[content/](content):** the documentation, in MDX, as docs.nowgate.io renders it. Start with the
  [quickstart](content/quickstart.mdx).
- **[openapi/openapi.yaml](openapi/openapi.yaml):** the merchant API, described in OpenAPI 3.1.
- **[openapi/errors.json](openapi/errors.json):** every problem code the API returns, with its HTTP
  status.
- **[openapi/webhooks/signature-vectors.json](openapi/webhooks/signature-vectors.json):** the
  published webhook signature vectors, to check a verifier against.

## The SDKs

| Language                | Install                            | Repository                                                 |
| ----------------------- | ---------------------------------- | ---------------------------------------------------------- |
| TypeScript / JavaScript | Coming soon on npm                 | [Nowgate/nowgate-node](https://github.com/Nowgate/nowgate-node)     |
| Python                  | `pip install nowgate`              | [Nowgate/nowgate-python](https://github.com/Nowgate/nowgate-python) |
| PHP                     | `composer require nowgate/nowgate` | [Nowgate/nowgate-php](https://github.com/Nowgate/nowgate-php)       |

## Contributing

Spotted a mistake or something unclear? Open an issue or a pull request. Never put API keys, webhook
secrets or other credentials in an issue or a pull request. For a security issue, see
[SECURITY.md](SECURITY.md).

## License

[MIT](LICENSE) © Nowgate
