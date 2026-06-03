# Warm Darkness

A deep night-dark VS Code theme built for long coding sessions. The background sits at near-black `#0c141c` — easy on the eyes in low light — while a warm gold accent `#f1bb39` guides your attention through the UI. Every language gets its own colour story; nothing blends into nothing.

---

## Colour Palette

### UI

| Role | Hex | Used for |
|---|---|---|
| Base background | `#0c141c` | Editor, terminal |
| Panel background | `#0e1822` | Sidebar, panels |
| Tab bar | `#111d28` | Activity bar, tab headers |
| Selection | `#1c2a38` | Selected text, list items |
| Accent (gold) | `#f1bb39` | Active tab border, cursor, badges, links |
| Plain text | `#8fa9ba` | Default editor and terminal text |
| Bright text | `#c8d3e0` | Active tab, selected items |
| Borders | `#1a2535` | Subtle separators throughout |

### Syntax

| Token | Colour | Example |
|---|---|---|
| Keywords / storage | `#c792ea` purple italic | `if` `const` `async` `class` |
| Functions / methods | `#82cfff` cyan | `doSomething()` |
| Types / classes | `#82aaff` blue | `MyClass` `interface` `Promise` |
| Strings | `#98c379` green | `"hello world"` |
| Numbers | `#f78c6c` orange | `42` `3.14` |
| Constants | `#f78c6c` orange | `MAX_SIZE` `true` `null` |
| Parameters | `#f78c6c` orange italic | `(param, index)` |
| Operators | `#89ddff` light cyan | `+` `===` `=>` `??` |
| Decorators | `#f1bb39` gold | `@Injectable()` |
| Comments | `#3d5166` gray italic | `// explanation` |
| `this` / `self` | `#f07178` coral italic | `this.value` |
| Regex | `#e06c75` red | `/pattern/gi` |

---

## Language Support

### HTML
- Tag names in warm **coral-pink** — distinct from plain text
- Attribute names in **gold**
- Attribute values treated as strings (**green**)
- `< >` brackets in a subtler teal so they recede behind the tag name

### CSS / SCSS / Less
- Element selectors: coral-pink
- Class and ID selectors: gold
- Property names: blue
- Property values: green
- Units (`px`, `em`, `rem`): orange
- At-rules (`@media`, `@keyframes`): purple
- `!important`: red bold
- SCSS variables: light text

### JavaScript / TypeScript
- Full **semantic highlighting** via the TS language server
- Arrow functions: cyan
- JSX/TSX native tags (`div`, `span`): coral-pink bold
- JSX/TSX component names (`MyComponent`): blue
- JSX attribute names: gold
- Type annotations and generics: blue
- Decorators: gold

### PHP
| Token | Colour |
|---|---|
| `<?php` `<?=` `?>` | `#f78c6c` orange bold |
| Control flow (`if`, `foreach`, `while`, `return`…) | `#c792ea` purple italic |
| Output constructs (`echo`, `print`) | `#82cfff` cyan |
| Built-in functions | `#82cfff` cyan |
| `$variables` | `#c8d3e0` light |
| `$` sign | `#c792ea` purple |
| Class / interface / trait names | `#82aaff` blue |
| Namespaces | `#82aaff` blue |
| Constants | `#f78c6c` orange |

### SQL
| Token | Colour |
|---|---|
| DML (`SELECT`, `FROM`, `WHERE`, `JOIN`…) | `#c792ea` purple bold |
| DDL (`CREATE`, `ALTER`, `DROP`) | `#e5c07b` amber bold |
| Constraints (`AUTO_INCREMENT`, `NOT NULL`, `PRIMARY KEY`) | `#f1bb39` gold |
| Data types (`INT`, `VARCHAR`, `TEXT`) | `#82aaff` blue |
| Table names | `#82cfff` cyan |
| Functions (`COUNT`, `COALESCE`…) | `#82cfff` cyan |

### Markdown
- Headings: gold bold
- Bold: bright white bold
- Italic: bright white italic
- Inline code and code blocks: green
- Links: gold underlined
- Blockquotes: dimmed gray italic
- Strikethrough: dimmed with strikethrough style

### Other
Full bracket pair colorisation across 6 levels. Inlay hints, ghost text, and sticky scroll all follow the same colour system. The terminal uses a full 16-colour ANSI palette tuned to match the theme.

---

## Installation

### From the VS Code Marketplace
1. Open VS Code
2. Press `Ctrl+Shift+X` to open Extensions
3. Search **Warm Darkness**
4. Click **Install**

### From a VSIX file
1. Download the latest `.vsix` from the [Releases](https://github.com/edizorici/warm-darkness-vscode/releases) page
2. Press `Ctrl+Shift+P` → **Extensions: Install from VSIX…**
3. Select the downloaded file

### Activate the theme
Press `Ctrl+K Ctrl+T` and select **Warm Darkness**.

---

## Reporting Issues

If a language construct, UI element, or extension doesn't look right:

1. Open the file where the colour is wrong
2. Press `Ctrl+Shift+P` → **Developer: Inspect Editor Tokens and Scopes**
3. Click the token that looks off and copy the **textmate scopes** output
4. Open an [issue](https://github.com/edizorici/warm-darkness-vscode/issues) with the scope info and a brief description

---

## Contributing

Pull requests are welcome. For significant changes please open an issue first to discuss what you'd like to change.

---

## License

MIT © [Eduard Zorici](https://github.com/edizorici)
