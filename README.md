# ScrapEth

An application, and in future perhaps an API, to scrape repositories for Ethereum smart contract addresses. This is partly an exercise in learning Elixir/Phoenix, and partly useful when performing security audits of Ethereum dapps - these addresses will be listed with links to block explorers and other analytics.

For now (may be more permanent in future) see https://kawapi.io/scan and try `ProteaNetwork/protea-gather`.

## Roadmap

0. Scrape GitHub repos
1. Scrape website Javascript code
2. Scrape other sources

## Development

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Install Node.js dependencies with `cd assets && npm install`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Phoenix framework

  * Official website: http://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
