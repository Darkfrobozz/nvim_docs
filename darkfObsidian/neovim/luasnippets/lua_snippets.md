A snippet is composed of three distinct parts:
1. Basic parameters
2. Snippet nodes
3. Custom expansion conditions and callback functions

```lua
-- Anatomy of a LuaSnip snippet
require("luasnip").snippet(
  snip_params:table,  -- table of snippet parameters
  nodes:table,        -- table of snippet nodes
  opts:table|nil      -- *optional* table of additional snippet options
)
```
