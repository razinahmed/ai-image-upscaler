# AI Image Upscaler

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-Powered-purple)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered image upscaling tool that enhances low-resolution images using deep learning models. Produces sharp, high-quality results with intelligent detail reconstruction and noise reduction.

---

## Features

- **Super-Resolution** -- Upscale images 2x, 4x, or 8x with AI-driven detail enhancement
- **Noise Reduction** -- Removes compression artifacts and noise during upscaling
- **Batch Processing** -- Process entire directories of images in one command
- **Format Support** -- Handles PNG, JPEG, WebP, TIFF, and BMP formats
- **Quality Preservation** -- Maintains color accuracy and natural textures
- **GPU Acceleration** -- Leverages CUDA for fast inference on supported hardware

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| OpenAI / LLM API | AI inference engine |
| Pillow / OpenCV | Image processing |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/ai-image-upscaler.git
cd ai-image-upscaler

# Install dependencies
pip install -r requirements.txt

# Upscale an image
python core/ai_worker.py --input image.jpg --scale 4
```

---

## Project Structure

```
ai-image-upscaler/
├── core/
│   └── ai_worker.py       # Main AI processing engine
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
