# NodeJS project template

## Description

This template uses:

- Typescript
- TypeORM
- NodeJS
- Express
- Postgres
- ESLint

## Configuration

Make sure you have node and docker installed by typing `node -v` and `docker -v` in terminal.

1. Use the repository as template (by forking it or using this one directly)
2. Install dependencies `yarn`
3. Run `docker run -d --name postgres -e POSTGRES_PASSWORD=mypass -e POSTGRES_USERNAME=postgres -e POSTGRES_DATABASE=mydb -p 5432:5432 postgres:latest`
4. Configure `.env` file copying the .env.example and setting the variables
5. Configure `ormconfig.json` by copying the ormconfig.example.json and setting the variables
6. If you want to integrate basic users authentication features, merge the branch feat/authentication using `git checkout main` and `git merge feat/authentication`

## Notes

Don't forget to check if the template features fits your use case!
