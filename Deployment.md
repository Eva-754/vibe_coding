Deployment Document: Roblox Obby Project
Project Overview

This project is a Roblox obby (obstacle course) created as part of the NOS 110 Vibe-Coding Jam.
It includes AI-assisted features as required by the assignment:

Team Bio Sign – displays a short line about each team member at the start of the obby.

Spam Ads – random messages appear when players touch checkpoints.

AI Overlord Feature – clicking a designated part triggers a humorous “AI has taken over” message.

All code generated with AI is commented accordingly. All other aspects, including obby design and part placement, were manually created.

System Requirements

Roblox Studio installed on Windows or Mac.

Internet connection to load Roblox assets.

Basic familiarity with navigating Roblox Studio to test the game.

How to Run the Project

Open Roblox Studio.

Open the project file (.rbxl or .rbxlx).

Press Play to start the game.

Instructions for Players

Start Obby – read the Team Bio Sign at the start.

Navigate through the Obby – jump across platforms and avoid falling.

Checkpoints – when touching a checkpoint, a random spam ad pops up.

AI Overlord – click the special part near the end to trigger a “AI has taken over” message.

Project Structure
Workspace
│
└── Checkpoint1, Checkpoint2…   -- Parts for spam ads
└── ClickablePart               -- Part for AI Overlord feature
    └── ClickDetector

StarterGui
│
└── ScreenGui
    └── TextLabel / ImageLabel  -- Spam ads and AI pop-ups

StarterPlayer
│
└── StarterPlayerScripts
    └── LocalScript             -- Controls GUI and click interactions

AI Assistance

Spam Ads Script – generated using AI.

Click-to-show-image / AI Overlord Script – generated using AI.

All other coding, obby design, and content were manually created by the team.

Example of AI-generated code comment:

-- AI-generated: This script displays random spam ads when a checkpoint is touched

Contributions

[Your Name] – Team Bio setup, spam ads GUI and script, Deployment.md creation.

[Partner Name] – Obby design, AI Overlord part setup, testing, and final polish.

How to Modify

Add spam ads: update the ads table in the LocalScript.

Add checkpoints: insert Parts in Workspace named with "Checkpoint".

Change images: upload new images to Roblox, get asset IDs, and update the ImageLabel’s Image property in the script.

Notes

Ensure all Parts are anchored and correctly named.

Scripts must remain in StarterPlayerScripts (LocalScript) for GUI interactions to work properly.

All content is school-appropriate.