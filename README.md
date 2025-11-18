# Shosetsu Extensions (Auto-Generated)

This repository contains automatically generated Shosetsu extensions using intelligent web scraping and site classification.

## Adding this repository to Shosetsu

1. Open Shosetsu app
2. Go to **Settings** → **Extensions** → **Repositories**
3. Tap the **+** button
4. Enter this URL:
   ```
   https://raw.githubusercontent.com/Opalminoncs/shosetsu-extensions-auto/main/
   ```
5. Tap **Add**

## Repository Structure

```
.
├── icons/          # Extension icons
├── lib/            # Shared Lua libraries
├── src/            # Extension source files
│   ├── en/        # English sources
│   └── multi/     # Multi-language sources
├── index.json     # Repository manifest
└── README.md      # This file
```

## Development Pipeline

This repository is generated using an automated pipeline that:

1. **Discovers** novel sites from community submissions and web crawls
2. **Classifies** sites into families (Madara, WordPress, custom APIs)
3. **Extracts** parameters (selectors, endpoints, pagination logic)
4. **Generates** Lua extensions from templates
5. **Validates** extensions through automated testing
6. **Publishes** only working extensions to this repository

## Project Status

🚧 **Phase 1: Manual Foundation** (In Progress)
- Setting up repository structure
- Learning Shosetsu extension API
- Creating initial extensions manually

## Contributing

To suggest a novel site for automated extension generation, please open an issue with:
- Site URL
- Example novel page
- Notes about the site structure (if known)

## License

Extensions in this repository are provided as-is for use with Shosetsu. Please respect the terms of service of the novel sites these extensions access.
