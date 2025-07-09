# 📦 Evolva Docker

Deploy unificado do **Evolva Panel (frontend)** e **Evolva Core (backend)** utilizando **Docker** e **Docker Compose** em uma VPS.

---

## 🚀 Tecnologias

- 🐳 Docker
- ⚙️ Docker Compose
- 🌐 NGINX (opcional)
- 🔐 Spring Boot (backend)
- 🎨 React + Tailwind (frontend)

---

## 📁 Estrutura do Projeto

```bash
evolva-docker/
├── evolva-core/       # Submódulo Git do backend (Spring Boot)
├── evolva-panel/      # Submódulo Git do frontend (React)
├── docker-compose.yml
├── .env               # Variáveis de ambiente
└── README.md
```

---

## ⚙️ Pré-requisitos

- Git instalado
- Docker e Docker Compose instalados
- Acesso root (ou sudo) à sua VPS

---

## 🔧 Setup Inicial

1. Clone este repositório:
```bash
git clone https://github.com/Eman134/evolva-docker.git
cd evolva-docker
```

2. Adicione os submódulos:
```bash
git submodule add https://github.com/Eman134/evolva-core
git submodule add https://github.com/Eman134/evolva-panel
```

---

## ▶️ Comandos

### 🔨 Build dos containers
```bash
docker-compose build
```

### 🚀 Iniciar os serviços
```bash
docker-compose up -d
```

### 🛑 Parar os serviços
```bash
docker-compose down
```

---

## 🌐 Acesso

- **Frontend:** `http://seu-dominio-ou-ip:3000`
- **Backend:** `http://seu-dominio-ou-ip:8080`

---

## ✨ Autor

- Kayke Emanoel — [GitHub @Eman134](https://github.com/Eman134)
- Projeto principal: [Evolva](https://github.com/Eman134/evolva-panel)
