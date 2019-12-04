# Ci Tasks

Simple docker based CI tasks that you can use with your repo. It shares the current working directory with your container allowing it to check the current code base from within docker.

## Install

To build the images:

```bash
./bin/build
```

To install the CI tool:

```bash
./bin/install
```

After running install you want to reload bash.

You can do this by running:

```
source ~/.bash_profile
```

## How to use

To run a ci inspector, cd to a repo and run:

```
ci cloc
```

Available tasks to run:

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
- git-stats - Extract git metrics from current codebase