<div align="center">

# Jogo do Número Secreto

Aplicação desenvolvida durante meus estudos na **Alura + Oracle Next Education (ONE)** para praticar fundamentos de lógica de programação utilizando JavaScript.

<br>

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)

</div>

---

## Sobre o projeto

O **Jogo do Número Secreto** é uma aplicação simples desenvolvida para colocar em prática conceitos fundamentais de programação com **JavaScript**.

O sistema gera aleatoriamente um número secreto dentro de um intervalo definido. 

O jogador informa seus palpites e recebe uma indicação se o número secreto é maior ou menor que o valor informado.

O jogo continua até que o jogador descubra o número correto.

Este projeto representa uma das primeiras experiências práticas da minha formação em desenvolvimento de software.

---

## Objetivo

O principal objetivo foi aplicar conceitos básicos de lógica de programação em uma aplicação funcional.

Durante o desenvolvimento foram trabalhados:

* Variáveis e tipos de dados
* Operadores de comparação
* Estruturas condicionais
* Estruturas de repetição
* Geração de números aleatórios
* Incremento de variáveis
* Operador ternário
* Interação com o usuário através de `prompt()` e `alert()`
* Organização da lógica em JavaScript

---

## Como funciona

O fluxo principal da aplicação pode ser representado da seguinte forma:

```text
Início
  ↓
Geração do número secreto
  ↓
Jogador informa um número
  ↓
Comparação com o número secreto
  ↓
O palpite está correto?
   ↙              ↘
 Não              Sim
 ↓                 ↓
Informa se o       Exibe mensagem
número é maior     de vitória
ou menor           ↓
 ↓               Fim
Nova tentativa
```

O número secreto é gerado utilizando `Math.random()` e o jogador possui tentativas ilimitadas até encontrar o valor correto.

---

## Tecnologias utilizadas

| Tecnologia     | Utilização                               |
| -------------- | ---------------------------------------- |
| **JavaScript** | Lógica principal e funcionamento do jogo |
| **HTML5**      | Estrutura da página                      |
| **CSS3**       | Estilização da interface                 |
| **Git**        | Versionamento do projeto                 |
| **GitHub**     | Hospedagem e documentação do código      |

---

## Estrutura do projeto

```text
jogo-numero-secreto-basico/
│
├── img/
│   └── recursos visuais do projeto
│
├── app.js
├── index.html
├── style.css
└── README.md
```

### Principais arquivos

**`app.js`**

Contém toda a lógica do jogo, incluindo a geração do número secreto, recebimento dos palpites, comparação dos valores, controle das tentativas e mensagens apresentadas ao jogador.

**`index.html`**

Define a estrutura da página e os elementos visuais apresentados ao usuário.

**`style.css`**

Responsável pela estilização da interface, incluindo layout, tipografia, cores e elementos visuais.

**`img/`**

Contém as imagens utilizadas na composição visual da aplicação.

---

## Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/Lamarcks/jogo-numero-secreto-basico.git
```

### 2. Acesse a pasta

```bash
cd jogo-numero-secreto-basico
```

### 3. Execute o projeto

Abra o arquivo:

```text
index.html
```

diretamente no navegador.

Também é possível utilizar uma extensão como **Live Server** no Visual Studio Code.

---

## Exemplo de funcionamento

Ao iniciar a aplicação, o JavaScript gera um número secreto entre **1 e 10**.

O jogador recebe uma solicitação para informar um número:

```text
Escolha um número entre 1 e 10
```

Caso o palpite esteja incorreto, o sistema informa uma direção:

```text
O número secreto é maior que 4
```

ou:

```text
O número secreto é menor que 8
```

Quando o número correto é encontrado, o sistema informa a quantidade de tentativas utilizadas.

---

## Conceitos praticados

Entre os principais conceitos utilizados no código estão:

```javascript
Math.random()
```

Utilizado para gerar um valor aleatório para o número secreto.

```javascript
while
```

Utilizado para manter o jogo funcionando até que o número correto seja encontrado.

```javascript
if / else
```

Utilizado para comparar o palpite do jogador com o número secreto.

```javascript
tentativas++
```

Utilizado para controlar a quantidade de tentativas realizadas.

```javascript
condição ? valor1 : valor2
```

Utilizado para definir corretamente a palavra `tentativa` ou `tentativas` na mensagem final.

---

## Aprendizados

O desenvolvimento deste projeto ajudou a consolidar conceitos que serviram como base para projetos posteriores, principalmente:

* Pensamento lógico e estruturação de algoritmos;
* Controle de fluxo de uma aplicação;
* Manipulação de variáveis;
* Comparação e tomada de decisões no código;
* Utilização de funções nativas do JavaScript;
* Interação entre código e usuário;
* Testes e depuração durante o desenvolvimento.

---

## Autor

**Ihago Lamarcks**

Estudante de **Análise e Desenvolvimento de Sistemas**, com interesse em desenvolvimento de software, automação, Python, Inteligência Artificial e tecnologias web.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ihago%20Lamarcks-0A66C2?style=for-the-badge\&logo=linkedin)](https://www.linkedin.com/in/ihago-lamarcks1/)

---

<div align="center">

**Projeto desenvolvido durante minha formação em tecnologia.**

Oracle Next Education • Alura 

</div>
