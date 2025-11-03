# 🎬 ffmpeg-android-arm64-gpl
**Zhivoglas welcomes you!**  
I present to you my custom build of **FFmpeg for Android (arm64-v8a)**.
Thanks to the ffmpeg developers.
Special thanks to the creators and developers of **ChatGPT** for assistance with documentation and formatting.

---

## 🧩 Overview

This repository contains **prebuilt FFmpeg GPL shared libraries** for **Android (arm64-v8a)**.  
They are ready for integration into **Android Studio** projects.

📜 This build includes GPL components and is licensed under **GNU General Public License v3.0 (GPLv3)**.  
By using these binaries, you agree to comply with the GPLv3 license terms.

🔗 Original FFmpeg source: https://ffmpeg.org  
⚠️ This repository is *not* affiliated with the official FFmpeg project.

---

## ⚙️ Build Information

- **FFmpeg version:** 8.0  
- **Configuration:** `--enable-gpl --enable-nonfree --enable-shared`  
- **Target ABI:** `arm64-v8a`

---

## 📦 Installation

1. Clone or download this repository.  
2. Extract and copy "arm64-v8a" folder into your Android project at:  
   `app/src/main/jniLibs/`  
   
🚀 Usage
After integration, FFmpeg features can be accessed through JNI or wrappers.

⚠️ Important: Any software linked with these binaries must also comply with GPLv3.

🧾 License
This repository is distributed under the
GNU General Public License v3.0 (GPLv3).
See the LICENSE file for full terms.

license from source GNU GENERAL PUBLIC LICENSE (Version 3, 29 June 2007)
Copyright (C) 2007 Free Software Foundation, Inc.
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

🙏 Credits
🧠 FFmpeg Project — https://ffmpeg.org
Licensed under GPLv3

⚠️ Disclaimer
This repository is distributed without any warranty.
It is intended solely for educational and development purposes.
