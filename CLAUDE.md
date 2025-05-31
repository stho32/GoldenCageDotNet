# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

GoldenCageDotNet is a standardized .NET project template (Golden Cage) designed for AI-assisted development. It provides a structured foundation with comprehensive documentation, standardized prompts, and clear separation of concerns.

## Project Structure

```
/
├── Dokumentation/          # Comprehensive project documentation
│   ├── Anforderungen/      # Application requirements (R00001-*.md format)
│   ├── Architektur/        # Architecture docs (CodeStyle, Programming Patterns)
│   ├── Commands/           # Standard AI prompts for reviews
│   └── Technologien/       # Technology stack documentation
├── Scripts/                # Automation scripts for development/deployment
├── Source/
│   ├── Code/               # Main application code
│   └── DBMigrations/       # Database migration scripts
├── Tests/
│   ├── Datenbank/          # Database tests
│   └── UI/                 # User interface tests
├── Initialize-AI.md        # Quick AI initialization commands
└── README.md              # Project overview and structure
```

## AI-Optimized Development

This template is specifically designed for AI collaboration:

### Quick AI Initialization
Use `Initialize-AI.md` for rapid context loading:
```bash
cat Initialize-AI.md  # Contains all necessary read commands
```

### Standard Prompts Available
- `Dokumentation/Commands/Security-Review.md` - Security analysis
- `Dokumentation/Commands/Code-Quality.md` - Code quality review  
- `Dokumentation/Commands/Architektur-Pruefung.md` - Architecture review
- `Dokumentation/Commands/Rechtschreibpruefung.md` - German spell checking

### Documentation Standards
- Requirements: `R{00001}-{description}.md` format in Anforderungen/
- Architecture: CodeStyle.md and ProgrammierPatterns.md templates
- Technology: Individual .md files for each library/framework

## Development Workflow

1. **Start with Documentation**: Always read requirements and architecture docs first
2. **Use Standard Prompts**: Leverage pre-built prompts for consistent reviews
3. **Follow Golden Cage Structure**: Maintain clear separation between documentation, code, tests, and scripts
4. **AI-First Approach**: Use Initialize-AI.md to quickly orient AI assistants

## Key Principles

- **Documentation-Centric**: All decisions and requirements are documented
- **AI-Friendly**: Structure optimized for AI understanding and assistance
- **Standardized**: Consistent formats and naming conventions
- **Scalable**: Works for projects of any size
- **German Documentation**: Primary documentation language is German