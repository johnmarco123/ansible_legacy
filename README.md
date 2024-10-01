# Quick setup

### Clone repo and copy paste this:
    ansible-playbook -K --ask-vault-pass local.yml
    
### Currently the following work flawlessly
    ssh
    git-setup
    core-setup
    python-setup
    nvim-setup <--- make sure you go to packer, source it and PackerSync
    dotfiles
    productivity-tools
    lsp-setup
    node
    nvm
    
## Building dockers
    docker run --rm -it nvim-computer bash <- creates the environment basically
    ./build-dockers
    
## Running specific tags (stow in this case)
    ansible-playbook -K --ask-vault-pass local.yml --tags stow
