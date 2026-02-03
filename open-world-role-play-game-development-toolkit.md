# OPEN WORLD RPG GAME DEVELOPMENT TOOLKIT

<p align="center">

![Project](https://img.shields.io/badge/PROJECT-OPEN%20WORLD%20RPG%20GAME%20DEVELOPMENT%20TOOL%20KIT-111111?style=for-the-badge)

</p>

![NOTE](https://img.shields.io/badge/PROJECT-SUMMARY-FF6F61?style=for-the-badge)

> The Open World RPG Development Toolkit is a blueprint framework designed for game developers who want to create open-world role-playing games using the powerful Unreal Engine. With this toolkit, developers can build immersive and expansive worlds, featuring customizable character controllers, dialogue systems, weapon systems, and much more.

> The framework is highly modular and flexible, allowing developers to craft unique RPG experiences that match their vision. One of its core features is a comprehensive inventory system, which simplifies the creation and management of player inventories, interactable objects, and pickups. Additionally, the toolkit provides tools for branching storylines, scripted events, and other dynamic elements, ensuring that players remain engaged and immersed in the game world.

> Overall, the Open World RPG Development Toolkit is a complete suite of tools for developing immersive role-playing games in Unreal Engine. Its modular design and customizable features give developers the flexibility to create distinctive RPG experiences that captivate and delight players.



## KEY FEATURES
<details open>
  <summary>
    <img src="https://img.shields.io/badge/01-Advanced%20Player%20Movements-00C2FF?style=for-the-badge" alt="Advanced Player Movements">
  </summary>

- **Armed movements** – In armed movements, the player can run, walk, sprint, crouch, and roll **with a weapon**.  
- **Unarmed movements** – In unarmed movements, the player can run, walk, sprint, crouch, and roll **without a weapon**.

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/02-Weapon%20System-00C2FF?style=for-the-badge" alt="Weapon System">
  </summary>

- **Primary weapon** – The main weapon available to the player.  
- **Secondary weapon** – A backup weapon for combat situations.  
- **Handgun** – A small, fast-firing firearm for quick encounters.  

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/03-Dialogue%20System-00C2FF?style=for-the-badge" alt="Dialogue System">
  </summary>

- This section describes the dialogue system in the toolkit in detail. Open world RPGs mostly use **interactable dialogue systems** for quests or NPC interactions. This toolkit implements an interactive dialogue system to the **standard of open world RPG games**.  

- It is implemented as an **actor class** containing an invisible trigger. When a character enters the collision, it activates the dialogue functionalities. The **sound manager class** holds an array of dialogue audio files for playback.  

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/04-Inventory%20System-00C2FF?style=for-the-badge" alt="Inventory System">
  </summary>

- This section describes the inventory system in detail. The inventory manages all objects the player interacts with during gameplay.  

- It is implemented using **arrays**, with customizable slot numbers. Each slot can hold any object. If a player picks up an item already in the inventory, it **stacks in the same slot**.  

- Slot numbers are temporarily stored in a variable, making it easy to manage pickups. Clicking on an inventory slot allows the player to **use the item**, and hovering shows a **brief description**.  

- Pickup items are derived from a **master pickup class**, allowing the creation of multiple item types by inheritance. Each item’s properties can be customized in the **property panel**.  

- The inventory UI has a **game-ready look**, conforming to open world RPG standards, so it can be used directly without further implementation.  

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/05-Intractable%20Drone%20System-00C2FF?style=for-the-badge" alt="Intractable Drone System">
  </summary>

- This toolkit includes a functionality for an **interactable drone vehicle**, a new feature in the Open World RPG development toolkit.  

- When a player interacts with the drone, the **player controller switches** from the character to the drone. The drone has a **customizable input system**, allowing different control schemes.  

- The drone supports **first-person and third-person views**, giving players a unique experience as they shift between perspectives during gameplay.  

</details>



## Screenshots
<details open>
  <summary>
    <img src="https://img.shields.io/badge/01-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>
  
  <img src="open-world-role-play-game-development-toolkit_19.jpeg" alt="Image1" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/02-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>
  
  <img src="open-world-role-play-game-development-toolkit_20.jpeg" alt="Image1" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>
<details open>
  <summary>
    <img src="https://img.shields.io/badge/03-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>
  
  <img src="open-world-role-play-game-development-toolkit_21.jpeg" alt="Image1" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>
<details open>
  <summary>
    <img src="https://img.shields.io/badge/04-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>
  
  <img src="open-world-role-play-game-development-toolkit_22.jpeg" alt="Image1" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>
<details open>
  <summary>
    <img src="https://img.shields.io/badge/05-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>
  
  <img src="open-world-role-play-game-development-toolkit_1.jpg" alt="Image1" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/06-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_2.jpg" alt="Image2" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/07-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_3.jpg" alt="Image3" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/08-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_4.jpg" alt="Image4" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/09-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_5.jpg" alt="Image5" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/10-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_6.jpg" alt="Image6" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/11-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_7.jpg" alt="Image7" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
    <summary>
    <img src="https://img.shields.io/badge/12-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_8.jpg" alt="Image8" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/13-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_9.jpg" alt="Image9" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
    <summary>
    <img src="https://img.shields.io/badge/14-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_10.jpg" alt="Image10" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
    <summary>
    <img src="https://img.shields.io/badge/15-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_11.jpg" alt="Image11" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/16-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_12.jpg" alt="Image12" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/17-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_13.jpg" alt="Image13" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/18-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_14.jpg" alt="Image14" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/19-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_15.jpg" alt="Image15" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/20-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_16.jpg" alt="Image16" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/21-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_17.jpg" alt="Image17" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/22-Snap%20Shot-ffce2b?style=for-the-badge" alt="Intractable Drone System">
  </summary>

  <img src="open-world-role-play-game-development-toolkit_18.jpg" alt="Image18" width="800" style="border: 2px solid #ddd; border-radius: 8px;">
  
</details>


## Project Summary

| **Category**       | **Details**                           |
|--------------------|---------------------------------------|
| **Platform**       | Unreal Engine Editor                   |
| **Languages**      | C++, Blueprints                        |
| **API**            | None                                   |
| **Version Control**| GitHub                                  |
| **Deployment**     | Unreal Engine 4.27                     |



## Installation

Provide step-by-step instructions on how to install your project.

```bash
# Example installation commands
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
npm install
