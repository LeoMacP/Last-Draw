
![Leonardo_Phoenix_A_visually_striking_professional_graphic_desi_1](https://github.com/user-attachments/assets/a89cd88a-21c8-413b-89a9-23123aeb01ba)



# Project Description:
Last Draw is a Western-themed point-and-click adventure game in which players must make quick, strategic decisions within time limits. Each choice influences the game's narrative path and outcomes.


# Overview
Purpose: 
  This project aims to provide players an engaging, time-sensitive adventure where choices impact the story and the final challenge.

# 1. Scope:
  - Included Features:
      Interactive decision-making, shoot-target mini-game, time-sensitive mechanics, and a scoring system based on attribute management.
    
  - Excluded Features:
      Multiplayer mode, advanced AI for NPCs.

# 2 System Architecture
  - Overview: 
      The game is developed using WPF (.NET Framework) and C#, utilizing a modular design where each decision point and mini-game is a separate module.
    
  - System Architecture Diagram:
    - Client-Server Communication:
      - Protocols and technologies used for client-server communication (e.g., REST APIs, WebSockets)
      - Overview of the client-side and server-side components and their responsibilities
        ![Captura de tela 2024-11-13 100352](https://github.com/user-attachments/assets/292efce6-2326-47a7-a19f-60f0ba8d7528)


    - Decision points flow and Attributes Management:
      ![image](https://github.com/user-attachments/assets/1b9d6219-0859-4bd1-9d2f-a30ae0570aa5)

   

# 3 Data Dictionary
   - 3.1 Data Elements:
     - Player:
        Stores player score and attributes (Health, Audacity and Stealth).
     
     - Decision Node:
         Represents each choice, outcome, and possible rewards/penalties.
     
# 4 Data Design
  - Persistent/Static Data:
      Data for tracking player stats and progress across different sessions.
    
  - Data Structure:
      Player Stats:
        Attributes and Scores are tracked through a basic class structure in C#.

# 5 User Interface Design
  - UI Overview:
      Game screen with timer, decision options, and disc-hunting area.
      Attributes and Score display panel.
    ![image](https://github.com/user-attachments/assets/9a9a62d1-b1d4-4aa6-9db3-5a5ef649fa47)
    
  - UI Navigation Flow:
      Start Screen -> Game Screen -> End Screen
