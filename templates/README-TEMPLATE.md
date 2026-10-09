<!--
  MODELO DE README — copie este arquivo para o seu projeto como README.md.
  Legenda:  [OBRIGATÓRIO] = nunca deixe de fora  |  [RECOMENDADO]  |  [OPCIONAL]
  Apague todos os comentários <!-- --> e seções opcionais que não se aplicam.
-->

<!-- [OBRIGATÓRIO] Nome + descrição em UMA frase: o que é e para quem serve. -->
<h1 align="center">Nome do Projeto</h1>
<p align="center">Uma frase clara explicando o problema que o projeto resolve.</p>

<!-- [RECOMENDADO] Badges: status do build, versão, licença, tecnologia principal. -->
<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square" alt="Status"/>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="Licença"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET"/>
</p>

<!-- [RECOMENDADO] Sumário — útil quando o README passa de ~4 seções. -->
## 📑 Sumário
- [Sobre](#-sobre)
- [Demonstração](#-demonstração)
- [Tecnologias](#-tecnologias)
- [Como executar](#-como-executar)
- [Uso](#-uso)
- [Estrutura do projeto](#-estrutura-do-projeto)
- [Testes](#-testes)
- [Roadmap](#-roadmap)
- [Como contribuir](#-como-contribuir)
- [Licença](#-licença)
- [Autor](#-autor)

## 📖 Sobre
<!-- [OBRIGATÓRIO] Contexto: qual problema resolve, por que existe, principais funcionalidades. -->
Explique em 2–4 linhas o objetivo do projeto e o problema que ele resolve.

**Principais funcionalidades**
- ✅ Funcionalidade 1
- ✅ Funcionalidade 2
- 🚧 Funcionalidade 3 (em andamento)

## 🎬 Demonstração
<!-- [RECOMENDADO] Print, GIF ou link para o deploy. Um GIF de 10s vale mais que 10 parágrafos. -->
![Demo](docs/demo.gif)

🔗 **Online:** https://seu-projeto.exemplo.com

## 🛠️ Tecnologias
<!-- [OBRIGATÓRIO] O que foi usado, com versões quando importarem. -->
| Camada | Tecnologia |
|---|---|
| Back-end | C# / .NET 9 |
| Front-end | Angular 20 |
| Banco de dados | PostgreSQL 16 |
| Infra | Docker, GitHub Actions |

## 🚀 Como executar
<!-- [OBRIGATÓRIO] Alguém que nunca viu o projeto deve conseguir rodar copiando os comandos. Teste num ambiente limpo. -->

### Pré-requisitos
- [.NET SDK 9+](https://dotnet.microsoft.com/download)
- [Docker](https://www.docker.com/) (opcional)
- Um banco PostgreSQL acessível

### Instalação
```bash
# 1. Clone o repositório
git clone https://github.com/brunogomesc/NOME-DO-REPO.git
cd NOME-DO-REPO

# 2. Configure as variáveis de ambiente
cp .env.example .env

# 3. Restaure as dependências
dotnet restore

# 4. Execute
dotnet run --project src/NomeDoProjeto.Api
```

### Variáveis de ambiente
<!-- [OBRIGATÓRIO se houver configuração] NUNCA coloque valores reais/segredos aqui. -->
| Variável | Descrição | Exemplo |
|---|---|---|
| `ConnectionStrings__Default` | String de conexão do banco | `Host=localhost;Database=app` |
| `JWT__Secret` | Chave de assinatura do token | `<defina-a-sua>` |

## 💡 Uso
<!-- [RECOMENDADO] Exemplos reais: chamadas de API, comandos de CLI, telas principais. -->
```bash
curl -X GET https://localhost:5001/api/recurso
```
Documentação da API (Swagger): `https://localhost:5001/swagger`

## 🗂️ Estrutura do projeto
<!-- [OPCIONAL] Útil em projetos com mais de uma camada/pasta. -->
```
├── src/
│   ├── NomeDoProjeto.Api/
│   ├── NomeDoProjeto.Application/
│   └── NomeDoProjeto.Domain/
├── tests/
└── docs/
```

## ✅ Testes
<!-- [RECOMENDADO] Como rodar os testes. -->
```bash
dotnet test
```

## 🧭 Roadmap
<!-- [OPCIONAL] Mostra que o projeto está vivo. -->
- [x] Versão inicial
- [ ] Autenticação com Keycloak
- [ ] Deploy automatizado

## 🤝 Como contribuir
<!-- [RECOMENDADO para projetos abertos] -->
1. Faça um fork
2. Crie uma branch: `git checkout -b feature/minha-feature`
3. Commit: `git commit -m "feat: minha feature"`
4. Push: `git push origin feature/minha-feature`
5. Abra um Pull Request

## 📄 Licença
<!-- [OBRIGATÓRIO em projetos públicos] Sem licença, ninguém pode legalmente usar seu código. Adicione o arquivo LICENSE. -->
Distribuído sob a licença MIT. Veja [LICENSE](LICENSE).

## 👤 Autor
**Bruno Gomes** — [LinkedIn](https://www.linkedin.com/in/brunog-costa/) · [GitHub](https://github.com/brunogomesc)
