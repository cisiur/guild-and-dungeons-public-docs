# Guild & Dungeons — Art Asset Brief

## 1. Project overview

**Guild & Dungeons** is a dark fantasy, UI-driven, turn-based RPG with roguelite tension and resource-management systems. The player rebuilds an adventurers’ guild, recruits heroes, sends parties into dangerous dungeons, gathers resources, upgrades the town, and tries to survive tactical combat where character death is permanent.

The game is not an open-world RPG with free character movement. Most gameplay happens through structured screens: town hub, guild/recruitment, dungeon selection, dungeon map, tactical combat, inventory, market, blacksmith, temple, quest board, expedition results, and game over screens.

The visual direction should follow the existing class card style: **dark fantasy, premium RPG UI, deep navy/black backgrounds, metallic frames, blue and gold accents, parchment/map/blueprint details, realistic painterly characters, high contrast, serious tone**.

The attached class artwork should be treated as the main visual reference for quality, palette, UI framing, and tone.

---

## 2. Existing art situation

We currently have high-quality class presentation graphics similar to the attached **Warrior** class card. These are suitable for class showcase screens, encyclopedia-style views, promotional material, and possibly hero/class selection.

However, the game still needs practical gameplay assets: icons, UI frames, combat tokens, dungeon backgrounds, enemy portraits, town building cards, inventory icons, status effects, and screen backgrounds.

The most important task is not to create more large class splash screens first, but to build a coherent, reusable art system for the actual application screens.

---

## 3. Core art direction

### Style

- Dark fantasy RPG.
- Serious, grounded, medieval-fantasy tone.
- Premium UI, similar to collectible RPG cards or tactical RPG interfaces.
- Metal, leather, stone, parchment, old maps, blueprint-like markings, subtle magical glyphs.
- Strong use of frames, panels, ornaments, icons, and readable silhouettes.

### Color palette

- Primary background: very dark navy / near-black.
- Main accent: desaturated steel blue.
- Secondary accent: warm gold / brass.
- Frame materials: dark iron, worn steel, bronze, leather.
- Danger states: muted crimson.
- Magic states: blue, violet, pale gold, green depending on effect.

### UI principles

- Assets must remain readable at small sizes.
- The same frame language should be reused across character cards, item cards, building cards, dungeon cards, buttons, and tooltips.
- Avoid overly bright cartoon fantasy colors.
- Avoid mobile-casual, chibi, or low-detail styles.
- All UI assets should support a landscape 16:9 layout.

---

## 4. Highest priority: Combat Art Pack

The combat screen is one of the most important visual areas of the game. Combat is turn-based, viewed from an isometric/top-down perspective, and uses a four-zone battlefield:

1. Back Line
2. Contested
3. Front Line
4. Entrance

The party starts near the Entrance / Front Line side, while enemies usually start in the Back Line or Contested zone.

### Required combat assets

| Asset | Quantity | Priority | Notes |
|---|---:|---|---|
| Battlefield background: Mine | 1 | Critical | First test combat environment |
| Battlefield backgrounds for all dungeon types | 5 total | High | Mine, Forest, Ruins, Fortress, Crypt |
| Four-zone battlefield overlay | 1 set | Critical | Back Line, Contested, Front Line, Entrance |
| Zone highlight states | 5 states | Critical | Normal, hover, selected, valid target, invalid target |
| Hero combat tokens | 6 classes | Critical | Transparent PNGs, readable in zone layout |
| Enemy combat tokens | Minimum 5 | Critical | Basic MVP enemy set |
| Boss combat tokens | 5 | Medium/High | One boss per dungeon type |
| Turn order frame | 1 | High | Small portrait/icon row |
| Active character panel frame | 1 | High | Right-side or focused character panel |
| Skill button frames | 3 states | High | Normal, disabled, selected/active |
| AP icon | 1–3 variants | High | Action Point indicator |
| HP bar frame | 1–2 variants | High | Hero and enemy variants if needed |
| Damage/heal number popup style | 3–4 variants | Medium | Damage, heal, critical, miss |
| Targeting cursor / reticle | 1–2 variants | High | For selecting characters/zones |

### Combat effect assets

