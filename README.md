# Домашнее задание к занятию «k8s Helm» - Сергей Ситкарёв

## Задание 1. Подготовить Helm-чарт для приложения

![Задание1](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/img/1.jpg)

Необходимо упаковать приложение в чарт для деплоя в разные окружения.

Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.

В переменных чарта измените образ приложения для изменения версии.

[values_dev](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/src/helm-nginx/values_dev.yaml)

[values_test](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/src/helm-nginx/values_test.yaml)

[values_prod](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/src/helm-nginx/values_prod.yaml)

## Задание 2. Запустить две версии в разных неймспейсах

Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.

![Задание2](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/img/2.jpg)

Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.

![Задание2](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/img/3.jpg)

Продемонстрируйте результат.

![Задание2](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/img/4.jpg)

![Задание2](https://github.com/SSitkarev/2.5-k8s-helm/blob/main/img/5.jpg)