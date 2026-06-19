# crx_leobadge
A simple FiveM LEO Badge item and script for LEO's and Government Agent's to show other players proof of realism!
You may NOT resell or reupload this content as your own!
Or I will find you!!! >:(

# Dependencies
qb-core & es_extended

# Supported Inventories
qb-inventory & ox_inventory

# Steps on installing
* Drag and drop crx_leobadge into your resource folder
* Add paste the following in your server.cfg
* ensure crx_leobadge

# Configuration
```
Config = {}

Config.Framework = "qb" -- "qb" or "esx"
Config.Inventory = "qb" -- "qb" or "ox"
Config.DisplayTime = 5000 

-- Directly hooks into your rpemotes system
Config.EmoteCommand = "idcardb"
Config.DisplayTime = 5000 -- Matches the 5-second show timer

-- Precise alignment fixed from screenshots
Config.UI = {
    BadgeWidth = "600px",          
    BadgeHeight = "600px",
    BadgePositionTop = "50%",
    BadgePositionLeft = "50%",
    
    -- Moved down from 53% to 61% to sit perfectly in the center blank space
    NameTop = "61%",
    NameLeft = "26%",
    NameFontSize = "20px",
    NameColor = "#0d1b2a",         
    
    -- Shifted down that final fraction from 38.5% to 39.2%
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
