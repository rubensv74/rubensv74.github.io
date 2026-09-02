# Power Apps 3D POC

Public test location for GLB files used to validate the Power Apps **3D object / ViewIn3D** control for AssetPlan.

## Current test assets

- `ap-eq-motor-electric-procedural-v2.glb` — current POC motor model
- `ap-eq-motor-electric-procedural.glb` — previous lightweight motor model

## Power Apps Source

Recommended URL for the current POC:

```powerfx
"https://raw.githubusercontent.com/rubensv74/rubensv74.github.io/main/assets/powerapps-poc/ap-eq-motor-electric-procedural-v2.glb"
```

Use the `raw.githubusercontent.com` URL rather than a GitHub `/blob/` page URL so Power Apps receives the GLB binary directly.

## POC gates

- POC-3D-01 — external GLB loads in Power Apps: PASS
- POC-3D-02 — predefined preservation pins bind to the GLB and can be selected: PASS (validated 2026-09-02; test selection returned `PIN 3 | LOW | PR-003`)
- POC-3D-03 — selected pin drives AssetPlan properties panel: PENDING
