# Blupinta's public libraries

Official libraries for [Blupinta](https://blupinta.app)'s public API, `https://api.blupinta.app/v1`: read a home's
saved versions, its files and its furniture, follow new versions as they are saved, save a version from outside, and
sign people in at `auth.blupinta.app` (OAuth 2.1 and OpenID Connect, the device flow for screens without a keyboard).
Each language has its own repository.

| Repository | Packages | For |
|---|---|---|
| [blupinta-js](https://github.com/blupinta/blupinta-js) | `@blupinta/sdk`, `@blupinta/react`, `@blupinta/home`, `@blupinta/cli`, `@blupinta/mcp` on npm | TypeScript in the browser and in Node, React, the home format's types, the `blupinta` command line, an MCP server for AI agents |
| [blupinta-python](https://github.com/blupinta/blupinta-python) | `blupinta` on PyPI | Python, sync and async |

Swift, Kotlin, C# and PHP will follow, each in its own repository, generated from the API's OpenAPI document.

**Status: nothing is released yet but the name on PyPI.** The libraries are about to have their first releases.

## Documentation

The public API is described at `GET https://api.blupinta.app/v1` and explained in the guide, with each library's first
lines: <https://docs.blupinta.app/reference/libraries/>.

## Reporting a problem

A problem with a library: an issue in its repository. A security problem: see [SECURITY.md](SECURITY.md), never a
public issue.

## Licence

Apache License 2.0, see [LICENSE](LICENSE).
