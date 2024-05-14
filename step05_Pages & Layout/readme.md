# Pages & Layout

## page.tsx:

- This file defines a React component that maps to a specific URL path in your Next.js application.
- When a user visits that path, Next.js renders the corresponding page component.
- Inside the `page.tsx` file, you write the content that you want to display on that page, such as headings, paragraphs, images, links, and forms.

## layout.tsx:

- This file defines a wrapper component that can be used to enclose one or more pages in your application.
- The layout component typically contains common UI elements that are shared across multiple pages, such as a header, navigation bar, and footer.
- When Next.js renders a page component, it wraps it within the layout component, creating a consistent and reusable structure for your application.

**Example:**

- `app/page.tsx`: This file defines the page component for your home page (usually at the root URL, `/`).
- `app/layout.tsx`: This file defines the layout component that will be used to wrap most or all of your application's pages.

**What you can include in the layout component:**

- **Header:** This section typically appears at the top of the page and might contain your application's logo, navigation bar, search bar, or user profile information.
- **Sidebar:** This optional section appears on the side of the page and might be used for navigation, filters, user account options, or displaying advertisements.
- **Footer:** This section appears at the bottom of the page and might contain copyright information, contact details, social media links, or legal disclaimers.

**Benefits of using layouts:**

- **Reusable UI:** By creating a layout component, you can define the common UI elements once and reuse them across all your pages, saving time and effort.
- **Consistent Design:** Layouts help maintain a consistent look and feel throughout your application, providing a more unified user experience.
- **Improved Code Organization:** Separating page content and layout logic into distinct files makes your code base more readable, maintainable, and easier to scale.


## Nested Layout:
In Next.js, nested layouts allow you to create a hierarchical structure for your application's UI. Imagine it like placing layouts within layouts. This way, you can define common components (header, footer) at a higher level and then "nest" specific page content within them.


[Nested Layout]()
