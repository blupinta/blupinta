# Blupinta SDKs

Official libraries for [Blupinta](https://blupinta.app)'s public API, `https://api.blupinta.app/v1`: read a home's
saved versions, its files and its furniture, follow new versions as they are saved, and sign people in at
`auth.blupinta.app` (OAuth 2.1 and OpenID Connect, the device flow for screens without a keyboard).

**Status: nothing is published yet.** The packages below are planned; this repository will hold their sources as they
are released.

| Package | Registry | For |
|---|---|---|
| `@blupinta/home` | npm | the home format: types, parser, migrations, JSON Schema |
| `@blupinta/sdk` | npm | TypeScript, in the browser and in Node |
| `@blupinta/react` | npm | React hooks and provider |
| `@blupinta/cli` | npm | the `blupinta` command line |
| `@blupinta/mcp` | npm | an MCP server for AI agents |
| `blupinta` | PyPI | Python, sync and async |

Swift, Kotlin and C# clients will follow, generated from the API's OpenAPI document.

## Documentation

The public API is described at `GET https://api.blupinta.app/v1` and explained in the guide:
<https://docs.blupinta.app/reference/public-api/>.

## Licence

Apache License 2.0, see [LICENSE](LICENSE).
