# crx_leobadge
A simple FiveM LEO Badge item and script for LEO's and Government Agent's to show other players proof of realism!
You may NOT resell or reupload this content as your own!
Or I will find you!!! >:(

# Dependencies
qb-core, es_extended, & repemotes-reborn

# Supported Inventories
qb-inventory & ox_inventory

# Steps on installing
* Drag and drop crx_leobadge into your resource folder
* Add paste the following in your server.cfg
* ensure crx_leobadge

# Example of Badges
<img width="2048" height="2048" alt="badge1" src="https://github.com/user-attachments/assets/06bc555b-e691-4341-b00b-4bb7bcc89de3" />
<img width="2048" height="2048" alt="badge2" src="https://github.com/user-attachments/assets/f22c67bb-6ef9-487e-8d40-6fdf9fbc34bd" />
<img width="2048" height="2048" alt="badge3" src="https://github.com/user-attachments/assets/9013e40f-40b1-466d-8e5a-87db1093beda" />
<img width="2048" height="2048" alt="badge4" src="https://github.com/user-attachments/assets/9c4f5b51-d868-4d90-8052-a6e8e50072e7" />
<img width="128" height="153" alt="none" src="https://github.com/user-attachments/assets/4911e402-4c6a-4f2e-9d09-e8105fdde6ce" />

# Configuration
```
Config = {}

Config.Framework = "qb" -- "qb" or "esx"
Config.Inventory = "qb" -- "qb" or "ox"
Config.DisplayTime = 5000 

Config.EmoteCommand = "idcardb"
Config.DisplayTime = 5000 -- 5 second show timer

Config.UI = {
    BadgeWidth = "600px",          
    BadgeHeight = "600px",
    BadgePositionTop = "50%",
    BadgePositionLeft = "50%",
    
    NameTop = "61%",
    NameLeft = "26%",
    NameFontSize = "20px",
    NameColor = "#0d1b2a",         
    
    PhotoTop = "39.2%",
    PhotoLeft = "33%",
    PhotoWidth = "84px",
    PhotoHeight = "113px"
}

Config.Jobs = {
    ["police"] = { img = "badge1.png", label = "LSPD" },
    ["lssd"]   = { img = "badge2.png", label = "LSSD" },
    ["bcso"]   = { img = "badge3.png", label = "BCSO" },
    ["sasp"]   = { img = "badge4.png", label = "SASP" },
    ["sahp"]   = { img = "badge5.png", label = "SAHP" },
    ["sast"]   = { img = "badge6.png", label = "SAST" },
    ["fib"]    = { img = "badge7.png", label = "FIB" },
    ["noose"]  = { img = "badge8.png", label = "NOOSE" }
}
```
# How to use #
Get the badge from wherever you want the badges to be available from,
or give yourself the badge using a command,
In your inventory click use or press the number of the slot it's in
and flash your badge to other players!

* start the server
* ensure the resource has started in your console log
* get the badge and boom your done

# Support
[Discord Server](https://discord.gg/6QchSKDY7j)
[Discord Server 2](https://discord.gg/YJXZagSzh7)
