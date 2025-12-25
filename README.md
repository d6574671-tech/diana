# Diana Project: Infrastructure Automation

## 1. Басқару әдістемесі (Management)
* **Scrum**: 2 апталық спринттер арқылы икемді даму.
* **Рөлдер**: PM, Backend (Go), Frontend (Next.js), DevOps Engineer.
* **Тақта**: [GitHub Projects сілтемесін осында қойыңыз]

## 2. Архитектуралық схема
Жоба Cloud-Native концепциясына негізделген.
* **Frontend**: Next.js (Vercel/Docker)
* **Backend**: Go API (Docker)
* **Database**: PostgreSQL (Managed service)

## 3. CI/CD Процесі (GitHub Actions)
1. **Push**: Код GitHub-қа түседі.
2. **Test**: Unit-тесттер мен Linter іске қосылады.
3. **Build**: Docker бейнесі жиналады.
4. **Deploy**: Terraform арқылы бапталған серверге автоматты түрде жүктеледі.

## 4. Жол картасы (Roadmap)
| Кезең | Тапсырма | Нәтиже |
|-------|----------|--------|
| 1-апта | Инфрақұрылым (IaC) | Terraform & Docker файлдары дайын |
| 2-апта | Backend & DB | API интерфейсі мен МБ байланысы |
| 3-апта | Автоматтандыру | CI/CD пайплайны мен Grafana мониторингі |
