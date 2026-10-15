# Виталий · DevOps (практика)

**Формат:** удалённо · частичная занятость · совместительство  
**Локация:** Россия, Республика Саха (Якутия)  
**GitHub:** [@x-optima](https://github.com/x-optima) · **Портфолио:** [Netology-DevOps](https://github.com/x-optima/Netology-DevOps)

С июля 2025 — DevOps: курс Нетологии и стенды в Yandex Cloud.

Ищу удалённую команду в формате совместительства: Terraform, Ansible, CI, мониторинг на ВМ.

[Telegram](https://t.me/kuchinvn) · [почта](mailto:vkuchin-home@yandex.ru) · [Max](https://set.ki/5wVk9Nj)

---

## Профиль

| | |
|---|---|
| **Формат** | удалёнка, частичная занятость, совместительство |
| **Фокус** | IaC, Linux, CI/CD, observability, PostgreSQL, HA/backup |
| **Облако** | Yandex Cloud: сеть → ВМ → сервис → мониторинг |
| **Подход** | инфраструктура как код, воспроизводимые учебные стенды |
| **Портфолио** | [Netology-DevOps](https://github.com/x-optima/Netology-DevOps) — каталог ДЗ курса |

---

## Опыт

**2025 – н.в. · Нетология, практика DevOps**  
Программа «DevOps-инженер с нуля: расширенный курс». Стенды в Yandex Cloud: сеть, ВМ, IaC, CI/CD, мониторинг, логи, БД.

---

## Стек со стендов

| Область | Технологии |
|---------|------------|
| Cloud / IaC | Yandex Cloud, Terraform, Ansible |
| CI/CD | GitLab CI, TeamCity, Jenkins, GitHub Actions |
| Containers / Orchestration | Docker, Compose, Kubernetes (MicroK8s), HAProxy, Keepalived |
| Observability | Prometheus, Grafana, Zabbix, ELK, Filebeat, Vector, Alertmanager |
| Data | PostgreSQL, MySQL, Redis, RabbitMQ, ClickHouse |
| OS / Scripting | Linux (Debian/Ubuntu), Bash, Python |
| API / Microservices | NGINX (API Gateway), Flask, REST |

---

## Ключевые проекты

Репозитории курса — домашние работы и учебные стенды.

### Kubernetes

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [kubernetes1](https://github.com/x-optima/kubernetes1) | MicroK8S, kubectl, установка, dashboard | Kubernetes · MicroK8s · kubectl |
| [kubernetes2](https://github.com/x-optima/kubernetes2) | Pod, Service, port-forward, развёртывание | Kubernetes · Pods · Services |
| [kubernetes3](https://github.com/x-optima/kubernetes3) | Deployment, Service, init-контейнеры, масштабирование | Kubernetes · Deployments · Init Containers |
| [kubernetes4](https://github.com/x-optima/kubernetes4) | ClusterIP, NodePort, Ingress, сетевое взаимодействие | Kubernetes · Ingress · Networking |
| [kubernetes5](https://github.com/x-optima/kubernetes5) | emptyDir, PersistentVolume, PVC, StorageClass | Kubernetes · Volumes · Storage |
| [kubernetes6](https://github.com/x-optima/kubernetes6) | ConfigMaps, Secrets, RBAC: конфигурация приложений и доступ | Kubernetes · ConfigMap · Secrets · RBAC |
| [kubernetes7](https://github.com/x-optima/kubernetes7) | Helm-чарт для деплоя приложения в MicroK8s | Kubernetes · Helm |
| [kubernetes8](https://github.com/x-optima/kubernetes8) | Развёртывание многокомпонентного приложения: БД + сервисы, ресурсы | Kubernetes · Deployments · Services |
| [kubernetes9](https://github.com/x-optima/kubernetes9) | Установка кластера k8s: 1 master + 4 worker (Ubuntu) | Kubernetes · установка кластера |
| [kubernetes10](https://github.com/x-optima/kubernetes10) | Сетевые политики; развёртывание кластера в Cloud.ru / Yandex Cloud | Kubernetes · NetworkPolicy · Terraform |

### Terraform

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [terraform1](https://github.com/x-optima/terraform1) | Базовый стенд в YC: deploy.sh, сеть и ВМ | Terraform · YC · Bash |
| [terraform2](https://github.com/x-optima/terraform2) | Переменные, locals, outputs, NAT, платформы ВМ | Terraform · YC |
| [terraform3](https://github.com/x-optima/terraform3) | count/for_each, шаблоны tftpl, диски, security groups | Terraform · YC |
| [terraform4](https://github.com/x-optima/terraform4) | Модули и окружения, cloud-init | Terraform · YC · cloud-init |
| [terraform5](https://github.com/x-optima/terraform5) | Практические задания (zadanie1, zadanie2) | Terraform · YC |
| [terraform6](https://github.com/x-optima/terraform6) | Итоговый стенд в YC: FastAPI в Docker, Managed MySQL, секреты в Lockbox, remote state | Terraform · YC · Lockbox · Ansible · Container Registry |

### Ansible

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [ansible1](https://github.com/x-optima/ansible1) | Занятие 1 — заготовка (репозиторий пуст) | Ansible |
| [ansible2](https://github.com/x-optima/ansible2) | Занятие 2 — заготовка (репозиторий пуст) | Ansible |
| [ansible3](https://github.com/x-optima/ansible3) | Стек ClickHouse + Vector + LightHouse, playbook в YC | Ansible · ClickHouse · Vector · LightHouse · YC |
| [ansible4](https://github.com/x-optima/ansible4) | Playbook из ansible3 разбит на roles | Ansible · roles |
| [ansible5](https://github.com/x-optima/ansible5) | Занятие 5 — заготовка (репозиторий пуст) | Ansible |
| [vector-role](https://github.com/x-optima/vector-role) | Роль Vector: установка из .deb, отправка логов в ClickHouse | Ansible · Vector · ClickHouse |
| [lighthouse-role](https://github.com/x-optima/lighthouse-role) | Роль LightHouse: Nginx + статика, прокси /clickhouse/ | Ansible · Nginx · LightHouse |

### CI/CD и Git

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [gitlab-yc](https://github.com/x-optima/gitlab-yc) | GitLab в Docker на ВМ в YC: Terraform + Ansible | GitLab · Terraform · Ansible · YC |
| [teamcity](https://github.com/x-optima/teamcity) | TeamCity + агент + Nexus в YC: Maven test/deploy по ветке | TeamCity · Nexus · Terraform · Ansible · YC |
| [jenkins-dz1](https://github.com/x-optima/jenkins-dz1) | Материалы к ДЗ блока «Введение в DevOps» (CI/CD) | CI/CD · Jenkins |
| [github-hw](https://github.com/x-optima/github-hw) | ДЗ по GIT: форк, переименование, коммиты | Git · GitHub |
| [github-hw2](https://github.com/x-optima/github-hw2) | ДЗ «Что такое DevOps? CI/CD» | DevOps · CI/CD |
| [github-hw3](https://github.com/x-optima/github-hw3) | Заготовка ДЗ (репозиторий пуст) | Git |
| [github-hw4](https://github.com/x-optima/github-hw4) | Шаблон ДЗ (fork Netology) | Git · GitHub |
| [git1](https://github.com/x-optima/git1) | Системы контроля версий: подготовка репозитория | Git |
| [git3](https://github.com/x-optima/git3) | Ветвления: merge и rebase | Git · branching |
| [new-repo](https://github.com/x-optima/new-repo) | Тестовый репозиторий | Git |

### Мониторинг и логи

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [monitoring](https://github.com/x-optima/monitoring) | Zabbix на ВМ в YC: Terraform + Ansible | Zabbix · Terraform · Ansible · YC |
| [monitoring2](https://github.com/x-optima/monitoring2) | Шаблон ДЗ (fork Netology) | Prometheus · Grafana |
| [monitoring3](https://github.com/x-optima/monitoring3) | Шаблон ДЗ (fork Netology) | Prometheus · Grafana |
| [monitoring4](https://github.com/x-optima/monitoring4) | Prometheus, Grafana, Node Exporter, Alertmanager на ВМ в YC | Prometheus · Grafana · Terraform · Ansible · YC |
| [apm](https://github.com/x-optima/apm) | Мониторинг парка спецтехники: метрики, дашборды, алерты | Prometheus · Grafana · MQTT · Alertmanager · Docker Compose |
| [monlog1](https://github.com/x-optima/monlog1) | Системы мониторинга: практика sandbox, awesome-monitoring | Prometheus · Grafana |
| [monlog2](https://github.com/x-optima/monlog2) | Grafana + Prometheus + Node Exporter, алерты | Prometheus · Grafana · Node Exporter |
| [monlog3](https://github.com/x-optima/monlog3) | Elastic Stack 8.x: hot/warm ES, Logstash, Kibana, Filebeat | Elasticsearch · Logstash · Kibana · Filebeat · Docker |
| [elk](https://github.com/x-optima/elk) | ELK на ВМ в YC: Terraform + Ansible, централизованный сбор логов | ELK · Elasticsearch · Kibana · YC |

### Базы данных

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [database](https://github.com/x-optima/database) | ДЗ по базам данных (database-dz1) | PostgreSQL |
| [database1](https://github.com/x-optima/database1) | Проектирование БД: create_employee_db.sql, ER-диаграмма | PostgreSQL · проектирование |
| [database2](https://github.com/x-optima/database2) | ДЗ по БД + окружение mysql-dev | MySQL · PostgreSQL |
| [sql1](https://github.com/x-optima/sql1) | ДЗ по SQL (sql1-dz) | SQL |
| [sql2](https://github.com/x-optima/sql2) | ДЗ по SQL (sql2-dz) | SQL |
| [indexes](https://github.com/x-optima/indexes) | Индексы БД: ДЗ (indexes-dz) | SQL · indexes |
| [replica1](https://github.com/x-optima/replica1) | Master-slave репликация MySQL (mysql-slave) | MySQL · replication |
| [replica2](https://github.com/x-optima/replica2) | Репликация БД (replica2-dz, sql) | MySQL · replication |
| [dbbackup](https://github.com/x-optima/dbbackup) | Стратегии backup PostgreSQL: pg_dump, PITR, cron | PostgreSQL · backup |
| [dbcloud](https://github.com/x-optima/dbcloud) | БД в облаке — заготовка (репозиторий пуст) | PostgreSQL · YC |
| [rabbitmq](https://github.com/x-optima/rabbitmq) | RabbitMQ: producer/consumer на Python + playbook | RabbitMQ · Python · Ansible |
| [cache](https://github.com/x-optima/cache) | Кэширование Redis + playbook (cache-dz1) | Redis · cache · Ansible |

### Виртуализация и сеть

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [virt1](https://github.com/x-optima/virt1) | Введение в виртуализацию | KVM · виртуализация |
| [virt2](https://github.com/x-optima/virt2) | Занятие 2 — заготовка (репозиторий пуст) | виртуализация |
| [virt3](https://github.com/x-optima/virt3) | Docker Compose: оркестрация группой контейнеров | Docker Compose |
| [virt4](https://github.com/x-optima/virt4) | FastAPI-приложение для изучения Docker Compose | FastAPI · Docker Compose |
| [cluster](https://github.com/x-optima/cluster) | HAProxy + два backend-сервиса, round-robin | HAProxy · Ansible · Terraform · YC |
| [cloud_balancer](https://github.com/x-optima/cloud_balancer) | Балансировка в облаке: loadbalancer.tf + playbook | HAProxy · Terraform · Ansible · YC |
| [rsync](https://github.com/x-optima/rsync) | Синхронизация файлов через rsync + cron | rsync · cron |
| [disaster1](https://github.com/x-optima/disaster1) | Отказоустойчивость сети: HSRP (Packet Tracer) | HSRP · сеть · DR |
| [protecthost](https://github.com/x-optima/protecthost) | Защита хоста: ДЗ (protecthost-dz) | Linux · security |

### API и микросервисы

| Проект | Что сделано | Навыки |
|--------|-------------|--------|
| [microservices1](https://github.com/x-optima/microservices1) | Микросервисы: принципы, API Gateway на NGINX + Compose | Docker Compose · NGINX · микросервисы |
| [microservices2](https://github.com/x-optima/microservices2) | API Gateway: nginx + security (Flask) + uploader (Node.js) + MinIO, метрики Prometheus | NGINX · Flask · Node.js · MinIO · Prometheus |
| [pobeda_practice1](https://github.com/x-optima/pobeda_practice1) | Flask-приложение, SQLite, REST API /users | Python · Flask · SQLite |
| [tivali-api-tests](https://github.com/x-optima/tivali-api-tests) | pytest для /posts JSONPlaceholder: GET/POST/PUT/DELETE | Python · pytest · API testing |
| [kursovoy_site](https://github.com/x-optima/kursovoy_site) | Курсовой сайт + мониторинг (Prometheus, Grafana, Alertmanager) | Web · Prometheus · Grafana · Ansible |
| [devops-cases1](https://github.com/x-optima/devops-cases1) | Кейсы — заготовка (репозиторий пуст) | DevOps |
| [ib1](https://github.com/x-optima/ib1) | Информационная безопасность: сканы портов, эксплуатация vsftpd | ИБ · Python · nmap |
| [x-optima-my_own_collection](https://github.com/x-optima/x-optima-my_own_collection) | Ansible Collection: собственные модули, стек ELK в YC | Ansible · Collection · ELK · YC |

→ Полный каталог: **[Netology-DevOps](https://github.com/x-optima/Netology-DevOps)**

---

## English

DevOps training + Yandex Cloud labs since July 2025. Part-time, remote. Best repo: [terraform6](https://github.com/x-optima/terraform6).

---

## Контакт

- Email: [vkuchin-home@yandex.ru](mailto:vkuchin-home@yandex.ru)
- Telegram: [@kuchinvn](https://t.me/kuchinvn)
- Max: [set.ki/5wVk9Nj](https://set.ki/5wVk9Nj)
- GitHub: [github.com/x-optima](https://github.com/x-optima)
