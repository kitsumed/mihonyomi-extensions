# Mihonyomi Extensions
Mihonyomi-extensions is a repo containing extension for **self-hosted servers**. It support the free and open source manga reader [Tachiyomi](https://github.com/tachiyomiorg/extensions) and any of it's fork who __kept support__ like [Mihon](https://github.com/mihonapp/mihon).

This repository contains the compiled extensions (`.apk`) under the `releases` branch. Current release code is available on the `main` branch and unreleased (not yet compiled) code is available on others branch.
> [!IMPORTANT]
> The developer of Tachiyomi have [ended it's development](https://tachiyomi.org/news/2024-01-13-goodbye) due to legal circonstances, forks like [Mihon](https://github.com/mihonapp/mihon) or [TachiyomiSY](https://github.com/jobobby04/TachiyomiSY) should still works as long as their code support tachiyomi extensions.

## What self-hosted servers do we support?
> [!NOTE]
> Altrought this repo description claims to support multiples extensions, it was made for my own use with Komga. I probably won't be maintaining or adding by myself new extensions for self-hosting, however, I am open to pull requests to some extents. If you want a extension for Kivita, go check their [official extension](https://github.com/Kareadita/tachiyomi-extensions).
* [Komga](https://github.com/kitsumed/mihonyomi-extensions/blob/main/src/all/komga/README.md)

## Downloads
[![CI build push](https://github.com/kitsumed/mihonyomi-extensions/actions/workflows/build_push.yml/badge.svg?event=push)](https://github.com/kitsumed/mihonyomi-extensions/actions/workflows/build_push.yml)
> [!CAUTION]
> Make sure you always know what you are installing and running. Do not install or run anything that looks suspicious. There has been a rise of closed-source extensions and fake tachiyomi compatible readers since tachiyomi announced ending developement. This project is open source, feel free to compile the extensions yourself.
#### Option 1
You can add the Mihonyomi list manually by pasting `https://raw.githubusercontent.com/kitsumed/mihonyomi-extensions/releases/index.min.json` in the corresponding section of your application.

#### Option 2
You can install the apks files manually from the releases branch.

# Requests

To request a new extension, feature or bug fix, [create an issue](NULL_LINK/issues/new/choose).

Note that requesting something does not imply that something will be added or fixed. Furthermore, some extensions may be impossible to do or prohibitively difficult to maintain due to bad or missing API documentation.

I won't do / accepts extensions if they aren't self-hosted by the user and require scrapping instead of the use of a API. I might always refuse even if these criteria are met.

> [!TIP]
> If you would like to see a request fulfilled and have the necessary skills to do so, consider contributing!

## License

    Copyright 2024 kitsumed
    Copyright 2015-2024 Javier Tomás

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

## Disclaimer
> [!NOTE]
> The developer of this application does not have any affiliation with the content providers available. These extensions are designed to work with user-hosted servers. The user is solely responsible for what is hosted on said server.
