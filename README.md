# Savvy, nextjs & tailwindcss blog.

forked from [nextjs-blog](https://github.com/timlrx/tailwind-nextjs-starter-blog)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/farlandliu/savvy.git)

## Customize

- change fonts
- change theme color;
- change layout to simple layout

## releases

- 2024-03-07 change highlight code font, in `css/prism.css`

```css
.code-highlight {
  @apply float-left min-w-full;
  @apply font-mono;
}

```
change font color of titles in `css/tailwind.css`

```css
prose {
  @apply text-lg;
}
.prose h2, h3, h4{
 
  @apply  text-gray-700;
  @apply  dark:text-gray-300;
}
```