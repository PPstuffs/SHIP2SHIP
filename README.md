# SHIP2SHIP

SHIP2SHIP is a horizontal scrolling spaceship themed videogame, taking inspiration from the legendary R-Type game (1987).

## Short description

In SHIP2SHIP, you play as a human, who just managed to escape from alien prison within the alien mothership, by stealing an alien spaceship.
They have sent all their spaceships after you to stop you from making it back to earth.
You would totally use your newfound spaceship to shoot back at them, but... unfortunately, you could only figure out how to fly it, not use it's weapons!
So, as a remedy... you can instead jump from ship to ship, hijacking aliens' and continuing on, while dodging all of their bullets!
You must be careful to jump out of your ship before it gets blown up, but also before it self-destructs! (due to their human lifeform detection system)
All you need is to survive for just over 10 minutes... Give it your best!

SHIP2SHIP features co-op with up to 7 players (but we could make it much higher honestly), so, have fun with that!

## Installation

### Windows

Download and execute the installer, then follow its steps:
```txt
<github-link-to-installer>
```

### Linux

Execute this set of commands:
```bash
sudo apt update && sudo apt install unzip wget libcsfml-dev # install dependencies
wget https://github.com/PPstuffs/SHIP2SHIP/archive/refs/heads/main.zip -O repo.zip -O ship2ship.zip # Download the game
unzip ship2ship.zip # unzip it
sudo mkdir -p /opt/SHIP2SHIP # Create the folder for the game
sudo cp -r SHIP2SHIP-main/linux/. /opt/SHIP2SHIP/ # Copy the game inside the folder
sudo cp -r SHIP2SHIP-main/assets /opt/SHIP2SHIP/ # Copy assets inside the folder
sudo chmod +x /opt/SHIP2SHIP/SHIP2SHIP # Allow the game to be executed
sudo cp /opt/SHIP2SHIP/SHIP2SHIP.desktop /usr/share/applications/ # Add the game to your desktop
rm -rf ship2ship.zip SHIP2SHIP-main # Remove temporary zip file
```

## Credits

### Development

- Online development: Pamplemom & Pathie
- Game development: Pathie
- UI development: Pamplemom

- Music and SFX: Pathie
- Game Art: Frost
- UI Art: Pamplemom

### Special thanks:


# Uninstall :(

### Windows

Search our game inside the start menu, you should have an option to uninstall. Press it and follow the steps.

### Linux

Simply execute this set of functions
```bash
sudo rm -rf /opt/SHIP2SHIP # Remove the game files
sudo rm -f /usr/share/applications/SHIP2SHIP.desktop # Remove destop icon
sudo update-desktop-database /usr/share/applications 2>/dev/null || true # Refresh app database
```

---

Thanks to all!
