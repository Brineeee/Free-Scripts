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
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Brineeee/Free-Scripts/main/Source"))()
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

-----------------------
- Don't use slider its currently bug
-----------------------
