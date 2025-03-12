# mVara Public Assets Repository

This repository contains all public assets for mVara products, marketing, documentation, and extensions. It serves as a centralized location for publicly accessible resources while allowing other repositories with sensitive code to remain private.

## Repository Structure

```
/
├── extensions/            # VS Code and other IDE extension assets
│   └── logos/            # Logos specific to extensions
├── marketing/            # Marketing materials and brand assets
└── documentation/        # Images and resources for documentation
```

## Usage Guidelines

### For VS Code Extensions

VS Code extension marketplace requires all images in README files to be served from public HTTPS URLs. When referencing assets in extension READMEs, use the raw GitHub URL format:

```
https://raw.githubusercontent.com/jackccrawford/mvara-assets/master/extensions/logos/mvara-logo-white.png
```

### For Other mVara Products and Documentation

The same raw GitHub URL format can be used to embed images in any documentation, websites, or other materials:

```
https://raw.githubusercontent.com/jackccrawford/mvara-assets/master/path/to/asset.png
```

## Contributing New Assets

To add new assets to this repository:

1. Place the asset in the appropriate directory based on its purpose
2. Commit and push to the repository
3. Use the raw GitHub URL to reference the asset in your documentation or code

## Contents

### Extension Assets
- `extensions/logos/mvara-logo-white.png` - mVara logo on white background

### Marketing Assets
*(Add marketing assets here as they are created)*

### Documentation Assets
*(Add documentation assets here as they are created)*
