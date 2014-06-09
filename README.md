A working ansible example used in conjunction with [debian-preseed](https://github.com/roberttstephens/debian-preseed).

First run sudo ansible-galaxy install Ansibles.mysql

To use

 - sudo ansible-galexy install Ansibles.mysql
 - git clone https://github.com/roberttstephens/ansible-example
 - cd ansible-example
 - ansible-playbook -i hosts site.yml -k
