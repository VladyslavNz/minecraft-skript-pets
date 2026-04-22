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

* **Mobs** – Select your pet
* **Despawn Pet** – Remove current pet
* **Particles** – Choose particle effects
* **Rename Pet** – Rename your pet via chat

### Pet Selection

Choose from different animals.
Spawning a new pet will automatically remove the old one.

### Particles Menu

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

## 👤 Author

Created by VladyslavNz

---
