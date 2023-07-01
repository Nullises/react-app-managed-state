# Managing React State (FULL UPDATED)

Based on https://app.pluralsight.com/library/courses/react-state-managing

 BUT... updated with

 * React-Router v6
 * React Hooks (useEffect, useState, etc...)
 * Redux Hooks (useDispatch, useSelector)
 * Vite

1. Install Concurrently globally to run backend and frontend at same time

```
yarn add global concurrently
  or
npm i -g concurrently
```

2. Run `prestart:api` to recreate the DB

3. Run `npm run dev` to run concurrently server and Vite app.