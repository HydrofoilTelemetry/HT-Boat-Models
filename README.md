# HT-Boat-Models
HTX1 Series / HTX2 Series
# Hydrofoil Telemetry — Custom Boat Expansion Fleet

**Custom High-Performance Foiling Boats for Hydrofoil Generation**

Hydrofoil Telemetry has developed a fleet of 10 custom and upgraded boat models for *Hydrofoil Generation*, expanding the game's original lineup with new designs, advanced foiling configurations, and enhanced sailing performance.

These are not simply modified 3D renderings. Each boat is a complete, game-ready package containing its own model geometry, physics data, skins, rigging, server data, and supporting files.

All models are designed to integrate directly into Hydrofoil Generation's existing boat system.

## HT X1 Series — Fleet Expansion

Five custom high-performance foiling boats:

- **HTX1** — A longer, narrower evolution of the JX50 with improved stability, higher pointing ability, deeper downwind angles, and faster maneuvers.
- **HTXE** — A compact twin-hull foiler featuring deck-level trampolines, narrow beam, and dual wings.
- **HTXS** — A powerful hybrid-wing offshore racer designed for extreme speeds exceeding 75 knots.
- **HTXZ** — An extreme offshore maxi foiler built for high-speed open-water racing.
- **HTXX** — A high-performance experimental foiler pushing the limits of the HT fleet.

## HT X2 Series — Fleet Expansion

Five additional custom boat models:

- **HTX2** — A sleek, elongated JX40-inspired design with a forward-positioned foresail, improved stability, and enhanced upwind performance.
- **HTXM** — A compact 10-meter micro foiler featuring trampolines, rapid foil takeoff, and responsive handling.
- **HTXR** — An exceptionally long and narrow 75-foot offshore racer with modified sails, rigging, and a surfing bow, designed for speeds approaching 75–80 knots.
- **HTXF** — The flagship HT offshore racing machine, featuring a distinctive gooseneck bow, twin wing rigs, and advanced foresail configurations.
- **HTXY** — An experimental high-performance foiling design expanding the HT X2 racing fleet.

## Installation

**Requirements:** A working Steam installation of Hydrofoil Generation.

1. Download the desired boat package from this repository.
2. Extract the ZIP archive.
3. Open your Hydrofoil Generation installation directory. In Steam, right-click *Hydrofoil Generation*, select **Manage → Browse local files**, and navigate to `content\boats`.
4. Copy the included HT boat folders directly into the `boats` directory.
5. Launch Hydrofoil Generation and select your new HT boat.

### Example directory structure

```text
Hydrofoil Generation/
└── content/
    └── boats/
        ├── f50/
        ├── jx40/
        ├── jx50/
        ├── HTX1/
        ├── HTXE/
        ├── HTXS/
        ├── HTXZ/
        ├── HTXX/
        ├── HTX2/
        ├── HTXM/
        ├── HTXR/
        ├── HTXF/
        └── HTXY/
```

**Important:** Do not place an additional ZIP package folder between `boats` and the individual boat model folders. Preserve the original folder names and file structure.

## Game Integration

Each HT boat package includes the supporting data required for Hydrofoil Generation to recognize and load the model.

When a boat is used, Hydrofoil Generation automatically generates its corresponding user setup and performance targets `.kl` files. These files can be edited and updated by the game.

For multiplayer use, the server and participating players may need matching custom boat files.

## Uninstallation

To remove an HT boat, close Hydrofoil Generation and delete only that model's folder from `content\boats`.

Do not delete or modify the original game boat folders.

## Hydrofoil Telemetry

Hydrofoil Telemetry develops independent applications, utilities, custom content, and research tools for Hydrofoil Generation.

Visit the official HT website for additional information, project updates, and documentation.

**Website:** https://sites.google.com/view/hydrofoil-telemetry/home

*Hydrofoil Telemetry is an independent community project and is not officially affiliated with the developers of Hydrofoil Generation.*
