<div align=center>

  <img  width="160" src="https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/assets/81358657/26415d14-c46e-4bdd-aa26-f7f0234911ce" alt="logo">

<h3>Unofficial Internationalization for Mir Korabli PublicTest</h3>

[![stars](https://img.shields.io/github/stars/LocalizedKorabli/Korabli-LESTA-I18N.svg)](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N/stargazers)
[![release](https://img.shields.io/github/release/LocalizedKorabli/Korabli-LESTA-I18N.svg)](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N/releases/latest)
[![last-commit](https://img.shields.io/github/last-commit/LocalizedKorabli/Korabli-LESTA-I18N.svg)](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N/commit)

</div>

Looking for 简体中文 Localization for PublicTest? Check [Korabli-LESTA-L10N-PublicTest](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N-PublicTest)!

## Download & Installation

### Download

#### Via GitHub

I18n Package: Extract the `global.mo` file from the downloaded archive in the [latest release](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N-PublicTest/releases/latest).

### Installation

I18n Installer WIP, but you can check out [BingBongBrian's Tutorial](https://www.reddit.com/r/MirKorabley/comments/1c3k3z8/how_to_set_game_client_to_english/) for now to manually install the package. **PublicTest Client won't parse things in the res_mods folder, so you should directly overwrite the global.mo in res\texts\ru\LC_MESSAGES**

<details><summary style="font-size: 20px;">Optional</summary>

#### Mods (Modifications)

Mods for i18n are **NOT READY**.

#### Download Mods

Mods for i18n are **NOT READY**.

#### Apply Mods

Mods for i18n are **NOT READY**.

</details>

## Q&A

- Q: Armory and dockyard unlocalized?

  A: Those are website pages displayed by the game's built-in browser and are not able to be localized via MO localization.
  
- Q: After a certain startup, the game shows up in Russian again?

  A: The build number folder in the `bin` directory is replaced with each version update, just reinstall the package.

## Background

As of September 20, 2022, World of Warships CIS Zone players have begun to transfer, with some choosing to merge into Wargaming's European server and others being shunted to the new Russian server (Lesta server) managed by Lesta Games.

As the Lesta server is primarily for Russian and Belarusian players, its World of Warships client retains only the Russian localization files.
Non-Russian-speaking players who wanted to play on the Lesta servers would generally overwrite the Russian language files with localization files extracted from the Wargaming client.
This worked initially, but as versions change, the Lesta server is introducing content that was not present on the Wargaming server.
Its text will obviously not be overwritten by the Wargaming's, and thus will not display properly, affecting the experience.

Thus, this project was born.

## Portal

LocalizedKorabli is making localizations for multiple languages and server types.

You can easily access the corresponding project repositories by clicking on the links in the table below.

| Language\Server Type | Live Server | Public Test Server |
|:--------------------:|:-----------:|:------------------:|
| L10N-简体中文 | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N) | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N-PublicTest) |
| I18N-English | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N) | **This Repository** |
