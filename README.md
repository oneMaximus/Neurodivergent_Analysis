# Neurodivergent_Analysis
NeuroLens aims to bridge communication gaps for neurodiverse users by interpreting non-literal social cues. Using a Raspberry Pi 5, it processes audio and video at the Edge to detect tone and gestures. This ensures sub-200ms latency and 100% data privacy, helping users validate social intent in real-time without cloud risks.

NeuroLens - Real-Time Tonality Analytics
NeuroLens is a private-by-design, real-time edge computing system developed for the Raspberry Pi 5. It identifies social intent by analyzing the "how" of speech—detecting discrepancies between literal words and vocal tone to help users interpret communication nuances like sarcasm or emotional shifts.

✨ Key Features
Real-Time Audio Processing: Converts live speech into Mel Spectrograms for immediate tonality classification.

Local NLP Sentiment Analysis: Processes text locally to determine literal intent without cloud dependency.

Privacy-First Architecture: 100% on-device processing ensures sensitive conversations never leave the local environment.

Performance Monitoring: Live dashboard for tracking inference latency, thermal levels, and model confidence.

🛠️ Tech Stack
Hardware: Raspberry Pi 5 (8GB), Logitech C270 HD Webcam.

AI Models: * STT: OpenAI Whisper (Tiny.en) optimized for CPU.

Tonality: Custom MobileNetV2 CNN (Quantized).

Sentiment: Phi-3-mini (4-bit quantization).

Edge Logic: Python 3.11, OpenVINO / ONNX Runtime.

🚀 Getting Started
Prerequisites
Raspberry Pi OS (64-bit) installed on the provided MicroSD card.

Logitech C270 connected via USB.

Monitor connected via HDMI.