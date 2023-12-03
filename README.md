# prompts# Опис маніфестів Kubernetes

| NAME                       | PROMPT                 | DESCRIPTION                   | EXAMPLE                                      |
|----------------------------|------------------------|-------------------------------|----------------------------------------------|
| app.yaml                   | Кореневий маніфест     | Основний маніфест додатка     | [app.yaml](./yaml/app.yaml)                  |
| app-livenessProbe.yaml      | Create a manifest with aLiveness Probe         | Налаштування livenessProbe   | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml     | Create a manifest with a Readiness Probe        | Налаштування readinessProbe  | [app-readinessProbe.yaml](./yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml       | Create a manifest with Volume Mounts          | Налаштування volumeMounts    | [app-volumeMounts.yaml](./yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml            | Create a CronJob that runs every hour and tells time               | Крон-задача                  | [app-cronjob.yaml](./yaml/app-cronjob.yaml)    |
| app-job.yaml                | Create a job that does something useful on a cluster                    | Задача                       | [app-job.yaml](./yaml/app-job.yaml)          |
| app-multicontainer.yaml     | Creatr a pod with multiple containers     | Под з декількома контейнерами| [app-multicontainer.yaml](./yaml/app-multicontainer.yaml) |
| app-resources.yaml          | Create a deployment with resources  | Вимоги до ресурсів           | [app-resources.yaml](./yaml/app-resources.yaml) |
| app-secret-env.yaml         | Create a secret environment | Використання секретів як змінних оточення | [app-secret-env.yaml](./yaml/app-secret-env.yaml) |
