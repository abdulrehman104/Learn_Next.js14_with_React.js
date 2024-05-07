# Linking & Navigation

## <Link> Component

`<Link>` is a built-in component that extends the HTML `<a>` tag to provide prefetching and client-side navigation between routes. It is the primary and recommended way to navigate between routes in Next.js.

```tsx
import Link from 'next/link'

export default function Page() {
return <Link href="/dashboard">Dashboard</Link>
}
```


```tsx
import Link from "next/link";


export default function Navbar() {
  return (
    <div>
      <ul className="flex items-center justify-center gap-x-4 bg-slate-700">
        <Link href='/'>Home</Link>
        <Link href='/about'>About</Link>
        <Link href='/contact'>Contact</Link>
        <a href="/about">About</a>
      </ul>
    </div>
  );
}
```

