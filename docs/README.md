# Codewars OpenAPI Specification

[![download](https://img.shields.io/badge/download-OAS3-blue.svg)](https://noid.dev/codewars-openapi/codewars.yaml)
[![preview](https://img.shields.io/badge/preview-OAS3-blue.svg)](https://noid.dev/codewars-openapi)
[![build](https://img.shields.io/github/actions/workflow/status/noid-dev/codewars-openapi/build.yml)](https://github.com/noid-dev/codewars-openapi/actions/workflows/build.yml)
[![hits](https://img.shields.io/badge/dynamic/xml?color=success&label=hits&query=//*[name()=%27text%27][3]&url=https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fnoid-dev%2Fcodewars-openapi)](https://hits.seeyoufarm.com/api/count/graph/dailyhits.svg?url=https://github.com/noid-dev/codewars-openapi)
[![chat](https://img.shields.io/gitter/room/noid-dev/community?color=49c39e)](https://gitter.im/noid-dev/community)

Welcome aboard fellow developer, this is where you will find the OAS
for [Codewars' public API](https://dev.codewars.com).

## What is OAS?

The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to HTTP APIs which
allows both humans and computers to discover and understand the capabilities of the service
without access to source code, documentation, or through network traffic inspection. When properly
defined, a consumer can understand and interact with the remote service with a minimal amount of
implementation logic.

An OpenAPI definition can then be used by documentation generation tools to display the API, code
generation tools to generate servers and clients in various programming languages, testing tools,
and many other use cases.

-- <cite>[OpenAPI Initiative (OAI)][1]</cite>

## Project Status

The Codewars OpenAPI Specification is currently in Early Availability. While the specification
should be accurate, it is under active development. The structure of this repository may continue to
evolve. If you encounter any inaccuracies or have feedback on how it can better suite your use case,
please [open an issue](https://github.com/noid-dev/codewars-openapi/issues/new) to let us know.

## Development

To generate a bundled version of the specification locally, run:

> npm run build

To preview the documentation locally, run:

> npm start

The documentation will be available at: http://127.0.0.1:8080

[1]: https://spec.openapis.org/oas/latest.html