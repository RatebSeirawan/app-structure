File structure

````
├── app
|  ├── config
|  |  ├── env.dev.js
|  |  ├── env.js
|  |  └── env.prod.js
|  ├── constants
|  |  └── index.ts
|  ├── graphql
|  ├── hooks
|  |  ├── index.ts
|  |  ├── test
|  |  └── use-something.ts
|  ├── i18n
|  |  ├── en.ts
|  |  └── index.ts
|  ├── services
|  |  ├── analytics
|  |  └── reactotron
|  ├── utils
|  └── views
|     ├── common
|     |  ├── button
|     |  |  ├── button.preset.ts
|     |  |  ├── button.props.ts
|     |  |  ├── button.story.tsx
|     |  |  └── button.tsx
|     |  ├── index.ts
|     |  └── test
|     |     └── bullet-item.test.ts
|     ├── components
|     |  ├── bullet-item
|     |  |  └── bullet-item.tsx
|     |  └── test
|     ├── navigation
|     |  ├── index.ts
|     |  ├── navigation.utilities.tsx
|     |  ├── routes.ts
|     |  └── stack-navigator.tsx
|     ├── screens
|     |  ├── home-screen
|     |  |  └── home-screen.tsx
|     |  └── index.ts
|     └── theme
|        ├── color.ts
|        ├── fonts
|        ├── index.ts
|        └── typography.ts
├── e2e
├── storybook
└── test
```