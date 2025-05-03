# Frequently Asked Questions

This page answers common questions about Mako Code.

## General Questions

### What is Mako Code?

Mako Code is a modern development framework designed to streamline the process of building web applications. It provides a component-based architecture, reactive data binding, and powerful build tools to enhance developer productivity.

### Is Mako Code free to use?

Yes, Mako Code is open-source software released under the MIT license. You can use it for personal and commercial projects without cost.

### Who maintains Mako Code?

Mako Code is maintained by a team of dedicated developers and a community of contributors. The project is overseen by the core team, who review contributions and guide the project's direction.

## Technical Questions

### How does Mako Code compare to React/Vue/Angular?

Mako Code shares some similarities with these frameworks, such as component-based architecture and reactive data flow. However, Mako Code differentiates itself by:

- Focusing on simplicity and developer experience
- Providing a more integrated solution with less configuration
- Offering better performance through advanced optimization techniques
- Supporting a wider range of output targets

### Can I use Mako Code with TypeScript?

Yes, Mako Code has first-class TypeScript support. All APIs have proper type definitions, and the build system is configured to work seamlessly with TypeScript.

### Does Mako Code support server-side rendering (SSR)?

Yes, Mako Code includes built-in support for server-side rendering. This allows you to render your components on the server for improved performance and SEO.

### How do I handle routing in Mako Code?

Mako Code provides a built-in router that supports:

- Nested routes
- Route parameters
- Route guards
- Lazy loading

See the [Router API Reference](../api/router.md) for more details.

## Installation and Setup

### What are the system requirements for Mako Code?

Mako Code requires:
- Node.js v14.0.0 or higher
- npm v6.0.0 or higher

### How do I update Mako Code to the latest version?

To update Mako Code, run:

```bash
npm update mako-code --global
```

### Can I use Mako Code with my existing project?

Yes, Mako Code can be integrated with existing projects. See our [Migration Guide](../guides/migration.md) for details on how to integrate Mako Code with different frameworks.

## Troubleshooting

### I'm getting a "Cannot find module" error. What should I do?

This usually indicates that a dependency is missing. Try running:

```bash
npm install
```

If the problem persists, check that the module name is spelled correctly and that it's listed in your package.json.

### How do I debug my Mako Code application?

Mako Code includes several debugging tools:

1. The `mako debug` command provides detailed information about your application
2. The browser extension offers real-time inspection of components
3. Source maps are generated automatically for easier debugging

See our [Debugging Guide](../guides/debugging.md) for more information.

### Where can I get help if my question isn't answered here?

If your question isn't answered here, you can:

- Check the [documentation](../)
- Ask in our [community forum](https://forum.mako-code.org)
- Open an issue on [GitHub](https://github.com/mako-code/mako-code/issues)
- Join our [Discord server](https://discord.gg/mako-code)
