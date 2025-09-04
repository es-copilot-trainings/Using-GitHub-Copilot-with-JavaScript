# Recipe App

This is a small, purposefully-incomplete recipe app intended to be used in some Copilot workshops. 

- Built with Node.js, Express, Handlebars, and Sqlite.
- Scafholds a database with seed data on first launch.
- Handles the creation, listing, and editing of recipes.

Some ideas of what to add:

- A `/recipes/random` endpoint to select a random recipe.
- A way to delete recipes within the web application.
- A way to search recipes.
- Support for multiple units of measurement on recipes. 

## Prerequisites

Before running this application, ensure you have the following tools installed:

### Required Tools

- **Node.js**: Version 18.0.0 or higher (recommended: 18.x LTS or later)
  - Express 5.x requires Node.js 18+
  - Download from [nodejs.org](https://nodejs.org/)
- **npm**: Version 8.0.0 or higher (comes bundled with Node.js)
  - Used for package management and running scripts

### Verification Commands

You can verify your installations by running:

```bash
node --version    # Should show v18.0.0 or higher
npm --version     # Should show 8.0.0 or higher
```

## Requirements

The setup should be the following commands in your terminal:

```bash
npm install
npm start
```
Visit `http://localhost:3000` to start managing your recipes.

## License

This project is licensed under the terms of the MIT open source license. Please refer to [MIT](https://github.com/github-samples/node-recipe-app/blob/main/LICENSE) for the full terms.

## Support & Contributions

There is no support for this repository. It will periodically be updated as the needs for workshops where it is used evolves. We do not currently accept contributions. 
