# YOU-ARE-NOT
Build. Play. Win on Solana! A fateful battle: The Undead King and the Legendary Hero. Who will win? And we... 
| Controls: W/A/S/D — move | LMB — action | F — entry mode |


# Submission to 2025 Solana Colosseum Submission by:
- Nazar Torekhanov. Game Designer, 3D Modeler. [GitHub](https://github.com/H-Z-N). [TG](https://t.me/tor_T_N). [X](https://x.com/hybrid_Z_N).
- Sultan Batyrkhanov. Systems Programmer. [TG](https://t.me/DeadmaidenILS).
- Nurali Amangeldiyev. Unity Developer. [TG](https://t.me/Cubex33).
- Ramil Gimaletdinov. Environment Designer. [TG](https://t.me/ramilgrr).

# Resources
- ссылка на презентацию проекта
- ссылка на видео о проекте
- https://idosgames.com/en/app/?id=FN8Z66LE
- https://t.me/game_you_are_not
- https://www.youtube.com/channel/UCSxlhQkcR0JBp_j8R03nc6Q

# Problem and solution
1. High latency:
- RPC → TPU → Banking Stage causes 300–500 ms delay and missed arbitrage.
- BBM: Direct Trader → BBM with pre-simulation cuts latency to 50–100 ms.
2. Inefficient block assembly:
- Validators fill blocks only 70–80 %, wasting compute on conflicts.
- BBM: Parallel processing, conflict resolution, optimized bundles.
3. Limited transaction logic:
 - Solana lacks conditional execution and privacy.
 - BBM: Adds conditional and atomic bundles with concealed content.
4. App-controlled execution:
- Validators dictate order, enabling MEV.
- BBM: Lets apps set their own auction logic and fair ordering.
# Summary of Submission Features

- Integration with IDos Games SDK for player authentication and reward system

- Play-to-Earn mechanics — players earn in-game currency after completing levels

- In-game currency convertible to Sovana cryptocurrency

- Custom-built C# game framework created by our team

- Cross-platform availability — playable both in browser and Windows

- Secure wallet connection through IDos Games platform

- Offline mode support for local builds

- Developed with Unity Engine (URP, Cinemachine, TextMeshPro, Input System)

- Optimized for low-end PCs (lightweight assets and shaders)

# Tech Stack
Languages:

- C#

Frameworks:

- Custom in-house game framework built by our team

SDKs:

- IDos Games SDK

Libraries:

- UnityEngine API

- Cinemachine (camera system)

- TextMeshPro (UI text rendering)

- Input System (player input handling)

- URP (Universal Render Pipeline) for lighting and post-processing

# Architecture
[User] 
   │
   ▼
[Login via Aidos Games SDK]
   │
   ▼
[Access to Game Framework]
   │
   ▼
[Gameplay Layer]
   │
   ├── Game Logic (C# Scripts)
   ├── Player Controller (Input System)
   ├── Environment (Level Design, Lighting, VFX)
   └── UI System (Menus, Currency Display)
   │
   ▼
[Completion of the Game]
   │
   ▼
[Reward System]
   │
   └── User receives in-game currency
           ▼
           Can be exchanged for Sovana cryptocurrency


# Quick start

### **Installation & Launch Guide**

There are **two ways** to try our game:

#### Option 1 — Windows Version (Recommended)

1. This repository:

   git (https://github.com/H-Z-N/YOU-ARE-NOT.git)
   
2. Open the folder `Build/Windows/`
3. Run the executable file:

   ```
   YourGameName.exe
   ```
4. Play and enjoy!

*(This version provides the most stable performance and works without requiring an SDK login.)*

---

#### Option 2 — Web Version (via Aidos Games)

1. Go to **[IDos Games Platform](https://idosgames.com/en/app/?id=FN8Z66LE)**
2. Log in using your **IDdos Games account**
3. Launch the game directly from the site
4. After completing the game, you’ll receive **in-game currency**, which can be exchanged for **Sovana cryptocurrency**
