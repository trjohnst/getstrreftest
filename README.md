Demoing a potential issue with `GetStringByStrRef` always returning empty in build 8193.9

Issue also present in 8193.7

Issue not present in 8193.5, 8193.6

Uses [nasher](https://github.com/squattingmonk/nasher.nim) to build/unpack module.

Uses [docker-compose](https://docs.docker.com/compose/install/) to run beamdogs nwserver with the built module.
