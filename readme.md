# DL COM Items

Read Me last updated 12/12/2025

Project for managing custom items data for the Deadlock community.

## Project Structure

### `/scripts`
- **abilities.vdata** - The actively used items configuration file
- **example_item.txt** - Example item template for reference

### `/panorama/images/upgrades`
Contains item image folders organized by category:
- `mods_armor/` - Armor item images
- `mods_tech/` - Tech item images
- `mods_utility/` - Utility item images
- `mods_weapons/` - Weapon item images

### `/resource/localization`
Key folders for item details:
- **citadel_gc_mod_names/** - Item name localizations (viewable details)
- **citadel_mods/** - Item descriptions and stats (viewable details)

## Getting Started

### Clone Locally

```bash
git clone https://github.com/your-username/dl-com-items.git
cd dl-com-items
```

Then navigate to the relevant folder based on what you're working on:
- **Items configuration**: `/scripts/abilities.vdata`
- **Item images**: `/panorama/images/upgrades/`
- **Item names & descriptions**: `/resource/localization/citadel_gc_mod_names/` and `/resource/localization/citadel_mods/`

### Reference Items

Check out the [Items Spreadsheet](https://docs.google.com/spreadsheets/d/1rAlvao_ccZCZ5Ld74oyKNhafY2A1uFNSmsmJ5bLUYIM/edit?usp=sharing) for a comprehensive list of items being used. Not all items will be added to the project, but it's a helpful reference for what's available.

## Contributing

We welcome contributions! Here's how to help:

### Making a Pull Request

1. **Fork the repository** on GitHub
2. **Clone your fork locally**:
   ```bash
   git clone https://github.com/your-username/dl-com-items.git
   ```
3. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** to the relevant files
5. **Commit your changes**:
   ```bash
   git commit -m "Brief description of your changes"
   ```
6. **Push to your branch**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request** on the main repository with a clear description of your changes

### What to Contribute

- New items or item modifications
- Item images and assets
- Localization improvements for item names and descriptions
- Bug fixes or documentation improvements

### Event Participation

This project is open to community contributions during development events. Check back for announcements on special events where we focus on expanding the item database. All contributors are welcome!

