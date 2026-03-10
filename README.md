# Galaxy Fighters 🛸

A thrilling two-player space combat game built with Pygame where two spaceships battle it out in an epic galactic showdown!

## 📋 Description

Galaxy Fighters is a local multiplayer game where two players control spaceships on opposite sides of the screen. Each player can move their spaceship and fire bullets at their opponent. The first player to reduce their opponent's health to zero wins!

## ✨ Features

- **Two-Player Local Multiplayer**: Battle against a friend on the same keyboard
- **Health System**: Each player starts with 10 health points
- **Bullet Mechanics**: Fire up to 3 bullets at a time per player
- **Sound Effects**: Immersive audio for shooting and hit detection
- **Real-time Health Display**: Track both players' health on screen
- **Victory Screen**: Displays the winner when a player's health reaches zero
- **Space-Themed Graphics**: Custom spaceship sprites and space background

## 🎮 Controls

### Yellow Spaceship (Left Side)
- **W**: Move Up
- **A**: Move Left
- **S**: Move Down
- **D**: Move Right
- **Q**: Fire Bullet

### Red Spaceship (Right Side)
- **↑**: Move Up
- **←**: Move Left
- **↓**: Move Down
- **→**: Move Right
- **SPACE**: Fire Bullet

## 🛠️ Requirements

- Python 3.x
- Pygame library

## 📦 Installation

1. Clone this repository:
   ```
   git clone https://github.com/uzairrrhussain/galaxy-fighters.git
   cd galaxy-fighters
   ```

2. Install the required dependencies:
   ```
   pip install pygame
   ```

3. Ensure you have the required assets in the `Assets` folder:
   - `spaceship_yellow.png` - Yellow spaceship sprite
   - `spaceship_red.png` - Red spaceship sprite
   - `space.png` - Space background image
   - `Grenade+1.mp3` - Bullet hit sound effect
   - `Gun+Silencer.mp3` - Bullet fire sound effect



## 🎯 Game Rules

1. Each player starts with **10 health points**
2. Players can fire up to **3 bullets** at a time
3. Each successful hit reduces the opponent's health by **1 point**
4. The game ends when one player's health reaches **0**
5. Players cannot cross the center dividing line

## 🎨 Customization

You can customize the game by modifying these variables in the code:

- `VEL`: Player movement speed (default: 5)
- `BULLET_VEL`: Bullet speed (default: 7)
- `MAX_BULLETS`: Maximum bullets per player (default: 3)
- `FPS`: Frames per second (default: 60)
- `SPACESHIP_WIDTH` & `SPACESHIP_HEIGHT`: Spaceship dimensions
- Starting health values (default: 10 for each player)


## 📝 Future Enhancements

- [ ] Implement power-ups (health packs, rapid fire, shield)
- [ ] Add background music
- [ ] Create single-player mode with AI opponent
- [ ] Add different weapon types
- [ ] Implement a score/round system
- [ ] Add particle effects for explosions
- [ ] Create a main menu and settings screen
- [ ] Add online multiplayer capability


## 🎮 Tips for Players

- Keep moving to avoid enemy bullets
- Don't waste all your bullets at once - aim carefully!
- Use the center border as cover strategically
- Watch your opponent's bullet count to know when to attack


---
