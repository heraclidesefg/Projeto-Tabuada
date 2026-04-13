# ➗ Projeto Tabuada de Multiplicação

Este projeto consiste em uma aplicação web simples e interativa que gera a tabuada de multiplicação de um número informado pelo usuário, utilizando HTML, CSS e JavaScript puro.

É um projeto ideal para iniciantes, pois trabalha conceitos fundamentais como formulários, eventos, manipulação do DOM e laços de repetição.

## 🎯 Objetivo do Projeto
* Permitir que o usuário informe um número base
* Definir até qual número a tabuada será calculada
* Gerar dinamicamente a tabuada de multiplicação
* Exibir os resultados diretamente na tela, sem recarregar a página

## 🗂 Estrutura do Projeto

├── index.html      # Estrutura da página

├── script.js       # Lógica da tabuada em JavaScript

├── style.css       # Estilos visuais (opcional, se existir)

├── favicon/        # Ícone do site (opcional)

└── README.md       # Documentação do projeto

## 🧩 Tecnologias Utilizadas
* **HTML5** – Estrutura do formulário e da página
* **CSS3** – Estilização da interface (quando aplicado)
* **JavaScrip**t (Vanilla JS) – Lógica de cálculo e manipulação do DOM

## 🖥️ Funcionamento do Projeto
### 1️⃣ Interface do Usuário

***A página apresenta:***

Um título explicativo

***Um formulário com dois campos numéricos:***
* Tabuada do: número base
* Multiplicar até: limite da multiplicação
* Um botão para calcular a tabuada
* Uma área onde os resultados são exibidos

### 2️⃣ Envio do Formulário

***Ao clicar em Calcular:***

>**O comportamento padrão do formulário é bloqueado (preventDefault)**
* Os valores digitados são capturados
* O sistema valida se os campos estão preenchidos corretamente

### 3️⃣ Geração da Tabuada

***A função createTable():***

* Limpa resultados anteriores
* Utiliza um laço de repetição (for)
* Calcula o resultado da multiplicação
* Cria dinamicamente cada linha da tabuada no HTML

Exemplo de saída:

* 3 * 1 = 3
* 3 * 2 = 6
* 3 * 3 = 9


### 4️⃣ Manipulação do DOM

***O JavaScript:***

* Atualiza o título da tabuada com o número escolhido
* Insere dinamicamente os elementos HTML usando DOMParser
* Exibe os resultados sem recarregar a página

## ▶️ Como Executar o Projeto
* Faça o download ou clone o repositório
* Abra o arquivo index.html em qualquer navegador moderno
* Digite:
  * O número da tabuada
  * O limite de multiplicação
  * Clique em Calcular
  * Veja a tabuada sendo gerada na tela

## 📌 Regras e Validações
* Os campos aceitam apenas números
* Valores vazios não geram tabuada
* O valor mínimo aceito é 1

## 📚 Conceitos Trabalhados

Eventos em formulários (submit)

Prevenção de comportamento padrão

Laços de repetição (for)

Funções em JavaScript

Manipulação dinâmica do DOM

Conversão de valores para número (Number / +)

## 🚀 Possíveis Melhorias Futuras
* Adicionar botão para limpar a tabuada
* Estilizar melhor os resultados
* Permitir escolha entre soma, subtração e divisão
* Tornar o layout responsivo
* Adicionar validações visuais para erros

👨‍💻 Autor
**Professor: Heraclides Mourão**
* Projeto desenvolvido com fins educacionais, ideal para:
  * Introdução ao JavaScript
  * Prática de lógica de programação
  * Atividades acadêmicas e exercícios práticos