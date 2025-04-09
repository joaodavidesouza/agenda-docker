# 📅 Agenda Eletrônica

Aplicação Angular para gestão de compromissos, contatos, locais e usuários, com autenticação via JWT e dois perfis de acesso:

- **Usuário comum**: Gerencia seus próprios compromissos e contatos  
- **Administrador**: Acesso total ao sistema (incluindo cadastro de locais e usuários)  

---

## 🧰 Tecnologias

- Angular
- Docker
- Docker Compose
- NGINX
- JSON Server (simulação de API REST)

---

## 🚀 Como rodar o projeto com Docker

### Pré-requisitos

- Docker e Docker Compose instalados
- Git (para clonar o projeto)

### Clonando o projeto

```bash
git clone https://github.com/joaodavidesouza/agenda-docker.git
cd agenda-docker
docker build -t agenda-app . 
docker-compose up –d 
