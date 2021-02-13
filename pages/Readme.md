# Pages folder

## Description

The pages folder reflects the routes of the application. Each component inside this folder has its own route.

A page component will contain children from components folder, or its own subfolder. It has its own state, and usually call some services as well.
## Structure

    pages
        | Page
            | Page.tsx
            | Page.scss
            | index.ts
            | __tests__
                | Page.test.tsx
            | components
                | Component
                    | Component.tsx
                    | Component.scss
                    | index.ts
                    | __tests__
                        | Component.test.tsx
                