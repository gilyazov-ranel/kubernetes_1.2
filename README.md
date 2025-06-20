# Домашнее задание к занятию «Базовые объекты K8S»
### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
2. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).
### Ответ
![image](https://github.com/user-attachments/assets/c290f06f-781d-417e-971b-e523b0db9b36)
![image](https://github.com/user-attachments/assets/c5b8573b-e837-4dc1-b8cf-e946f354a826)


------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web.
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web.
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).
### Ответ
![image](https://github.com/user-attachments/assets/18949834-f7f8-4a86-97b6-b722b667422a)

![image](https://github.com/user-attachments/assets/270e1718-f396-4809-8c1c-a8322ef2e0f0)

------
