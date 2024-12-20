# Kyoyu

A Minecraft mod inspired by syncmatica.
Share litematics with other players on the server.

[![License](https://img.shields.io/github/license/Vulpeus-Server/kyoyu)](http://www.gnu.org/licenses/lgpl-3.0.html)
[![Modrinth](https://img.shields.io/modrinth/dt/VozTPxB4?label=Modrinth%20Downloads)](https://modrinth.com/mod/VozTPxB4)
[![Discord](https://img.shields.io/discord/1157213775791935539?logo=Discord)](https://discord.gg/tjayanzYMf)

[![GitHub Workflow](https://github.com/Vulpeus-Server/kyoyu/actions/workflows/gradle.yml/badge.svg)](https://github.com/Vulpeus-Server/kyoyu/actions/workflows/gradle.yml)
[![GitHub Issues](https://img.shields.io/github/issues/Vulpeus-Server/kyoyu)](https://github.com/Vulpeus-Server/kyoyu/issues)
[![GitHub Created At](https://img.shields.io/github/created-at/Vulpeus-Server/kyoyu)](https://github.com/Vulpeus-Server/kyoyu)

## Versions

### server
| version | platforms                      | dependency         |
|---------|--------------------------------|--------------------|
| 1.14.4  | fabric, forge                  | `>=1.14 <=1.14.4`  |
| 1.15.2  | fabric, forge                  | `>=1.15 <=1.15.2`  |
| 1.16.5  | fabric, forge                  | `>=1.16 <=1.16.5`  |
| 1.17.1  | fabric, forge                  | `>=1.17 <=1.17.1`  |
| 1.18.2  | fabric, forge                  | `>=1.18 <=1.18.2`  |
| 1.19.4  | fabric, forge, paper           | `>=1.19 <=1.19.4`  |
| 1.20.4  | fabric, forge, paper           | `>=1.20 <=1.20.4`  |
| 1.20.6  | fabric, forge, neoforge, paper | `>1.20.4 <=1.20.6` |
| 1.21.3  | fabric, forge, neoforge, paper | `>=1.21 <=1.21.3`  |

### client
| version | platforms     | dependency         |
|---------|---------------|--------------------|
| 1.14.4  | fabric        | `>=1.14 <=1.14.4`  |
| 1.15.2  | fabric        | `>=1.15 <=1.15.2`  |
| 1.16.5  | fabric, forge | `>=1.16 <=1.16.5`  |
| 1.17.1  | fabric        | `>=1.17 <=1.17.1`  |
| 1.18.2  | fabric        | `>=1.18 <=1.18.2`  |
| 1.19.4  | fabric        | `>=1.19 <=1.19.4`  |
| 1.20.4  | fabric        | `>=1.20 <=1.20.4`  |
| 1.20.6  | fabric        | `>1.20.4 <=1.20.6` |
| 1.21.3  | fabric        | `>=1.21 <=1.21.3`  |


## Features (WIP)

- [x] Error Handling
- [x] Code Format and Review
- [x] Client only depend (malilib, litematica)
- [ ] legacy litematica support?
- [ ] Forgematica support?
- [ ] Plugin support?
- Network
- [x] Handshake Packet
- [x] FileRequest Packet
- [x] FileResponce Packet
- [x] LoadExplorer Packet
- [x] PlacementMeta Packet
- [x] RemovePlacement Packet
- Client
- [x] Share button on Placements menu
- [x] Synced Litematics List UI
    - [x] Download
    - [x] Load
    - [x] Material List
    - [x] Remove
- [ ] Re-Lock (modify)
- [x] Unload
- [x] Relogin compatibility
- [x] on Placement Update Event
- Server
- [x] Save SyncLitematicConfig
- [x] Restore SyncLitematicConfig
- Data Types
- [x] Pos
- [x] Mirror
- [x] Rotation
- [ ] Ignore Entities
- [ ] Subregion
    - [x] Pos
    - [x] Mirror
    - [x] Rotation
    - [ ] Ignore Entities
    - [ ] Placement ON/OFF
