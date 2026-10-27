# dbt

A minimal [dbt](https://www.getdbt.com/) starter project scaffold.

## Project structure

- `dbt_project.yml` - dbt project configuration
- `models/example/` - starter models and schema tests
- `.gitignore` - ignores generated dbt artifacts

## Quick start

1. Install dbt for your warehouse adapter (for example `dbt-core` + adapter package).
2. Configure your `profiles.yml` with a profile named `dbt`.
3. Run:
   - `dbt debug`
   - `dbt run`
   - `dbt test`
