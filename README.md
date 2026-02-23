# Hi there, I'm Syed S. Mashaam

**Embedded Systems Engineer · IoT Systems · Real-Time OS · Hardware Designer · Embedded System Architecture**

---

I'm a embedded systems engineer who lives at the boundary between hardware and the firmware. Most of my time goes into writing C code for microcontrollers, designing real-time task architectures with FreeRTOS, and wiring tiny embedded devices into large-scale cloud backends. I'm drawn to the challenge of making constrained hardware do surprisingly sophisticated things reliably, securely, and at scale.

I currently work at **Azoox Technologies Pvt. Ltd.**, where I develop production firmware and hardware for clientels like Urban Company, Schneider Electric, Yamaha, and Panasonic.

---

### What I'm building

- **WiserVC** — A voice controller based on the Espressif's ESP32-S3. It listens for a wake word using Espressif's on-device neural network (WakeNet), recognizes custom voice commands with MultiNet, and controls smart switches both through Azure IoT Hub over MQTT and locally through mDNS-discovered WebSocket connections — all at the same time.

- **Mini Co-Pilot** — A brand agnostic, multi appliance, integrated full stack diagnostic system.

- **4G/2G Payment Soundbox** — 

- ****

Both projects are part of a connected ecosystem: the voice controller discovers and controls the switches locally when the cloud isn't reachable, and syncs state back up when it is.

---

### What I'm learning 🌱

- Offline-first IoT design — building systems that degrade gracefully without a cloud connection and recover cleanly when it comes back
- Production security for embedded devices — per-device certificate provisioning, NVS encryption, and secure boot on ESP32
- Tighter RTOS patterns — task pools, event-driven state machines, and deterministic inter-task communication using FreeRTOS event groups and queues

---

### Tech stack 🛠️

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=flat&logo=powershell&logoColor=white) 
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white) 

**Platforms & Frameworks**

![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8CC84B?style=flat-square)
![Azure IoT](https://img.shields.io/badge/Azure_IoT-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white)
![Mosquitto](https://img.shields.io/badge/mosquitto-%233C5280.svg?style=flat&logo=eclipsemosquitto&logoColor=white)

**Protocols**

`BLE 5.0` · `MQTT over TLS` · `WebSocket Secure (WSS)` · `mDNS` · `HTTP/HTTPS`

**Hardware**

`ESP32-S3` · `PDM Microphones (I2S)` · `WS2812B LEDs` · `Relay Control` · `GPIO`

---

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=shigarf&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=shigarf&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=shigarf&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

---

### A bit more ⚡

There's something genuinely satisfying about squeezing a wake-word neural network, a full TLS stack, an MQTT client, a BLE provisioning service, and a WebSocket client onto a chip with 16MB of flash — and watching it all hold together under real-world conditions. That puzzle is what keeps me interested.

I care a lot about the engineering details: task stack sizing, reconnection logic with proper backoff, flash partition layout, certificate lifecycle. The stuff that looks boring on paper but determines whether a device works in someone's house a year after it ships.

---

### Get in touch 📫

Feel free to reach out. I'm always happy to talk embedded systems, IoT architecture, or anything that runs close to the metal.

[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:shigarfmashaam2@gmail.com)
