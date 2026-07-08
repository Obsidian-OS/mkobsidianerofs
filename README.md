# mkobsidianerofs
`mkobsidianerofs` is an alternative to `mkobsidiansfs`, mainly used with Project Pillar (i.e. ObsidianOS Atomic).

## Configuration
Configuration is pretty much exactly the same as `mkobsidiansfs`, except that it adds `PILLAR_MIRROR` which is the signature URL for Pillar, located in `/etc/is-pillar`, is used for the Arch mirrors, and is used with `obsidianctl`'s Netupdate feature.

## License
Basically the same license as `mkobsidiansfs`, the [MIT License](LICENSE)
