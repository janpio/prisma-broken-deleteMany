- Add database connection string to `.env` file (E.g. via https://db-provision.cloud.prisma.io/)
- `npm install`
- `npx prisma db push`
- `node script.js`
- Observe the end of the output:
```
with_compound_unique after [
  { id: 0, name: 'with_compound_unique 0', WART_id: null },
  { id: 1, name: 'with_compound_unique 1', WART_id: null },
  { id: 2, name: 'with_compound_unique 2', WART_id: null },
  { id: 3, name: 'with_compound_unique 3', WART_id: null },
  { id: 4, name: 'with_compound_unique 4', WART_id: null },
  { id: 5, name: 'with_compound_unique 5', WART_id: null },
  { id: 6, name: 'with_compound_unique 6', WART_id: null },
  { id: 7, name: 'with_compound_unique 7', WART_id: null },
  { id: 8, name: 'with_compound_unique 8', WART_id: null },
  { id: 9, name: 'with_compound_unique 9', WART_id: null }
]
```
This is unexpected and the table should be empty.