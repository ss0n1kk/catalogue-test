# PromptHub - AI Prompts Catalogue

A comprehensive catalogue of 500+ AI prompts for various professions including SMM, lawyers, realtors, programmers, copywriters, and marketers.

## Features

- 🚀 500+ ready-to-use AI prompts
- 📊 Vercel Speed Insights integration for performance monitoring
- 🎨 Modern, responsive design
- ⚡ Optimized for fast loading

## Vercel Speed Insights

This project includes Vercel Speed Insights to monitor real-world performance metrics.

### Setup

The project uses `@vercel/speed-insights` package for tracking. The integration is already configured and will automatically work when deployed to Vercel.

### Building

To build the Speed Insights bundle:

```bash
npm install
npm run build
```

This will create the bundled Speed Insights script in `dist/speed-insights.bundle.js`.

### Development

To watch for changes during development:

```bash
npm run dev
```

## Deployment

Deploy to Vercel to activate Speed Insights:

1. Connect your repository to Vercel
2. Deploy the project
3. Speed Insights will automatically start tracking performance metrics

## Files

- `index.html` - Main HTML file with the catalogue interface
- `speed-insights.js` - Speed Insights initialization script
- `dist/speed-insights.bundle.js` - Bundled Speed Insights script (generated)
- `package.json` - Project dependencies and build scripts

## License

ISC
