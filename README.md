# Fly Away Text
<br>
Plugin for the Corona game engine that animates each letter of a text object

Simply drop the FlyAwayText.lua file somwhere in your project and:

```lua
local flyAwayText = require("FlyAwayText")
```

Usage:
<br><br>
Create a new FlyAwayText object, it is like instantiating a Text display object in Corona, so its sole parameter is a table containing the text options which are:
<ul>
<li>- text </li>
<li>- font </li>
<li>- x </li>
<li>- y </li>
</ul>
<br>
Instiate the object like so:
```lua
local text = FlyAwayText.new({text="Fly Away Text",font=font})
```
If no x or y values are passed in then they default to <i>display.contentCenterX and display.contentCenterY</i>
