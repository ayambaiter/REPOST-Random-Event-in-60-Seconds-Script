--SCRIPT::

getgenv().mode = "both" --This Selects The Script's Event Choices (both,curse,benefit).
getgenv().difficulty = "hardcore" --This Selects The Difficulty Of The Script (easy,medium,hard,hardcore).
getgenv().start = true --This Toggles The Script.

loadstring(game:HttpGet("https://raw.githubusercontent.com/ayambaiter/REPOST-Random-Event-in-60-Seconds-Script/refs/heads/main/script"))()
