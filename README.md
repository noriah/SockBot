# SockBot

[![Dependency Status](https://img.shields.io/david/noriah/sockbot.svg?style=flat)](https://david-dm.org/noriah/sockbot)

## About

SockBot is a *simple* bot for [Discord](https://discordapp.com/). It runs on node, blood, sweat and tears.

It's still in major development and will be added to all the time.


## Other Stuff

SockBot uses a redis server for caching data. Data is kept for a varried length of time depending
on the type of data. 

Currently, the chat prefix is `]`. This will be changing once I reach a point that makes sense?

## Commands
All commands must be prefxied with `]`

Command arguments follow the format `<required> (optional)`

#### Games:
- `lol` - Commands for league of legends
- `lol match <region> <summoner>` - Get current match data for a summoner in a region
