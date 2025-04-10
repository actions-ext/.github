# Extension Actions

This organization contains helper composite actions for use in GitHub Actions workflows.

**This organization is not affiliated with GitHub**

## Inventory

### general

General purpose actions

| Name                                                                                          | Action Reference                         | Description                                                                                      |
| :-------------------------------------------------------------------------------------------- | :--------------------------------------- | :----------------------------------------------------------------------------------------------- |
| [initialize-variables](https://github.com/actions-ext/general/tree/main/initialize-variables) | actions-ext/general/initialize-variables | Inspect commits, PR titles, and args for "full builds"                                           |
| [yardang](https://github.com/actions-ext/yardang)                                             | actions-ext/yardang                      | Setup [yardang](https://github.com/python-project-templates/yardang) for building documentation  |
| [copier-update](https://github.com/actions-ext/copier-update)                                 | actions-ext/copier-update                | Action to update [copier](https://copier.readthedocs.io/en/stable/)-templated repo from upstream |

### python

Helper actions for Python projects

| Name                                                                                                 | Action Reference                              | Description                                                                        |
| :--------------------------------------------------------------------------------------------------- | :-------------------------------------------- | :--------------------------------------------------------------------------------- |
| [setup](https://github.com/actions-ext/python/tree/main/setup)                                       | `actions-ext/python/setup`                    | Setup Python with `pip` caching and `uv`                                           |
| [setup-cibuildwheel](https://github.com/actions-ext/python/tree/main/setup-cibuildwheel)             | `actions-ext/python/setup-cibuildwheel`       | Setup [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/) and caching |
| [setup-cibuildwheel-cache](https://github.com/actions-ext/python/tree/main/setup-cibuildwheel-cache) | `actions-ext/python/setup-cibuildwheel-cache` | Setup [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/) caching     |
| [run-cibuildwheel](https://github.com/actions-ext/python/tree/main/run-cibuildwheel)                 | `actions-ext/python/run-cibuildwheel`         | Run [`cibuildwheel`](https://cibuildwheel.readthedocs.io/en/stable/)               |
| [upload-dist](https://github.com/actions-ext/python/tree/main/upload-dist)                           | `actions-ext/python/upload-dist`              | Upload a python sdist or wheel                                                     |
| [download-dist](https://github.com/actions-ext/python/tree/main/download-dist)                       | `actions-ext/python/download-dist`            | Download and install a python sdist or wheel                                       |

### cpp

Helper actions for C++ projects

| Name                                                        | Action Reference        | Description                       |
| :---------------------------------------------------------- | :---------------------- | :-------------------------------- |
| [setup](https://github.com/actions-ext/cpp/tree/main/setup) | `actions-ext/cpp/setup` | Setup CCache (Linux / Macos only) |

### rust

Helper actions for Rust projects

| Name                                                         | Action Reference         | Description                            |
| :----------------------------------------------------------- | :----------------------- | :------------------------------------- |
| [setup](https://github.com/actions-ext/rust/tree/main/setup) | `actions-ext/rust/setup` | Setup rust compiler and enable caching |

### node

Helper actions for Node / JavaScript projects

| Name                                                         | Action Reference         | Description                        |
| :----------------------------------------------------------- | :----------------------- | :--------------------------------- |
| [setup](https://github.com/actions-ext/node/tree/main/setup) | `actions-ext/node/setup` | Setup Node with `pnpm` and caching |
