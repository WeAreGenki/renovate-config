<!-- markdownlint-disable first-line-h1 -->

[![NPM version](https://img.shields.io/npm/v/@wearegenki/renovate-config.svg)](https://www.npmjs.com/package/@wearegenki/renovate-config)
[![Licence](https://img.shields.io/npm/l/@wearegenki/renovate-config.svg)](https://github.com/WeAreGenki/renovate-config/blob/master/LICENCE)

# We Are Genki Renovate Bot Preset

Sharable preset for the renovate bot 🤖. This makes it easier to change the config in one place rather than needing to update multiple projects.

Docs:

- Renovate config options: <https://renovatebot.com/docs/configuration-options/>
- Renovate sharable presets: <https://renovatebot.com/docs/config-presets/>

## Usage

Install in your project:

```sh
yarn add -D @wearegenki/renovate-config
```

Add to your renovate config file (e.g. `.renovaterc.json`):

```json
{
  "extends": [
    "@wearegenki",
  ],
}
```

## Licence

The contents of this repo are MIT licensed open source. See [LICENCE](https://github.com/WeAreGenki/renovate-config/blob/master/LICENCE).

-----

© 2018 [We Are Genki](https://wearegenki.com)
