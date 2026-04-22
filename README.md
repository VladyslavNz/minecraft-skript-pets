# 🐾 Pets System (Skript)

A simple and customizable pet system made with Skript for Minecraft servers.

Players can spawn pets, rename them, apply particle effects, and have them follow automatically.

---

## ✨ Features

* 🐺 Multiple pet types:

  * Wolf, Cat, Parrot, Fox, Rabbit
  * Bee, Turtle, Panda
  * Chicken, Cow

* 📦 GUI menu (`/pets`)

* 🧍 Smart follow system (pathfinding + teleport if too far)

* 🎨 Particle effects system

* 🏷️ Pet renaming via chat

* ❌ Despawn pet option

* 🛡️ Pets are protected from damage

* 🔄 Automatic removal on player quit

---

## 🎮 Command

```
/pets
```

Opens the main pet menu.

---

## 🖥️ GUI Menus

### Main Menu
<img width="344" height="144" alt="image" src="https://github.com/user-attachments/assets/81247f5f-067d-4e97-b5a7-1adbce95e291" />

* **Mobs** – Select your pet
* **Despawn Pet** – Remove current pet
* **Particles** – Choose particle effects
* **Rename Pet** – Rename your pet via chat

### Pet Selection
<img width="343" height="135" alt="image" src="https://github.com/user-attachments/assets/ff596951-6871-490a-baa8-a501bc5bc490" />

Choose from different animals.
Spawning a new pet will automatically remove the old one.

### Particles Menu
<img width="343" height="79" alt="image" src="https://github.com/user-attachments/assets/5cb6dad3-f873-4bf9-ba46-f478e772ac79" />

Available effects:

* Flame 🔥
* Hearts ❤️
* Slime 🟢
* Magic ✨
* None

---

## 🤖 How It Works

* Pets follow the player using navigation (NMS via skript-reflect)
* If distance > 15 blocks → pet teleports
* If distance 3–15 → pet walks using pathfinding
* If close → stops moving

Particles are displayed every few ticks above the pet.

---

## 🏷️ Rename System

* Click **Rename Pet**
* Type name in chat
* Name is saved and applied instantly

---

## 📦 Requirements

Make sure you have these plugins installed:

* **Skript**
* **SkBee**
* **skript-reflect**

---

## 📥 Installation

1. Install required plugins
2. Put the script file into:

   ```
   /plugins/Skript/scripts/
   ```
3. Reload Skript:

   ```
   /skript reload <filename>
   ```

---

## ⚠️ Notes

* Only one pet per player
* Pets are automatically removed on logout
* Pets cannot take damage
* Uses NMS navigation (requires skript-reflect)

---
### 🧪 Tested Version

Tested on 1.21.11

## 👤 Author

Created by VladyslavNz

---
