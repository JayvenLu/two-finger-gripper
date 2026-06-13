# Two-Finger Gripper

Plain static GitHub Pages site for the two-finger vision-tactile gripper build.

Live page: https://jayvenlu.github.io/two-finger-gripper/

## Open-source CAD

The editable hardware design source is available in [`assets/CAD`](assets/CAD):

| Model | STEP source |
| --- | --- |
| Complete gripper | [`2finger_gripper.STEP`](assets/CAD/2finger_gripper.STEP) |

Use the STEP file for manufacturing and modification.

The CAD source under `assets/CAD/` is licensed under the [CERN Open Hardware Licence Version 2 - Strongly Reciprocal](assets/CAD/LICENSE.txt). Modified designs conveyed to others must remain available under the reciprocal terms of that license. The website code, photographs, videos, and other media outside `assets/CAD/` are not covered by this CAD license.

Suggested citation:

> Xiaofan Lu and Yuankai Lin, "Two-Finger Gripper CAD," GitHub repository, 2026. https://github.com/JayvenLu/two-finger-gripper

See [`assets/CAD/README.md`](assets/CAD/README.md) for credits, license scope, and the canonical source location.

## Local preview

```powershell
python -m http.server 4181 --bind 127.0.0.1
```
