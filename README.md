# Awesome-Mixed-Reality-Headset-Hardware

# Awesome-Mixed-Reality-Headset-Hardware



**Curated List of Commercial Hardware & Open-Source Software Projects**

*Focused on Enterprise AR, Spatial Computing, Open-Source Firmware & Development Frameworks*

**Last updated: October 2026**



This repository tracks notable **commercial mixed reality headset hardware** and **open-source software projects** that maximize their potential. These tools help developers, enterprises, and researchers build spatial computing experiences—whether for industrial training, collaborative design, or immersive entertainment.



**Examples** include Microsoft HoloLens 2, Apple Vision Pro, Meta Quest Pro, Magic Leap 2, HTC Vive XR Elite, Varjo XR-4, Lynx R1, Pico 4 Enterprise, Lenovo ThinkReality VRX, and Sony SRH-S1 (the category leaders).



**Open-source emphasis**: The open-source mixed reality ecosystem is **focused and emerging**. **OpenGalea** provides an open-source brain-computer interface for mixed reality, built on OpenBCI and Meta Quest 3, at **~$1,900** versus **~$30,000** for commercial equivalents . The **Godot Engine** now has official **Microsoft GDK integration** for Xbox development, opening mixed reality development to the open-source engine community . **Godot XR Tools** and **OpenXR** provide the foundation for open-source XR development.



## 📖 Table of Contents



