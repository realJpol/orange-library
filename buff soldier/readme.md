# Buff Soldier

This folder contains the hexed version of **[Buff Soldier]** for use with Model Manager in Team Fortress 2.

## Original Model Information
- **Model Name:** <ins>MGE/Buff Soldier</ins>
- **Author(s):** <ins>IateMyBingoCard</ins> 
- **Original Model Link:** [Buff Soldier](https://gamebanana.com/mods/501234)

## File Structure
The following folder layout is used to organise the model and textures:

```
Server/
    models/
    └── custom/
        └── player/
            ├── [mge_soldier]

    materials/
    └── models/
        └── custom/
            └── player/
                ├── [mge_soldier]

FastDL/
    models/
    └── custom/
        └── player/
            ├── [mge_soldier]/

    materials/
    └── models/
        └── custom/
            └── player/
                ├── [mge_soldier]
```

### Explanation:
- **`Server/` Directory**: Includes normal model and materials files for the TF2 server directory.  
- **`FastDL/` Directory**: Includes compressed .bz2 files for your FastDL webserver.

Ensure these files are placed in their corresponding directories for correct functionality.

## Installation and Usage
1. Extract the contents of the `Server/` and `FastDL/` directories into the designated locations.
2. Update the Model Manager configuration to reference the hexed model:
   ```json
    "Buff Soldier"
    {
       "model"			"models/custom/player/mge_soldier/soldier.mdl"
       "flags"			""
       "classes"		        "SOLDIER"
       "teams"			"ALL"
     }
   ```
3. __tf_models_reload__  into the server console to reload list of configured models.

## Credits and Disclaimer
This hexed version is based on the original model created by **[IateMyBingoCard]**.  
All rights to the original work belong to its creator(s). If there are any issues or removal requests, please contact me.

## Contact
For questions, issues, or requests, reach out via PM.