| Effect | Priority | Notes |
|---|---|---|
| Sword slash | High | Basic melee attack |
| Heavy strike impact | Medium | Strong attack / stun chance |
| Shield block | High | Defend / guard effect |
| Taunt icon/effect | Medium | Warrior skill |
| Heal glow | High | Priest healing |
| Shield of Faith / protection | High | Priest defensive effect |
| Purification / cleanse | Medium | Priest anti-curse / anti-undead effect |
| Fireball / fire impact | High | Mage AoE |
| Ice chain / frost | Medium | Mage control |
| Smoke cloud | Medium | Rogue skill |
| Sneak attack mark | Medium | Rogue DPS skill |
| Arrow shot / volley | Medium | Ranger skills |
| Trap placement/disarm | High | Ranger/Rogue/utility use |
| Death marker | High | Permanent death feedback |

---

## 5. Character class gameplay assets

The game currently defines these classes:

- Warrior — Tank / DPS
- Rogue — DPS / crowd control
- Mage — Burst DPS
- Priest — Support / healing
- Ranger — Ranged DPS
- Cartographer — Utility, dungeon mapping, retreat-risk reduction, treasure finding

The existing full class cards are not enough for gameplay. Each class needs smaller reusable assets.

### Required assets per class

| Asset | Recommended Use | Priority |
|---|---|---|
| Full class card | Class screen / encyclopedia | Already mostly available |
| Large portrait crop | Recruitment, hero details | Critical |
| Small portrait crop | Turn order, roster, party selection | Critical |
| Combat token | Tactical combat zones | Critical |
| Class icon | UI lists, filters, tooltips | High |
| Transparent bust/cutout | Hero screen, recruit card | Medium |
| Wounded overlay | Roster and expedition result | High |
| Dead/permadeath overlay | Result screen, graveyard/game over | High |
| Class color badge | UI identity | Medium |

### Notes

The current class cards should be used as the visual source of truth. If possible, derive crops and cutouts from the existing class art before creating entirely new illustrations.

The combat token does not need to be a fully animated sprite. A clean, readable illustrated figure or bust on a transparent background is enough for the current UI-driven tactical combat.

---

## 6. Enemy art

The game supports encounters with one strong enemy, many weaker enemies, or mixed groups. For MVP, we need a small but polished enemy set.

### Minimum enemy set

| Enemy | Assets Needed | Priority |
|---|---|---|
| Goblin | Portrait, combat token, small icon | Critical |
| Giant Spider | Portrait, combat token, small icon | Critical |
| Skeleton / Undead | Portrait, combat token, small icon | Critical |
| Bandit / Raider | Portrait, combat token, small icon | Critical |
| Cave Beast / Mine Creature | Portrait, combat token, small icon | Critical |

### Bosses

| Boss Type | Dungeon | Assets Needed | Priority |
|---|---|---|---|
| Mine Boss | Mine | Large token, portrait | Medium/High |
| Forest Boss | Forest | Large token, portrait | Medium/High |
| Ruins Boss | Ruins | Large token, portrait | Medium/High |
| Fortress Boss | Fortress | Large token, portrait | Medium/High |
| Crypt Final Boss | Crypt | Large token, portrait, possible splash art | High later |

### Enemy asset rules

- Enemy silhouettes must be readable at small sizes.
- Tokens should work on dark battlefield backgrounds.
- Portraits should use the same frame language as hero portraits.
- Bosses should be visually larger, more detailed, and more threatening.

---

## 7. Dungeon and expedition art

The game currently uses five dungeon types:

1. Mine
2. Forest
3. Ruins
4. Fortress
5. Crypt

Each dungeon type should feel visually distinct while still belonging to the same UI style.

### Required assets per dungeon type

| Asset | Quantity per Dungeon | Priority | Notes |
|---|---:|---|---|
| Dungeon selection card | 1 | High | Used when choosing expedition target |
| Dungeon icon | 1 | High | Small UI icon |
| Combat background | 1–3 | High | Start with 1 per dungeon |
| Dungeon map background | 1 | High | Used behind procedural node map |
| Thematic ornament/frame variant | 1 | Medium | Optional color/detail variation |
| Boss portrait/token | 1 | Medium/High | One boss per dungeon type |

### Shared dungeon map icons

| Node Type | Priority |
|---|---|
| Start node | High |
| Combat node | High |
| Loot node | High |
| Event node | High |
| Boss node | High |
| Exit node | High |
| Unknown/unrevealed node | High |
| Trap node | Medium |
| Rest/safe node | Medium |

### Dungeon identity notes

- **Mine:** narrow tunnels, stone, ore, lantern light, dust, collapses.
- **Forest:** dark woods, roots, fog, organic enemies, traps, lost paths.
- **Ruins:** ancient stone, broken pillars, magical traps, cursed artifacts.
- **Fortress:** militarized, iron gates, banners, elite enemies, alarm state.
- **Crypt:** undead, bones, tombs, despair aura, final boss atmosphere.

