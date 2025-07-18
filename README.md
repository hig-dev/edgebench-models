# EdgeBench Models
This repository contains the model artifacts used for my master thesis *Benchmarking Computer Vision Tasks on Edge AI Hardware*.

Benchmarking framework: https://github.com/hig-dev/edgebench

### Model export scripts:
- https://github.com/hig-dev/mmpose/blob/main/quick_export.py
- https://github.com/hig-dev/mmpose/blob/main/quick_export_edgetpu.py
- https://github.com/hig-dev/mmpose/blob/main/quick_export_hailo.py
- https://github.com/hig-dev/mmpose/blob/main/quick_export_hhb.py
- https://github.com/hig-dev/mmpose/blob/main/quick_export_tidl.py
- https://github.com/hig-dev/mmpose/blob/main/quick_export_vela.py

### Directory structure

| Directory | Description |
|-----------|-------------|
| `executorch(xnnpack)/` | ExecuTorch model files optimized with XNNPACK backend for CPU inference |
| `hef/` | Hailo Executable Format files for Raspberry Pi AI HAT+ |
| `hhb/` | Heterogeneous Honey Badger (HHB) compiled models for BeagleV-Ahead |
| `onnx/` | ONNX models with opset 20 |
| `pytorch/` | PyTorch model files (.pth format) |
| `tflite(float32)/` | TensorFlow Lite models with float32 precision |
| `tflite(int8-edgetpu)/` | TensorFlow Lite models quantized to int8 for Coral Edge TPU |
| `tflite(int8-ethosu55)/` | TensorFlow Lite models quantized to int8 for Arm Ethos-U55 NPU |
| `tflite(int8)/` | TensorFlow Lite models with int8 quantization |
| `tidl(am67a)/` | Texas Instruments Deep Learning (TIDL) models optimized for AM67A processors |
