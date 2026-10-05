# Awesome-Digital-Card-Games

# Awesome-Digital-Card-Games

**Curated List of Commercial Card Games & Open-Source GitHub Projects**
*Focused on Solitaire Collections, TCG Engines, Roguelike Deckbuilders & Multiplayer Card Games*
**Last updated: October 2026**

This repository tracks notable **commercial card games** and **open-source projects** for **Digital Card Gaming**. These tools help players enjoy classic solitaire variants, competitive trading card games, and roguelike deckbuilders—and help developers build their own card game engines.

**Examples** include Microsoft Solitaire Collection, Hearthstone, Magic: The Gathering Arena, Legends of Runeterra, Yu-Gi-Oh! Master Duel, Marvel Snap, Gwent, Slay the Spire, Balatro, and Solitaired (the category leaders).

**Open-source emphasis**: The open-source card game ecosystem is **diverse and production-proven**. **PySolFC** is the definitive solitaire collection with **over 1,200 games**, a hint system, unlimited undo, and player statistics . **Cardinal Codex** provides a headless, deterministic TCG engine with TOML-based rule definitions . **Cardio** delivers a roguelike deckbuilding platform inspired by Inscryption, written in Python . **Slay the Web** is a browser-based Slay the Spire clone with a UI-agnostic game engine .

## 📖 Table of Contents

