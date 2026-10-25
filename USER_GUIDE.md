# Farmers Market Signs — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.0.0** package linked in [this release](https://github.com/dafke1305/FS25_FarmersMarketSigns/releases/tag/v1.0.0.0). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_FarmersMarketSigns.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Place and personalize a board

1. Open **Construction > Decoration**. Choose the billboard, entrance sign, A-frame, portrait, totem or rustic board. Prices are 150, 450, 600, 750, 1,000 and 1,500; upkeep is zero.
2. Place the board for your farm. The limit is **six boards per farm across all models**, not six of each model.
3. Walk to it and use **Edit advertising board** in the contextual/F1 help. You must belong to the owner farm or be an in-game administrator.
4. Choose one of six designs. Edit the **top title**, separate **heading**, and up to **four product/price rows**. Empty product names hide their rows.
5. Titles/headings allow 40 characters; product names 32; price/unit text 24. In manual mode, price text is a label, for example `EUR 250 / 1000 L`; it does not charge buyers or create a trade.

Changing a design preserves the board's text. Night lighting on both sides is automatic.

## Farm logos

Choose **Choose farm logo** for one of eleven included generic logos, or the standard goods illustration without a logo. A logo selection changes **all boards owned by the farm**; individual board designs and text stay separate.

Custom DDS logos must be added to a shared mod package first. Selecting a local image does not upload it to the server. Any customized package must be identical on the server and all clients.

## Optional Farmers' Market display

The signs work without Farmers' Market in manual mode. To display offers automatically, enable a compatible **FS25_FarmersMarket**, create published offers for the board's owner farm, then select **Product source > Follow Farmers Market automatically**.

Automatic mode displays up to four published product/price combinations from that farm, priced per 1,000 litres. It reads offers; it does not create listings, change prices or move goods. Saved manual rows are preserved when switching modes; switch back to manual to edit them.

## Troubleshooting

| Problem | Check |
| --- | --- |
| Cannot place another board | Count all six models together for your farm. |
| No edit prompt | Approach on foot; check board ownership or admin access. |
| Automatic rows are empty | Check that the market is enabled/ready and has published stock for the same owner farm. Unsupported companion builds may not expose the integration. |
| A logo changed on several boards | That is the farm-wide logo setting; designs and text remain board-specific. |

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_FarmersMarketSigns/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
