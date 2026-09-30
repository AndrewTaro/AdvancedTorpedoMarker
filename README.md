# Advanced Torpedo Marker
This modification displays more advanced information on the torpedo markers.

Homing Level
- 1 Ping: ▼ with waving Lines,
- 2 Ping: ▼ with waving Lines + "M" on top of it,

Threshold of Homing: If the torpedo is actively guided into you or your target, the "focus" marker will be displayed. When it crosses the threshold of homing to be "dumbfire" mode, that icon disappears.

Detection: A dot appears above the torpedo once it comes within the torpedo detection range of a ship on the other team. The range is estimated on your client.

![image](https://github.com/user-attachments/assets/e7b195b7-2f78-42b7-b7d6-ac4d83392522)
![image](https://github.com/user-attachments/assets/56a55d65-5575-42ba-a698-69814dfa149f)

# Install
1. Download a zip.
2. Unzip the archive and you should get `gui`, `PnFMods`, `ModSchemas` folders, and `PnFModsLoader.py`.
3. Move them to `(wows)/bin/(latest_number)/res_mods/`. So the path will look like `res_mods/PnFModsLoader.py`, etc.
4. Done!

# Requirements
You must install the following for this mod to work:
- [TTaro Mod Utils](https://github.com/AndrewTaro/TTaroModUtils): the settings of this mod live there.

# Config
Configure the mod in [TTaro Mod Utils](https://github.com/AndrewTaro/TTaroModUtils).

### Detection: Display Mode
- Shows or hides the detection dot.
### Homing Lock: Display Mode
- Shows or hides the homing lock marker.

Both settings take the same values:
- **Disable**: Do not show.
- **Enable**: Always show. (default)
- **Adaptive**: Show only while the Alt-key is pressed.
