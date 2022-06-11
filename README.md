# East Hub - UI Library

-----------------------
- UI Library Features :
-----------------------

- Button
- Notification ( its not mine )
- Dropdown
- Toggle
- Label
- Slider ( bugs )
- Text Box

# Source

```html
- Adding Library
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Brineeee/Free-Scripts/main/SourceFE"))()
```

```html
- Adding Window
local win = Library:CreateWindow()
```

```html
- Adding Tabs
local Tab1 = win:CreateTab("Tab 1")
```

```html
- Adding Notification
Tab1:CreateNotification("Notification Title", "Notification Description", 10)
```

```html
- Adding Button
Tab1:CreateButton("Example Button", function()
	print()
end)
```

```html 
- Adding Toggle
Tab1:CreateToggle("Example Toggle", function(sssss)
	print()
end)
```

```html
- Adding Textbox
Tab1:CreateTextbox("Example Textbox","Type", function() 
    print() 
end) 
```

```html
- Adding Dropdown
Tab1:CreateDropdown("Example Dropdown", {"Option1", "Option2"},function()
    print() 
end) 
```

```html
- Adding Label
Tab1:CreateLabel("Example Label")
```

```html
- Want a full library? I got you! 
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Brineeee/Free-Scripts/main/SourceFE"))()

local win = Library:CreateWindow()
local Tab1 = win:CreateTab("Tab 1")
local Tab2 = win:CreateTab("Tab 2")

Tab1:CreateButton("Example Notification", function() 
Tab1:CreateNotification("Notification Title", "Notification Description", 10)
end) 

Tab1:CreateButton("Example Button", function()
	print()
end)
Tab1:CreateToggle("Example Toggle", function(sssss)
	print()
end)
Tab1:CreateTextbox("Example Textbox","Type", function() 
    print() 
end) 

Tab1:CreateDropdown("Example Dropdown", {"Option1", "Option2"},function()
    print() 
end) 

Tab1:CreateLabel("Example Label")
```

-----------------------
- Don't use slider its currently bug
-----------------------
