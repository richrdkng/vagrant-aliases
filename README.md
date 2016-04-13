# vagrant-aliases

Useful bash aliases for vagrant. The naming of the aliases quickly and intuitively describes their functions
based on common conventions.
<br>
**Choose what you need, use what you can.**

## Aliases with underscore including 2 common abbreviations

```bash
# start vagrant - starts the virtual machine and ssh into it
alias vagrant_start='vagrant up && vagrant ssh'
alias vgr_start='vagrant up && vagrant ssh'
alias vag_start='vagrant up && vagrant ssh'

# pause vagrant - suspends the virtual machine, so next time it will start just a couple of seconds
alias vagrant_pause='vagrant suspend'
alias vgr_pause='vagrant suspend'
alias vag_pause='vagrant suspend'

# stop vagrant - halts the virtual machine
alias vagrant_stop='vagrant halt'
alias vgr_stop='vagrant halt'
alias vag_stop='vagrant halt'

# restart vagrant - halts the virtual machine, then start it and ssh into it
alias vagrant_restart='vagrant halt && vagrant up && vagrant ssh'
alias vgr_restart='vagrant halt && vagrant up && vagrant ssh'
alias vag_restart='vagrant halt && vagrant up && vagrant ssh'

# remove vagrant - destroys the virtual machine without prompt
alias vagrant_remove='yes | vagrant destroy'
alias vgr_remove='yes | vagrant destroy'
alias vag_remove='yes | vagrant destroy'

# reinstall vagrant - destroys the virtual machine without prompt, then start it and ssh into it
alias vagrant_reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vgr_reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vag_reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
```

## Aliases with dash including 2 common abbreviations

```bash
# start vagrant - starts the virtual machine and ssh into it
alias vagrant-start='vagrant up && vagrant ssh'
alias vgr-start='vagrant up && vagrant ssh'
alias vag-start='vagrant up && vagrant ssh'

# restart vagrant - halts the virtual machine, then start it and ssh into it
alias vagrant-restart='vagrant halt && vagrant up && vagrant ssh'
alias vgr-restart='vagrant halt && vagrant up && vagrant ssh'
alias vag-restart='vagrant halt && vagrant up && vagrant ssh'

# stop vagrant - halts the virtual machine
alias vagrant-stop='vagrant halt'
alias vgr-stop='vagrant halt'
alias vag-stop='vagrant halt'

# remove vagrant - destroys the virtual machine without prompt
alias vagrant-remove='yes | vagrant destroy'
alias vgr-remove='yes | vagrant destroy'
alias vag-remove='yes | vagrant destroy'

# reinstall vagrant - destroys the virtual machine without prompt, then start it and ssh into it
alias vagrant-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vgr-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vag-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
```

## Usage