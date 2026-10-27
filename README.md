# noname122021 Cydia Repository

<p align="center">
  <img src="CydiaIcon.png" width="96" height="96" alt="Cydia Repository Icon" style="border-radius: 20px;"><br>
  <b>Cydia Repository for iOS 6</b><br>
  <i>DictaKey offline voice dictation and speech recognition models.</i>
</p>

<p align="center">
  <a href="https://noname122021.github.io/cydia-repo/"><img src="https://img.shields.io/badge/Web%20Repo-Open%20Showcase-blue.svg?style=for-the-badge" alt="Web Repo"></a>
  <a href="cydia://url/https://cydia.saurik.com/api/share#?source=https://noname122021.github.io/cydia-repo/"><img src="https://img.shields.io/badge/Cydia-Add%20to%20Cydia-orange.svg?style=for-the-badge" alt="Add to Cydia"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/iOS-6.0%20--%206.1.6-blue.svg" alt="iOS 6.0 - 6.1.6">
  <img src="https://img.shields.io/badge/arch-ARMv7%20(32--bit)-success.svg" alt="ARMv7 32-bit">
  <img src="https://img.shields.io/badge/APT-Debian%20Binary-lightgrey.svg" alt="APT Repo">
</p>

> ### 📦 **Add to Cydia**
> - **Direct URL (copy & paste into Cydia):**  
>   `https://noname122021.github.io/cydia-repo/`
> - **One-Tap Install on iOS Device:**  
>   [Tap here to open in Cydia (`cydia://`)](cydia://url/https://cydia.saurik.com/api/share#?source=https://noname122021.github.io/cydia-repo/)
> - **Web Showcase:**  
>   [https://noname122021.github.io/cydia-repo/](https://noname122021.github.io/cydia-repo/)

---

## Available Packages

### Base Tweaks

| Package Name | Identifier | Version | Size | Description |
|---|---|:---:|:---:|---|
| **DictaKey** | `com.noname122021.dictakey` | 1.0.0 | 4.2 MB | Completely offline on-device speech-to-text dictation keyboard tweak for iOS 6. Injects a skeuomorphic dictation microphone key into `UIKeyboardImpl`. Features fast integer VAD, recognizer reuse (~0.5s first-word latency on iPhone 4), and zero-overhead keyboard typing. ([Source Code](https://github.com/noname122021/dictakey)) |

### Language Models for DictaKey (Vosk Kaldi FST)

Pre-trained, quantized, and baked with OpenFST `ConstFst` graphs, kernel mmap alignment, memory-mapped symbol tables, and pre-computed acoustic/i-vector covariance caches (`final.mdl.cache`, `final.ie.cache`):

| Package Name in Cydia | Identifier | Size | Features |
|---|---|:---:|---|
| **DictaKey Model: Russian** | `com.noname122021.dictakey-model-ru` | 59 MB | Full universal vocabulary with spoken punctuation, pre-baked caches |
| **DictaKey Model: Russian (Small)** | `com.noname122021.dictakey-model-ru-small` | 43 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: English** | `com.noname122021.dictakey-model-en` | 51 MB | Full vocabulary, pre-baked caches. Spoken punctuation: comma, period, colon, dash, hyphen |
| **DictaKey Model: English (Small)** | `com.noname122021.dictakey-model-en-small` | 45 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: German** | `com.noname122021.dictakey-model-de` | 56 MB | Full vocabulary, pre-baked caches. Spoken punctuation: komma, doppelpunkt, gedankenstrich |
| **DictaKey Model: German (Small)** | `com.noname122021.dictakey-model-de-small` | 41 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: French** | `com.noname122021.dictakey-model-fr` | 55 MB | Full vocabulary, pre-baked caches. Spoken punctuation: virgule, deux-points, tiret |
| **DictaKey Model: French (Small)** | `com.noname122021.dictakey-model-fr-small` | 44 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: Spanish** | `com.noname122021.dictakey-model-es` | 53 MB | Full vocabulary, pre-baked caches. Spoken punctuation: coma, dos puntos, guion |
| **DictaKey Model: Spanish (Small)** | `com.noname122021.dictakey-model-es-small` | 39 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: Italian** | `com.noname122021.dictakey-model-it` | 65 MB | Full vocabulary, pre-baked caches. Spoken punctuation: virgola, due punti, trattino |
| **DictaKey Model: Italian (Small)** | `com.noname122021.dictakey-model-it-small` | 46 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |
| **DictaKey Model: Ukrainian** | `com.noname122021.dictakey-model-uk` | 74 MB | Full vocabulary, spoken punctuation: кома, двокрапка, тире, дефіс |
| **DictaKey Model: Ukrainian (Small)** | `com.noname122021.dictakey-model-uk-small` | 58 MB | Lightweight conversational 15k vocabulary (iPhone 4 / A4 optimized) |

---

## How to Add this Repository in Cydia

1. Open **Cydia** on your jailbroken iOS 6 device.
2. Tap the **Manage** tab at the bottom, then select **Sources**.
3. Tap **Edit** (top right), then tap **Add** (top left).
4. Enter the repository URL:
   ```text
   https://noname122021.github.io/cydia-repo/
   ```
5. Tap **Add Source**. Cydia will verify the repository and download package indexes.
7. Install the tweak: go to **Sections** $\to$ **Tweaks** $\to$ **DictaKey** (or select **All Packages** inside the repository).
8. Install language models: go to **Sections** $\to$ **Addons (DictaKey)** and select your desired offline speech models.

---

## Compatibility

- **iOS Versions:** iOS 6.0, 6.0.1, 6.0.2, 6.1, 6.1.1, 6.1.2, 6.1.3, 6.1.4, 6.1.5, 6.1.6
- **Architectures:** ARMv7 (32-bit)
- **Supported Devices:** iPad (2, 3, 4, mini 1), iPhone (4, 4S, 5), iPod touch (4th, 5th gen)
- **Dependencies:** `mobilesubstrate`, `preferenceloader`

## Recommended Tweaks & HTTPS on iOS 6

- **[LegacyRay](https://github.com/LR-Vensuki/LegacyRay)** (Cydia Repo: `http://repo.legacyreborn.cfd/`):  
  **Strongly Recommended.** Modern HTTPS endpoints (including GitHub Releases where deb packages are hosted) require TLS 1.2+ and modern root certificates. LegacyRay includes `legacyraytlsfix`, a system-wide TLS hook (`SecTrust` / `SSLSetProtocol`) enabling seamless HTTPS and certificate trust across all iOS 6 apps and Cydia.

---

## Source Repositories & Links

- **DictaKey Tweak Source Code:** [https://github.com/noname122021/dictakey](https://github.com/noname122021/dictakey)
- **Web Repository Page:** [https://noname122021.github.io/cydia-repo/](https://noname122021.github.io/cydia-repo/)
- **LegacyRay Repository:** [http://repo.legacyreborn.cfd/](http://repo.legacyreborn.cfd/) ([GitHub](https://github.com/LR-Vensuki/LegacyRay))
- **Bug Reports & Issues:** [https://github.com/noname122021/dictakey/issues](https://github.com/noname122021/dictakey/issues)

