_Playbook_, реализующий следующее:
* на машинах группы app выполняется установка и запуск Docker;
* на машинах группы database выполняется установка и запуск postgresql-server (версия и data-директория - переменные, задающиеся в inventory).


```
ansible-playbook playbook.yml -K
```
