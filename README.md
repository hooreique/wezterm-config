```lua
-- use powershell
config.default_prog = { 'path/to/AppData/Local/Microsoft/WindowsApps/Microsoft.PowerShell_8wekyb3d8bbwe/pwsh.exe' }
config.color_scheme = 'Monokai Remastered'
config.font = wezterm.font 'JetBrains Mono'
config.font_size = 11.5
config.initial_cols = 120
config.initial_rows = 31
-- disable ligature
config.harfbuzz_features = { 'calt=0', 'clig=0', 'liga=0' }
```