# Shared Libraries

This directory contains reusable Lua libraries that multiple extensions can reference.

Libraries are used to avoid code duplication for sites that share common patterns (e.g., Madara-based sites, WordPress sites with similar themes).

## Usage

Extensions can require libraries using:

```lua
-- In your extension
local lib = Require("LibraryName")
```

Libraries are listed in the root `index.json` under the `libraries` array.
