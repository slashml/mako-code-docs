# Basic Concepts

This page explains the fundamental concepts and principles behind Mako Code.

## Core Philosophy

Mako Code is built around the principle of "code as data" - treating your code as a structured data format that can be analyzed, transformed, and optimized.

## Key Concepts

### Components

In Mako Code, components are the building blocks of your application. Each component is a self-contained unit that encapsulates:

- Rendering logic
- Styling
- Behavior
- Data dependencies

### Templates

Templates define the structure of your components. Mako Code uses a declarative template syntax that allows you to express complex UI patterns concisely.

```javascript
// Example template
const template = `
  <div class="card">
    <h2>{{title}}</h2>
    <p>{{content}}</p>
    <button @click="handleClick">{{buttonText}}</button>
  </div>
`;
```

### Transformers

Transformers are functions that modify your code during the build process. They can:

- Optimize for performance
- Add cross-cutting concerns
- Transform syntax
- Generate code

### Plugins

Plugins extend the functionality of Mako Code. They can add new commands, transformers, or integration with other tools.

## Data Flow

Mako Code follows a unidirectional data flow pattern:

1. State is the single source of truth
2. UI is a function of state
3. Actions trigger state changes
4. State changes trigger UI updates

## Compilation Process

When you build a Mako Code project, it goes through several phases:

1. **Parsing**: Your code is parsed into an Abstract Syntax Tree (AST)
2. **Transformation**: The AST is transformed according to your configuration
3. **Code Generation**: The transformed AST is converted back into code
4. **Bundling**: The generated code is bundled for deployment

## Next Steps

Now that you understand the basic concepts, you can:

- Explore [Advanced Concepts](./advanced-concepts.md)
- Learn about [Core Features](../features/core-features.md)
- Check out the [API Reference](../api/overview.md)
