# rockchip-multimedia-config

This debian package is to enable legacy multimedia support in ARM Linux environments with Rockchip SoCs.

Installing rockchip-multimedia-config enables hardware media decoding and encoding provided by [mpp](https://github.com/rockchip-linux/mpp) and others on your system (requires separate installation of [mpp](https://github.com/tsukumijima/mpp/releases), [librga](https://github.com/tsukumijima/librga/releases) and others).  
Note that additional configs may be required.

## Installation

```bash
wget https://github.com/tsukumijima/rockchip-multimedia-config/releases/download/v1.0.1-1/rockchip-multimedia-config_1.0.1-1_all.deb
sudo apt install ./rockchip-multimedia-config_1.0.1-1_all.deb
rm rockchip-multimedia-config_1.0.1-1_all.deb
```
