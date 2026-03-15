# hdr-demo

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A WebGPU-based HDR rendering demo using `rgba16float` and `Float16Array`.

## Demo
[Try the demo online](https://fukuno.jig.jp/3927)

## Features
- Generates HDR content on the fly using `Float16Array`
- Supports both standard and extended HDR tone mapping modes
- Adjustable exposure and maximum stop values
- Responsive design that adapts to the canvas size

## Requirements
- A web browser that supports WebGPU (e.g., Chrome Canary or Edge Canary)
- Float16Array support in the browser

## Usage
1. Open the demo in a compatible web browser.
2. Adjust the "exposure" and "maxStops" sliders to see the effect on the HDR rendering.
3. The canvas will automatically resize to fit the browser window.

## License
This project is licensed under the [MIT License](LICENSE).