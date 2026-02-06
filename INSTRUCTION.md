Зробити fork репозиторію та клонувати його локально.

Запустити кластер за допомогою kind:
kind create cluster --config cluster.yml

Запустити скрипт деплою:
./bootstrap.sh

Перевірити, що pod застосунку запущений:
kubectl get pods

Перевірити, що Ingress Controller працює:
kubectl get pods -n ingress-nginx

Перевірити створення Ingress:
kubectl get ingress

Відкрити в браузері:
http://localhost

Переконатися, що застосунок відкривається та в консолі браузера немає 404 помилок.