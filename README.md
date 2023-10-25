# PabloLibUpdatedTUT
Hello in this tutorial im gonna show you how to use the "Pablo Lib". Its pretty easy to use. Lets get into it.

### 1. Booting up the Pablo Lib
```lua
local PabloLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/BatuKvi123/PabloLibUpdated/main/updated"))()
```
### 2. Creating The Window
```lua
local window = PabloLib:Create("Name")
```

### 3. Creating a tab
```lua
local tab1 = window:CreateTab("Tab Name")
```
### 4. Creating a button
```lua
tab1:CreateButton("Button", function()
print("Hello World!")
end)
```

### 5. Creating a toggle
```lua
tab1:CreateToggle("Toggle", function(state)
if state then
print("Enabled!")
else
print("Disabled!")
end)
```

### 6. Creating a slider
```lua
tab1:CreateSlider("Slider, 0, 100, function(arg)
print(arg)
end)
```

### 7. Creating a textbox
```lua
tab1:CreateTextbox("Textbox", function(a)
print(a)
end)
```

### 8. Creating a title
```lua
tab1:CreateTitle("Title")
```

Thats all! I hope you liked the tutorial. Have a good day, bye! :)
