# Store folder

## Description

The store folder will be included actions and reducers subfolder to manage redux states.

Mostly, the actions and reducers will be called in the page components so they usually named based on pages that use them.

## Structure

    store
        | actions
            | index.ts
            | user.actions.ts   
        | reducers
            | index.ts
            | user.reducers.ts
        | constants
            | index.ts
            | user.constants.ts
        
     