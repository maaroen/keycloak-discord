# [0.7.0](https://github.com/maaroen/keycloak-discord/compare/v0.6.1...v0.7.0) (2025-03-08)


### Features

* discord role sync ([e98c2e5](https://github.com/maaroen/keycloak-discord/commit/e98c2e52aaf72afe1e8d5751f94dea824c8b85cb))

# 1.0.0 (2025-03-08)


### Bug Fixes

* eliminate the possibility of NullPointerException ([#56](https://github.com/maaroen/keycloak-discord/issues/56)) ([e2b5991](https://github.com/maaroen/keycloak-discord/commit/e2b5991c7ef33ee3ac6483ca00e3e854bb935371))
* ignore discriminator if the value is "0" ([4c68b69](https://github.com/maaroen/keycloak-discord/commit/4c68b69b0bf0d6421589e03e4baf8bbbe5138caa))
* update authorization URL ([#28](https://github.com/maaroen/keycloak-discord/issues/28)) ([a31c116](https://github.com/maaroen/keycloak-discord/commit/a31c116092183318fdbe09fa059a1f63bb0d794c))
* update discord api endpoint urls ([0aa7f14](https://github.com/maaroen/keycloak-discord/commit/0aa7f14edf48a5f9e8a75a68f530cfb1945935e9))
* use DiscordIdentityProvider class in instantiating the Logger ([93003c2](https://github.com/maaroen/keycloak-discord/commit/93003c28bc377577b5d4b218e3d89d984a3f1ae6))


### Features

* implement IdentityProviderFactory#createConfig() which is ([9f359f5](https://github.com/maaroen/keycloak-discord/commit/9f359f5f61848131f1b19994a2c75d6955bb9b27))
* update to keycloak 17.0.0 (based on Quarkus) ([f24ed18](https://github.com/maaroen/keycloak-discord/commit/f24ed1801141da1fbb58d0a58fafdb5aeb0bfa6e))
* update to keycloak 22.0.1 (support new admin console) ([#37](https://github.com/maaroen/keycloak-discord/issues/37)) ([2c8da2d](https://github.com/maaroen/keycloak-discord/commit/2c8da2da4b48ea081644deb7fc11931aba55ba8f))
* update to keycloak 26.0.5 ([05a3df4](https://github.com/maaroen/keycloak-discord/commit/05a3df43f21289762f72e3ac6780fd6b543d8c07))
* updated provider for Keycloak 25.x ([#49](https://github.com/maaroen/keycloak-discord/issues/49)) ([c10480b](https://github.com/maaroen/keycloak-discord/commit/c10480b79864a85817d20d48f949475020322090))
* use "Theme Resources" for the custom template ([7cb885c](https://github.com/maaroen/keycloak-discord/commit/7cb885cea7ae317ae071a2ac72956faa67d4fdf9))

# 0.7.0 (2025-03-08)
### Features
* Updated to keycloak 26.1.3
* Added Discord role syncing support (work done by [NotActuallyTerry](https://github.com/NotActuallyTerry/keycloak-discord))
* Added a fix to also sync roles (delete all) if no roles were returned for the discord guild (Inspired by [pierrearma](https://github.com/NotActuallyTerry/keycloak-discord/pull/2))

## [0.6.1](https://github.com/wadahiro/keycloak-discord/compare/v0.6.0...v0.6.1) (2024-11-02)


### Bug Fixes

* eliminate the possibility of NullPointerException ([#56](https://github.com/wadahiro/keycloak-discord/issues/56)) ([e2b5991](https://github.com/wadahiro/keycloak-discord/commit/e2b5991c7ef33ee3ac6483ca00e3e854bb935371))

# [0.6.0](https://github.com/wadahiro/keycloak-discord/compare/v0.5.0...v0.6.0) (2024-11-02)


### Bug Fixes

* ignore discriminator if the value is "0" ([4c68b69](https://github.com/wadahiro/keycloak-discord/commit/4c68b69b0bf0d6421589e03e4baf8bbbe5138caa))


### Features

* update to keycloak 26.0.5 ([05a3df4](https://github.com/wadahiro/keycloak-discord/commit/05a3df43f21289762f72e3ac6780fd6b543d8c07))
* updated provider for Keycloak 25.x ([#49](https://github.com/wadahiro/keycloak-discord/issues/49)) ([c10480b](https://github.com/wadahiro/keycloak-discord/commit/c10480b79864a85817d20d48f949475020322090))
