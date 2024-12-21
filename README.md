## 🌐 [English Version of README](README_EN.md)

# Organo

Organo é uma aplicação desenvolvida em React que permite a criação e organização de cards de colaboradores em diferentes times.

## 🔨 Funcionalidades do Projeto

- Adicionar colaboradores a times específicos.
- Exibir times com cores personalizadas.
- Interface responsiva e amigável.

### Exemplo Visual do Projeto

![chrome-capture-2024-12-21](https://github.com/user-attachments/assets/91d47dad-689f-4278-a736-3252c64265ae)

## ✔️ Técnicas e Tecnologias Utilizadas

- **React** para criação de componentes e gerenciamento do estado.
- **CSS** para estilização personalizada.
- **HTML** para estrutura básica.
- **JavaScript (ES6+)** para lógica e funcionalidade.

## 📁 Estrutura do Projeto

- **public/**
    - favicon.ico: Ícone do site.
    - index.html: Arquivo HTML principal.
    - manifest.json: Metadados do app para navegadores e PWA.
    - robots.txt: Arquivo para direções de crawlers.
    - **imagens/**
        - banner.png: Banner principal do site.
        - logo192.png: Logo em alta resolução.
        - logo512.png: Logo maior para dispositivos.

- **src/**
    - App.js: Componente principal que integra os demais.
    - index.js: Ponto de entrada do projeto.
    - **componentes/**
        - **Banner/**: Componente para o banner principal.
        - **Botao/**: Componente reutilizável para botões.
        - **CampoTexto/**: Componente de campo de entrada de texto.
        - **Colaborador/**: Componente que exibe informações de um colaborador.
        - **Formulario/**: Formulário para adicionar novos colaboradores.
        - **ListaSuspensa/**: Componente de seleção de opções.
        - **Rodape/**: Rodapé do site.
        - **Time/**: Componente que organiza os cards dos colaboradores.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:

```bash
node -v
```

- Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

```bash
git clone <URL_DO_REPOSITORIO>
```

3. **Instale as dependências**:
    - Acesse a pasta do projeto e execute:

```bash
npm install
```

4. **Inicie o servidor de desenvolvimento**:
    - Para rodar o projeto, utilize o comando:

```bash
npm start
```

- O projeto será iniciado em [http://localhost:3000](http://localhost:3000).

## 🌐 Deploy

Para realizar o deploy do projeto, siga estas etapas:

1. **Compile o projeto para produção**:

```bash
npm run build
```

2. **Hospede os arquivos gerados**:
    - Os arquivos serão gerados na pasta `build/`. Eles podem ser hospedados em serviços como [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/) ou [GitHub Pages](https://pages.github.com/).

3. **Configure o servidor**:
    - Certifique-se de que o servidor está configurado para servir o arquivo `index.html` para todas as rotas.


