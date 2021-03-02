File structure

```
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

# Refactoring plan
## File structure

- [ ] Moving `components - navigation - pages - theme` to `src/views` folder
- [ ] Moving all graphql related files (cache - client - config) to `src/graphql`
- [ ] Moving `useData.js` to hooks and naming them correctly
- [ ] Make manager and pumper pages not seperated by folder but by functionality and file name

## Moving business logic to BE

- [ ] Find places where attr propagation is happening on the client and move that logic to the BE.


