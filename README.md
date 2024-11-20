# Text-Based Adventure Game

A simple text-based adventure game implemented in Java. The goal of the game is to navigate through different rooms, interact with NPCs, fight enemies, and collect the treasure in the Treasure Room.

## Features
- **Room Exploration**: Navigate through different rooms using directional commands (`north`, `south`, `east`, `west`).
- **Inventory Management**: Collect items like potions and treasures and view them in your inventory.
- **NPC Interaction**: Talk to Non-Player Characters (NPCs) for hints or items.
- **Combat System**: Engage in combat with enemies using attack and run options.
- **Win and Lose Conditions**: Win by collecting the treasure, or lose if your health drops to zero.

## How to Play
1. Run the program using a Java compiler.
2. Follow the on-screen instructions to explore the game world.

### Commands
- `go <direction>`: Move to a different room in the specified direction (`north`, `south`, `east`, `west`).
- `check inventory`: View the items you have collected.
- `pick up <item>`: Pick up an item from the room and add it to your inventory (e.g., `pick up potion`).
- `talk`: Interact with an NPC in the room to receive dialogue or items.
- `attack`: Engage in combat with an enemy present in the room.
- `run`: Retreat from a combat encounter, moving back to the previous room.

## Game World
- **Entrance**: Starting point of the game. An NPC guard provides an introductory message.
- **Forest**: Contains a potion and an NPC Wanderer who provides a helpful item.
- **Dungeon**: Contains a goblin enemy and an NPC Captured Knight.
- **Treasure Room**: Final room containing the treasure and the Treasure Keeper NPC.

## Gameplay Example
```plaintext
Welcome to the Text-Based Adventure Game!
Your goal is to reach the Treasure Room and collect the treasure.
Type commands like the following:
1. 'go <direction>' - Move to a different room.
2. 'check inventory' - View the items you have collected.
3. 'pick up <item>' - Pick up an item from the room.
4. 'talk' - Talk to an NPC (Non-Player Character) in the room.
5. 'attack' - Fight an enemy that may be present in the room.
6. 'run' - Run away from a fight with an enemy.

You are in the Entrance.
You are at the entrance of a mysterious world.
Exits: [north]
> go north
You are in the Forest.
You are in a dense forest. There's a potion here. You see: [potion]
Exits: [south, east]
> pick up potion
You picked up the potion!
