## ANXS - vim [![Build Status](https://travis-ci.org/ANXS/vim.png)](https://travis-ci.org/ANXS/vim)

Ansible role that installs your favourite flavour of vim.

#### Requirements & Dependencies
- Tested on Ansible 1.3 and higher

#### Variables

```yaml
vim_base: "vim-nox"     # package name of your favourite vim flavour
vim_extras: []          # list of vim extras
```

#### Testing
This project comes with a VagrantFile, this is a fast and easy way to test changes to the role, fire it up with `vagrant up`

See [vagrant docs](https://docs.vagrantup.com/v2/) for getting setup with vagrant


#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/vim/issues)!
