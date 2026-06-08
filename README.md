# qwen3tts.cpp Windows Binary (Faster Qwen-tts using C++)

Pre-built qwen3-tts-cli.exe for Windows (x64).

## Usage
`ash
qwen3-tts-cli.exe -m <model_dir> -t "Text to speak" -o output.wav -l en -j 4
`

## Requirements
- Windows 10/11 x64
- Model files (download separately from HF)
- Visual C++ Redistributable

## Model Directory Structure Expected
`
models/
â”œâ”€â”€ qwen3-tts-0.6b-f16.gguf        (or your model)
â””â”€â”€ qwen3-tts-tokenizer-f16.gguf   (tokenizer)
`

## Build Info
- Built from qwen3-tts.cpp
- CUDA-enabled (requires NVIDIA GPU for best performance)
- Linked against ggml/llama.cpp
