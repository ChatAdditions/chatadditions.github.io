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
    <img src="https://img.shields.io/badge/discussions-в%20Telegram%20группе-informational?style=flat-square&logo=googlechat"
         alt="Telegram">
</p>
      
<p align="center">
  <a href="#о-системе">О Системе</a> •
  <a href="#требования">Требования</a> •
  <a href="#установка">Установка</a> •
  <a href="#обновление">Обновление</a> •
  <a href="#загрузки">Загрузки</a> •
  <a href="#возможности">Возможности</a> •
  <a href="#wiki">Wiki</a> •
  <a href="#поддержка-вклад">Поддержка (вклад)</a> •
  <a href="#контакты">Контакты</a>
</p>

---

## О Системе
Chat Additions - это набор инструментов для управления как голосовым, так и текстовым чатом для вашего HLDS сервера. 
Позволяет полностью или выборочно ограничить игрока в использовании любого чата (голосовой, общий, командный, администраторский).
Модульная система, позволяет использовать только необходимые возможности задач, тем самым экономя ресурсы сервера.
Богатые возможности API позволяют подключить к системе любой функционал (работа со статистикой игроков, автоматизация решений о блокировке).
<p align="center">
  <img src="https://user-images.githubusercontent.com/18553678/125630814-d572260e-f64a-419b-8a61-6c30b788c188.gif" alt="Chat Additions в работе"></a>
</p>

## Требования
- Установленый HLDS;
- Установленный [ReGameDLL](https://github.com/s1lentq/ReGameDLL_CS);
- Установленный AMXModX ([`v1.9`](https://www.amxmodx.org/downloads-new.php) или [`v1.10`](https://www.amxmodx.org/downloads-new.php?branch=master));
    - Установленный [ReAPI](https://github.com/s1lentq/reapi) модуль; 

## Установка
- [Скачать крайнюю](https://github.com/ChatAdditions/ChatAdditions_AMXX/releases/latest) стабильную версию в разделе релизов.
- Распаковать `cstrike` папку в корневую папку HLDS сервера;
- Убедиться, что все плагины запущены и в корректном порядке следования с помощью команды `amxx list`.

## Обновление
- Поместите новые плагины и lang-файлы (`plugins/*.amxx` & `data/lang/*.txt`) в `amxmodx/` папку на HLDS сервере;
- Сделайте рестарт сервера (команда `restart` или смените карту);
- Убедиться, что все плагины запущены и в корректном порядке следования с помощью команды `amxx list`.

## Загрузки
- [Стабильные версии](https://github.com/ChatAdditions/ChatAdditions_AMXX/releases)
- [dev-версии](https://github.com/ChatAdditions/ChatAdditions_AMXX/actions/workflows/CI.yml)
      
## Возможности
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

## Поддержка (вклад)
Got **something interesting** you'd like to **share**? Learn about [contributing](CONTRIBUTING.md).

## Контакты
I would like to thank the creators of AMXModX and ReAPI and everyone who helps me in developing and testing this system, who supports my interest.
      
**Thank you guys! 👍**

## Поддержка
Reach out to me at one of the following places:
- Github issues;
- Github discussions;
- [Telegram](https://t.me/ShorokhovSergey);
- [Telegram group](https://t.me/ChatAdditions_group);
- E-Mail;

## Лицензия
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
 Copyright © Sergey Shorokhov
