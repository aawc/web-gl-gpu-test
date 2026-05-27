# WebGL and WebGPU Minimal PoCs

This repository contains the smallest possible Proof of Concepts (PoCs) for WebGL and WebGPU, designed to be hosted on GitHub Pages.

**Live Demo:** [http://varun.khaneja.org/web-gl-gpu-test/](http://varun.khaneja.org/web-gl-gpu-test/)

## Features & API PoCs

This site explicitly demonstrates minimal usages of:

1. **`WebGLRenderingContext.compileShader()`**
   - Compiles minimal Vertex and Fragment shaders.
   - If successful, draws a Blue square/point in the middle.
2. **`WebGLRenderingContext.linkProgram()`**
   - Links the compiled vertex and fragment shaders into a unified shader program.
3. **`GPUAdapter.requestDevice()`**
   - Requests a GPU device from the fetched adapter, initializing the WebGPU logical device.
   - Clears the canvas to Green upon success.

## Usage

Open [index.html](file:///usr/local/google/home/vakh/git/hub/aawc/web-gl-gpu-test/index.html) in a compatible web browser. Use the buttons to trigger either the WebGL context clear or the WebGPU context clear.

