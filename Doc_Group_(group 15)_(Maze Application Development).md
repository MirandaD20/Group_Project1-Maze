
# Overview
This maze game is a simple maze navigation game implemented in MIPS assembly language. This game allows players to navigate through the maze to find their way out with keys and doors.

# Technical Details
 Language: MIPS Assembly  
 Simulator: MARS MIPS simulator  
 Implementation: Uses MIPS instructions for user interaction, maze creation, and key-to-door interaction.

# Installation and Usage 

1. Run MARS: Open the Code_Group_15_MazeApplicationDevelopment.asm you downloaded in MARS

2. Configure to Bitmap:  
• Go to tools > Bitmap Display  
• Change the settings and do not close window:
- Unit width and unit height should both be set to 8
- Pixel Display width and height should both be set to 512
- Base address should be set to: 0x10010000

3. Open Keyboard and Display MMIO Simulator:
- Open tools and click on Keyboard and Display MMIO Simulator
- Click connect to MIPS and leave open this window  


4. Assemble and Run: Assemble the code and run the game to navigate through the maze using WASD controls In Keyboard and Display MMIO Simulator. As soon as the game starts, click on the keyboard input box to control the pixel.


