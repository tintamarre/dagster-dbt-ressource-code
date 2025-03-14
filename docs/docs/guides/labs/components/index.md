---
title: "Components"
sidebar_position: 20
---

:::info

This feature is still in development and might change in patch releases. It’s not production ready, and the documentation may also evolve. Stay tuned for updates.

:::

{/* The snippets in this guide are generated by running `make regenerate_cli_snippets` in the root `docs` folder, generated from
    `/examples/docs_beta_snippets/docs_beta_snippets_tests/snippet_checks/guides/components/test_components_docs.py` */}
Welcome to Dagster Components.

Dagster Components is a new way to structure your Dagster projects. It aims to provide:

- An opinionated project layout that supports ongoing scaffolding from "Hello world" to the most advanced projects.
- A class-based interface (`Component`) for dynamically constructing Dagster definitions from arbitrary data (such as third-party integration configuration files).
- A toolkit for building YAML DSLs for `Components`, allowing instances of components to be defined with little to no Python code.
- A Dagster-provided set of component types that provide a simplified user experience for common integrations.

## Installation

To use the Components framework, you must install the `dg` command line tool, which lives in the published Python package `dagster-dg`. `dg` is designed to be globally installed and has no dependency on `dagster` itself. `dg` allows you to quickly scaffold Dagster projects and populate them with components.

### 1. Install uv

import InstallUv from '../../../partials/\_InstallUv.md';

<InstallUv />

### 2. Install the dg command line tool

import InstallDg from '../../../partials/\_InstallDg.md';

<InstallDg />

## dg API reference

Below is the help message for `dg`, which also serves as the API reference:

<CliInvocationExample path="docs_beta_snippets/docs_beta_snippets/guides/components/index/1-help.txt"  />

## Next steps

* [Follow the components ETL pipeline tutorial](components-etl-pipeline-tutorial)
* [Build your own pipeline with components](building-pipelines-with-components)
