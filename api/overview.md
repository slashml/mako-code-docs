# API Overview

This section provides a comprehensive overview of the Mako Code API. The API is designed to be intuitive, consistent, and powerful, giving you the tools you need to build sophisticated applications.

## API Structure

The Mako Code API is organized into several modules:

- **Core**: Essential functionality for creating and managing components
- **State**: State management utilities
- **Router**: Navigation and routing capabilities
- **Utils**: Helper functions and utilities
- **CLI**: Command-line interface for project management
- **Server**: Server-side rendering and API integration

## Core API

The Core API provides the fundamental building blocks for creating Mako applications.

### Key Functions

| Function | Description |
|----------|-------------|
| `createComponent()` | Creates a new component with the specified options |
| `mount()` | Mounts a component to the DOM |
| `unmount()` | Removes a component from the DOM |
| `update()` | Manually triggers an update of a component |

### Example Usage

```javascript
import { createComponent, mount } from 'mako-code/core';

// Create a component
const MyComponent = createComponent({
  name: 'MyComponent',
  props: {
    message: String,
    count: Number
  },
  setup(props) {
    // Component logic here
    return {
      render() {
        return `
          <div>
            <h1>${props.message}</h1>
            <p>Count: ${props.count}</p>
          </div>
        `;
      }
    };
  }
});

// Mount the component
mount(MyComponent, {
  target: document.getElementById('app'),
  props: {
    message: 'Hello, Mako!',
    count: 42
  }
});
```

## State API

The State API provides tools for managing application state.

### Key Functions

| Function | Description |
|----------|-------------|
| `createStore()` | Creates a new state store |
| `reactive()` | Creates a reactive object |
| `computed()` | Creates a computed value |
| `watch()` | Watches for changes in reactive data |

## Next Steps

For detailed information about specific API modules, check out:

- [Core API Reference](./core.md)
- [State API Reference](./state.md)
- [Router API Reference](./router.md)
- [Endpoints Reference](./endpoints.md)
