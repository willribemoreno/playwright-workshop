# Table of Contents
1. [Configuração do projeto](#configuração-do-projeto)

2. [Input](#input)   
    - [Enter your full Name](#enter-your-full-name)
    - [What is inside the text box](#what-is-inside-the-text-box)
    - [Clear the text](#clear-the-text)
    - [Confirm edit field is disabled](#confirm-edit-field-is-disabled)
    - [Confirm text is readonly](#confirm-text-is-readonly)
    - [Append a text and press keyboard tab](#append-a-text-and-press-keyboard-tab)

3. [Buttons](#buttons)
    - [Goto Home and come back here using driver command](#goto-home-and-come-back-here-using-driver-command)
    - [Get the X & Y co-ordinates](#get-the-x--y-co-ordinates)
    - [Find the color of the button](#find-the-color-of-the-button)
    - [Find the height & width of the button](#find-the-height--width-of-the-button)
    - [Confirm button is disabled](#confirm-button-is-disabled)
    - [Click and Hold Button](#click-and-hold-button)

4. [Select](#select-dropdown)
    - [Select the apple using visible text](#select-the-apple-using-visible-text)
    - [Select your super hero's](#select-your-super-heros)
    - [[Home Challenge] Select your super hero's](#challenge-select-your-super-heros)
    - [Select the last programming language and print all the options](#select-the-last-programming-language-and-print-all-the-options)

5. [Multi-Select](#multi-select)   
    - [Let's select all](#lets-select-all)

6. [Radio & Checkbox](#radio--checkbox)
    - [Select any one](#select-any-one)
    - [Accept the T&C](#accept-the-tc)

7. [Form](#forms)
    - [Preencher o form](#preencher-o-form)

8. [Documentações úteis](#documentações-úteis)

# Configuração do projeto
Abra o terminal da sua IDE e digite os seguintes comandos

``` javascript
npm i
```

``` javascript
npm run playwright:install:browsers
```

``` javascript
npm run test:dryrun
```

# Input
Todos os testes são realizados na página "Input"

[Clique aqui](https://letcode.in/edit) para abrir a página

## Enter your full Name
![](/doc-assets/input/input-enter-full-name.png)

### O que precisa ser feito?
É necessário apenas inserir um nome no campo `Enter your full Name`, e validar se o texto inserido no campo é igual ao texto atual do campo   

## What is inside the text box
![](/doc-assets/input/what-is-inside.png)

### O que precisa ser feito?
É necessário apenas validar se o texto do campo é igual a  `ortonikc`


## Clear the text
![](/doc-assets/input/clear-text.png)

### O que precisa ser feito?
É necessário apenas limpar o texto do campo e verificar se o campo ficou vazio após o `clear` 

## Confirm edit field is disabled
![](/doc-assets/input/confirm-disabled.png)

### O que precisa ser feito?
É necessário apenas verificar se o campo está desabilitado 

## Confirm text is readonly
![](/doc-assets/input/confirm-read-only.png)

### O que precisa ser feito?
É necessário apenas verificar se o campo está configurado como apenas leitura

## Append a text and press keyboard tab
![](/doc-assets/input/append-text.png)

### O que precisa ser feito?
É necessário manter o mesmo texto atual do campo(I am good), e apenas adicionar um novo texto ao final do campo, realizar uma concatenação no campo.

Exemplo 1:

![](/doc-assets/input/append-text2.png)

Exemplo 2:

![](/doc-assets/input/append-text3.png)
 

# Buttons
Todos os testes são realizados na página "Buttons"

[Clique aqui](https://letcode.in/buttons) para abrir a página

## Goto Home and come back here using driver command
![](/doc-assets/buttons/go-to-home.png)

### O que precisa ser feito?
Clique no botão "Goto Home" e volte novamente para a página [buttons](https://letcode.in/buttons)

## Get the X & Y co-ordinates
![](/doc-assets/buttons/coordinates.png)

### O que precisa ser feito?
Extraia as coordenadas do botão, e depois verifique se as coordenadas atuais do botão são iguais as que foram extraídas.

> **Nota:** Em um caso real, você pode usar as coordenadas para verificar se um elemento está visível na tela, ou se está em uma posição específica. Neste nosso caso estamos usando a mesma coordenada extraída no passo 1, então, naturalmente o teste sempre irá passar, mas entenda que o conceito é verificar a posição do elemento na tela.

## Find the color of the button
![](/doc-assets/buttons/get-color.png)

### O que precisa ser feito?
Extraia a cor do botão, e em seguida, verifique se cor atual do botão é a mesma do valor extraído.

## Find the height & width of the button
![](/doc-assets/buttons/height-and-width.png)

### O que precisa ser feito?
Extraia a altura e largura atual do botão, e em seguida, verifique se os valores atuais do botão são iguais aos extraídos

## Confirm button is disabled
![](/doc-assets/buttons/disabled.png)

### O que precisa ser feito?
Verifique se o botão está configurado como `disabled`

## Click and Hold Button
![](/doc-assets/buttons/click-and-hold.png)

### O que precisa ser feito?
Clique no botão por no mínimo 5 segundos e valide se o texto do botão mudou para `Button has been long pressed`


# Select (dropdown)
Todos os testes são realizados na página "Dropdowns"

[Clique aqui](https://letcode.in/dropdowns) para abrir a página

## Select the apple using visible text
![](/doc-assets/select/selectApple.png)

### O que precisa ser feito?
Selecione a opção que possui o `texto/label` igual a `Apple`

## Select your super hero's
![](/doc-assets/select/superHero.png)

### O que precisa ser feito?
Selecione um ou mais super heroes utilizando o atributo `value` da opção que deseja selecionar

## [Challenge] Select your super hero's

### O que precisa ser feito?
Selecione múltiplos super heroes utilizando a `label` ou o `value` da opção que deseja selecionar.   
Verifique se as opções selecionadas estão iguais as opções que você espera que deveriam estar selecionadas

## Select the last programming language and print all the options
![](/doc-assets/select/programmingLang.png)

### O que precisa ser feito?
Selecione a última opção através do index da opção desejada

# Multi-Select
Todos os testes são realizados na página "Selectable"

[Clique aqui](https://letcode.in/selectable) para abrir a página

## Let's select all
![](/doc-assets/multi-select/multi-select.png)

### O que precisa ser feito?
Selecione todas as opções disponíveis

# Radio & Checkbox
Todos os testes são realizados na página `Radio & Checkbox`

[Clique aqui](https://letcode.in/radio) para abrir a página

## Select any one
![](/doc-assets/radio/radio.png)

### O que precisa ser feito?
Selecionar umas das opções(Yes/No) no radio button `Select any one`

## Accept the T&C
![](/doc-assets/radio/checkbox.png)

### O que precisa ser feito?
Clicar no checkbox `Accept the T&C` para aceitar os termos e condições

# Forms
Todos os testes são realizados na página `Forms`

[Clique aqui](https://letcode.in/forms) para abrir a página

## Preencher o form
![](/doc-assets/form/form.png)

### O que precisa ser feito?
Realize o preenchimento de todos os campos do form utilizando o conhecimento adquirido durante as interações com os elementos que já trabalhamos (`buttons`, `input`, `dropdown` e `radio`)

> **Nota:** Após clicar no botão de subtmeter o form, todos os campos do form serão limpos, ficarão vazios. Este é o comportamento esperado após submeter o form...

# Documentações úteis

## Ações do Playwright
O Playwright possui uma documentação que aborda como realizar ações com a ferramenta. Essas ações podem ser cliques, preencher campos, pressionar teclas do teclado, etc...   
Clique no link abaixo para acessar a documentação.   
- [Actions](https://playwright.dev/docs/input#text-input)

## Asserções
O Playwright fornece uma série de "métodos" que podem ser utilizados para realizar validações(asserções).   
A documentação completa a respeito das asserções suportadas pode ser verificada abaixo.   
- [Assertions](https://playwright.dev/docs/test-assertions)  

## Extrair texto de elementos do tipo `input`, `textarea`, `select`   
- [inputValue](https://playwright.dev/docs/api/class-elementhandle#element-handle-input-value)

## Navegar para uma URL específica
Verifique a documentação abaixo para entender como navegar até uma URL específica
- [goto](https://playwright.dev/docs/api/class-page#page-goto)

## Verificar a URL atual
O Playwright fornece um método específico para verificar a URL atual do browser. Para mais detalhes, verifique a documentação no link abaixo

- [page-url](https://playwright.dev/docs/api/class-page#page-url)

## Verificar coordenadas, altura e largura
Verifique a documentação abaixo para entender como extrair as coordenadas, altura e largura de um elemento.

- [bounding box](https://playwright.dev/docs/api/class-locator#locator-bounding-box)

## Selecionar uma opção em um dropdown
Verifique a documentação abaixo para entender como selecionar um dropdown a partir da sua `label` ou `value`

- [selectOption](https://playwright.dev/docs/api/class-locator#locator-select-option)

## Rodar um JavaScript na página
Verifique a documentação abaixo para entender como utilizar um JavaScript na page sob testes.
- [evaluateAll](https://playwright.dev/docs/api/class-locator#locator-evaluate-all)

## Extrair as opções selecionadas de um dropdown com suporte a múltipla escolha
- [StackOverflow](https://stackoverflow.com/questions/5866169/how-to-get-all-selected-values-of-a-multiple-select-box)

## Selecionar um radio ou checkbox
- [Checkboxes and radio buttons](https://playwright.dev/docs/input#checkboxes-and-radio-buttons)

- [check](https://playwright.dev/docs/api/class-locator#locator-check)
