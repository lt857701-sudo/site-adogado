# Bernstein Advocacia - Landing Page Institucional

Site institucional da Bernstein Advocacia Empresarial, escritório de advocacia especializado em direito empresarial, societário, contratos, contencioso estratégico e planejamento patrimonial.

## Estrutura de Pastas

```
stitch_bernstein_advocacia_institutional_portal/
├── index.html              # Página principal
├── assets/
│   ├── css/
│   │   └── style.css       # Estilos customizados
│   ├── js/
│   │   └── main.js         # Scripts customizados
│   ├── images/
│   │   ├── heroes/         # Imagens de destaque (hero)
│   │   ├── team/           # Fotos da equipe
│   │   ├── icons/          # Ícones
│   │   └── logos/          # Logos
│   ├── fonts/              # Fontes locais (opcional)
│   └── screenshots/        # Capturas de tela do site
├── docs/                   # Documentação
├── .gitignore
└── README.md
```

## Tecnologias

- HTML5 semântico
- Tailwind CSS (via CDN)
- FontAwesome (ícones)
- Google Fonts (Cormorant Garamond, Cinzel, Plus Jakarta Sans)
- JavaScript vanilla

## Como rodar localmente

Abra o arquivo `index.html` diretamente no navegador ou use um servidor local:

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

Em seguida acesse: `http://localhost:8000`

## Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Ative o GitHub Pages nas configurações do repositório
4. O site estará disponível em `https://seu-usuario.github.io/seu-repositorio/`

## Licença

Privado - Bernstein Advocacia
