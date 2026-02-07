# rlbot/scratch-example

This repo contains everything you need to get started making a scratch bot for
RLBot v5!

## Running in "dev-mode"

1. Add the bot.toml file to your RLBot GUI using the `Add/Remove` button
1. Run the bridge binary (`./rlbot-scratch-bridge` on linux,
   `./rlbot-scratch-bridge.exe` on windows)
1. Open `project.sb3` in the turbowarp editor
1. Start a match with the bot and **make sure you've disabled autostart for your 
   bot!**
1. Press the green flag

## Running using autostart

1. Add the bot.toml file to your RLBot GUI using the `Add/Remove` button
1. Start a match with the bot, and it should run headless

## Bridge notes

The bridge binary supports a couple of CLI flags, such as `--packetrate`. To
see all of the available flags, run the binary with the `--help` flag.
