# Alura Space - Frontend

Este é o front-end do projeto **Alura Space**, uma galeria interativa com as fotos mais incríveis do espaço! Ideal para quem quer explorar imagens de galáxias, nebulosas, estrelas e planetas, com uma interface moderna e responsiva.

## ✨ Funcionalidades

- Busque imagens do espaço por categoria ou palavra-chave.
- Visualize banners e descrições detalhadas de cada imagem.
- Interface intuitiva: design limpo e responsivo para todos os dispositivos.
- Sistema de administração com gerenciamento de ícones (Font Awesome 6.7.2).

## 🚀 Tecnologias Utilizadas

- **HTML, CSS, JavaScript**: Estrutura e dinâmica da interface.
- **Django Templates**: Utilização de templates para renderização de páginas.
- **Font Awesome Free 6.7.2**: Ícones visuais no sistema admin.

## 📁 Estrutura de Pastas

- `static/admin/img/`  
  Ícones SVG utilizados no painel administrativo. Veja o [README](static/admin/img/README.md) para detalhes da licença e como contribuir.
- `static/admin/js/`  
  Scripts JavaScript para funcionalidades do admin (ex: manipulação de selects, URLify).
- `templates/galeria/`  
  Templates HTML das páginas principais, como:
  - `index.html`: Página inicial e principal da galeria.
  - `imagem.html`: Página de detalhe da imagem selecionada.

## 🛠️ Como Rodar o Projeto

1. **Clone este repositório**
   ```bash
   git clone https://github.com/seu-usuario/alura_space-projeto_front.git
   ```
2. **Acesse a pasta do projeto**
   ```bash
   cd alura_space-projeto_front
   ```
3. **Sirva os arquivos estáticos**
   - Você pode usar um servidor local simples, como o Python HTTP server:
     ```bash
     python -m http.server
     ```
   - Ou inserir esses templates em um projeto Django.

4. **Acesse via navegador**
   - Vá até `http://localhost:8000/` (ou a porta configurada).