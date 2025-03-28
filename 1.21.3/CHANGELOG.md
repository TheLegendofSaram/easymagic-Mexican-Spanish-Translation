# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v21.3.2-1.21.3] - 2024-12-28
### Fixed
- Fix `keepEnchantmentScreenBook` client config option breaking re-rolling

## [v21.3.1-1.21.3] - 2024-12-26
### Added
- Add support for [Enchantment Descriptions](https://modrinth.com/mod/enchantment-descriptions) mod
### Changed
- Overhaul enchanting screen internally to use proper widgets instead of checking screen areas manually
- Improve internal dedicated reroll item slot handling
- Improve quick move behavior inside the enchanting menu to be more convenient similar to furnaces
- Revert previous enchantment clue change, they are once again synced from the server

## [v21.3.0-1.21.3] - 2024-12-24
- Port to Minecraft 1.21.3
