{
  "id": "aetherial-expanse",
  "title": "Aetherial Expanse",
  "description": "Setting guide for the Aetherial Expanse by Ghostfire.",
  "manifest": "https://r2.foundryvtt.com/packages-public/aetherial-expanse/module.json",
  "url": "https://ghostfiregaming.com/aetherial-expanse/",
  "version": "1.0.5",
  "protected": false,
  "bugs": "https://support.metamorphic-digital.com",
  "changelog": "https://support.metamorphic-digital.com/changelog/aetherial-expanse",
  "authors": [
    {
      "name": "MetaMorphic Digital Studio",
      "url": "https://metamorphic-digital.com/"
    },
    {
      "name": "Ghostfire",
      "url": "https://ghostfiregaming.com/aetherial-expanse/"
    }
  ],
  "compatibility": {
    "minimum": "12.331",
    "verified": "13"
  },
  "media": [
    {
      "type": "cover",
      "url": "modules/aetherial-expanse/assets/art/ae-setting-guide-cover-new.webp"
    },
    {
      "type": "icon",
      "url": "modules/aetherial-expanse/assets/art/ae-setting-guide-cover-new.webp"
    },
    {
      "type": "setup",
      "url": "modules/aetherial-expanse/assets/art/ae-setting-guide-cover-new.webp"
    }
  ],
  "languages": [
    {
      "lang": "en",
      "name": "English",
      "path": "lang/en.json",
      "flags": {}
    }
  ],
  "packs": [
    {
      "label": "Books",
      "name": "books",
      "type": "JournalEntry",
      "path": "packs/books",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/ae-setting-guide-cover-new.webp",
      "flags": {
        "dnd5e": {
          "display": "table-of-contents"
        }
      }
    },
    {
      "label": "Items",
      "name": "items",
      "type": "Item",
      "path": "packs/items",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/0224-fb02-book-a-commander-s-lair-fina.webp"
    },
    {
      "label": "Subclasses",
      "name": "subclasses",
      "type": "Item",
      "path": "packs/subclasses",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/fb002-6-1-oceane-the-bard-nikki-dawes.webp"
    },
    {
      "label": "Tables",
      "name": "tables",
      "type": "RollTable",
      "path": "packs/tables",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/fb002-1-sg-gate-of-the-fatherland-jake-murray-copy.webp"
    },
    {
      "label": "Monsters",
      "name": "monsters",
      "type": "Actor",
      "path": "packs/monsters",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/0149-aesg-monster-cmyk.webp"
    },
    {
      "label": "Origins",
      "name": "origins",
      "type": "Item",
      "path": "packs/origins",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/0114-aesg-creating-character-export.webp"
    },
    {
      "label": "Scenes",
      "name": "scenes",
      "type": "Scene",
      "path": "packs/scenes",
      "system": "dnd5e",
      "package": "aetherial-expanse",
      "visible": true,
      "banner": "modules/aetherial-expanse/assets/art/0083-aesg-island-bound.webp"
    }
  ],
  "scripts": [],
  "esmodules": [
    "./index.js"
  ],
  "styles": [
    "./style.css"
  ],
  "flags": {
    "dnd5e": {
      "sourceBooks": {
        "Aetherial Expanse": "GFGAE.BOOK"
      },
      "spellLists": [
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellsbard0000",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellscleric00",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellsdruid000",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellspaladin0",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellsranger00",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellssorcerer",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellswarlock0",
        "Compendium.aetherial-expanse.books.JournalEntry.gfgaexps10newspe.JournalEntryPage.10spellswizard00"
      ]
    }
  },
  "relationships": {
    "systems": [
      {
        "id": "dnd5e",
        "type": "system",
        "manifest": "https://raw.githubusercontent.com/foundryvtt/dnd5e/master/system.json",
        "compatibility": {
          "minimum": "4.3",
          "verified": "5.0"
        }
      }
    ]
  },
  "packFolders": [
    {
      "name": "Aetherial Expanse",
      "sorting": "a",
      "color": "#632727",
      "packs": [
        "books",
        "items",
        "tables",
        "monsters",
        "origins",
        "scenes",
        "subclasses"
      ]
    }
  ]
}
