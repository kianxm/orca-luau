# Luau Syntax

Highlights [Luau](https://luau.org), the language Roblox uses, in `.luau` and `.lua` files: type annotations, type aliases and type functions, generics, type casts, interpolated strings, attributes such as `@native`, compound assignment and the Luau and Roblox standard library.

Like the luau-lsp VS Code extension, the plugin also claims `.lua`, because many Roblox projects still use that extension. Luau is based on Lua 5.1, so plain Lua files highlight correctly too, but while this plugin is enabled it replaces Orca's built-in Lua colours for every `.lua` file. From Orca 1.4.246, an enabled plugin syntax takes precedence over the built-in one. Older Orca versions show "Needs Orca 1.4.246".

The TextMate grammar is from [JohnnyMorganz/Luau.tmLanguage](https://github.com/JohnnyMorganz/Luau.tmLanguage) at commit `350b8a6ef8ab7d0de843fa08f85b759ca76531dc`, the same grammar the luau-lsp VS Code extension ships. Its MIT license is included. The comment, bracket and auto-closing settings follow [luau-lsp](https://github.com/JohnnyMorganz/luau-lsp/blob/bd4a2ab3a78df82569fb7c2c8fa63d222b4346e0/editors/code/language-configuration.json).
