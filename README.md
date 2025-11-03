# 🎬 ffmpeg-android-arm64-gpl

**Zhivoglas welcomes you!**  
I present to you my custom build of **FFmpeg for Android (arm64-v8a)**.
Thanks to the ffmpeg developers.
💡 *Special thanks to the creators and developers of **ChatGPT** for assistance with documentation and formatting.*

---

## 🧩 Overview

This repository contains **prebuilt FFmpeg GPL shared libraries** for **Android (arm64-v8a)**.  
They are ready for integration into **Android Studio** projects.

📜 This build includes GPL components and is licensed under **GNU General Public License v3.0 (GPLv3)**.  
By using these binaries, you agree to comply with the GPLv3 license terms.

🔗 Original FFmpeg source: [https://ffmpeg.org](https://ffmpeg.org)  
⚠️ This repository is *not* affiliated with the official FFmpeg project.

---

## ⚙️ Build Information

- **FFmpeg version:** 6.0  
- **Configuration:** `--enable-gpl --enable-nonfree --enable-shared`  
- **Target ABI:** `arm64-v8a`

---

## 📦 Installation

1. Clone or download this repository.  
2. Extract the `jniLibs` folder (or `jniLibs.zip` if provided).  
3. Copy it into your Android project at:  
   `app/src/main/jniLibs/arm64-v8a/`  
4. Load the native libraries in your Java/Kotlin code using:  
   `System.loadLibrary("avcodec");`  
   `System.loadLibrary("avformat");`  
   `System.loadLibrary("avutil");`

---

## 🚀 Usage

After integration, FFmpeg features can be accessed through JNI or wrappers.

**Example command:**  
`ffmpeg -i input.mp4 -vn -acodec copy output.aac`

⚠️ **Important:** Any software linked with these binaries must also comply with **GPLv3**.

---

## 🧾 License

This repository is distributed under the  
**GNU General Public License v3.0 (GPLv3)**.  
See the LICENSE file for full terms.

license from source  
   GNU GENERAL PUBLIC LICENSE  
                       Version 3, 29 June 2007  

 Copyright (C) 2007 Free Software Foundation, Inc.  
 Everyone is permitted to copy and distribute verbatim copies  
 of this license document, but changing it is not allowed.

---

## 🙏 Credits

- 🧠 **FFmpeg Project** — https://ffmpeg.org  
  Licensed under **GPLv3**  
- 🛠️ **Preparation and packaging:** [Zhivoglas](https://github.com/zhivoglas)  
- 🤖 **Documentation assistance:** чат (GPT-5, via [gptonline.ai](https://gptonline.ai/))

---

## ⚠️ Disclaimer

This repository is distributed **without any warranty**.  
It is intended solely for **educational and development purposes**.
