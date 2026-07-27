# Portfólio — Arthur Rian Casagrande

Site pessoal com meu perfil, stack e projetos, focado em análise de dados, automação e desenvolvimento de software.

🔗 **Demo:** https://arthurrc02.github.io/portfolio/

## Sobre

Estudante de Gestão de TI (IFSC — Campus Florianópolis) com experiência prática em organização de dados, planilhas em Excel, modelos de custo e apoio à gestão operacional. Atuo também no desenvolvimento de projetos próprios de engenharia de software e automação, unindo tecnologia, organização e tomada de decisão.

## Estrutura do projeto

```
.
├── index.html          # Página principal (marcação/conteúdo)
├── css/
│   └── style.css       # Estilos do site
├── js/
│   └── main.js         # Animações de entrada (IntersectionObserver)
├── assets/
│   └── images/         # Ícones e imagens do site (favicon, etc.)
├── LICENSE
└── README.md
```

## Tecnologias

- HTML5 semântico
- CSS3 (custom properties, Grid/Flexbox, media queries)
- JavaScript puro (Intersection Observer para animações de scroll)
- [Google Fonts](https://fonts.google.com/) — Sora & Inter

Sem frameworks, sem build step: é só abrir o `index.html` no navegador.

## Como rodar localmente

Como o site é 100% estático, basta abrir o arquivo diretamente:

```bash
git clone https://github.com/arthurrc02/portfolio.git
cd portfolio
```

Depois é só abrir `index.html` no navegador, ou, se preferir um servidor local (recomendado para evitar bloqueios de CORS/caminhos relativos):

```bash
# com Python
python -m http.server 8000

# ou com a extensão Live Server do VS Code
```

E acessar `http://localhost:8000`.

## Projetos em destaque

| Projeto | Descrição | Stack |
|---|---|---|
| [Análise de Cooperados e Inadimplência](https://github.com/arthurrc02/dashboard-transpocred) | Dashboard com 2 páginas analisando 200 cooperados de uma cooperativa de crédito, taxa de inadimplência e concentração de risco. | Power BI · DAX · Excel |
| [Sentinel](https://github.com/arthurrc02/sentinel-monitor) | Plataforma de monitoramento de infraestrutura com agente coletor, API REST e dashboard web. | FastAPI · React · PostgreSQL |

## Deploy (GitHub Pages)

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
3. Salve — o site fica disponível em `https://arthurrc02.github.io/portfolio/` em poucos minutos.

## Contato

- E-mail: [arthurriancasagrande@gmail.com](mailto:arthurriancasagrande@gmail.com)
- LinkedIn: [arthur-rian-casagrande](https://www.linkedin.com/in/arthur-rian-casagrande-b22b71289/)
- GitHub: [@arthurrc02](https://github.com/arthurrc02)

## Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para mais detalhes.
