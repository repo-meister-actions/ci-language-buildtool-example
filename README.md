# Repo Meister Java Maven Example

This repository shows how the reusable GitHub Actions and Workflows for Continuous Integration are used.

**Repo Meister workflow:** [`main.yml`](.github/workflows/main.yml)

**Repo Meister action:** [`main-action.yml`](.github/workflows/main-action.yml)

## Running the example

The code in this repository is not important, but in case you want to run it, these are the steps:

1. Clone the repository

2. Install dependencies and run the unit-tests:

  ```shell
  mvn install
  ```

4. Run the application:

  ```shell
  mvn exec:java -Dexec.mainClass="com.github.repomeisteractions.FizzBuzz"
  ```
