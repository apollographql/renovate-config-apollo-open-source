# Apollo Open Source Renovate Configuration

This is a [Renovate](https://renovateapp.com/) configuration which is used by Apollo Open Source repositories.

For example, the following repositories inherit from this configuration, rather than maintaining their own.

* [apollo-server](https://github.com/apollographql/apollo-server)
* [apollo-client](https://github.com/apollographql/apollo-client)
* [federation](https://github.com/apollographql/federation)
* [router](https://github.com/apollographql/router)
* [rover](https://github.com/apollographql/rover)

## Usage

To use this configuration, add the following to your `renovate.json` file:

```json
{
  "extends": [
    "github>apollographql/renovate-config-apollo-open-source"
  ]
}
```
