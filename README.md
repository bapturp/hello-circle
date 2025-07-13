# hello-circle

## Configuration

The entire CI/CD process is orchestrated through a single file called `config.yml` located in a folder called `.circleci/` at the root of the project that defines the entire pipelines.

- **Pipeline**: represents the entirety of the configuration.

- **Workflows:** Responsible for orchestrating multiple _jobs_.

- **Jobs**: Responsible for running a series of _steps_ that perform commands.

- **Steps**: Run commands (such as installing dependencies or running tests) and shell scripts to do the work required for the project.
