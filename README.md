# spairs
### [Stanley](https://github.com/Wolf2789/Stanley) package with sorted order iterator function.

## Usage:
```lua
local table = { 'c', 'a', 'd', 'b', 1, 2, 3 }
for key, value in spairs(table) do
    print(key .. ' = ' .. value)
end
--[[ output will be:
2 = a
4 = b
1 = c
3 = d
5 = 1
6 = 2
7 = 3
]]
```
