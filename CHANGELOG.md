# CHANGELOG

## 1.1.2 - 2022-02-22

- Makes `withAuthRequired` work for API routes as well. See [the docs](./src/nextjs/README.md#protecting-api-routes) for more details.
- Removes `onUserLoaded` prop as it was rather confusing and user might want to choose other ways to manage their user state rather than React context.

## 1.1.1 - 2022-02-22

- [#24](https://github.com/supabase-community/supabase-auth-helpers/pull/24): feat: onUserLoaded prop in UserProvider:
  - Added the `onUserDataLoaded` on the `UserProvider` component fro conveninet fetching of additional user data. See [the docs](./src/nextjs/README.md#loading-additional-user-data) for more details.