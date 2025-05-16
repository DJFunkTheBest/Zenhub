# Load Library
```lua
local ui = loadstring(game:HttpGet("https://raw.githubusercontent.com/zenhutest/moon/refs/heads/main/testingg"))()
```

# Window
```lua
local Window = ui:NewWindow('Nocturn Hub', "Zen Hub Window", 'rbxassetid://17775417459')
local MenuFunctions = Window:AddMenu(game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId).Name, "", 'ticket', 'tab')
```
# Tab
local Tab = MenuFunctions:AddTab("Example Tab", 10723415903, "Player info, stats")

# Section
```lua
local ExampleSection = ExampleTab:AddSection("Section", "Configurate your section")
```

# Toggle
```lua
ExampleSection:AddToggle("Section Toggle", false, function(value)
    -- your code here
end)
```

# DropDowns
```lua
AutoFarmSection:AddDropdown("Example Dropdown", 1, nil, function(value)
    -- your code here
end)
```

# Label
```lua
local Label = ExampleSection:AddLabel("Zenhub UI")
```

# Sliders
```lua
ExamplemSection:AddSlider("Example Slider", 1, 100, 1, function(value)
    -- your code here
end)
```
# 
