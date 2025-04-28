# NEW Notification UI Library

**Capybara Notif** is a **simple, stylish and easy to use** Notification library!

# Features

- Clean animated notification popups

- Automatic stacking of multiple notifications

- Supports custom title, description, image, and duration

- Multiple Modes for expressing different kind of messages

- TOTALLY Free to use!

---

# Modes:

- ```success```

- ```warning```

- ```alert``` 

- ```default```

---

# Usage

```
loadstring(game:HttpGet("https://raw.githubusercontent.com/OfficialDex/Capybara-Notif-lib/refs/heads/main/code.lua"))() 
notify({
    title = "Your Title",
    description = "Your Description Here",
    imageId = 032797, -- Optional (default icon if not provided)
    duration = 4,         -- Optional (default = 4 seconds)
    mode = "success"      -- Optional
})

```

Example:

```
loadstring(game:HttpGet("https://raw.githubusercontent.com/OfficialDex/Capybara-Notif-lib/refs/heads/main/code.lua"))() 
notify({
    title = "Correct Code!",
    description = "You have successfully executed the script!",
    imageId = 6034996695,
    duration = 5,
    mode = "success"
})
```

Another example (mode: warning):

```
loadstring(game:HttpGet("https://raw.githubusercontent.com/OfficialDex/Capybara-Notif-lib/refs/heads/main/code.lua"))() 
notify({
    title = "Warning!",
    description = "You are not using Arise Hub, Loser.",
    imageId = 6034328955,
    duration = 5,
    mode = "warning"
})
```

---

# UI Images
![with Modes](Screenshot_20250427-202154.jpg)
![without any Mode](IMG_20250428_175624.jpg)


---


# Credits

Created by: [#blaze.developer.](https://discord.com)

Script Name: Capybara Notif

Version: 0.1

License: MIT License



---

# Notes:
- This is first version of this library so expect a few bugs (dm me on discord if you find any bug)
- On both, the title And description there's a text limit that if you exceed then your exceeded text will **NOT** be included.
- If you don't want to use any of the modes then you can simply remove that line in code so you will get default mode which is white 
- before you would say i'm a skid too so I'll let you know that yes i used ChatGPT but **only** for positioning frames properly, Nothing more than that
- You are **NOT** allowed to skid the source code of this library
- Next update on (?/?/?)
