# Hyprland plugin requalification, 2026-11-27T17:00:01Z

CI requalification of the Cua Hyprland plugin per Hyprland build. Not native certification and not a package: the reviewed kit/profile process stays the release gate.

| Channel | Hyprland | ABI key | Plugin (refs) | Build | CTest | Load | Input smoke | Status |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| arch | 0.57.2-2 | `9afded099cfa1866` | cua-driver-rs-v0.38.0 (`aa330aebe172`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| arch | 0.57.2-2 | `9afded099cfa1866` | cua-driver-rs-v0.33.2 (`5b3d63841bb6`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| arch | 0.57.2-2 | `9afded099cfa1866` | main (`48b1b7fa3712`) | pass | pass (21/21) | pass | pass | pass |
| omarchy-edge | 0.57.2-2 | `9afded099cfa1866` | cua-driver-rs-v0.38.0 (`aa330aebe172`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| omarchy-edge | 0.57.2-2 | `9afded099cfa1866` | cua-driver-rs-v0.33.2 (`5b3d63841bb6`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| omarchy-edge | 0.57.2-2 | `9afded099cfa1866` | main (`48b1b7fa3712`) | pass | pass (21/21) | pass | pass | pass |
| omarchy-rc | 0.57.2-7 | `abbcd3efd3b02da4` | main (`48b1b7fa3712`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| omarchy-rc | 0.57.2-7 | `abbcd3efd3b02da4` | cua-driver-rs-v0.33.2 (`5b3d63841bb6`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| omarchy-rc | 0.57.2-7 | `abbcd3efd3b02da4` | cua-driver-rs-v0.38.0 (`aa330aebe172`) | **FAIL** | n/a | n/a | n/a | **FAIL** |
| omarchy-stable | 0.56.2-4 | `89cc2f58bf5a70e9` | main (`48b1b7fa3712`) | pass | pass (21/21) | pass | pass | pass |
| omarchy-stable | 0.56.2-4 | `89cc2f58bf5a70e9` | main (`aa330aebe172`) | pass | pass (20/20) | pass | pass | pass |
| omarchy-stable | 0.56.2-4 | `89cc2f58bf5a70e9` | main (`b477f0617505`) | pass | pass (20/20) | pass | pass | pass |
| omarchy-stable | 0.56.2-4 | `89cc2f58bf5a70e9` | main, cua-driver-rs-v0.34.0 (`0dec07dc8358`) | pass | pass (20/20) | pass | pass | pass |
| omarchy-stable | 0.56.2-4 | `89cc2f58bf5a70e9` | cua-driver-rs-v0.32.0 (`5b3d63841bb6`) | pass | pass (20/20) | pass | pass | pass |

## Header and module hashes

| Hyprland | Binary SHA-256 | Header inventory SHA-256 | GCC | Module SHA-256 | Plugin tree |
| --- | --- | --- | --- | --- | --- |
| 0.57.2-2 | `d9117121713a84d5b0774f426e3f2f5a9baecb8c02e11726c813429de61ba427` | `546d1e2fd886d9d62f3abd8cf3e0df35b47c6bfa270499171bcc720a8869e345` | 16.2.1 20260810 | `` | `5b3d63841bb6` |
| 0.57.2-2 | `d9117121713a84d5b0774f426e3f2f5a9baecb8c02e11726c813429de61ba427` | `546d1e2fd886d9d62f3abd8cf3e0df35b47c6bfa270499171bcc720a8869e345` | 16.2.1 20260810 | `` | `aa330aebe172` |
| 0.57.2-7 | `` | `` |  | `` | `48b1b7fa3712` |
| 0.57.2-7 | `` | `` |  | `` | `5b3d63841bb6` |
| 0.57.2-7 | `` | `` |  | `` | `aa330aebe172` |

Upstream Hyprland: [v0.57.2](https://github.com/hyprwm/Hyprland/releases/tag/v0.57.2) (packaged).

Omarchy `cua-hyprland-plugin 0.47.8-11` on omarchy-edge: NOT installable.

Omarchy `cua-hyprland-plugin 0.47.8-10` on omarchy-rc: installable.

Omarchy `cua-hyprland-plugin 0.33.2-3` on omarchy-stable: installable.
