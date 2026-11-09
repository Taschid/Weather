# Weather Rainmeter skin

Rainmeter weather card fed by Open-Meteo via a local toolkit.

The skin is a read-only viewer. It polls a single pipe-separated status file
written by a local toolkit; no credentials or account data live here.

## Install

1. Copy this folder into `Documents\Rainmeter\Skins\Weather`.
2. Load `Weather.ini` from the Rainmeter manager.
3. Set your toolkit folder under `[Variables]` in the ini:

   `ini
   ToolsRoot=C:\Tools
   `

   The skin expects its toolkit under `%ToolsRoot%\weather`.
   The Lua helpers, if present, have a `PATH` constant near the top with
   the same value in forward-slash form.
