# Linking & Navigation

## <Link> Component

`<Link>` is a built-in component that extends the HTML `<a>` tag to provide prefetching and client-side navigation between routes. It is the primary and recommended way to navigate between routes in Next.js.

import Link from 'next/link'

export default function Page() {
return <Link href="/dashboard">Dashboard</Link>
}
