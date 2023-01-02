# rman-schema

This is a [FlatBuffer][flatbuffers] schema for the [.manifest][manifest] format made by
[RiotGames][riot-games].

## Status

Currently, the code, generated by the schema, is able to parse the data of `.manifest` files
successfully, however, some variables and their types are still unknown. Those variables are
named `unkX` and have all of the possible types listed in the inline comments.

## Building

To build the provided schema you will need `flatc`. You can build `flatc` yourself (see
[building][flatbuffers-guide-building]), or use one of the prebuilt binaries (see
[releases][flatbuffers-releases]).

Once you have `flatc` installed, you can build it for the language of you choice (see
[using the compiler][flatbuffers-guide-using-schema-compiler]).

## Contributing

If you find a bug with the schema, or you find the usage for the remaining unknown variables,
please open up an issue or make a PR.

## Acknowledgements

- @moonshadow565 for the amazing work over at
[rman - set of CLI tools for rito manifest and bundle files][moonshadow565-rman]. Most of the
schema is based upon his work.
- @Morilli for creating [ManifestDownloader][morilli-manifest-downloader], which was my first
exposure to the inner workings of `.manifest` format, and for answering my question on discord.

## Legal

Riot Games, VALORANT, and any associated logos are trademarks, service marks, and/or registered
trademarks of Riot Games, Inc.

This project is in no way affiliated with, authorized, maintained, sponsored or endorsed by Riot
Games, Inc or any of its affiliates or subsidiaries.

I, the project owner and creator, am not responsible for any legalities that may arise in the use
of this project. Use at your own risk.


[flatbuffers]: https://github.com/google/flatbuffers
[flatbuffers-guide-building]: https://google.github.io/flatbuffers/flatbuffers_guide_building.html
[flatbuffers-guide-using-schema-compiler]: https://google.github.io/flatbuffers/flatbuffers_guide_using_schema_compiler.html
[flatbuffers-releases]: https://github.com/google/flatbuffers/releases
[manifest]: https://technology.riotgames.com/news/supercharging-data-delivery-new-league-patcher
[moonshadow565-rman]: https://github.com/moonshadow565/rman
[morilli-manifest-downloader]: https://github.com/Morilli/ManifestDownloader
[riot-games]: https://www.riotgames.com
