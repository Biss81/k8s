# Лабараторная работа по теме Kubernetes

Репозиторий предназначен для разверывания приложения simple-todo с исползованием базы данных MongoDB в Kubernetes.
Приложение публикуется через NodePort на порту 30010

### Разворачиваем приложение в Kubernetes:

```bash
git clone https://github.com/Biss81/k8s.git
cd k8s
kubectl apply -f deploy/
```
