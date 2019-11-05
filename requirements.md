## Migrations

#### If knex isn't installed globally, you need npx before each command

Initialize Knex for our project: `knex init`

Create a migration: `knex migrate:make <file name>`

Use the migration to declare the changes we plan to make to the schema

Run a migration: `knex migrate: up`

Undo last migration: `knex migrate: down`

Update database to latest changes/migrations: `knex migrate:lastest`

Undo multiple migrations that ran together: `knex migrate:rollback`
