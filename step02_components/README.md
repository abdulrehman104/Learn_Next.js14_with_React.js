# Components

In React, components are the fundamental building blocks for creating user interfaces (UI). They are reusable pieces of code that encapsulate both the UI structure (what it looks like) and the logic (how it behaves).

## Why use it?

- Reusable: Components can be used multiple times throughout your application, promoting code efficiency and maintainability.
- Independent: Components are self-contained units, making it easier to reason about and test them in isolation.
- Composable: Components can be nested within other components, allowing you to build complex UIs from simpler ones.

## Key Points

- Components are a function.
- The first letter of a component's name is capitalized.
- Components are reusable.
- JSX includes HTML-like syntax mixed with JavaScript expressions.
- When rendered, JSX is converted into HTML elements.
- We write HTML and CSS inside JavaScript and TypeScript within a component.
- You can write JavaScript and TypeScript inside HTML within a component

```tsx
// Navbar

import Link from "next/link";


export default function Navbar() {
  return (
    <div>
      <ul className="flex items-center justify-center gap-x-4 bg-slate-700">
        <Link href='/'>Home</Link>
        <Link href='/about'>About</Link>
        <Link href='/contact'>Contact</Link>
      </ul>
    </div>
  );
}

```

```tsx
// Sidebar

const Sidebar = () => {
  return (
    <div>
      <h1>sidebar</h1>
    </div>
  );
};

export default Sidebar;

```
