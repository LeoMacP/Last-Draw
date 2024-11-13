
![Leonardo_Phoenix_A_visually_striking_professional_graphic_desi_1](https://github.com/user-attachments/assets/a89cd88a-21c8-413b-89a9-23123aeb01ba)



# Project Description:
Last Draw is a Western-themed point-and-click adventure game in which players must make quick, strategic decisions within time limits. Each choice influences the game's narrative path and outcomes.


# Overview
Purpose: 
  This project aims to provide players an engaging, time-sensitive adventure where choices impact the story and the final challenge.

Scope:
  - Included Features:
      Interactive decision-making, shoot-target mini-game, time-sensitive mechanics, and a scoring system based on attribute management.
    
  - Excluded Features:
      Multiplayer mode, advanced AI for NPCs.

# System Architecture
  - Overview: 
      The game is developed using WPF (.NET Framework) and C#, utilizing a modular design where each decision point and mini-game is a separate module.
    
  - Architecture Diagram:
    
    - Decision points flow and Attributes Management:
      ![image](https://github.com/user-attachments/assets/1b9d6219-0859-4bd1-9d2f-a30ae0570aa5)

   -  Gameplay UI
![Imagem do WhatsApp de 2024-11-12 à(s) 22 17 43_8a71b180](https://github.com/user-attachments/assets/5e1c525d-74c3-4197-8c61-0b170564d926)


# Data Dictionary
   - Data Elements:
      Player:
        Stores player score and attributes (Health, Audacity and Stealth).
     
   - Decision Node:
         Represents each choice, outcome, and possible rewards/penalties.
     
# Data Design
  - Persistent/Static Data:
      Data for tracking player stats and progress across different sessions.
    
  - Data Structure:
      Player Stats:
        Attributes and Scores are tracked through a basic class structure in C#.

# User Interface Design
  - UI Overview:
      Main screen with options for starting the game and viewing scores.
      Game screen with timer, decision options, and disc-hunting area.
      Attributes and Score display panel.
    
  - UI Navigation Flow:
      Start Screen -> Game Screen -> End Screen
