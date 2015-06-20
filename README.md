ansible-role-base
=============

Install base packages

### Variables:

| name | type | description |
|------|------|-------------|
| `base_create_swap_file` | boolean | option to create a swap file |
| `base_swap_file_path` | string | the swap file base path |
| `base_swap_file_size_kb` | integer | the size of the swap file |
| `base_update_cache` | boolean | run apt cache update or not |
| `base_sys_packages` | list | system packages to install |
| `base_pip_packages` | list | pip packages to install |


**TODO**

* tests
* travis config
* rhel
