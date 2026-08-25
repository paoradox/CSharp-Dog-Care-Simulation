# CSharp-Dog-Care-Simulation — Dog Hut: A Dog Care Simulation

[![Built with](https://img.shields.io/badge/built_with-Unity_3D-02aaff?style=for-the-badge&logo=unity)](https://unity.com/)
[![Language](https://img.shields.io/badge/language-C%23-02aaff?style=for-the-badge&logo=csharp)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Platform](https://img.shields.io/badge/platform-Android-02aaff?style=for-the-badge&logo=android)](https://www.android.com/)

**Dog Hut** is a 3D Android-based dog care simulation application developed in C# using the Unity 3D game engine. It was created as a research project to explore how interactive virtual pet games can help children aged 9–11 develop empathy, responsibility, and an understanding of basic dog care concepts.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Virtual Dog Ownership** | Adopt and name a dog, choose from different breeds, and care for it |
| **Interactive Gameplay** | Swipe, tap, and drag to feed, bathe, play with, and groom your virtual pet |
| **Realistic Needs** | The dog gets hungry, thirsty, dirty, and tired — just like a real pet |
| **Health System** | Dogs can become sick (stomachache, diarrhea, skin dryness) and need veterinary care |
| **Day/Night Cycle** | Time-based mechanics with daily rewards and scheduled events |
| **Achievements** | Unlock rewards and track your progress as a dog owner |
| **Notifications** | Stay informed about your dog’s status and upcoming needs |
| **3D Environment** | Explore a fully 3D house with rooms: Living Room, Kitchen, Bathroom, Bedroom, Clinic, and Dog Store |
| **Augmented Reality (AR)** | Play outside with your dog using AR features |

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Game Engine** | Unity 3D (version 5.01f1) |
| **Programming Language** | C# |
| **IDE** | MonoDevelop |
| **Database** | SQLite 3 |
| **Platform** | Android (version 4.0 Ice Cream Sandwich or higher) |
| **3D Modeling** | Autodesk 3ds Max, Blender |
| **Audio** | Adobe Audition, Audacity |
| **Graphics** | Adobe Photoshop, Adobe Illustrator |

---

## 📂 Project Structure

```
CSharp-Dog-Care-Simulation/
├── Assets/                 # All game assets (scripts, scenes, models, textures)
│   ├── Scripts/            # C# scripts for game logic
│   ├── Scenes/             # Unity scene files
│   ├── Models/             # 3D models (dog, furniture, environment)
│   ├── Textures/           # UI textures, environment textures
│   ├── Audio/              # Sound effects and background music
│   └── Prefabs/            # Reusable game objects
├── ProjectSettings/        # Unity project settings
├── Builds/                 # Compiled APK files
├── Documentation/          # SRS, SDD, and research documents
│   ├── Dog Hut - SRS.pdf
│   ├── Dog Hut - SDD.pdf
│   └── Dog Hut - Thesis.pdf
└── README.md               # This file
```

---

## 🚀 Getting Started

### Prerequisites
- **Unity 3D** (version 5.01f1 or newer) installed on your system
- **Android SDK** and **JDK** configured for Android builds
- (Optional) An Android device (version 4.0+) for testing

### Build from Source
1. **Clone the repository**
   ```bash
   git clone https://github.com/paoradox/CSharp-Dog-Care-Simulation.git
   ```
2. **Open the project in Unity**
   - Launch Unity Hub and click "Add Project"
   - Navigate to the cloned folder and select it
   - Open the project in Unity
3. **Build for Android**
   - Go to `File > Build Settings`
   - Switch platform to Android
   - Click `Build` and save the APK file
4. **Install on your Android device**
   - Transfer the APK to your phone
   - Enable "Install from Unknown Sources" in settings
   - Open the APK file to install

---

## 📸 Preview

Here are some screenshots from the game, showcasing its interface and key features:

### Dog Selection & Buying
| Choose a Breed | Dog Summary | Name Your Dog |
|----------------|-------------|---------------|
| ![Buy a Dog](Preview%20Screenshots/B.3%20Buy%20Dog_compressed.PNG) | ![Dog Summary](Preview%20Screenshots/B.3%20Buy%20Dog_compressed.PNG) | ![Name Your Dog](Preview%20Screenshots/B.3.3%20Dog%20Naming%20Interface_compressed.PNG) |

### In-Game Rooms
| Living Room | Kitchen | Bathroom |
|-------------|---------|----------|
| ![Living Room](Preview%20Screenshots/B.3%20Buy%20Dog_compressed.PNG) | ![Kitchen](Preview%20Screenshots/B.7%20Kitchen_compressed.PNG) | ![Bathroom](Preview%20Screenshots/B.6%20Bathroom_compressed.PNG) |

| Bedroom | Clinic | Dog Store |
|---------|--------|-----------|
| ![Bedroom](Preview%20Screenshots/B.8%20Bedroom_compressed.PNG) | ![Clinic](Preview%20Screenshots/B.9%20Clinic2_compressed.PNG) | ![Dog Store](Preview%20Screenshots/B.11%20Dog%20Store_compressed.PNG) |

### Gameplay
| Feeding the Dog | Bathing the Dog | Playing Outside |
|-----------------|-----------------|-----------------|
| ![Feed Dog](Preview%20Screenshots/B.7.1%20Feed%20Dog_compressed.PNG) | ![Bathe Dog](Preview%20Screenshots/B.6.1%20Bathe%20Dog2_compressed.PNG) | ![Play Outside](Preview%20Screenshots/) |

| Achievements | Notifications | Game Settings |
|--------------|---------------|---------------|
| ![Achievements](Preview%20Screenshots/B.12%20View%20Achivements_compressed.PNG) | ![Notifications](Preview%20Screenshots/B.13%20Notifications_compressed.PNG) | ![Game Settings](Preview%20Screenshots/B.15%20Game%20Settings_compressed.PNG) |

---

## 🎮 Gameplay Overview

### Core Mechanics
- **Dog Status Tracking**: Hidden meters track your dog's health, hygiene, hunger, thirst, and happiness
- **Room-Based Interaction**: Move between rooms to perform specific activities
- **Time-Based Events**: The dog's needs change over time; daily rewards are available

### Key Activities
| Activity | Location | Action |
|----------|----------|--------|
| **Feed** | Kitchen | Drag food to the bowl to feed your dog |
| **Bathe** | Bathroom | Apply soap and shampoo to clean your dog |
| **Rest** | Bedroom | Let your dog sleep and regain energy |
| **Play** | Backyard | Train your dog to run, fetch, sit, and search |
| **Check-up** | Clinic | Visit the vet for health checks, vaccinations, and deworming |
| **Groom** | Clinic | Brush, clip nails, and trim fur |
| **Shop** | Dog Store | Buy food, clothing, hygiene products, utensils, and toys |

---

## 🧪 Testing

The application was developed using the **Game Development Life Cycle (GDLC)** methodology:

| Phase | Description |
|-------|-------------|
| **Initiation** | Concept and idea generation |
| **Pre-production** | Game design, prototyping, and requirements definition |
| **Production** | Asset creation, coding, and integration |
| **Testing** | Alpha and beta testing with advisers and panelists |
| **Release** | Deployment and evaluation |

---

## 📄 Documentation

Comprehensive documentation is available in the `Documentation/` folder:
- **Software Requirements Specification (SRS)** — Detailed functional and non-functional requirements
- **Software Design Document (SDD)** — Architecture, data design, and UI specifications
- **Thesis Document** — Full research paper with background, methodology, and conclusions

---

## 👥 Contributors

| Name | Role |
|------|------|
| **Jentzen Paolo A. Javier** | Developer, UI/UX Design, 3D Modeling, Research |
| **Aubrey G. Cabanlig** | Developer, Research, Documentation |
| **Melchor O. Cariño** | Developer, 3D Modeling, Animation |
| **Allan A. Emilio** | Developer, Programming, Testing |

### Advisers & Panelists
- **Cherry Ann C. Carpiso** — Subject Adviser
- **Erna-Kristi N. Martinez** — Technical Adviser
- **Cherrie L. Almazan** — Panelist
- **Glammoco C. Camora** — Panelist
- **Perry A. Agustin Jr.** — Panelist
- **Dr. Ellen M. Halover** — Dean, School of Information Technology

---

## 📜 License & Disclaimer

This project is **freeware** and was created for **educational and research purposes**.

> **DOG HUT COMES WITH ABSOLUTELY NO WARRANTY.**  
> This software is provided "as is" without any warranties of any kind, either expressed or implied.

- **No commercial use** — This project was not intended for commercial distribution.
- **Modify at your own risk** — Source code is provided for learning purposes.
- **Attribution** — Some methodologies and assets may be owned by their respective authors.

---

## 🙏 Acknowledgements

- **Unity Technologies** — For providing the Unity 3D game engine.
- **Microsoft** — For the C# programming language and .NET framework.
- **Ilovepaws** — For dog care concepts used in the research.
- **PAWS Animal Rehabilitation Center (PARC)** — For veterinary care insights.
- **University of Baguio** — For supporting this research project.

---

**Dog Hut** — A Research Project by BSIT Students, University of Baguio · 2016
