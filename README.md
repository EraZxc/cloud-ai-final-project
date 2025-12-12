# Cloud-Native AI Application Deployment (Yandex Cloud)

Структура проекта:

project-repo/
├── terraform/
│ ├── modules/
│ │ ├── network/
│ │ ├── bucket/
│ │ └── function/
│ ├── envs/
│ │ └── dev/
├── src/
│ ├── backend/
│ └── frontend/
└── docs/

Проект создаётся для деплоя AI-приложения с использованием:
- Yandex Cloud
- Yandex GPT
- Terraform
- Cloud Functions
- Object Storage