# JUCE MonoSynth 🎹

A simple monophonic synthesizer built using the JUCE framework. This project was developed as a creative exploration into sound design and audio DSP, and serves as a great starting point for understanding how virtual analog synths are built from the ground up.

## 🔧 Features

- Monophonic voice architecture
- Oscillator with selectable waveform(s)
- ADSR envelope control
- Simple filter for tone shaping
- MIDI input support
- Built with JUCE (cross-platform C++ framework for audio apps)

## 📁 Project Structure

- `Source/`: Core source files, including audio processors and UI components.
- `Builds/`: Platform-specific build files (e.g., Visual Studio, Xcode).
- `JuceLibraryCode/`: Auto-generated JUCE wrapper code.
- `tapSynth.jucer`: JUCE project file. Open this with the Projucer to configure and generate builds.

## 🚀 Getting Started

### Prerequisites

- [JUCE](https://juce.com/) installed (Tested with JUCE 6+)
- Projucer or CMake (for generating platform-specific builds)
- C++17 compatible compiler
- An audio plugin host (like [VST3PluginTestHost](https://steinbergmedia.github.io/vst3_dev_portal/pages/Tools/VSTTestHost.html), [Reaper](https://www.reaper.fm/), etc.)

### Build Steps

1. Clone the repo:
    ```bash
    git clone https://github.com/YOUR_USERNAME/Juce-MonoSynth.git
    ```

2. Open `tapSynth.jucer` with Projucer.

3. Choose your IDE from the exporters (e.g., Xcode, Visual Studio) and save the project.

4. Open the generated IDE project and build the plugin.

5. Load the plugin into your DAW or plugin host.

## 🎛️ Controls

- **Oscillator Section**: Choose waveform type (sine, square, saw, etc.)
- **ADSR Envelope**: Adjust Attack, Decay, Sustain, Release
- **Filter**: Simple low-pass or high-pass (depending on config)

## 🧠 Concepts Used

- Basic audio DSP (waveform generation, filters, envelopes)
- MIDI handling
- JUCE AudioProcessor / AudioProcessorEditor architecture
- Realtime audio constraints

## 📜 License

MIT License. See `LICENSE` for details.

---

Made with ❤️ using JUCE.
