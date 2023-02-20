# RX11 V1
The LuaU version of DX11
 
# Documentation
```lua
local rx11 = link or table (of file)

rx11:draw_rect(int_x, int_y, int_width, int_height, color3_color)       -- Will render a filled rect

rx11:draw_square(int_x, int_y, int_width, int_height, color3_color)    -- Will render an unfilled square / rect

rx11:draw_string(string_content, int_x, int_y, color3_color)           -- Will render a string

rx11:draw_string_custom_font(string_content, int_x, int_y, int_font, color3_color, color3_outline_color) -- Will render  a strng with custom font

rx11:draw_string_outline(string_content, int_x, int_y, color3_color, color3_outline_color)  -- Will render an outline string

rx11:draw_string_centered(string_content, int_x, int_y, color3_color)  -- Will render a centered string


You can use the RX11_RENDERED table to handle rendered objects

Example:
for i, object in pairs(rx11.DX11_RENDERED) do   -- Loop through the RX11_RENDERED table
    if object then 
        object:Remove()                         -- Remove the rendered object from roblox.
    end
end
```

More will be added to RX11, this is only a small project.
