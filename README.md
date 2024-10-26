# CCMINER 
FOR ANDROID!
Mine various cryptocurrencies using ccminer ! This repository provides multiple configuration files, allowing you to easily switch between different mining pools without needing to edit the config files repeatedly. Perfect for miners who want flexibility!

## Default Configuration

- The default `./start.sh` script is configured to mine to **NiceHash**. Follow the steps below to set up your mining rig and start earning BTC!

## Available Configurations

1. **config_nh_vh.json**: 
   - Mines **VerusHash** at NiceHash for Bitcoin (BTC).

2. **config_vh.json**: 
   - Mines **Verus Coin** at VerusPool.
3. **config_X11.json**: 
   - Mines coins associated with **X11** at Nicehash, and get paid in **BTC**.

## Prerequisites

- **Linux Knowledge**: Some fundamental Linux knowledge is required. Brush up on it via an online course if needed.
- **Linux Screen**: Learn how to use `screen` for long-term mining sessions.
- **SSH and SCP**: Recommended for remote management.
- **Stable Network**: Ensure a stable WiFi or cellular connection.

## How to Use

1. **Installing CCMINER & config files**:
```
curl -o- -k https://raw.githubusercontent.com/tanishdt/ccminer/main/install.sh | bash
```
3. **Start Mining!**
   # For mining VerusHash at NiceHash
   ```
   ./ccminer -c config_nh_vh.json
   ```
   
   # For mining Verus Coin at VerusPool

   ```
   ./ccminer -c config_vh.json 
   ```
   # For X11 at Nicehash
   ```
      ./ccminer -c config_X11.json 
   ```
