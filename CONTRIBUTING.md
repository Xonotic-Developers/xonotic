# Contributing to Xonotic

🎮 **Welcome to the Xonotic development community!** We're excited that you want to contribute to making the best open-source arena shooter even better.

## 🚀 Quick Start

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create** a feature branch
4. **Make** your changes
5. **Test** thoroughly
6. **Submit** a pull request

## 🎯 Ways to Contribute

### 🐛 Bug Reports
Found a bug? Help us squash it!

**Before submitting:**
- Check existing [issues](https://github.com/Xonotic-Developers/xonotic/issues)
- Test on latest version
- Gather system information

**Include in your report:**
- **System specs** (OS, GPU, CPU)
- **Xonotic version**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots/videos** if applicable
- **Console output** if relevant

### 💡 Feature Suggestions
Have an idea for improving Xonotic?

**Use this template:**
```
**Problem:** What issue does this solve?
**Solution:** Brief description of your idea
**Alternatives:** Other solutions considered
**Additional context:** Screenshots, mockups, examples
```

### 🎨 Map Creation
Create new battlegrounds for players!

**Requirements:**
- Use NetRadiant editor
- Follow [mapping guidelines](docs/mapping-guide.md)
- Include proper lighting and optimization
- Test thoroughly with bots and players

**Submission process:**
1. Create map in `.map` format
2. Compile to `.bsp`
3. Test extensively
4. Submit via pull request with screenshots

### 🔧 Code Contributions

#### Development Setup
```bash
git clone https://github.com/Xonotic-Developers/xonotic.git
cd xonotic
./all update -l best
./all compile
```

#### Code Standards
- **Language**: QuakeC for game logic, C for engine
- **Style**: Follow existing code conventions
- **Comments**: Document complex logic
- **Testing**: Test your changes thoroughly

#### Pull Request Guidelines
- **Branch naming**: `feature/description` or `fix/issue-number`
- **Commit messages**: Clear, descriptive (50 chars max for title)
- **Size**: Keep PRs focused and manageable
- **Tests**: Include tests when applicable

### 🎵 Audio Contributions
Help improve Xonotic's audio experience!

**Formats accepted:**
- **Music**: OGG Vorbis format
- **Sound Effects**: WAV or OGG
- **Quality**: High quality, game-appropriate

**Guidelines:**
- Original compositions only
- Compatible with GPL-3.0 license
- Fit the futuristic arena theme

### 📝 Documentation
Improve documentation for players and developers!

**Areas needing help:**
- Player guides and tutorials
- Developer documentation
- Translation into other languages
- Wiki maintenance

### 🌐 Translations
Make Xonotic accessible worldwide!

**Process:**
1. Check [current translations](https://github.com/Xonotic-Developers/xonotic/tree/master/data/xonotic-data.pk3dir/common)
2. Update existing or create new language files
3. Follow [localization guide](docs/localization.md)
4. Test in-game

## 🛠️ Development Guidelines

### Testing
- **Compile** without warnings
- **Test** on multiple platforms when possible
- **Check** for regressions
- **Verify** multiplayer compatibility

### Performance
- **Profile** performance-critical code
- **Optimize** for various hardware configs
- **Maintain** stable frame rates
- **Consider** network performance

### Compatibility
- **Backward compatibility** with existing content
- **Cross-platform** functionality
- **Network protocol** stability
- **Demo playback** compatibility

## 📋 Code Review Process

### For Contributors
1. **Self-review** your code
2. **Document** changes clearly
3. **Respond** to feedback promptly
4. **Update** based on reviews

### Review Criteria
- **Functionality**: Does it work as intended?
- **Performance**: Any negative impact?
- **Style**: Follows project conventions?
- **Testing**: Adequately tested?
- **Documentation**: Properly documented?

## 🏆 Recognition

### Hall of Fame
Outstanding contributors are recognized in:
- Game credits
- Website contributor page
- Special in-game achievements
- Community Discord roles

### Contribution Types
- **Core Developers**: Regular code contributors
- **Map Makers**: Level designers
- **Artists**: Visual and audio creators
- **Translators**: Localization team
- **Community Managers**: Forum/Discord moderators

## 🔗 Communication Channels

### Primary
- **GitHub Issues**: Bug reports and features
- **GitHub Discussions**: General development talk
- **Pull Requests**: Code review and collaboration

### Community
- **Discord**: [Xonotic Community](https://discord.gg/xonotic)
- **Forums**: [Official Forums](https://forums.xonotic.org)
- **IRC**: #xonotic on irc.quakenet.org

### Developer-Specific
- **Mailing List**: dev@xonotic.org
- **Matrix**: #xonotic-dev:matrix.org

## 📚 Resources

### Documentation
- [Official Wiki](https://gitlab.com/xonotic/xonotic/-/wikis/home)
- [Mapping Guide](docs/mapping-guide.md)
- [Scripting Reference](docs/scripting.md)
- [Engine Documentation](docs/engine.md)

### Tools
- **NetRadiant**: Level editor
- **Blender**: 3D modeling
- **GIMP**: Texture editing
- **Audacity**: Audio editing

## ⚖️ Legal

### License
All contributions must be compatible with **GPL-3.0**.

### Copyright
By contributing, you agree that your contributions will be licensed under GPL-3.0.

### Attribution
Contributors are credited in game files and documentation.

## 🎉 Getting Started

Ready to contribute? Here are some good first issues:
- [Good First Issue](https://github.com/Xonotic-Developers/xonotic/labels/good%20first%20issue)
- [Help Wanted](https://github.com/Xonotic-Developers/xonotic/labels/help%20wanted)
- [Documentation](https://github.com/Xonotic-Developers/xonotic/labels/documentation)

Questions? Join our [Discord](https://discord.gg/xonotic) and ask in #development!

---

**Thank you for helping make Xonotic even more awesome!** 🚀 