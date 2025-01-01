# Pepsiman

This folder contains the hexed version of **[Pepsiman]** for use with Model Manager in Team Fortress 2.

## Original Model Information
- **Model Name:** <ins>Pepsiman for Scout (playermodel)</ins>
- **Author(s):** <ins>Aftroid</ins> 
- **Original Model Link:** [Pepsiman](https://gamebanana.com/mods/206174)

## File Structure
The following folder layout is used to organise the model and textures:

```
Server/
    models/
    └── custom/
        └── player/
            ├── [pepsi]

    materials/
    └── models/
        └── custom/
            └── player/
                ├── [pepsi]

FastDL/
    models/
    └── custom/
        └── player/
            ├── [pepsi]

    materials/
    └── models/
        └── custom/
            └── player/
                ├── [pepsi]
```

### Explanation:
- **`Server/` Directory**: Includes normal model and materials files for the TF2 server directory.  
- **`FastDL/` Directory**: Includes compressed .bz2 files for your FastDL webserver.

Ensure these files are placed in their corresponding directories for correct functionality.

## Installation and Usage
1. Extract the contents of the `Server/` and `FastDL/` directories into the designated locations.
2. Update the Model Manager configuration to reference the hexed model:
   ```json
    "Pepsiman"
    {
       "model"			"models/custom/player/pepsi/scout.mdl"
       "flags"			""
       "classes"		        "SCOUT"
       "teams"			"ALL"
     }
   ```
3. __tf_models_reload__  into the server console to reload list of configured models.

## Credits and Disclaimer
This hexed version is based on the original model created by **[IateMyBingoCard]**.  
All rights to the original work belong to its creator(s). If there are any issues or removal requests, please contact me.

## Contact
For questions, issues, or requests, reach out via PM.
