# CLI Options

This document provides information about the available options for CLI commands in TaskMaster.

## taskmaster init

- `--template <template>`: Specify a template for the project.

```bash
taskmaster init --template basic
```

## taskmaster start
--port <port>: Specify the port to run the application on.

```bash
taskmaster start --port 4000
```

## taskmaster build
--env <environment>: Specify the environment for the build.

```bash
taskmaster build --env production
```

## taskmaster test
--watch: Run tests in watch mode.

```bash
taskmaster test --watch
```
