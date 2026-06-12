# pinq-doq

Deveng Group shared Claude rules and project standards.

## Usage

Clone this repo alongside your project repos. In each project's `CLAUDE.md`, import the relevant files:

```markdown
@../pinq-doq/common.md
@../pinq-doq/android-kotlin.md

# Project-specific rules
...
```

For C# backend projects:
```markdown
@../pinq-doq/common.md
@../pinq-doq/csharp-dotnet.md
```

## Files

| File | Scope |
|---|---|
| `common.md` | All projects, all languages |
| `android-kotlin.md` | Android, KMP, Compose projects |
| `csharp-dotnet.md` | C# / .NET backend projects |
| `tasks/prepare-release.md` | Release preparation workflow |

## Contributing

Changes to these standards affect all projects. Open a PR and get team review before merging.
