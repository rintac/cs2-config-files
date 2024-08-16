# cs2-config-files

## INFORMATION
- These are my current keybind configuration files for Counter-Strike 2
- There is a "default" keybind configuration that automatically executes upon launch, and "gamemode" specific keybind configurations that need to be executed when desired
  - Surf configuration (c_surf.cfg)
  - Demo configuration (c_demo.cfg) [**WORK IN PROGRESS**]
  - Throwable practice server configuration (c_nade.cfg)

## INSTALLATION & VERIFICATION
1. Extract (or `git clone`) the .cfg files to the Counter-Strike 2 configuration directory
  - **Windows:** `~\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\`
  - **Linux:** `TBD`
1. Add `+exec !!init.cfg` to the *beginning* of your launch options of Counter-Strike 2
1. Add `-console` *after* the launch option added in the previous step
1. Open the console (~) upon starting the game, you should see an ASCII banner; this verifies that the "autoexecute" configuration file ran properly

## USAGE
- To execute a "gamemode" specific configuration file, enter `exec c_name` in the console
  - For instance, this would be `exec c_demo` in the console whenever reviewing demos
- If returning to regular gameplay, enter `exec !!init` in the console

## TODO
- Flesh out the demo config
- Add Crosshair/HUD config files and update !!init to include them

## CREDITS
- [PAT or JK ASCII Art Generator](https://patorjk.com/software/taag/)
- [CFG.TF ASCII Art Console Converter](https://cfg.tf/tools/asci/)
