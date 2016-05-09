# Vagrant Aliases

Useful bash aliases for Vagrant. The naming of the aliases quickly and intuitively describes their functions
based on common conventions. **Choose what you need, use what you can.**

## Aliases with dash including common abbreviations

```bash
# start vagrant - starts the virtual machine and ssh into it
alias vagrant-start='vagrant up && vagrant ssh'
alias vag-start='vagrant up && vagrant ssh'
alias vgr-start='vagrant up && vagrant ssh'
alias vg-start='vagrant up && vagrant ssh'

# pause vagrant - suspends the virtual machine, so next time it will start just a couple of seconds
alias vagrant-pause='vagrant suspend'
alias vag-pause='vagrant suspend'
alias vgr-pause='vagrant suspend'
alias vg-pause='vagrant suspend'

# stop vagrant - halts the virtual machine
alias vagrant-stop='vagrant halt'
alias vag-stop='vagrant halt'
alias vgr-stop='vagrant halt'
alias vg-stop='vagrant halt'

# status of vagrant - shows the status of the current virtual machine whether it is on or not
alias vagrant-status='vagrant status'
alias vag-status='vagrant status'
alias vgr-status='vagrant status'
alias vg-status='vagrant status'

# enter vagrant - enters into the the current virtual machine via ssh into it if it is running
alias vagrant-enter='vagrant ssh'
alias vag-enter='vagrant ssh'
alias vgr-enter='vagrant ssh'
alias vg-enter='vagrant ssh'

# restart vagrant - halts the virtual machine, then start it and ssh into it
alias vagrant-restart='vagrant halt && vagrant up && vagrant ssh'
alias vag-restart='vagrant halt && vagrant up && vagrant ssh'
alias vgr-restart='vagrant halt && vagrant up && vagrant ssh'
alias vg-restart='vagrant halt && vagrant up && vagrant ssh'

# remove vagrant - destroys the virtual machine without prompt
alias vagrant-remove='yes | vagrant destroy'
alias vag-remove='yes | vagrant destroy'
alias vgr-remove='yes | vagrant destroy'
alias vg-remove='yes | vagrant destroy'

# reinstall vagrant - destroys the virtual machine without prompt, then start it and ssh into it
alias vagrant-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vag-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vgr-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
alias vg-reinstall='yes | vagrant destroy && vagrant up && vagrant ssh'
```

## Usage

## Contribution

## Support

## License

[MIT](https://opensource.org/licenses/MIT) @ Richard King
