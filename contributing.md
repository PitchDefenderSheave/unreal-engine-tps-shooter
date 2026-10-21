# Unreal Engine TPS Shooter

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:F12711,100:F5AF19&height=220&section=header&text=UnrealEngineTpsShooter&fontSize=65&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Master%20The%20Art%20Of%20Third%20Person%20Combat&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-1.9.2-F12711?style=for-the-badge&logo=git&logoColor=white)
![Downloads](https://img.shields.io/badge/downloads-64.3K-F5AF19?style=for-the-badge&logo=download&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-2ECC71?style=for-the-badge&logo=opensourceinitiative&logoColor=white)
![Engine](https://img.shields.io/badge/engine-unreal%20engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)

</div>

---

## 🎮 Build Your Next Hit Shooter

Creating a third-person shooter from scratch is a monumental task. It requires tight character movement, responsive aiming, fluid animation blending, intelligent AI, and a robust weapon system — all working in perfect harmony. **Unreal Engine TPS Shooter** is a comprehensive, open-source template designed to give you a massive head start on your next action game project.

This repository provides a fully playable, highly polished foundation built entirely within Unreal Engine 5. We've combined the power of the new Enhanced Input system, the advanced locomotion framework, and cutting-edge Nanite/Lumen rendering to deliver an out-of-the-box experience that feels like a premium AAA title. Whether you're a solo developer prototyping an idea or a studio building a full-scale commercial product, this template gives you the architectural blueprint you need to succeed.

Instead of spending months building basic movement and shooting mechanics, you can focus your creative energy on what makes your game unique: the story, the art style, and the gameplay loop. We provide the mechanics; you provide the magic.

<img width="960" height="540" alt="956fa63b-2c63-4f3d-9340-daa046a8047d" src="https://github.com/user-attachments/assets/e921c426-a472-4097-887b-30e3c96dafd2" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🏃 **Advanced Locomotion** | Full support for sprinting, sliding, vaulting, and climbing |
| 🔫 **Robust Weapon System** | Hitscan, projectile, and shotgun logic with recoil and spread |
| 🧠 **Smart AI** | Behavior trees for enemy patrol, cover, and flanking tactics |
| 📸 **Dynamic Camera** | Smooth over-the-shoulder aiming with collision avoidance |
| 💥 **VFX And Audio** | High-quality Niagara effects and spatialized sound cues |
| 🎒 **Inventory System** | Seamless weapon switching and ammo management UI |
| 🌐 **Multiplayer Ready** | Fully replicated actor components for online play |
| ⚙️ **Modular Architecture** | Clean, well-commented C++ and Blueprint codebase |

---

## 🚀 Getting Started

Before you begin, ensure you have Unreal Engine 5.2 or higher installed via the Epic Games Launcher.

```bash
# Clone the repository to your local machine
git clone https://github.com/your-username/unreal-engine-tps-shooter.git

# Navigate into the project directory
cd unreal-engine-tps-shooter

# Right-click the .uproject file and select "Generate Visual Studio project files"
# Build the solution in Visual Studio, then launch the editor.
```

Once the editor is open, navigate to the `Content/Maps` folder and open the `Playground` level. Press the Play button and you can immediately control the character, test the weapons, and witness the AI in action.

---

<div align="center">

### 🔗 Ready to jump into the action?

[![Get Template](https://img.shields.io/badge/🎮_GET_TEMPLATE-F12711?style=for-the-badge&logoColor=white)](https://share.google/6IJCjX2F5OZvEqz89)

</div>

---

## 🧠 Deep Dive Into The Architecture

What truly separates a good shooter from a great one is how it feels. Our template places an enormous emphasis on "game feel." The character controller is built on top of Unreal's Character Movement Component, heavily modified to include features like camera shake, controller vibration feedback, and adaptive FOV changes when aiming down sights.

The weapon system is entirely data-driven. We use Data Assets to define everything from the rate of fire to the muzzle flash particle effect. This means you can create a brand new weapon in minutes without writing a single line of code. Need a new assault rifle? Simply duplicate an existing data asset, change the stats, and assign your mesh. The system handles the rest, including the replication logic for multiplayer matches.

The AI uses a custom Behavior Tree service that evaluates line-of-sight, distance, and current health to make intelligent decisions. Enemies will suppress you with suppressive fire, seek cover when reloading, and attempt to flank your position if you stay in one place for too long. This creates dynamic, challenging combat encounters that feel fair and engaging.

---

<div align="center">

### ⚙️ Need a detailed walkthrough?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-F5AF19?style=for-the-badge&logoColor=black)](https://share.google/6IJCjX2F5OZvEqz89)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Blueprints](https://img.shields.io/badge/Blueprints-1E90FF?style=flat-square&logo=unrealengine&logoColor=white)
![Git LFS](https://img.shields.io/badge/Git_LFS-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Game development is better when we build together. We highly encourage you to contribute new features, optimize existing code, or share your custom modifications with the community.

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-weapon`).
3. **Commit** your changes (`git commit -m 'Add new weapon'`).
4. **Push** to the branch (`git push origin feature/new-weapon`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and asset naming conventions. We also have a Discord server where you can showcase your progress, ask for help with Blueprint logic, and find collaborators for your next big project.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@unreal-tps.dev.

---

<div align="center">

### ⭐ If this template helps you build your dream game, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-2ECC71?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username/unreal-engine-tps-shooter)

---

### 🚀 Start building your masterpiece today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-0E1128?style=for-the-badge&logoColor=white)](https://share.google/6IJCjX2F5OZvEqz89)

<sub>Crafted with precision and ❤️ by the Unreal Engine TPS community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:F5AF19,100:F12711&height=120&section=footer)

</div>
