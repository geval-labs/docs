# Geval Documentation

This repository contains the documentation for [Geval](https://geval.io) - Eval-driven release gates for AI applications.

## Structure

This documentation follows [Mintlify's](https://mintlify.com) template structure:

- `docs.json` - Configuration file for Mintlify
- `index.mdx` - Landing page
- `getting-started.mdx` - Getting started guide
- `cli/` - CLI command documentation
- `contracts/` - Contract reference documentation
- `integration/` - CI/CD integration guides
- `api/` - API reference documentation
- `examples/` - Example use cases

## Local Development

To preview the documentation locally:

```bash
# Install Mintlify CLI
npm install -g mintlify

# Start development server
mintlify dev
```

The documentation will be available at `http://localhost:3000`

## Deployment

This documentation is deployed to `docs.geval.io` via Mintlify's hosting platform.

## Contributing

1. Make changes to `.mdx` files
2. Update `docs.json` if adding new pages
3. Test locally with `mintlify dev`
4. Commit and push changes
5. Mintlify will automatically deploy

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Geval GitHub](https://github.com/geval-labs/geval)
- [Geval Website](https://geval.io)
