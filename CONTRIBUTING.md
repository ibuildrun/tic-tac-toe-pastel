# Contributing

Thank you for your interest in contributing to this project.

## Getting Started

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/tic-tac-toe-pastel.git
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Install dependencies**:
   ```bash
   npm install
   ```
5. **Start the dev server**:
   ```bash
   npm run dev
   ```

## Commit Guidelines

This project uses [Conventional Commits](https://www.conventionalcommits.org/):

| Type | Description |
|------|-------------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | Documentation changes |
| `style` | Code formatting (no logic changes) |
| `refactor` | Code refactoring |
| `perf` | Performance improvements |
| `test` | Adding or updating tests |
| `chore` | Maintenance tasks |
| `ci` | CI/CD changes |
| `deps` | Dependency updates |

### Commit Message Format

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

### Examples

```bash
feat(game): add zen mode infinite gameplay
fix(audio): resolve sound not playing on iOS
docs: update README with deployment instructions
ci: add GitHub Pages deployment workflow
deps: update react to v19.2.3
```

### Scope (optional)

- `game` - game logic
- `ui` - user interface
- `audio` - sound system
- `api` - backend API
- `telegram` - Telegram integration
- `docker` - containerization

## Code Style

- **TypeScript** - strict typing, avoid `any`
- **React** - functional components with hooks
- **Tailwind CSS** - utility-first, inline classes
- **Imports** - use `@/*` alias

## Testing

```bash
# Backend tests
cd server
npm test
```

## Pull Request Process

1. Ensure code passes type check: `npx tsc --noEmit`
2. Update documentation if needed
3. Fill out the PR template
4. Wait for review

## Release Process

Releases are automated via GitHub Actions:

1. Version bump: Use the "Version Bump" workflow or manually update `package.json`
2. Create a tag: `git tag v1.2.3 && git push origin v1.2.3`
3. The release workflow will automatically:
   - Build the project
   - Run tests
   - Create a GitHub Release with changelog
   - Deploy to GitHub Pages

## Ideas for Contribution

- Localization to other languages
- New themes and wallpapers
- New achievements
- Test coverage
- Mobile UX improvements

## Questions?

Create an [Issue](https://github.com/ibuildrun/tic-tac-toe-pastel/issues) or reach out on Telegram.
