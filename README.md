# 🎨 Redesign & Style Guide Figma — Itaú

Este repositório contém as especificações, tokens de design e documentação para a reprodução exata da prancha de **Style Guide e Manual de Cores** no programa **Figma**.

---

## 📑 Sumário
- [📌 Objetivo do Trabalho](#-objetivo-do-trabalho)
- [🎨 Tokens de Cor (Color Styles)](#-tokens-de-cor-color-styles)
- [🔤 Tipografia & Escala (Text Styles)](#-tipografia--escala-text-styles)
- [📐 Estrutura do Layout](#-estrutura-do-layout)
- [🛠️ Instruções de Execução no Figma](#️-instruções-de-execução-no-figma)

---

## 📌 Objetivo do Trabalho

Recriar com precisão a prancha de identidade visual no Figma aplicando as melhores práticas do ecossistema de UI/UX Design:
* Uso de **Auto Layout** (`Shift + A`) para estrutura responsiva e alinhamentos.
* Criação de **Color Styles** (Estilos Globais de Cor).
* Criação de **Text Styles** (Estilos Globais de Tipografia).
* Organização em quadros (*Frames*) limpos e bem nomenclaturados.

---

## 🎨 Tokens de Cor (Color Styles)

Cadastre as seguintes cores no painel de estilos do Figma:

### 🔴 Primário
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Primário +1** | `#FF8133` | 🟧 |
| **Primário** | `#FF6200` | 🟧 |
| **Primário -1** | `#CC4E00` | 🟧 |

### 🔵 Secundário
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Secundário -1** | `#539AE9` | 🟦 |
| **Secundário** | `#267FE3` | 🟦 |
| **Secundário +1** | `#1866BE` | 🟦 |

### ⬛ Dark
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Dark +1** | `#403B3B` | ⬛ |
| **Dark** | `#262323` | ⬛ |
| **Dark -1** | `#0B0A0A` | ⬛ |

### ⚪ Light
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Light -1** | `#FFFFFF` | ⬜ |
| **Light** | `#F2F5F7` | ⬜ |
| **Light +1** | `#D3DDE4` | ⬜ |

### 🟢 Sucess
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Sucess +1** | `#7BE085` | 🟩 |
| **Sucess** | `#52D65F` | 🟩 |
| **Sucess -1** | `#2FC63E` | 🟩 |

### 🔴 Danger
| Nome | Código HEX | Amostra |
| :--- | :---: | :---: |
| **Danger +1** | `#FF2705` | 🟥 |
| **Danger** | `#D11C00` | 🟥 |
| **Danger -1** | `#9E1500` | 🟥 |

---

## 🔤 Tipografia & Escala (Text Styles)

* **Fonte utilizada**: [Poppins](https://fonts.google.com/specimen/Poppins) *(Google Fonts)*

### 📐 Escala Tipográfica (Font Scale)
Configure a hierarquia de textos no Figma conforme a tabela abaixo:

| Estilo de Texto | Tamanho (px) | Peso Sugerido |
| :--- | :---: | :--- |
| **Small** | `14px` | Regular / Medium |
| **Parágrafo** | `16px` | Regular |
| **H5** | `18px` | Medium / SemiBold |
| **H4** | `24px` | SemiBold |
| **H3** | `28px` | Bold |
| **H2** | `34px` | Bold |
| **H1** | `40px` | Bold |

---

## 📐 Estrutura do Layout

O arquivo no Figma deve conter os seguintes blocos bem definidos:

1. **Logo**: Inserção do logotipo oficial da marca (ícone laranja com cantos arredondados e a marca em branco).
2. **Color Swatches**: Grade com as amostras de cores exibindo o quadrado com a cor, o nome do Token e o código HEX.
3. **Contraste / Tipografia**: Testes e amostras do tipo `Poppins` ("Aa") em fundos variados para validação de contraste visual.
4. **Font Scale**: Coluna demonstrativa com a aplicação prática dos textos ordenados do menor ao maior.

---

## 🛠️ Instruções de Execução no Figma

1. **Configuração Inicial**: Instale a fonte **Poppins** no seu computador.
2. **Criação do Canvas**: Crie um Frame principal (ex: `Desktop - 1440px` ou livre).
3. **Estilos Globais**:
   * Adicione todas as cores em `Color Styles` (`+`).
   * Adicione todos os tamanhos de texto em `Text Styles` (`+`).
4. **Organização em Auto Layout**:
   * Use **Auto Layout** (`Shift + A`) nos blocos de cores para manter os espaçamentos dinâmicos e uniformes.
   * Aplique cantos arredondados (*Corner Radius*) padrão para os *cards* de cor.
5. **Entrega**: Exporte a prancha final em PDF/PNG ou compartilhe o link do projeto no Figma.
