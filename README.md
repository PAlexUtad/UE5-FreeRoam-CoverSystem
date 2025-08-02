# 🧱 UE5 Free-Roam Cover System

A compact, highly customizable **C++ Cover System Component** for Unreal Engine 5.  
Snap to walls, crouch or stand automatically, detect corners, and dynamically transfer between covers with a root motion animation (of your choice).

---

### 🎮 Core Features

- 🧱 **Static Mesh-Based Covers**  
  Works out-of-the-box with any static mesh acting as a wall or cover geometry.

- 🧠 **Automatic Crouch Detection**  
  Dynamically determines whether the player should crouch or stand based on wall height in front of them.

- 🔄 **Corner Detection with Player Choice**  
  When reaching a corner, the system halts movement until the player explicitly inputs a direction to peek or transition, giving control back to the player.

- 🔫 **Combat-Ready from Cover**  
  Fully compatible with aiming and firing systems; capsule collision automatically adjusts depending on the player's stance.

- 🧗 **Traversal-Ready**  
  Designed to work with vaulting, mantling, and other traversal mechanics.

- ↔️ **Cover-to-Cover Transitions**  
  When exiting a cover with directional input, the component performs a sphere trace ahead.  
  If another cover is found, it plays a roll animation and snaps to the new cover automatically.

---

### 🛠️ Integration

1. Add the component to your custom character class.
2. Call `StartCover()` from input or AI logic.
3. Customize detection radii, offsets, movement speeds, etc.
4. Use your own montages, sounds, or UI feedback.

---

### 🎥 Demo 
![cover1](https://github.com/user-attachments/assets/bdeb7d1c-2e2e-4309-b15c-9490dc48babe)
![cover12](https://github.com/user-attachments/assets/cce9b122-14b9-4347-be58-219c3a4c1aef)
![cover123](https://github.com/user-attachments/assets/dd3962c4-304b-4a55-8eed-dab0ad5b760e)



