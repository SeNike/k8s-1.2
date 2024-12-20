# Домашнее задание к занятию «Базовые объекты K8S»



### Задание 1. Создать Pod с именем hello-world

1. Создать манифест (yaml-конфигурацию) Pod.
   [hello-world-pod.yaml](https://github.com/SeNike/k8s-1.2/blob/main/hello-world-pod.yaml)
3. Использовать image - gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
4. Подключиться локально к Pod с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/1.1/hello-world.png)

------

### Задание 2. Создать Service и подключить его к Pod

1. Создать Pod с именем netology-web. [netology-web-pod.yaml](https://github.com/SeNike/k8s-1.2/blob/main/netology-web-pod.yaml)
2. Использовать image — gcr.io/kubernetes-e2e-test-images/echoserver:2.2.
3. Создать Service с именем netology-svc и подключить к netology-web. [netology-service.yaml](https://github.com/SeNike/k8s-1.2/blob/main/netology-service.yaml)
4. Подключиться локально к Service с помощью `kubectl port-forward` и вывести значение (curl или в браузере).

![IMG](https://github.com/SeNike/Study_24/blob/main/k8s/1.1/netology-web.png)

------

### Правила приёма работы

1. Домашняя работа оформляется в своем Git-репозитории в файле README.md. Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.
2. Файл README.md должен содержать скриншоты вывода команд `kubectl get pods`, а также скриншот результата подключения.
3. Репозиторий должен содержать файлы манифестов и ссылки на них в файле README.md.


