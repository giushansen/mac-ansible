Open terminal

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`brew install ansible`

`cd && git clone git@github.com:giushansen/mac-ansible.git .mac-ansible && cd .mac-ansible`

`ansible-playbook playbook.yml -i inventory`