- [💼 Commercial Card Games](#-commercial-card-games)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 💼 Commercial Card Games

> **📊 Market Context**: The digital card game market is **moderately fragmented** across solitaire, TCG, and roguelike deckbuilder segments. **Solitaire** remains the most accessible category, with **Disney Solitaire** and **Solitaire Grand Harvest** leading grossing charts . **Pokémon TCG Pocket** has surged to **#3 in top-grossing card apps** , while **Magic: The Gathering Arena** (#6), **Yu-Gi-Oh! Master Duel** (#12), and **Hearthstone** (#15) remain dominant TCGs . **Marvel Snap** offers a streamlined, fast-paced TCG experience popular on mobile . The roguelike deckbuilder segment, pioneered by **Slay the Spire**, has expanded with **Balatro's** poker-inspired twist. No single vendor holds a winner-take-all position; players typically engage with multiple card games across platforms.

| Game | Description | Pricing | Free Tier Limits | Company Size |
|------|-------------|---------|------------------|--------------|
| **[Microsoft Solitaire Collection](https://www.microsoft.com/en-us/p/microsoft-solitaire-collection/9wzdncrfj3tj)** | **The default Windows solitaire suite.** Klondike, Spider, FreeCell, Pyramid, TriPeaks with daily challenges and events. | **Free** with Windows; **Premium** removes ads. | **Free tier**: Core games with ads. **Premium**: Ad-free experience. | **~$281B revenue (Microsoft FY2025)** |
| **[Hearthstone](https://playhearthstone.com/)** | **Blizzard's flagship TCG.** Accessible gameplay, regular expansions, and robust esports scene. | **Free-to-play** with card packs and cosmetics. | **Free**: Starter decks and solo content. **Paid**: Card packs and adventure content. | **~$8.7B revenue (Activision Blizzard FY2025 est.)** |
| **[Magic: The Gathering Arena](https://magic.wizards.com/en/mtgarena)** | **Digital adaptation of the physical TCG.** Full rules implementation, draft formats, and regular set releases. | **Free-to-play** with gem and gold purchases. | **Free**: Starter decks and daily quests. **Paid**: Gems, packs, and cosmetics. | **~$1B+ revenue (Hasbro Wizards of the Coast est.)** |
| **[Marvel Snap](https://www.marvelsnap.com/)** | **Fast-paced, streamlined TCG.** 12-card decks, 6-turn matches, and location-based strategy. | **Free-to-play** with season passes and bundles. | **Free**: Core gameplay with progression. **Paid**: Season pass and variants. | **Private (Second Dinner)** |
| **[Slay the Spire](https://www.megacrit.com/)** | **The roguelike deckbuilder that defined the genre.** Build a deck, climb the Spire, and defeat the Corrupt Heart. | **$24.99** one-time purchase. | **No free tier**. Full game purchase required. | **Private (Mega Crit Games)** |
| **[Balatro](https://www.playbalatro.com/)** | **Poker-inspired roguelike deckbuilder.** Build poker hands to score points and break the game. | **$14.99** one-time purchase. | **No free tier**. Full game purchase required. | **Private (LocalThunk/Playstack)** |
| **[Solitaired](https://solitaired.com/)** | **Free online solitaire collection.** Over 500 game variants with no downloads. | **Free** — ad-supported. | **Free**: Full access to 500+ solitaire games. | **Private** |
| **[Gwent: The Witcher Card Game](https://www.playgwent.com/)** | **The Witcher universe TCG.** Strategic, round-based gameplay with faction decks. | **Free-to-play** with card packs. | **Free**: Starter decks and progression. | **Part of CD Projekt Red** |
| **[Yu-Gi-Oh! Master Duel](https://www.konami.com/yugioh/masterduel/)** | **Digital Yu-Gi-Oh! TCG.** Full card pool with ranked and casual play. | **Free-to-play** with gem purchases. | **Free**: Starter decks and solo content. | **~$2B+ revenue (Konami FY2025 est.)** |
| **[Legends of Runeterra](https://playruneterra.com/)** | **Riot's League of Legends TCG.** Generous free-to-play model with region-based decks. | **Free-to-play** with cosmetic purchases. | **Free**: Full card collection progression. | **~$1.5B+ revenue (Riot Games est.)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[PySolFC](https://github.com/shlomif/PySolFC)** — **The definitive open-source solitaire collection.** Fork of PySol with **over 1,200 solitaire card games** . Features: modern look and feel, multiple cardsets and tableau backgrounds, sound, unlimited undo, player statistics, hint system, demo games, solitaire wizard, plugin support, and integrated HTML help . **GPLv2+/GPLv3+** . Available on Flathub and FreeBSD ports . | [![Stars](https://img.shields.io/github/stars/shlomif/PySolFC?style=social&color=white)](https://github.com/shlomif/PySolFC/stargazers) | ~1,000 |
| **[KPatience](https://invent.kde.org/games/kpat)** — **KDE's polished solitaire collection.** Ships with **13 of the most popular Solitaire variants**—Klondike, Spider, Simple Simon, Yukon, Golf, and others . **Quality-over-quantity approach**: cleaner modern interface, full keyboard support, smoother animations, crisp art, and pleasant sound effects . First-party KDE application with seamless Plasma integration . **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/KDE/kpat?style=social&color=white)](https://github.com/KDE/kpat/stargazers) | ~500 |
| **[Cardinal Codex](https://github.com/Big-Sky-Tech/Cardinal-Codex)** — **Headless, deterministic game engine for trading card games (TCGs).** Define game rules in **TOML**—no code changes needed . Features: fully deterministic (same seed + actions = identical outcome), 14 builtin effects, hybrid card system (TOML + Rhai scripts), headless (embed in any interface), event-based complete game log, 67 tests . **Production-ready tooling** for validation, compilation, and testing . | [![Stars](https://img.shields.io/github/stars/Big-Sky-Tech/Cardinal-Codex?style=social&color=white)](https://github.com/Big-Sky-Tech/Cardinal-Codex/stargazers) | ~100 |
| **[Cardio](https://github.com/ymyke/cardio)** — **Open-source, community-driven roguelike deckbuilding card game.** Written in Python, heavily inspired by **Inscryption** . Single-player, terminal-based. Aspires to become a platform for a game that evolves over time, driven by community of players and developers . **GPLv3**. | [![Stars](https://img.shields.io/github/stars/ymyke/cardio?style=social&color=white)](https://github.com/ymyke/cardio/stargazers) | ~200 |
| **[Slay the Web](https://github.com/oskarrough/slaytheweb)** — **Browser-based Slay the Spire clone.** Single-player deck-building roguelike for the web . **UI-agnostic game engine** with an example web UI . JavaScript-based, deployed on Cloudflare. Open for community contributions (new cards, monsters, worlds) . | [![Stars](https://img.shields.io/github/stars/oskarrough/slaytheweb?style=social&color=white)](https://github.com/oskarrough/slaytheweb/stargazers) | ~500 |
| **[AisleRiot (GNOME Games)](https://gitlab.gnome.org/GNOME/aisleriot)** — **GNOME's solitaire collection.** Part of the GNOME Games suite with dozens of solitaire variants . Free and open source with GNOME integration . | [![Stars](https://img.shields.io/github/stars/GNOME/aisleriot?style=social&color=white)](https://github.com/GNOME/aisleriot/stargazers) | ~200 |
| **[PokerTH](https://github.com/pokerth/pokerth)** — **Open-source Texas Hold'em poker client.** Online multiplayer lobbies, local network games, and AI opponents with adjustable difficulty . Flexible match lengths from 10-minute sessions to longer strategic games . **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/pokerth/pokerth?style=social&color=white)](https://github.com/pokerth/pokerth/stargazers) | ~500 |
| **[Scoundrel](https://github.com/Lizzard1123/scoundrel)** — **Dungeon-crawling card game for the terminal.** Navigate rooms, collect cards, and battle monsters . Includes **MCTS agent** with parallelization, **RL agent** using Transformer-based architecture with PPO training, and interactive terminal UI . Python-based, PyPI package available . | [![Stars](https://img.shields.io/github/stars/Lizzard1123/scoundrel?style=social&color=white)](https://github.com/Lizzard1123/scoundrel/stargazers) | ~100 |
| **[LSkat](https://invent.kde.org/games/lskat)** — **Digital implementation of the German card game Skat.** Simplified variant (Lieutenant Skat) designed for two players—human vs AI or human vs human . Fast-paced, tactical, with clean and polished modern visual style . **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/KDE/lskat?style=social&color=white)](https://github.com/KDE/lskat/stargazers) | ~100 |
| **[TriPeaks NEUE](https://github.com/)** — **Stylish, modern take on classic TriPeaks solitaire.** Emphasizes speed and pattern recognition, ideal for quick sessions . Available on Flathub. | [![TriPeaks](https://img.shields.io/badge/TriPeaks-NEUE-blue)](https://github.com/) | N/A |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[SolitaireCG](https://fdroid.gitlab.io/jekyll-fdroid/en/packages/net.sourceforge.solitaire_cg/index.html)** — Android solitaire collection. Klondike, Spider, Freecell, Forty Thieves, and more. Multi-level undo, animated card movement, statistics . |
| **[TCG Engines](https://github.com/TheCardGoat/tcg-engines)** — Framework for building TCG engines. Includes Lorcana and Gundam reference implementations, template engine, and core utilities for card tooling, validation, and telemetry . |
| **[Journeys in the Land of Ash](https://github.com/kghawes/card-game)** — Morrowind-themed roguelike deckbuilding game inspired by Slay the Spire. Turn-based combat, dual-resource system, guild-based classes, randomized encounters . |
| **[cardstock](https://github.com/mgoadric/cardstock)** — General card game playing engine. Jupyter Notebook-based . |
| **[Tarok](https://github.com/mytja/Tarok)** — Open-source Tarock program. Online (WebSocket) or offline (bots) play . |
| **[end_of_eden](https://github.com/BigJK/end_of_eden)** — Slay the Spire-like roguelite fully in console. Lua-based, MIT licensed . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Commercial card games may include **loot boxes, microtransactions, or gambling mechanics**; review age ratings and parental controls before allowing minors to play.
- **Open-source reality**: The open-source ecosystem for digital card games is **diverse and production-proven**. **PySolFC** is the definitive solitaire collection with **over 1,200 games** . **Cardinal Codex** provides a headless, deterministic TCG engine with TOML-based rules . **Cardio** and **Slay the Web** demonstrate active roguelike deckbuilder communities . However, **commercial card games** (Hearthstone, MTG Arena, Marvel Snap) provide **polished UX, competitive matchmaking, and regular content updates** that open-source alternatives may lack. The open-source path is **genuinely viable** for solitaire enthusiasts and developers building custom card game engines.

---

**Made for card game enthusiasts, solitaire players, TCG competitors, and game developers.**
Let's make digital card gaming more open, transparent, and community-driven.
