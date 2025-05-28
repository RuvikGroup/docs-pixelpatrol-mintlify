# Pixel Patrol Documentation

This repository contains the official documentation for [Pixel Patrol](https://pixelpatrol.app), an AI-powered media moderation SaaS platform.

## 📚 Documentation Structure

- **Getting Started** - Installation, quickstart guides, and architecture overview
- **Core Concepts** - Teams, sites, rules, moderation workflows, and webhooks
- **Features** - Deep dives into AI moderation, rule-based filtering, and more
- **API Reference** - Complete API documentation with examples
- **Integration Guides** - Step-by-step tutorials for various frameworks

## 🚀 Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally:

```bash
npm i -g mintlify
```

Run the following command at the root of this directory:

```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`.

## 📝 Writing Guidelines

- Use clear, concise language
- Include code examples where relevant
- Add diagrams for complex concepts
- Keep API examples up-to-date
- Test all code snippets

## 🔧 Configuration

The documentation is configured via `docs.json`. Key settings include:
- Theme: Willow (blue theme)
- Navigation structure
- API reference configuration
- Custom branding

## 🚀 Deployment

Changes pushed to the main branch will be automatically deployed via Mintlify's GitHub integration.

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Test locally with `mintlify dev`
4. Submit a pull request

## 📞 Support

For questions about the documentation, please contact support@pixelpatrol.app.

## Troubleshooting

- **Mintlify dev isn't running** - Run `mintlify install` to re-install dependencies
- **Page loads as a 404** - Ensure you're running from the directory containing `docs.json`
- **Changes not reflecting** - Clear your browser cache or use incognito mode
