Run `deno fmt`.

Expected:
- only `client/file.ts` and `client/file.tsx` are formatted

Actual:
- all `client/file*` files are formatted, including `file.js` and `file.d.ts`