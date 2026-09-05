# Stockee

Smart stock, made simple.

Stockee keeps shelves, pallets and cabinets talking to your inventory system --
weight-sensing bins, plug-and-play ESP32 controllers, and one clean API.

## What lives here

- **StockeeGuardian** - door / cabinet controller. The same firmware also flashes
  as a Shelf controller, so one board does double duty.
- **StockeePallet** & **StockeeShelfV2** - weight-based controllers that watch
  the stock and report what changed.
- **Shared Arduino libraries** - the building blocks every controller uses
  (WiFi + config + upload, auth, I2C bin bus, console, OLED, logging), each with
  source-zip releases.
- **StockeeConfigurator** & **StockeePostgres** - the setup tooling and the
  backend that ties the fleet together.

## The idea

Walk up. Scan a card. The door opens, the shelf notices, the pallet knows.
Inventory updates itself - no clipboards, no guesswork.

Firmware ships as ready-to-flash binaries; libraries ship as source zips. See the
releases tab of each repo.
