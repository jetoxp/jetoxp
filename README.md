# Jetox

**Roblox systems developer.** I build the parts of a game that are easy to get wrong: data
persistence, item and inventory models, and the server-side validation that stops a client from
inventing its own state.

My interest is the boring half of a game — the half that quietly loses a player's progress — and
my habit is to prove it rather than assert it: session locks with a recovery path, save payloads
that carry a schema version, and a test suite that runs without opening Studio.

---

## Featured

### [InventoryKit](https://github.com/jetoxp/inventory-kit) — MIT

A modular, server-authoritative inventory system for Roblox. Metadata-aware stacking, a session
lock that survives a server crashing mid-session, and a core that runs in a plain Luau
interpreter — so its rules are covered by **103 tests in 5 suites** instead of by hope.

![The inventory UI, four stacks loaded from the DataStore](inventory_ui.jpg)

`Luau` `DataStore` `Rojo` `selene` `stylua`

The reasoning behind the design, and the bugs verification caught along the way:
**[case study](https://github.com/jetoxp/portfolio/tree/main/01_Roblox/2026-10-12_InventoryKit)**

---

## Tools I work in

Luau · Roblox Studio · Rojo · selene · stylua · DataStoreService · git

## More

Three more Roblox projects are in progress: a multiplayer elimination game, an extraction
roguelike, and a match engine. They are deliberately not on this page yet — I would rather it
list a few finished, documented systems than thirty half-built ones. It grows as each one is
finished and written up.

## Contact

- **Discord:** `Jetox.` 
- **DevForum:** [@Jetoxsaurio](https://devforum.roblox.com/u/Jetoxsaurio)
- **Email:** jetoxpve@gmail.com

For anything about a specific system, an issue on its repository works too.
