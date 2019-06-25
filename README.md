# Ci tasks

Simple docker based CI tasks that you can use with your repo. It shares the current working directory with your container allowing it to check the current code base from within docker.

To build the images:

```
./bin/build
```

To run a ci:

```
./bin/ci cloc
```

Available tasks:

- cloc - Count lines of code in your current codebase
- todo - Checks for lingering todos in your codebase
- prettier - Check formatting of repo
- yard - Generate ruby docs
- graphql-docs - Generate graphql docs from a schema
- rufo - Check wheter all ruby code is RUFO formatted
- trufflehog - Checks wheter the repo doesn't contain any secrets
- prettier - Checks wheter all files are formattted according prettier 
- brakeman - Checks for ruby vulnerabilities in rails applications
- bundle-audit - Checks for gem vulnerabilities
- notify - Send slack notfication