---

## 8. Environmental hazards

The combat system includes zone-specific hazards. These need clear icons and possibly small zone overlays.

| Hazard | Effect | Assets Needed | Priority |
|---|---|---|---|
| Spike Trap | Damages character entering the zone | Icon, zone overlay, disarmed state | Critical |
| Unstable Object | Blocks zone entry | Icon, obstacle art, destroyed/disarmed state | Critical |
| Shadow Tile | Gives Rogue bonus damage | Icon, subtle zone overlay | Critical |

### Hazard state variants

- Active
- Disarmed
- Destroyed / removed

---

## 9. Town hub and buildings

The town hub includes several functional locations. These are mainly UI cards/icons rather than full explorable environments.

### Required building assets

| Building | Function | Assets Needed | Priority |
|---|---|---|---|
| Adventurers’ Guild | Recruitment and roster management | Icon, building card/panel | Critical |
| Tavern / Quest Board | Quests, information, rest | Icon, building card/panel | High |
| Market | Buy/sell materials and equipment | Icon, building card/panel | High |
| Blacksmith | Crafting and upgrading equipment | Icon, building card/panel | High |
| Temple | Healing, buffs, curse removal | Icon, building card/panel | High |
| Dungeon Gate / Expedition Gate | Enter dungeons | Icon, building card/panel | Critical |
| Treasury | Resource management | Icon, building card/panel | Medium |
| Alchemist’s Guild | Potions and elixirs | Icon, building card/panel | Medium |

### Building state variants

Because the campaign includes rebuilding/upgrading the town, buildings may need visual states:

1. Destroyed / locked
2. Under construction
3. Rebuilt / active
4. Upgraded level 2–3, optional later

These can be separate illustrations or reusable overlays.

---

## 10. Items, resources, and economy icons

The game uses gold, materials, equipment, crafting, upgrades, potions, maps, and rare loot. These icons are important because many screens rely on them.

### Currency and resources

| Asset | Priority |
|---|---|
| Gold | Critical |
| Reputation / renown | High |
| Day/time icon | High |
| Iron ore | High |
| Stone | High |
| Wood | High |
| Herbs | High |
| Bone | Medium |
| Crystal | Medium |
| Rune fragment | Medium |
| Mithril | Medium |
| Adamantite | Medium |
| Dragon scale | Later |
| Demonic heart | Later |

### Equipment icons

| Asset | Priority |
|---|---|
| Sword | High |
| Axe | Medium |
| Dagger | Medium |
| Bow | High |
| Staff | High |
| Shield | High |
| Light armor | High |
| Medium armor | High |
| Heavy armor | High |
| Ring | Medium |
| Amulet | Medium |
| Potion | High |
| Dungeon map | High |
| Crafting recipe / blueprint | Medium |

### Item UI elements

| Asset | Priority |
|---|---|
| Item card frame | High |
| Inventory slot frame | High |
| Empty slot | High |
| Locked slot | Medium |
| Rarity frames: common, uncommon, rare, epic, legendary | High |
| Upgrade level indicators 0–3 | High |
| Compare item arrows / stat change icons | Medium |

---

## 11. Status effects and buffs/debuffs

Status effects need clear, small icons that are readable in combat, roster, hero details, and expedition result screens.

### Required status icons

| Status | Priority |
|---|---|
| Poisoned | High |
| Bleeding | High |
| Stunned | High |
| Guarded / Defending | High |
| Blessed | High |
| Shielded | High |
| DeathShield / lethal hit protection | Critical |
| Cursed | High |
| Fatigued | High |
| Wounded | High |
| Dead | Critical |
| Burning | Medium |
| Frozen / slowed | Medium |
| Accuracy penalty | Medium |
| Healing reduction | Medium |
| Alarm buff | Medium |

---

## 12. Quest and expedition result art

The game includes quests such as material gathering, dungeon clearing, escort missions, and timed quests. Expeditions end with loot, XP, deaths, injuries, retreat, victory, or defeat.

### Quest assets

| Asset | Priority |
|---|---|
| Quest board icon/card | High |
| Material gathering quest icon | Medium |
| Boss hunt / dungeon clear quest icon | Medium |
| Escort quest icon | Medium |
| Timed quest icon | Medium |
| Quest reward frame | Medium |
| Quest completed stamp/badge | Medium |
| Quest failed stamp/badge | Medium |

### Result screen assets

