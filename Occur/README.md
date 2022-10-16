# Welcome to `Occur`

Designed by `Peaxe#4347`
Scripted by `Peaxe#4347`

V3rmillion : `https://v3rmillion.net/member.php?action=profile&uid=2624688`
Discord : `Peaxe#4347`

##### Updates

`+e`

### Creating a Window

```lua
local Window = Occur:Load({Theme = Color3.fromRGB(255,255,255)}, {Title = "Title", Description = "Description"})
```

### Creating a Page

```lua
local Page = Window:New({Text = "Get started", Open = true}
```

- ```Make sure all of the pages is not open except one so the pages won't be buggy```

### Creating a Section

```lua
local Section = Page:Section({Text = "Features", OpenSection = false}
```

- ```OpenSection = false (If you want the section to close automatically when script is runned```
- ```OpenSection = true (If you want to open the section automatically when script is runned```

### Creating a Button

```lua
local Button = Section:Button({Text = "This is a button", Callback = function() print("Hi there!")}
```

```lua
Button:ChangeText("New Text")
```
