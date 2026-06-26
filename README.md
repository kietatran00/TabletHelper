# Tablet Helper v1.0

Tablet Helper highlights Precursor Tablets in inventory, stash, special Tablet stash, guild stash and merchant windows.

The plugin lets you create custom highlight groups per tablet type. Each group can use its own color, minimum uses-left requirement and selected tablet bonuses. If a tablet matches more than one group, all matching group names are shown on the item label.

Each group filters bonuses with three tabs:

- **Match** – highlight when at least the chosen number of these bonuses are present (the core rule).
- **Require** – an optional AND gate: the tablet must also have at least the chosen number of these. Leave empty to ignore.
- **Exclude** – an optional NOT gate: never highlight if the tablet has any of these. Leave empty to ignore.

A bonus can only sit in one tab at a time, so a mod can never be both wanted and excluded. Require and Exclude are fully opt-in, so existing groups behave exactly as before. Example: to highlight a juiced Hiveblood tablet only, put *Increased Quantity of Hiveblood* in **Match** and the generic juice mods (Monster Rarity, Rare Monsters, Monster Effectiveness) in **Require** – Hiveblood on its own no longer lights up, and juice without Hiveblood is ignored.

Supported tablet types:

- Irradiated Tablet
- Breach Tablet
- Delirium Tablet
- Abyss Tablet
- Ritual Tablet
- Overseer Tablet
- Temple Tablet

Debug options are included for collecting missing tablet bonus data, but they are disabled by default.
