A working ansible example used in conjunction with [debian-preseed](https://github.com/roberttstephens/debian-preseed).

To use

 - sudo ansible-galexy install Ansibles.mysql
 - sudo ansible-galaxy install nbz4live.php-fpm
 - sudo ansible-galaxy install jdauphant.nginx
 - git clone https://github.com/roberttstephens/ansible-example
 - cd ansible-example
 - ansible-playbook -i hosts site.yml -k
