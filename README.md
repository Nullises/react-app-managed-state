# Managing React State (FULL UPDATED)

Based on https://app.pluralsight.com/library/courses/react-state-managing

 BUT... updated with

 * React-Router v6
 * React Hooks (useEffect, useState, etc...)
 * Redux Hooks (useDispatch, useSelector)
 * Vite

1. Create an `.env` file in root folder with `VITE_API_BASE_URL` variable with your preferred port

2. Modify `"start-api":` script in `package.json` file with your preferred port. e.g.: `--port 3001`

3. Install Concurrently globally to run backend and frontend at same time

```
yarn add global concurrently
  or
npm i -g concurrently
```

4. Run `npm run start` to run concurrently server and Vite app.