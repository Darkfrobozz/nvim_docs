Luasnip builds the core of their [[lua_snippets]] using nodes, these are the core building blocks:

There are roughly 10 types of nodes.

1. Text nodes: 
	- Expanding snippet into static text.
	- Supply multiple parameters to expand to separate lines.
	- To expand to something like "\gamma" we need to write "\\gamma"
2. Insert nodes:
	- 