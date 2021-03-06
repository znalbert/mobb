# MOBB - My Opinionated Basic Boilerplate
This is an opinionated boilerplate for newbs looking to get into the world of HTML, CSS, and JavaScript development.

## Editor - VS Code
When I look at all the trade-offs for an editor, I do not know of another free editor that is as well-supported, full-featured, and active in plugin development. If you're some Vim wizard or Emacs god, fine. Otherwise, use VS Code to get up and running as quickly and painlessly as possible.

### Plugins
There are a bunch that I'd recommend, but depending on the project you'll want to enable/disable some via your Workspace Settings.

#### Favorites
- Beautify
- Document This
- EditorConfig for VS Code
- TSLint
- vscode-icons
- Path Intellisense

#### Others Worth Maybe Getting
- Auto Rename Tag
- Bracket Pair Colorizer
- Code Runner
- Color Highlight
- Color Picker
- CSS Peek
- Debugger for Chrome
- Git Blame
- Git History (git log)
- IntelliSense for CSS class names
- npm
- npm Intellisense
- Sass

### Configuration: User Settings
My user settings:
```
{
    "workbench.iconTheme": "vscode-icons",
    "editor.tabSize": 2,
    "editor.renderWhitespace": "boundary",
    "editor.rulers": [
        80
    ],
    "editor.minimap.enabled": true,
    "terminal.integrated.shellArgs.osx": [
        "-l"
    ],
    "[markdown]": {
        "editor.wordWrap": "wordWrapColumn",
        "editor.wordWrapColumn": 80,
        "editor.quickSuggestions": false,
        "editor.wrappingIndent": "same"
    },
    "eslint.enable": false,
    "tslint.enable": false, // Set this to true in the workspace settings
    "editor.wrappingIndent": "indent",
    "editor.renderIndentGuides": true,
    "workbench.editor.tabCloseButton": "left",
    "workbench.quickOpen.closeOnFocusLost": false,
    "files.trimTrailingWhitespace": true,
    "files.insertFinalNewline": true,
    "window.zoomLevel": 0,
    "editor.fontSize": 12,
    "emmet.syntaxProfiles": {
        "javascript": "jsx"
    }
}
```

### Configuration: Workspace Settings

## Package Manager - npm
npm might not be perfect, but I see it as the simplest way to get going.

### Node Security Platform - nsp
Scan your `node_modules/` for potential security issues. This should be incorporated into the `npm start` script in order to catch potential security issues early.

## Bundling, Minification, Sourcemaps, Transpiling - webpack and TypeScript

## Development Webserver - webpack-dev-server

## Linting - TSLint

## To Do's
- [ ] Editor & Configuration
  - [x] Editor
  - [x] Plugins
  - [x] User Settings
  - [ ] Workspace Settings
- [x] Package Management
- [x] Bundling
- [x] Minification
- [ ] Sourcemaps
- [x] Transpiling
- [ ] Dynamic HTML Generation
- [ ] Centralized HTTP
- [ ] Mock API framework
- [ ] Component Libraries
- [x] Development Webserver
- [x] Linting
- [ ] Automated Testing
- [ ] Continuous Integration
- [ ] Automated Build
- [ ] Automated Deployment
- [ ] Working Example App
