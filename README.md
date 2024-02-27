# Initializing DFX

Run dfx in separate terminal

```
dfx start --clean
```

# Configuring dfx.json

```
{
    "canisters": {
      "vanilla-icp": {
        "frontend": {
          "entrypoint": "src/index.html"
        },
        "source": ["src"],
        "type": "assets"
      }
    },
    "dfx": "0.17.0",
    "version": 1
  }
```

# Deploying your landing page (frontend)

Open VS Code and open a terminal instance and run:

```
dfx deploy
```
#   p r o j e c t - b l o c k c h a i n  
 