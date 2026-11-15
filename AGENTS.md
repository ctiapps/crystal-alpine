# CLAUDE.md

Static Crystal-lang compiler image for Alpine (musl), cross-compiled from a Debian build stage. Fork / derived from ysbaddaden's crystal:alpine approach; remote `ctiapps/crystal-alpine`.

- Base build: `crystallang/crystal:${CRYSTAL_VERSION}`; runtime: `alpine:latest`.
- ARGs: `CRYSTAL_VERSION` (0.31.1), `SHARDS_VERSION` (0.8.1).
- Helper script: `crystal.sh`.
- Last commit: 2019-02-17.
