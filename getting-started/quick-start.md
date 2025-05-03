# Quick Start Guide

This guide will help you get up and running with Mako Code quickly.

## Prerequisites

Before you begin, make sure you have:
- Installed Mako Code (see [Installation Guide](./installation.md))
- Basic understanding of JavaScript/TypeScript
- A project where you want to use Mako Code

## Creating Your First Mako Project

### 1. Initialize a New Project

```bash
mkdir my-mako-project
cd my-mako-project
mako init
```

This will create a basic project structure with the necessary configuration files.

### 2. Define Your First Component

Create a file named `HelloWorld.mako.js` in your project:

```javascript
// HelloWorld.mako.js
export default function HelloWorld({ name = 'World' }) {
  return {
    render: () => `<div>Hello, ${name}!</div>`,
    styles: `
      div {
        font-weight: bold;
        color: blue;
      }
    `
  };
}
```

### 3. Build Your Project

```bash
mako build
```

This will process all your `.mako.js` files and generate the corresponding output.

### 4. Run Your Project

```bash
mako serve
```

This will start a development server, typically at `http://localhost:3000`.

## Next Steps

Now that you've created your first Mako project, you can:

- Learn about [Basic Concepts](../concepts/basic-concepts.md)
- Explore [Core Features](../features/core-features.md)
- Check out the [API Reference](../api/overview.md)

## Example Projects

For more examples and inspiration, check out our [example repository](https://github.com/mako-code/examples).
