# custom_PTF_module_files
collection of "custom_list module files" for use in system configuration
leveraging the **Pentesters Framework (PTF)** for specific package management

# Getting Started with Pentesters Framework (PTF)

> Reference(s):
>
> `https://www.trustedsec.com/tools/pentesters-framework/`
>
> and
>
> `https://vimeo.com/137133837`

---
---
### Clone the PTF repo
`git clone https://github.com/trustedsec/ptf/`

execute `ptf` as root or with sudo -> `sudo ./ptf` this will create the launcher that will allow you to `ptf` from anywhere on the system.

---
### Getting started with modules
#### installing ALL included modules
###### # TIP: `sudo su` prior to "install_update_all" it will make the install go smoother
ptf> `use modules/install_update_all`

#### installing a subset of modules
ptf> `use modules/reversing/install_update_all`

#### installing an individual module
ptf> `use modules/exploitation/beef`
ptf:(use modules/exploitation/beef)> `run`

#### installing custom lists of modules
ptf> `use modules/custom_list/list`

_or_ 

ptf> `use modules/custom_list/<file of customized listing of modules>`

> place custom txt files in `<path to ptf>/modules/custom_list/<filename.txt>`
---
