Homework for lesson 6

1. Необходимо установить Jenkins(версии 2+) и выполнить все шаги из документа.
 * - Сделать все тоже самое, но уже с использованием pipeline(Scripted или Declarative на ваше усмотрение)
 ** - Собрать реальный проект из GitHub'а(любой проект) с использованием Jenkins.
 
2. Сделать playbook Ansible для установки и настройки mysql(можете использовать MariaDB). Конфигурация должна подкладываться из template с использованием переменных.
 Примерная структура playbook'a:

+-- play.yml
L-- roles
    L-- mysql
        +-- tasks
        ¦   L-- main.yml
        +-- templates
        ¦   L-- my.cnf
        L-- vars
            L-- main.yml

Результаты можете отправить на почту ivan_govorukhin@epam.com. В случае с Jenkins'ом можете прислать скриншоты двух последний заданий(либо pipeline'ы).
