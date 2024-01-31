The [[lua_snippets]] first part uses parameters to know when to activate.
This is a table consisting of snip_params.
In this table are various keys and their documentation and purpose can be find in *:help luasnip-snippets*.

```lua
return {
  -- Example: how to set snippet parameters
  require("luasnip").snippet(
    { -- Table 1: snippet parameters
      trig="hi",
      dscr="An autotriggering snippet that expands 'hi' into 'Hello, world!'",
      regTrig=false,
      priority=100,
      snippetType="autosnippet"
    },
    { -- Table 2: snippet nodes (don't worry about this for now---we'll cover nodes shortly)
      t("Hello, world!"), -- A single text node
    }
    -- Table 3, the advanced snippet options, is left blank.
  ),
}
```

An important part of this is *trig*, which can be regex or raw text and *regTrig* tells us if it is regex or not. 