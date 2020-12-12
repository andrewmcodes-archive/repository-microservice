<p align="center">
  <a href="https://andrewm.codes" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/andrewmcodes/repository-microservice/blob/main/.github/img/logo.png?raw=true" alt="Social Sharing Image" style="max-width:100%;">
  </a>
</p>

<p align="center">
  <img src="https://badgen.net/github/license/andrewmcodes/repository-microservice" alt="License: MIT">
  <img src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg" alt="Contributor Covenant">
</p>

<h1 align="center">
  Repository Microservice
</h1>

Take a [look at this Pawprint for a quick understanding!](https://paw.pt/fCAF6W7m)

## Features

API endpoint for my GitHub repositories via Vercel API.

It is currently hosted [on Vercel](https://repositories.andrewmcodes.vercel.app/), but that will change in the future and instead it will be on a subdomain of my blog.

## Usage

### Request

```sh
curl https://repositories.andrewmcodes.vercel.app/
```

### Response

```json
[
  {
    "id": 205964243,
    ...
    },
  {
    "id": 157638780,
    ...
  }
]
```

Output is a JSON array of repositories. See [GitHub's list organization repositories documentation](https://docs.github.com/en/free-pro-team@latest/rest/reference/repos#list-organization-repositories) to learn more.

## Installation

>NOTE this will use microlinks repo, not mine. The only major difference is I inlined my username for fetching the accounts vs using an env var.

[![Deploy with Vercel](https://zeit.co/button)](https://vercel.com/new/project?template=https://github.com/microlinkhq/oss)

## Achknowledgement

This was originally forked from [microlinkhq/oss](https://github.com/microlinkhq/oss) when deploying to Vercel (which is why this
repo is not an actual fork) by Vercel.

Big thanks to them for their work - Definitely check out some of their products if this repo is of interest to you.

> [microlink.io](https://microlink.io) · GitHub [microlink.io](https://github.com/microlinkhq) · Twitter [@microlinkhq](https://twitter.com/microlinkhq)

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2020-present, Andrew Mason
