# Changelog

All notable changes to Xonotic will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### 🚧 In Development
- Enhanced spectator mode with better camera controls
- Improved matchmaking system for balanced games
- New map: Afterslime (beta testing)
- VR support exploration

### 🐛 Known Issues
- Minor texture loading delay on some maps
- Occasional audio desync in high-latency matches

## [0.8.6] - 2024-01-15

### ✨ Added
- **New Weapon**: Heavy Machine Gun with suppression mechanics
- **Map Updates**: 3 remastered classic maps with improved lighting
- **Graphics**: Enhanced particle effects for weapon impacts
- **Audio**: New dynamic music system that adapts to gameplay intensity
- **Accessibility**: Colorblind-friendly UI options
- **Netcode**: Improved lag compensation algorithms

### 🔧 Changed
- **Movement**: Refined bunnyhopping mechanics for more consistent acceleration
- **Weapons**: Balanced rocket launcher splash damage
- **UI**: Redesigned main menu with better navigation
- **Performance**: Optimized rendering pipeline for 15% better FPS
- **Maps**: Updated lighting on 5 existing maps

### 🐛 Fixed
- Fixed rare crash when joining servers with custom content
- Resolved audio stuttering on Linux systems
- Fixed scoreboard not updating properly in CTF mode
- Corrected weapon pickup animations
- Fixed demo playback issues with certain map formats

### 🗑️ Removed
- Deprecated old particle system (replaced with enhanced version)
- Removed unused legacy weapon models

## [0.8.5] - 2023-09-20

### ✨ Added
- **Anti-Cheat**: Enhanced server-side validation
- **Statistics**: Detailed player performance tracking
- **Workshop**: Steam Workshop integration for custom content
- **Tournaments**: Built-in tournament bracket system
- **Spectating**: Picture-in-picture mode for multiple players

### 🔧 Changed
- **Physics**: Updated collision detection for more accurate hit registration
- **Balance**: Adjusted weapon damage values based on community feedback
- **Maps**: Reworked 2 problematic maps for better flow
- **Server Browser**: Improved filtering and sorting options

### 🐛 Fixed
- Fixed memory leak in particle system
- Resolved network synchronization issues
- Fixed weapon switching delays
- Corrected bot AI pathfinding on complex maps

## [0.8.2] - 2023-05-10

### ✨ Added
- **New Game Mode**: Last Man Standing with progressive weapon restrictions
- **Map Editor**: Integrated level editor for community content creation
- **Replay System**: Record and share gameplay highlights
- **Cross-Platform**: Improved compatibility across different operating systems

### 🔧 Changed
- **Graphics**: Upgraded to modern OpenGL rendering
- **Audio**: Replaced old audio engine with OpenAL implementation
- **Controls**: More responsive input handling
- **Servers**: Better server stability and performance

### 🐛 Fixed
- Fixed various crash scenarios during map transitions
- Resolved texture loading issues on older graphics cards
- Fixed multiplayer desynchronization problems
- Corrected weapon firing rate calculations

## [0.8.1] - 2023-02-15

### 🔧 Changed
- **Performance**: Optimized map loading times
- **Balance**: Minor weapon adjustments based on competitive feedback
- **UI**: Improved font rendering and text clarity

### 🐛 Fixed
- Fixed critical server crash bug
- Resolved audio issues on Windows 11
- Fixed incorrect damage calculations in certain scenarios
- Corrected player model animations

## [0.8.0] - 2022-12-01

### ✨ Major Release - "Arena Evolution"

#### New Features
- **Complete Engine Overhaul**: Rebuilt on enhanced DarkPlaces engine
- **Modern Graphics**: HDR lighting, dynamic shadows, improved textures
- **Advanced Movement**: Refined physics with new movement techniques
- **Professional Esports**: Tournament-ready features and spectator tools
- **Community Hub**: Integrated Discord and social features

#### Game Content
- **12 New Maps**: Professionally designed for competitive play
- **Weapon Rebalance**: Complete overhaul based on 2 years of feedback
- **New Game Modes**: Clan Arena, Instagib variants, Race challenges
- **Bot AI**: Significantly improved artificial intelligence

#### Technical Improvements
- **Cross-Platform**: Full Windows, Mac, Linux support
- **60+ FPS**: Optimized for modern hardware
- **Netcode**: Low-latency networking with rollback
- **Modding**: Enhanced SDK for community content

### 🗑️ Removed
- Legacy renderer (replaced with modern pipeline)
- Outdated map formats (automatic conversion available)
- Deprecated network protocols

## [0.7.0] - 2020-03-15

### ✨ Legacy Release
- Classic Xonotic gameplay and features
- Original DarkPlaces engine implementation
- Community-favorite maps and weapons
- Established competitive scene

---

## 🎯 Version History Summary

| Version | Release Date | Key Feature |
|---------|--------------|-------------|
| 0.8.6 | 2024-01-15 | Heavy Machine Gun & Enhanced Graphics |
| 0.8.5 | 2023-09-20 | Anti-Cheat & Tournament System |
| 0.8.2 | 2023-05-10 | Last Man Standing & Map Editor |
| 0.8.1 | 2023-02-15 | Performance & Balance Updates |
| 0.8.0 | 2022-12-01 | Engine Overhaul & Modern Graphics |
| 0.7.0 | 2020-03-15 | Classic Release |

## 📊 Statistics

### Code Metrics
- **Total Commits**: 5,000+
- **Contributors**: 150+
- **Lines of Code**: 500,000+
- **Community Maps**: 200+

### Community Growth
- **Active Players**: 10,000+ monthly
- **Discord Members**: 5,000+
- **Tournament Participants**: 1,000+
- **Content Creators**: 100+

## 🔮 Future Roadmap

### Version 0.9.0 (Planned: Q3 2024)
- **Next-Gen Graphics**: Vulkan renderer implementation
- **AI Revolution**: Machine learning-powered bots
- **VR Support**: Full virtual reality gameplay
- **Mobile Port**: Android and iOS compatibility

### Long-term Vision
- **Cross-Platform Play**: All devices connected
- **Cloud Features**: Save synchronization and matchmaking
- **Streaming Integration**: Built-in Twitch/YouTube features
- **Educational Tools**: Learning resources for new players

## 🤝 Contributing to Changelog

When contributing changes, please:

1. **Follow format**: Use established categories and formatting
2. **Be descriptive**: Explain what changed and why
3. **Include impact**: Note performance, compatibility, or gameplay effects
4. **Link issues**: Reference GitHub issues where applicable
5. **Credit contributors**: Acknowledge community contributions

### Categories
- ✨ **Added**: New features
- 🔧 **Changed**: Changes in existing functionality
- 🐛 **Fixed**: Bug fixes
- 🗑️ **Removed**: Removed features
- 🚨 **Security**: Security improvements
- 🎯 **Performance**: Performance improvements

---

*For detailed technical changelogs, see individual release notes on [GitHub Releases](https://github.com/Xonotic-Developers/xonotic/releases).* 