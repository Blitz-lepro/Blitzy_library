# REDz Library V2


# library
```lua
loadstring(game:httpget('https://pastebin.com/raw/WHfZHzFm'))()
--[[placer le tout en haut de votre script]]--
```

# créer une fenêtre
```lua
MakeWindow({
  Hub = {
    Title = "blitzyGUI",
    Animation = "par : Blitz-lepro"
  },
  Key = {
    KeySystem = false,
    Title = "Key System",
    Description = "",
    KeyLink = "",
    Keys = {"1234"},
    Notifi = {
      Notifications = true,
      CorrectKey = "Running the Script...",
      Incorrectkey = "The key is incorrect",
      CopyKeyLink = "Copied to Clipboard"
    }
  }
})
--[[
  Hub = {
    Title = "blitzyGUI" -- <string> titre de votre script
    Animation = "par : Blitz-lepro" -- <string> texte d'animation de votre script
  },
  Key = {
    KeySystem = <bollean> système de clé
    Title = "Key System" <string> ajouter un titre à votre système de clé
    Description = "" <string> une description pour votre système de clé
    KeyLink = "" <string> un lien pour pouvoir obtenir votre clé
    Keys = {"1234"} <table> la clé pour accéder au GUI
    Notifi = {
      Notifications = true <boolean> une notification pour votre script
      CorrectKey = "Running the Script..." <string> texte de clé valide
      Incorrectkey = "The key is incorrect" <string> texte de clé invalide
      CopyKeyLink = "Copied to Clipboard" <string> texte de copie
    }
  }
]]
```
