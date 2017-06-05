# LIVE SOLVE NOTES

## Pattern for CRUD

- `CREATE TABLE todos (id SERIAL PRIMARY KEY, description text, completed boolean DEFAULT false);`
- Create new to do

  - sequence diagram

NOTE: preventDefault() EXAMPLE: `function addTask(e){ e.preventDefault(); }`

`$.post([url], [data])` `$.post('/todos', task)`
