# Orange Pi 5 Pro Gaming (Yocto Edition)

*Bringing Desktop-class gaming to the RK3588 SBC.*

Most distributions for the Orange Pi 5 are bloated with background services. My Yocto-based image is stripped to the bone, redirecting all CPU/GPU resources to the game.

## Key Features:
* **UI:** RetroArch integrated as the default desktop environment.  
* **Compatibility:** Pre-configured **Box64, Wine, and DXVK** for running x86/Windows games on ARM.
* **Optimization:** Custom kernel patches for lower input lag and optimized Mali GPU drivers.
* **Performance:** Up to 15-20% better FPS compared to standard Debian/Armbian builds in CPU-bound emulators.  
* **Dynamic Mali/Mesa** Select GPU library dynamically.  
* **Custom NTSYNC** Use custom NTSYNC Driver for wine synchronization process.  

## # 🎮 Orange Pi 5 Pro: Yocto Gaming Performance Showcase

This document provides a visual demonstration of the **EmbeddedBitbake** Yocto image running high-quality PC games on the Orange Pi 5 Pro (RK3588). 

Unlike standard distributions, this image uses a custom-compiled **Box64 + Wine + DXVK** stack with kernel-level optimizations to ensure smooth framerates and low input latency.

---

## 📽️ Game Compatibility & Performance Gallery

Below are real screenshots captured directly from the hardware running our Yocto build.  

### 🍃 A Short Hike  

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/a.short.hike/image-0.png)
![Screen 1](./image/a.short.hike/image-1.png)
![Screen 2](./image/a.short.hike/image-2.png)

### 🌸 Bō: Path of the Teal Lotus  
Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/bo.ath.of.the.teal.lotus/image-0.png)
![Screen 1](./image/bo.ath.of.the.teal.lotus/image-1.png)
![Screen 2](./image/bo.ath.of.the.teal.lotus/image-2.png)

### 🐱 Cat Quest 3

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/cat.quest.3/image-0.png)
![Screen 1](./image/cat.quest.3/image-1.png)

### 🏔️ Celeste

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/celeste/image-0.png)
![Screen 1](./image/celeste/image-1.png)

### ⚔️ Deviator

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/deviator/image-0.png)
![Screen 1](./image/deviator/image-1.png)
![Screen 2](./image/deviator/image-2.png)

### 🐒 Gibbon: Beyond the Trees

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/gibbon.beyond.the.trees/image-0.png)
![Screen 1](./image/gibbon.beyond.the.trees/image-1.png)
![Screen 2](./image/gibbon.beyond.the.trees/image-2.png)

### 🎁 Gift

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/gift/image-0.png)
![Screen 1](./image/gift/image-1.png)
![Screen 2](./image/gift/image-3.png)

### 💎 Hyper Light Drifter

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/hyper.light.drifter/image-0.png)
![Screen 1](./image/hyper.light.drifter/image-1.png)
![Screen 2](./image/hyper.light.drifter/image-4.png)

### 🍄 Lone Fungus

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/lone.fungus/image-0.png)
![Screen 1](./image/lone.fungus/image-1.png)

### ☀️ Nine Sols

Running on :

OS: Yocto Custom  
Kernel: Armbian BSP 6.1.115  
Application : Box64, Wine, DXVK

![Screen 0](./image/nine.sols/image-0.png)
![Screen 1](./image/nine.sols/image-1.png)
![Screen 2](./image/nine.sols/image-2.png)

---