# Advanced Admin Commands

## Overview
Inteded for any Roblox game In need of admin commands

## Features
- Private command handler (no chat-based triggers)
- Admin whitelist (by UserId)
- Fully modular setup (easy to add commands)
- Clean output formatting
- Server-side commands only (secure)
- Fully customizable

## Installation
1. Download or clone this repository.
2. Insert the script/module into your game:
   - AdminRemotes (Folder) = ReplicatedStorage
   - AdminSystem (Folder) = ServerScriptService
   - AdminSystemClient (Folder) = StarterPlayerScripts
   - AdminJoinSound = SoundService
4. Connect any required dependencies or remotes
   - AdminRemotes > FlyToggle
   - AdminRemotes > AdminJoinNotice

## Usage
- In AdminHandler (Module Script) put UserID in "local Admins = {
	[3007046864] = true, -- My User ID
	-- Add more UserIds here"
}
- Excute command prefix is defualt to = ";" 

