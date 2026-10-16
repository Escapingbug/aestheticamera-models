# AesthetiCamera model assets

Public download chunks for [the local-browser demo](https://frame-charm-local.anciety512.chatgpt.site/).

This is [Q-ReAlign Mini 0.8B](https://huggingface.co/q-future/Q-ReAlign-Mini-0.8B), revision `fe1f45a7574c9e9d908875af9f7e90cb946aa19f`, adapted to a fixed aesthetics prompt and Q4 weight-only MatMul quantization. Input is a 256-square letterboxed image. Native score range: 0–1. Apache-2.0. See model-info.json for source, preprocessing, hashes, and conversion references.

The application concatenates chunks in manifest order and verifies SHA256 before local inference. This repository contains public model assets; user photos are never uploaded.
