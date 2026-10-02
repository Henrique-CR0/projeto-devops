# Projeto DevOps - Prática Integrada (Aulas 07 e 08)

Ambiente integrado com Dockerfile, Docker Compose e GitHub Actions.

## Serviços Utilizados
- **Aplicação Web (app)**: Porta 8080 (construída a partir do Dockerfile com Nginx Alpine)
- **phpMyAdmin**: Porta 8081
- **MySQL 8**: Comunicação interna via rede do Compose

## Comandos de Execução
- Iniciar e compilar ambiente: `docker compose up -d --build`
- Verificar status: `docker compose ps`
- Parar e remover ambiente: `docker compose down`