| Asset | Priority |
|---|---|
| Victory screen background | High |
| Defeat screen background | High |
| Retreat/fled screen background | Medium |
| Loot chest / reward container | High |
| XP gain icon | High |
| Character death/permadeath panel | Critical |
| Wounded character panel | High |
| Game Over screen | Critical |
| Campaign ending / final victory screen | Later |

---

## 13. Main menu and global UI

The game needs a consistent UI shell for all screens.

### Required global UI assets

| Asset | Priority |
|---|---|
| Game logo | High |
| Main menu background | High |
| Main menu button set | High |
| Generic panel frame | Critical |
| Modal/dialog frame | Critical |
| Tooltip frame | High |
| Confirmation window frame | High |
| Warning/permadeath confirmation frame | Critical |
| Scrollbar | Medium |
| Checkbox/toggle | Medium |
| Slider | Medium |
| Save slot frame | Medium |
| Loading screen | High |
| Generic dark fantasy background pattern | High |

### Button states

Every major button style should include:

- Normal
- Hover/focused
- Pressed
- Disabled
- Selected/active

---

## 14. Recommended production order

### Phase A — Combat Playtest Art Pack

This should be created first because combat is the most visually exposed and gameplay-critical part.

1. Combat tokens for 6 hero classes.
2. Portrait crops for 6 hero classes.
3. Combat tokens for 5 basic enemies.
4. Mine battlefield background.
5. Four-zone battlefield overlay.
6. Hazard icons: Spike Trap, Unstable Object, Shadow Tile.
7. Basic combat action icons: attack, heavy attack, defend, move, flee, item, skill.
8. HP/AP UI elements.
9. Skill button frames.
10. Status icons: poison, bleed, stun, guard, shield, DeathShield, fatigue, dead.

### Phase B — Dungeon Loop Art Pack

1. Dungeon selection cards for Mine, Forest, Ruins, Fortress, Crypt.
2. Combat backgrounds for all five dungeon types.
3. Dungeon map backgrounds for all five dungeon types.
4. Node icons: start, combat, loot, event, boss, exit, unknown.
5. Loot chest and reward frame.
6. Victory, defeat, and retreat screen backgrounds.

### Phase C — Town Hub Art Pack

1. Building cards/icons: Guild, Tavern/Quest Board, Market, Blacksmith, Temple, Dungeon Gate.
2. Resource icons: gold, reputation, day/time, ore, wood, herbs, stone.
3. Item icons for basic weapons, armor, potions, maps.
4. Recruitment card frame.
5. Item card frame.
6. Building upgrade/locked overlays.

### Phase D — Polish and release-facing art

1. Final logo polish.
2. Main menu background.
3. Loading screen.
4. Game Over screen.
5. Final boss splash art.
6. App icon.
7. Store capsule / promotional banner.
8. Optional animated UI effects.

---

## 15. File format and delivery requirements

### Recommended formats

- PNG with transparency for icons, tokens, UI frames, overlays.
- PSD or layered source files for complex UI panels and cards.
- 16:9 backgrounds, preferably 1920×1080 or higher.
- Icons should be delivered at high resolution and scalable down cleanly.

### Suggested export sizes

| Asset Type | Suggested Size |
|---|---:|
| Full background | 1920×1080 |
| Large class/character card | 1536×1024 or higher |
| Character portrait | 512×512 |
| Small portrait | 128×128 |
| Combat token | 512×512 or 384×384 transparent PNG |
| Class/item/status icon | 256×256 source, exported also at 128×128 and 64×64 |
| Small UI icon | 64×64 |
| Button source | Flexible 9-slice friendly asset |
| Panel/frame source | 9-slice friendly PNG or layered PSD |

### Naming convention suggestion

Use consistent lowercase snake_case names, for example:

- `class_warrior_portrait_large.png`
- `class_warrior_token.png`
- `enemy_goblin_token.png`
- `dungeon_mine_background_combat_01.png`
- `ui_button_primary_normal.png`
- `ui_button_primary_disabled.png`
- `icon_status_poison.png`
- `icon_resource_gold.png`
- `building_blacksmith_card.png`

---

## 16. Key visual consistency rule

The attached class artwork represents the desired quality bar and visual identity. All new assets should feel like they belong to the same game:

- dark navy/black background language,
- blue and gold accents,
- metallic frames,
- realistic dark fantasy characters,
- readable icons,
- premium RPG interface style,
- serious tone rather than cartoon fantasy.

The priority is to build a coherent gameplay asset library first. Large splash illustrations can be expanded later once the core UI, combat, dungeon, enemy, and town assets are consistent.
