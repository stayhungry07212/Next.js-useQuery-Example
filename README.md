## What is this?

It's an example repo that show show to go from a simple hook-based application to React Query, avoiding all of the "global state" madness that normally happens!

## Challenges

- Convert the custom hooks used to fetch data to use `useQuery`
- Implement per-screen background fetching indicators
- Convert the custom hooks used to create/update/delete to use `useMutation`
- Configure mutations to automatically invalidate related queries
- Implement optimistic updates for mutations
- Prefetch individual posts on hover using `queryCache.prefetchQuery` OR
- Use `initialData` to show placeholder content for individual posts that pull from the parent `posts` query
- Remove per-screen background fetching indicators and instead build a global refetching indicator
- Dehydrate/hydrate the cache to and from localStorage using the `react-query/hydration` APIs

## How do I develop on this?

- Run `yarn` and then `yarn dev` locally.
- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
- **NOTE:** The "database" used in this app is simply a JSON file and thus will not work as a deployed application. That said, you are more than welcome to hook it up to a real API if you want!
