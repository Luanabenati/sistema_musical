<div align="center">

<img src="assets/banner.svg" alt="Sistema Musical — catálogo de artistas e músicas" width="100%">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=3498DB&center=true&vCenter=true&width=720&height=48&lines=Cadastre+artistas+%F0%9F%8E%A4;Cadastre+m%C3%BAsicas+%F0%9F%8E%B5;Filtre+tudo+na+Biblioteca+Musical+%F0%9F%8E%BC;Funciona+no+computador+e+no+celular+%F0%9F%93%B1" alt="Cadastre artistas, cadastre músicas, filtre na biblioteca, funciona no computador e no celular"></a>

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/Responsivo-Desktop_+_Celular-27ae60?style=for-the-badge&logo=googlechrome&logoColor=white)
![Telas](https://img.shields.io/badge/Telas-5-3498db?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-0-2c3e50?style=for-the-badge&logo=javascript&logoColor=white)
![Status](https://img.shields.io/badge/Front--end-Conclu%C3%ADdo-27ae60?style=for-the-badge)

<br>

[![Telas](https://img.shields.io/badge/📺_Telas-2c3e50?style=flat-square)](#-as-5-telas)
[![Navegação](https://img.shields.io/badge/🧭_Navegação-2c3e50?style=flat-square)](#-mapa-de-navegação)
[![Paleta](https://img.shields.io/badge/🎨_Paleta-2c3e50?style=flat-square)](#-paleta-de-cores)
[![Responsivo](https://img.shields.io/badge/📱_Responsivo-2c3e50?style=flat-square)](#-responsividade)
[![Como abrir](https://img.shields.io/badge/▶️_Como_abrir-2c3e50?style=flat-square)](#%EF%B8%8F-como-abrir-o-projeto)
[![Estrutura](https://img.shields.io/badge/📁_Estrutura-2c3e50?style=flat-square)](#-estrutura-do-repositório)
[![Equipe](https://img.shields.io/badge/👥_Equipe-2c3e50?style=flat-square)](#-equipe)

</div>

<img src="assets/divider.svg" width="100%" alt="">

## 🎶 Sobre o projeto

O **Sistema Musical** é o front-end de um **catálogo de músicas**: você cadastra **artistas**, cadastra as **músicas** de cada um e consulta tudo numa **biblioteca com filtros**.

Esta etapa entrega somente a **interface** (HTML + CSS): cinco telas ligadas por links, formulários com validação nativa do navegador e um layout que se ajusta sozinho ao computador e ao celular.

<div align="center">

| 🎯 Tema | 🎤 Criador | 🎵 Obra | 🏫 Disciplina |
|:---:|:---:|:---:|:---:|
| **Música** | **Artista** | **Música** | **Aulas 11, 12, 13 e 14** |

</div>

<img src="assets/divider.svg" width="100%" alt="">

## ✨ Destaques

<table>
<tr>
<td align="center" width="33%">

### 🎨
**Um único `styles.css`**

Todas as telas compartilham a mesma folha de estilos, organizada em seções numeradas.

</td>
<td align="center" width="33%">

### 🧩
**Paleta no `:root`**

Cores, sombras, raio de borda e fonte viram variáveis CSS. Mudou uma, mudou o site todo.

</td>
<td align="center" width="33%">

### 📱
**Pensado para o celular**

Menu, formulários, filtros e tabelas se reorganizam em telas pequenas.

</td>
</tr>
<tr>
<td align="center">

### ✅
**Validação nativa**

`required`, `maxlength` e `accept` barram campos vazios e arquivos errados.

</td>
<td align="center">

### 🛡️
**Confirmação ao excluir**

Todo botão 🗑️ pergunta antes de enviar. Nada some por acidente.

</td>
<td align="center">

### 🧱
**Pronto para o back-end**

`method`, `action`, `enctype` e campos ocultos (`acao`, `id`) já estão no lugar.

</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## 📺 As 5 telas

> 💡 Clique em **“Campos e regras”** para abrir os detalhes de cada tela.

<table>
<tr>
<td align="center" width="50%">

**1️⃣ Login** · `login.html`

<img src="prints/login.png" alt="Tela de login" width="100%">

</td>
<td align="center" width="50%">

**2️⃣ Menu principal** · `index.html`

<img src="prints/index.png" alt="Menu principal" width="100%">

</td>
</tr>
<tr>
<td align="center">

**3️⃣ Cadastro do criador** · `cadastro_artista.html`

<img src="prints/cadastro_artista.png" alt="Cadastro de artistas" width="100%">

</td>
<td align="center">

**4️⃣ Cadastro da obra** · `cadastro_musica.html`

<img src="prints/cadastro_musica.png" alt="Cadastro de músicas" width="100%">

</td>
</tr>
<tr>
<td align="center" colspan="2">

**5️⃣ Listagem** · `listagem_musicas.html`

<img src="prints/listagem_musicas.png" alt="Biblioteca musical com filtros" width="70%">

</td>
</tr>
</table>

### 🔐 Tela 1 — Login

Cartão centralizado com **usuário** e **senha** (os dois obrigatórios) e uma dica com as credenciais iniciais.

<details>
<summary><b>📋 Campos e regras</b></summary>

<br>

| Campo | Tipo | Regra | Valor inicial |
|---|---|---|---|
| 👤 Usuário | texto | obrigatório | `admin` |
| 🔑 Senha | senha | obrigatório | `123` |

</details>

### 🏠 Tela 2 — Menu principal

Painel com **contadores** de artistas e músicas, três **cards de navegação** e o botão **🚪 Sair**.

<details>
<summary><b>📋 Cards e destinos</b></summary>

<br>

| Card | Descrição | Leva para |
|---|---|---|
| 🎤 Gerenciar Artistas | Cadastre, edite e consulte artistas | `cadastro_artista.html` |
| 🎵 Cadastrar Músicas | Adicione músicas e capas de álbuns | `cadastro_musica.html` |
| 🎼 Biblioteca Musical | Consulte e filtre todas as músicas | `listagem_musicas.html` |

</details>

### 🎤 Tela 3 — Cadastro do criador (artista)

Formulário em **duas colunas** e, logo abaixo, a tabela dos artistas cadastrados. O botão de excluir fica **desabilitado** enquanto o artista tiver músicas vinculadas.

<details>
<summary><b>📋 Campos e regras</b></summary>

<br>

| Campo | Tipo | Regra |
|---|---|---|
| Nome do Artista `*` | texto | obrigatório · até 100 caracteres |
| Gênero Musical | texto | até 50 caracteres |
| País | texto | até 50 caracteres |
| Foto do Artista | arquivo | JPG ou PNG · máx. 5 MB |

**Tabela:** foto, nome, gênero, país, nº de músicas e ações (✏️ Editar · 🎵 Músicas · 🗑️ Excluir).

</details>

### 🎵 Tela 4 — Cadastro da obra (música)

Formulário para registrar uma música e vinculá-la a um artista.

<details>
<summary><b>📋 Campos e regras</b></summary>

<br>

| Campo | Tipo | Regra |
|---|---|---|
| Título da Música `*` | texto | obrigatório · até 120 caracteres |
| Artista `*` | lista de seleção | obrigatório |
| Álbum | texto | até 100 caracteres |
| Gênero Musical | texto | até 50 caracteres |
| Link do YouTube | URL | precisa ser um endereço válido |
| Capa do Álbum | arquivo | JPG ou PNG · máx. 5 MB |
| Letra da Música | área de texto | opcional · ocupa as 2 colunas |

</details>

### 🎼 Tela 5 — Listagem (Biblioteca Musical)

Filtros no topo e tabela com todas as músicas.

<details>
<summary><b>📋 Filtros e colunas</b></summary>

<br>

- 🔍 **Busca geral** por título, álbum ou artista
- 🎤 Filtro por **artista** · 🎼 filtro por **gênero**
- 🧹 Botões **Filtrar** e **Limpar**
- ➕ Atalho **Nova Música** no topo

| Coluna | O que mostra |
|---|---|
| Capa | imagem do álbum |
| Título · Artista · Álbum · Gênero | dados da música |
| YouTube | link para assistir |
| Ações | ✏️ Editar · 🗑️ Excluir |

</details>

<img src="assets/divider.svg" width="100%" alt="">

## 🧭 Mapa de navegação

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#3498db','primaryTextColor':'#ffffff','primaryBorderColor':'#2980b9','lineColor':'#2c3e50','fontFamily':'Segoe UI'}}}%%
flowchart LR
    L(["🔐 login.html"]):::login -.->|após autenticar| M(["🏠 index.html<br/>Menu"]):::menu
    M --> A(["🎤 cadastro_artista.html"]):::tela
    M --> C(["🎵 cadastro_musica.html"]):::tela
    M --> B(["🎼 listagem_musicas.html"]):::tela
    A --> C
    B --> C
    C --> B
    A --> M
    B --> M
    C --> M

    classDef login fill:#2c3e50,stroke:#1a252f,color:#fff,stroke-width:2px;
    classDef menu fill:#27ae60,stroke:#1e8449,color:#fff,stroke-width:2px;
    classDef tela fill:#3498db,stroke:#2980b9,color:#fff,stroke-width:2px;
```

<sub>Linha tracejada = ligação que depende do back-end (veja [Escopo desta entrega](#-escopo-desta-entrega)).</sub>

<img src="assets/divider.svg" width="100%" alt="">

## 🎨 Paleta de cores

Todas as cores moram no `:root` do `styles.css`. Mudou a variável, mudou o site inteiro. 🪄

<img src="assets/palette.svg" alt="Paleta de cores do Sistema Musical" width="100%">

```css
:root {
    --primary:     #2c3e50;   /* títulos, cabeçalho da tabela, botão Voltar */
    --blue:        #3498db;   /* botão principal, editar, foco dos campos   */
    --blue-dark:   #2980b9;   /* hover dos botões azuis                     */
    --green:       #27ae60;   /* botão Músicas, mensagem de sucesso         */
    --red:         #e74c3c;   /* botão excluir, asterisco de obrigatório    */
    --red-dark:    #c0392b;   /* hover do botão excluir                     */
    --bg:          #f0f2f5;   /* fundo das páginas                          */
    --surface:     #ffffff;   /* cards, formulários e tabelas               */
    --border:      #dde1e7;   /* bordas e divisórias                        */
    --text-muted:  #6c757d;   /* textos de apoio                            */
    --radius:      8px;       /* cantos arredondados                        */
    --font:        'Segoe UI', system-ui, -apple-system, sans-serif;
}
```

<img src="assets/divider.svg" width="100%" alt="">

## 📱 Responsividade

<table>
<tr>
<th align="center">🖥️ Acima de 768px</th>
<th align="center">📱 Até 768px</th>
<th align="center">📱 Até 600px</th>
</tr>
<tr>
<td valign="top">

- Formulários em **2 colunas**
- Filtros **lado a lado**
- Menu com cards em **grade**

</td>
<td valign="top">

- Formulários em **1 coluna**
- Filtros **empilhados**
- Menu em **coluna única**
- Botões de ação menores
- Tabelas com **rolagem horizontal**

</td>
<td valign="top">

- Contadores do menu em **2 colunas**
- Filtro de artista em **largura total**

</td>
</tr>
</table>

> 🔎 **Testar o modo celular:** abra a página, aperte `F12`, clique no ícone de dispositivos (ou `Ctrl + Shift + M`) e escolha um celular.

<img src="assets/divider.svg" width="100%" alt="">

## 🛠️ Tecnologias

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-Estrutura_semântica-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Flexbox_·_Grid_·_Variáveis-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-Versionamento-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório_público-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

Sem frameworks e sem bibliotecas. Nesta fase, a única interação extra é o `confirm()` nativo do botão excluir.

<img src="assets/divider.svg" width="100%" alt="">

## ▶️ Como abrir o projeto

<details open>
<summary><b>⚡ Opção 1 — Direto no navegador (mais simples)</b></summary>

<br>

1. Baixe ou clone o repositório
2. Dê dois cliques em **`login.html`**
3. Navegue pelas telas usando os links e botões

</details>

<details>
<summary><b>💻 Opção 2 — Clonando com Git</b></summary>

<br>

```bash
git clone https://github.com/SEU-USUARIO/musica-vinycius.git
cd musica-vinycius
```

Depois é só abrir o `login.html` no navegador.

</details>

<details>
<summary><b>🌐 Opção 3 — Online com GitHub Pages</b></summary>

<br>

1. No repositório, vá em **Settings → Pages**
2. Em *Branch*, escolha `main` e a pasta `/ (root)`
3. Salve e aguarde o link de publicação aparecer

</details>

> ⚠️ Como ainda não há back-end, o botão **Entrar** não redireciona sozinho. Para continuar, abra o `index.html`.

<img src="assets/divider.svg" width="100%" alt="">

## 📁 Estrutura do repositório

```text
📦 musica-vinycius
 ┣ 📄 login.html              → Tela 1 · login
 ┣ 📄 index.html              → Tela 2 · menu principal
 ┣ 📄 cadastro_artista.html   → Tela 3 · cadastro do criador (artista)
 ┣ 📄 cadastro_musica.html    → Tela 4 · cadastro da obra (música)
 ┣ 📄 listagem_musicas.html   → Tela 5 · biblioteca com filtros
 ┣ 🎨 styles.css              → único arquivo de estilos (paleta no :root)
 ┣ 📂 prints/                 → capturas de tela das páginas
 ┣ 📂 assets/                 → banner, divisor e paleta animados do README
 ┗ 📘 README.md               → você está aqui
```

<details>
<summary><b>🧱 Como o <code>styles.css</code> está organizado</b></summary>

<br>

| Seção | Conteúdo |
|:---:|---|
| 1 | Variáveis (`:root`) e *reset* |
| 2 | Formulários (campos, rótulos, foco) |
| 3 | Botões (primário, voltar, editar, excluir, músicas, YouTube) |
| 4 | Mensagens de sucesso e erro |
| 5 | Tela de login |
| 6 | Layout base (`.container`) |
| 7 | Menu principal |
| 8 | Tipografia (`h2`, `h3`) |
| 9 | Cabeçalho de página com ações |
| 10 | Formulário em grade de 2 colunas |
| 11 | Tabelas |
| 14 | Filtros |
| 15 | Utilitários (`.mt-1`, `.mb-2`, `.text-center`…) |
| 16 | Responsividade (`@media`) |
| 17 | Elementos adicionais (contadores, botões desabilitados, formulários em linha) |

</details>

<img src="assets/divider.svg" width="100%" alt="">

## ✅ Checklist da atividade

| | Requisito |
|:---:|---|
| ✅ | 🖥️ As 5 telas: login, menu, cadastro do criador, cadastro da obra e listagem |
| ✅ | 🎨 Um único `styles.css` com a paleta no `:root` |
| ✅ | 📱 Funcionando no computador e no celular |
| ✅ | 👥 Nome dos integrantes em comentário no topo do `login.html` |
| ✅ | 📤 Arquivos soltos na raiz do repositório (sem `.zip`) |
| ✅ | 🔓 Repositório público |

<details>
<summary><b>🔎 Roteiro de testes</b></summary>

<br>

1. Abrir o `login.html`
2. Navegar por todas as telas pelos links
3. Tentar cadastrar com **campo vazio**. O navegador deve bloquear e avisar o campo obrigatório
4. Abrir no **modo celular** (`F12`) e conferir se nada quebra

</details>

<img src="assets/divider.svg" width="100%" alt="">

## 🧭 Escopo desta entrega

Esta é a **fase de front-end**. Por isso:

- 📝 Os dados das tabelas (Djavan, Marisa Monte, “Título da Música”…) são **exemplos fixos**, só para mostrar o visual
- 🔗 Os formulários estão **preparados** para um back-end, mas ainda não salvam nada
- 🚪 O botão **Sair** aponta para `logout.php`, que será criado na fase de back-end
- 🔐 A autenticação do login vem na próxima etapa

### 🚀 Próximos passos

- [ ] Back-end para salvar artistas e músicas
- [ ] Autenticação real no login
- [ ] Upload e redimensionamento das imagens
- [ ] Filtros funcionando de verdade na biblioteca
- [ ] Contadores do menu alimentados pelo banco de dados

<img src="assets/divider.svg" width="100%" alt="">

## 👥 Equipe

<div align="center">

| 👤 Integrante | 🎯 Função |
|:---:|:---:|
| **Vinycius Lopes Monteiro da Silva** | 💻 Desenvolvimento |

<sub>Os nomes também estão no comentário no topo do `login.html`.</sub>

<br>

### ⭐ Gostou do projeto? Deixe uma estrela no repositório!

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,17,20&height=120&section=footer&text=Feito%20com%20%F0%9F%92%99%20e%20muita%20m%C3%BAsica&fontSize=24&fontColor=ffffff&animation=fadeIn&fontAlignY=68" alt="Feito com amor e muita música" width="100%">

</div>
