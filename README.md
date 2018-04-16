* Open terminal and install `brew`

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

* Install ansible

`brew install ansible`

* Install the playbook

`cd && git clone git@github.com:giushansen/mac-ansible.git .mac-ansible && cd .mac-ansible`

* Run the playbook

`ansible-playbook playbook.yml -i inventory`
