# WaveForge 3D — Audio Visualizer

Real-time 3D audio visualization in your browser. Use your microphone or drop an audio file to see stunning WebGL-powered visualizations.

**Live Demo:** [waveforge-3d.surge.sh](https://waveforge-3d.surge.sh/)

## Features

- **Microphone input** — Real-time visualization of any audio
- **File playback** — Drag & drop or open MP3/WAV/OGG files
- **6 visualization modes:**
  - **Bars** — 3D spectrum analyzer with reflections
  - **Sphere** — Frequency-mapped waveform sphere
  - **Ring** — Multi-layer circular spectrum
  - **Wave** — Audio-driven terrain surface
  - **Particles** — Swirling particle vortex
  - **Terrain** — Oscillating frequency landscape
- **5 color themes** — Neon, Fire, Ocean, Pink, Monochrome
- **Beat detection** — Bass-responsive visual pulses
- **Orbit camera** — Drag to rotate, scroll to zoom
- **Touch support** — Mobile-friendly
- **Gain & smoothing controls** — Fine-tune responsiveness

## Tech

- WebGL point sprites and line rendering
- Web Audio API (AnalyserNode, FFT)
- Beat detection via bass frequency thresholding
- Custom 4x4 matrix math (perspective, lookAt)
- Single HTML file, zero dependencies

## License

MIT
