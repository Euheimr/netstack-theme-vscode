# Netstack Theme (VSCode)

## About

[Netstack Theme VSCode extension](vscode:extension/euheimr.netstack) by [Euheimr](https://github.com/euheimr) is a full editor and syntax highlighting theme based on the video game [Cyberpunk 2077](https://www.cyberpunk.net/us/en/cyberpunk-2077) by [CD Projekt Red](https://www.cdprojektred.com). I'm a massive fan.

Colors for this theme were sampled from in-game screenshots.

If you prefer to preview the theme before installing, see: 
https://vscode.dev/editor/theme/euheimr.netstack/netstack

### Install

[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=euheimr.netstack) or the [VSCode direct link](vscode:extension/euheimr.netstack)

VSCode direct link will launch Visual Studio Code, if not opened already.

## Screenshots by Language

**!TODO**: Add screenshots of the following languages:

- [ ] .sh
- [ ] .bat
- [ ] C
- [ ] C++
- [ ] Go
- [ ] HTML
- [ ] Java
- [ ] JavaScript
- [ ] JSON
- [ ] Markdown
- [ ] Rust
- [ ] TypeScript


## Development

- [Edit Theme](https://themes.vscode.one/theme/euheimr/7JmMw8T6)
- [Manage extensions](https://marketplace.visualstudio.com/manage)

1. Download the updated theme JSON
2. copy the contents of the new theme and paste into `themes/netstack-color-theme.json`
3. Increment `version` in `package.json`
4. `vsce package` to create a new `VSIX` extension package
5. `vsce publish` to https://marketplace.visualstudio.com/items?itemName=euheimr.netstack via Azure DevOps


## Reference

- [Publishing VSCode Themes](https://themes.vscode.one/faq/publishing-theme/)
- [VSCode extension manifest](https://code.visualstudio.com/api/references/extension-manifest)
