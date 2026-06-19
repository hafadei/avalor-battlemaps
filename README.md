# Avalor Battlemaps

Collection of custom battlemaps for [Avalor RPG](https://discord.gg/avalorrpg) — a D&D 5e West Marches / rift-based PbP server.

## Why GitHub?

Discord CDN links and many free image hosts (imgur, postimage, Free Image Hosting) have stopped working with Avrae's `!map` alias. GitHub's `raw.githubusercontent.com` URLs are stable, direct, and not rate-limited for static images.

## How to Use

1. **Open any `.png` file** in this repo
2. **Right-click the image** → **"Open image in new tab"**
3. **Copy the URL** (starts with `https://raw.githubusercontent.com/...`)
4. **Paste into Avrae**:
   ```
   !map bg -bg https://raw.githubusercontent.com/YOUR_USER/avalor-battlemaps/main/battlemaps/carnival_of_ash_v3.png -size 10
   ```

## Battlemaps

| Map | Version | Grid | Notes |
|-----|---------|------|-------|
| [Carnival of Ash](battlemaps/carnival_of_ash_v3.png) | v3 (brightened) | 10×10 (100 ft) | Burnt circus tent. Moonlit with warm lantern contrast. |
| [Carnival of Ash](battlemaps/carnival_of_ash_v2.png) | v2 (10×10 grid) | 10×10 (100 ft) | Cleaner grid, less cluttered |
| [Carnival of Ash](battlemaps/carnival_of_ash_v1.png) | v1 (20×20 grid) | 20×20 (100 ft) | Original dense-grid version |

### Encounter Context: "Carnival of Ash"

**Tier 1 Trial Rift** — single-wave encounter vs 6 Tier 1 PCs (~6,000 adj XP).

| Monster | Start Position | Role |
|---------|---------------|------|
| Jack of Strings | Center carousel (elevated) | Boss / puppeteer |
| Flaming Skeleton | North bleachers (overwatch) | Ranged fire |
| Space Clown | SE cotton-candy cart (concealed) | Ambusher / infiltrator |
| Animated Armor | West flank breach | Tank / frontline |
| Marionettes (×2) | Beside Jack | Minions |

**Map Features:**
- Collapsed carousel: half-cover, difficult terrain, +10 ft climb
- Scorched bleachers: elevation +5 ft
- Cotton-candy cart: half-cover
- Fortune-teller booth: half-cover, shatterable (AC 13, 5 HP)
- Sealed front entrance: AC 15, 30 HP
- Left/right flank breaches: where reinforcements enter
- Ash floor: lightly obscured beyond 30 ft

## Adding New Maps

1. Drop `.png` files into `battlemaps/`
2. Update this README table
3. Commit & push
4. Right-click → "Open in new tab" → copy raw URL for Avrae

---

*Maps generated with AI. Grids overlaid for 10-ft square (10×10) or 5-ft square (20×20) scale.*
