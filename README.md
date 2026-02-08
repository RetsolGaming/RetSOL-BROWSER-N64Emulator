# 🌀 RetSOL N64 - BETA

A high-performance Nintendo 64 (N64) emulator core optimized for web browsers on portable gaming handhelds and mobile devices.

## 🚀 Engine Features
* **WASM Core**: Powered by `n64wasm` for near-native 64-bit emulation speed via WebAssembly.
* **Direct ROM Injection**: Supports high-speed DMA loading for `.z64`, `.v64`, and `.n64` formats.
* **Handheld Optimized**: Designed with a responsive UI that scales to various handheld screen aspect ratios (4:3, 3:2, 16:9).
* **State Management**: Integrated Quick Save and Quick Load functionality using browser local storage.

---

## 🕹️ Operations Guide
1. **Load ROM**: Tap `🎮 LOAD N64 GAME` to open your device's local file picker.
2. **Controller Sync**: Uses the Standard Web Gamepad API. Most integrated handheld controllers and Bluetooth gamepads are detected automatically upon button press.
3. **Save States**: 
   * **Quick Save**: Captures the current system RAM and encodes it to your browser's local cache.
   * **Quick Load**: Instantly restores the encoded state from memory.

## ⚡ Performance Optimization
N64 emulation is computationally demanding. For the best experience on portable hardware:
* **Browser Settings**: Ensure "Hardware Acceleration" is enabled in your browser settings.
* **Memory Management**: Close unnecessary background tabs to free up RAM for the WASM engine.
* **Audio**: If audio stuttering occurs, it is usually a sign of CPU throttling; ensure your device is not in a "Power Saving" mode.

---

## 🛠️ System Architecture
| Component | Implementation |
| :--- | :--- |
| **Graphics Engine** | WebGL 2.0 / WebAssembly |
| **Input Driver** | Standard Gamepad API |
| **Storage** | Base64 Encoded LocalStorage |
| **Scaling** | Pixel-Perfect Integer Scaling |

**Developed for the RetSOL Gaming Hub.**
[Back to Hub](https://retsolgaming.github.io/RetSOL-Hub/)
