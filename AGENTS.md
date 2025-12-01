# AGENTS.md

## Commands
- **Build**: `vici build`
- **Dev**: `vici develop`
- **Lint**: `vici lint`
- **Format**: `biome format --write src`
- **No test commands available**

## Code Style
- **Language**: TypeScript with strict mode enabled
- **JSX**: Use `react-jsx` transform
- **Imports**: Group imports from same library, use named imports
- **Types**: Define interfaces/types after component declarations
- **Components**: Use arrow function syntax for component definitions
- **Naming**: camelCase for variables/functions, PascalCase for components/types
- **Error Handling**: Use `showToast` for user feedback and errors
- **Formatting**: Use Biome for consistent formatting