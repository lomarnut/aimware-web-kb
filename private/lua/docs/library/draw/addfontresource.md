# draw.AddFontResource
Add .ttf file data to available fonts.

## Syntax
```
draw.AddFontResource(string:ttfdata)
```

## Parameters
```string:ttfdata``` The .ttf file data.


## Example
```lua
draw.AddFontResource("location/to/ttf/file.ttf")
local Font = draw.CreateFont("ttfname", 20, 100)

callbacks.Register("Draw", function()
    draw.SetFont(Font);
	
	draw.Color(255, 138, 130, 255);
	
	draw.Text(60, 60, "Text");
end)
```

<figure>
  <img src="/kb/lua/docs/library/draw/createfont.png"/>
</figure>

## Fontlist
For more information about the different types of fonts.
[FontList](/kb/lua/docs/library/draw/fontlist/).
