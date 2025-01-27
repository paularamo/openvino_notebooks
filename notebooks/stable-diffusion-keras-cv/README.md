# Stable Diffusion with KerasCV and OpenVINO

This notebook demonstrates how to run [KerasCV Stable Diffusion](https://www.tensorflow.org/tutorials/generative/generate_images_with_stable_diffusion) using OpenVINO. An additional part demonstrates how to run optimization with [NNCF](https://github.com/openvinotoolkit/nncf/) to speed up pipeline.

![stable-diffusion-result](https://github.com/openvinotoolkit/openvino_notebooks/assets/67365453/4dc86beb-cbdf-48da-8465-f9079d15a7fd)

## Notebook Contents

This notebook demonstrates how to convert, run and optimize stable diffusion using OpenVINO and NNCF.

Notebook contains the following steps:

- Convert Stable Diffusion Pipeline models to OpenVINO
  - Convert text encoder
  - Convert diffusion model
  - Convert decoder
- Stable Diffusion Pipeline with OpenVINO
- Optimize pipeline with [NNCF](https://github.com/openvinotoolkit/nncf/)
- Compare results of original and optimized pipelines
- Interactive Demo

## Installation Instructions

This is a self-contained example that relies solely on its own code.</br>
We recommend running the notebook in a virtual environment. You only need a Jupyter server to start.
For details, please refer to [Installation Guide](../../README.md).