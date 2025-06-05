# ✅ dbt + Snowflake Mastery — 60-Day Checklist

> Track your zero-to-hero journey in dbt with Snowflake, one commit at a time.  
> Fork it, clone it, brag about it.

---

## 📦 Week 1: Foundations & Setup

- [ ] Install `dbt-core` and `dbt-snowflake`
- [ ] Create `profiles.yml` and configure Snowflake creds
- [ ] Run `dbt init` and explore folder structure
- [ ] Connect to Snowflake and run `dbt debug`
- [ ] Write and run your first model using `ref()`
- [ ] Create a `source()` block and use it in a model
- [ ] Generate and explore `dbt docs`

## 🧠 Week 2: Jinja, Macros & Testing

- [ ] Learn Jinja basics (loops, conditions, filters)
- [ ] Write a simple macro and use it in a model
- [ ] Add `not_null`, `unique`, and `relationship` tests
- [ ] Use `dbt-utils` for generic test patterns
- [ ] Add `description:` fields to models and columns
- [ ] Serve `dbt docs` with full metadata

## 🏗️ Week 3: Modeling Like a Pro

- [ ] Implement layered architecture: `stg_`, `int_`, `fct_`, `dim_`
- [ ] Use CTEs and model chaining via `ref()`
- [ ] Build a dimensional schema (fact + dims)
- [ ] Draw or generate your DAG
- [ ] Validate model grain and uniqueness

## ❄️ Week 4: Snowflake-Optimized Modeling

- [ ] Understand `materialized:` types (table, view, incremental, ephemeral)
- [ ] Implement `is_incremental()` logic in a model
- [ ] Use `tags`, `config`, and `post-hook` blocks
- [ ] Set custom `warehouse`, `role`, and `schema` per target
- [ ] Test runtime and cost impact of materializations

## ⏳ Week 5: Snapshots, Seeds & Python

- [ ] Create a `snapshot` for a slowly changing dimension
- [ ] Create a seed file (CSV) and load it as a model
- [ ] Use `dbt build` to run seeds, snapshots, models, and tests
- [ ] Write a basic `Python` model (e.g. scoring or transformation)
- [ ] Integrate `snowpark` logic into a Python model

## ⚙️ Week 6: CI/CD & GitOps

- [ ] Set up GitHub repo and version control
- [ ] Create feature branches and PR review flow
- [ ] Add CI pipeline using GitHub Actions or dbt Cloud
- [ ] Run `dbt deps`, `dbt test`, `dbt docs` in CI
- [ ] Use `selectors.yml` and `state:modified` for targeted runs

## 🚦 Week 7: Orchestration, Alerts & Monitoring

- [ ] Schedule dbt jobs via Airflow/Dagster/Prefect or dbt Cloud
- [ ] Add alerts on job failure via Slack or email
- [ ] Log test results using `run_results.json`
- [ ] Track query performance in Snowflake UI
- [ ] Use `audit-helper` or `dbt-artifacts` packages

## 🏁 Week 8: Capstone Project & Sharing

- [ ] Finalize project structure: sources, staging, marts, macros
- [ ] Generate full documentation and DAG
- [ ] Create `README.md` with project summary and setup steps
- [ ] Add screenshots or Loom demo of dbt Cloud or DAG
- [ ] Write blog post or LinkedIn post about what you built
- [ ] Bonus: Try out `dbt Mesh` or multi-project layout

## 🧩 Optional Enhancements

- [ ] Add Snowflake `MASKING POLICIES` via post-hook
- [ ] Integrate Tableau/Looker on top of marts
- [ ] Create parameterized macros with `args`
- [ ] Build a generic SCD2 macro for multiple snapshots
- [ ] Use `exposures` to track downstream BI dashboards