- [🥽 Commercial Hardware](#-commercial-hardware)

- [🔓 Open-Source Software Projects](#-open-source-software-projects)

- [🤝 How to Contribute](#how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## 🥽 Commercial Hardware



> **📊 Market Context**: The global mixed reality headset market is estimated at **~$8B in 2026**, growing toward **~$25B by 2032**. The sector is **moderately fragmented** — **Meta Quest** dominates consumer VR, **Apple Vision Pro** leads the premium spatial computing tier, and **Varjo** serves the high-end enterprise training segment. **Critical lifecycle notice**: **Microsoft HoloLens 2 production ended in October 2024** — enterprise AR is contracting, not expanding . **Magic Leap pivoted away from hardware** toward enterprise software . **Pricing varies dramatically**: Meta Quest Pro is **$869–$1,500** , Apple Vision Pro starts at **$3,499** ($3,699 after recent price increases) , HoloLens 2 was **$3,500** , Magic Leap 2 is **₹418,900** in India (~$5,000 USD) , Varjo XR-4 Secure Edition is **$32,468–$38,268** , and Sony SRH-S1 is **$4,750** . No single vendor holds a winner-take-all position.



| Hardware | Description | Pricing (Starting Tier) | Linux/Open-Source Support | Company Size |

|----------|-------------|------------------------|--------------------------|--------------|

| **[Microsoft HoloLens 2](https://www.microsoft.com/en-us/hololens)** | **Enterprise AR headset.** Transparent holographic lenses, hand and eye tracking, voice commands, Azure integration. **Production ended October 2024** . | **$3,500** (US) . **India**: **₹495,000–₹500,000** . | **No official support.** Windows Holographic platform. No Linux or open-source firmware. | **~$281B revenue (Microsoft FY2025)** |

| **[Apple Vision Pro](https://www.apple.com/apple-vision-pro/)** | **Premium spatial computing.** Micro-OLED displays, passthrough, Mac integration, visionOS ecosystem. | **$3,499** (US); **$3,699** after recent component cost increases . **India**: **₹3–5 lakhs** (import) . | **No official support.** visionOS is closed. No Linux installation possible. | **~$400B revenue (Apple FY2025 est.)** |

| **[Meta Quest Pro](https://www.meta.com/quest/quest-pro/)** | **Consumer/prosumer MR headset.** Pancake lenses, face and eye tracking, color passthrough. | **$869–$1,500** (US) . **India**: **₹149,316** (Desertcart) . | **Android-based.** **SideQuest** enables sideloading. **OpenGalea** project uses Quest 3 for BCI . | **Part of Meta (~$165B revenue)** |

| **[Magic Leap 2](https://www.magicleap.com/)** | **Enterprise AR headset.** Lightest AR device at **260g**, dynamic dimming, widest field of view . **Magic Leap pivoted away from hardware** . | **₹418,900** (India) . **Singapore**: **$30,244 SGD** . | **No official support.** Magic Leap OS is proprietary. | **Private (Magic Leap)** |

| **[HTC Vive XR Elite](https://www.vive.com/us/product/vive-xr-elite/)** | **All-in-one VR/AR headset.** Modular design, 12 GB RAM, convertible to glasses form factor. | **₹81,780–₹89,999** (India) . | **Android-based.** Some developer tools available. No Linux installation. | **Private (HTC)** |

| **[Varjo XR-4](https://varjo.com/)** | **High-end enterprise XR.** Highest resolution passthrough, secure edition for defense. | **$32,468–$38,268** (Secure Edition) . **Focal Edition**: **$20,693–$29,219** . | **No official support.** Varjo OS is proprietary. | **Private (~$100M+ raised)** |

| **[Lynx R1](https://lynx-r.com/)** | **Open mixed reality headset.** Modular design, **SteamVR compatible**, **OpenXR support planned** . | **$849** (standard); **$948** (with controllers). **Pro Edition**: **$1,299–$1,398** . | **SteamVR compatible** via streaming. **SideQuest** store for developers. **UnityXR plugin** provided . | **Private (Lynx)** |

| **[Pico 4 Enterprise](https://www.picoxr.com/)** | **Enterprise VR.** Panasonic-backed, 4K+ display, enterprise management tools. | **$943.95** (Knoxlabs) . | **Android-based.** Enterprise SDK available. No Linux support. | **Part of ByteDance** |

| **[Lenovo ThinkReality VRX](https://www.lenovo.com/)** | **Enterprise VR/MR headset.** Snapdragon XR2+ Gen 1, color passthrough, ThinkReality software platform. | **¥243,251–¥249,781** (Japan/Newegg) . | **Android-based.** Enterprise SDK. | **~$60B revenue (Lenovo FY2025 est.)** |

| **[Sony SRH-S1](https://www.sony.com/)** | **Spatial content creation headset.** 4K per-eye OLED microdisplays, Snapdragon XR2+ Gen 2, stylus and ring controllers. **Siemens partnership** for industrial design . | **$4,750** (US) . | **No official support.** Sony's proprietary platform. | **~$30B gaming revenue (Sony FY2025 est.)** |



## 🔓 Open-Source Software Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[OpenGalea](https://github.com/Caerii/OpenGalea)** — **Open-source mixed reality brain-computer interface.** Combines **OpenBCI Cyton board** with **Meta Quest 3** for brain-controlled mixed reality experiences. **~$1,900** total cost vs. **~$30,000** for commercial equivalents — **15.8× more cost-effective** . **Features**: EEG hardware, Unity + Meta XR SDK, colocation with shared spatial anchors, **UDP low-latency communication**, machine learning models for brain signal classification. **Applications**: Gaming (focus to aim, relax to trigger), therapeutic (neuroadaptive meditation), collaborative training, accessibility. **3D-printable headset components** (STL files included). **Open source** — hardware, software, and docs . | [![Stars](https://img.shields.io/github/stars/Caerii/OpenGalea?style=social&color=white)](https://github.com/Caerii/OpenGalea/stargazers) | ~200 |

| **[Godot Engine](https://github.com/godotengine/godot)** — **Open-source game engine with XR support.** **Microsoft released official GDK integration** for Godot in June 2026, enabling **Xbox on PC** development including sign-in, PlayFab, multiplayer, and game saves . Godot XR Tools and OpenXR support provide the foundation for building mixed reality applications without proprietary engines. **MIT License**. | [![Stars](https://img.shields.io/github/stars/godotengine/godot?style=social&color=white)](https://github.com/godotengine/godot/stargazers) | ~95,000 |

| **[Godot XR Tools](https://github.com/godotengine/godot-xr-tools)** — **XR utilities for Godot Engine.** Provides locomotion, UI interaction, hand tracking, and physics for VR/MR development. **MIT License**. | [![Stars](https://img.shields.io/github/stars/godotengine/godot-xr-tools?style=social&color=white)](https://github.com/godotengine/godot-xr-tools/stargazers) | ~1,000 |

| **[OpenXR SDK](https://github.com/KhronosGroup/OpenXR-SDK)** — **Khronos open standard for XR.** Vendor-neutral API for building mixed reality applications that run across multiple headsets. **Apache-2.0**. | [![Stars](https://img.shields.io/github/stars/KhronosGroup/OpenXR-SDK?style=social&color=white)](https://github.com/KhronosGroup/OpenXR-SDK/stargazers) | ~500 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Monado](https://gitlab.freedesktop.org/monado/monado)** — Open-source XR runtime for Linux. Primary OpenXR implementation for Linux-based headsets . |

| **[OpenXR-SDK-Source](https://github.com/KhronosGroup/OpenXR-SDK-Source)** — Source repository for OpenXR SDK. Includes loaders, layers, and sample code . |

| **[SideQuest](https://github.com/SideQuestVR/SideQuest)** — Open-source tool for sideloading apps onto Meta Quest headsets. VR store for indie developers . |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Mixed reality headsets are **commercial hardware**; open-source firmware can extend functionality but may void warranties.

- **Critical lifecycle notices**: **Microsoft HoloLens 2 production ended October 2024** . **Magic Leap pivoted away from hardware** toward enterprise software . Enterprise AR is contracting, not expanding.

- **Open-source reality**: The open-source ecosystem for mixed reality is **focused and emerging**. **OpenGalea** demonstrates that open-source BCI + MR is achievable at **~$1,900** versus **~$30,000** commercial equivalents . **Godot Engine** now has **official Microsoft GDK integration** for Xbox development, opening the door for open-source MR game development . However, **commercial headsets** (HoloLens 2, Vision Pro, Varjo XR-4) provide **polished hardware engineering, enterprise support, and certified safety packages** that open-source alternatives cannot match. The open-source path is **genuinely viable** for research, education, and indie development.



---



**Made for XR developers, spatial computing researchers, enterprise AR teams, and open-source enthusiasts.**

Let's make mixed reality more open, accessible, and developer-friendly.
