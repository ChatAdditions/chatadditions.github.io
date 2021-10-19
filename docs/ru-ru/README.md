<h1 align="center">
  <a href="https://github.com/ChatAdditions/ChatAdditions_AMXX/releases"><img src="https://user-images.githubusercontent.com/18553678/125533850-6771c07f-021f-4882-b395-7d68d2679513.png" width="500px" alt="Chat Additions"></a>
</h1>

<p align="center">Плагин AMXModX для управления чатом с богатой функциональностью и API.</p>

<p align="center">
    <a href="https://github.com/ChatAdditions/ChatAdditions_AMXX/releases/latest">
    <img src="https://img.shields.io/github/downloads/ChatAdditions/ChatAdditions_AMXX/total?label=Download%40latest&style=flat-square&logo=github&logoColor=white"
         alt="Build status">
    <a href="https://github.com/wopox1337/ChatsAdditions_AMXX/actions">
    <img src="https://img.shields.io/github/workflow/status/wopox1337/ChatsAdditions_AMXX/Build/master?style=flat-square&logo=github&logoColor=white"
         alt="Build status">
    <a href="https://github.com/wopox1337/ChatsAdditions_AMXX/releases">
    <img src="https://img.shields.io/github/v/release/wopox1337/ChatsAdditions_AMXX?include_prereleases&style=flat-square&logo=github&logoColor=white"
         alt="Release">
    <a href="https://www.amxmodx.org/downloads-new.php">
    <img src="https://img.shields.io/badge/AMXModX-%3E%3D1.9.0-blue?style=flat-square"
         alt="AMXModX dependency">
    <a href="https://t.me/ChatAdditions_group">
    <img src="https://img.shields.io/badge/discussions-on%20Telegram%20group-informational?style=flat-square&logo=googlechat"
         alt="Telegram">
</p>
      
<p align="center">
  <a href="#about">About</a> •
  <a href="#requirements">Requirements</a> •
  <a href="#installation">Installation</a> •
  <a href="#updating">Updating</a> •
  <a href="#downloads">Downloads</a> •
  <a href="#features">Features</a> •
  <a href="#wiki">Wiki</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#credits">Credits</a>
</p>

---

## About
Chat Additions - это набор инструментов для управления как голосовым, так и текстовым чатом для вашего HLDS сервера. 
Позволяет полностью или выборочно ограничить игрока в использовании любого чата (голосовой, общий, командный, администраторский).
Модульная система, позволяет использовать только необходимые возможности задач, тем самым экономя ресурсы сервера.
Богатые возможности API позволяют подключить к системе любой функционал (работа со статистикой игроков, автоматизация решений о блокировке).
<p align="center">
  <img src="https://user-images.githubusercontent.com/18553678/125630814-d572260e-f64a-419b-8a61-6c30b788c188.gif" alt="Chat Additions в работе"></a>
</p>

## Requirements
- Установленый HLDS;
- Установленный [ReGameDLL](https://github.com/s1lentq/ReGameDLL_CS);
- Установленный AMXModX ([`v1.9`](https://www.amxmodx.org/downloads-new.php) или [`v1.10`](https://www.amxmodx.org/downloads-new.php?branch=master));
    - Установленный [ReAPI](https://github.com/s1lentq/reapi) модуль; 
      
## Installation
- [Скачать крайнюю](https://github.com/ChatAdditions/ChatAdditions_AMXX/releases/latest) сиабильную версию с секции релизов.
- Распаковать `cstrike` папку в корневую папку HLDS сервера;
- Убедиться, что все плагины запущены и в корректном порядке следования с помощью команды `amxx list`.

## Updating
- Put new plugins and lang-files (`plugins/*.amxx` & `data/lang/*.txt`) into `amxmodx/` folder on the HLDS server;
- Restart the server (command `restart` or change the map);
- Make sure that the versions of the plugins are up to date with the command `amxx list`.

## Downloads
- [Release builds](https://github.com/ChatAdditions/ChatAdditions_AMXX/releases)
- [Dev builds](https://github.com/ChatAdditions/ChatAdditions_AMXX/actions/workflows/CI.yml)
      
## Features
- Compatibility with any chat manager;
- No [`VoiceTranscoder`](https://github.com/WPMGPRoSToTeMa/VoiceTranscoder) or [`ReVoice`](https://github.com/s1lentq/revoice/) required;
- Flexible system of access rights and immunities for players;
- Modular system, rich API capabilities, and flexibility;
- Simple, intuitive interface (UX);
- Multi-language support;
- Simple, user-friendly configuration;
- `CA_Gag`: Simple, flexible templates system (reasons, times, punishment type);
- `CA_Gag`: Support for SQLite, MySQL, CSBans, GameCMS;
- User-friendly logging system with good customization;
- Up-to-date support and updates.

## Wiki
Do you **need some help**? Check the _articles_ from the [wiki](https://github.com/ChatAdditions/ChatAdditions_AMXX/wiki).

## Contributing
Got **something interesting** you'd like to **share**? Learn about [contributing](CONTRIBUTING.md).

## Credits
I would like to thank the creators of AMXModX and ReAPI and everyone who helps me in developing and testing this system, who supports my interest.
      
**Thank you guys! 👍**

## Support
Reach out to me at one of the following places:
- Github issues;
- Github discussions;
- [Telegram](https://t.me/ShorokhovSergey);
- [Telegram group](https://t.me/ChatAdditions_group);
- E-Mail;

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
 Copyright © Sergey Shorokhov
