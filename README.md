# Boas-vindas ao repositório do projeto de Lições Aprendidas!

Projeto de avaliação feito durante o curso da Trybe.

<details>
<summary><strong>🧑‍💻 O que deverá ser desenvolvido</strong></summary><br />

Você vai desenvolver um site que contenha uma série de informações sobre o que você aprendeu aqui na Trybe ao longo dos últimos três blocos. O seu site deverá estar com elementos posicionados e estilizados e, além disso, deverá conter semântica apropriada para que seja acessível e melhor ranqueado.

</details>
  
# Orientações
  
<details>
  <summary><strong>Para acessar o projeto</strong></summary><br />

  1. Clone o repositório

  - Use o comando: `git clone git@github.com:priscilaSartori/project-lessons-learned.git`.
  - Entre na pasta do repositório que você acabou de clonar:
    - `cd project-tryunfo`

  2. Inicie a aplicação com a extensão Live Server no VSCode

</details>
  
<details>
<summary><strong>🎛 Linter</strong></summary><br />

Para garantir a qualidade do código, vamos utilizar neste projeto os linters `ESLint` e `StyleLint`.
Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível
e de fácil manutenção! Para rodá-los localmente no projeto, execute os comandos abaixo:

```bash
npm run lint
npm run lint:styles
```

O comando `npm run lint:styles` avalia se os arquivos com a extensão `CSS` estão no padrão correto.

O comando `npm run lint`, avalia se os arquivos com a extensão `JS` estão no padrão correto.

⚠ **NESTE PROJETO O STYLELINT e ESLINT NÃO SERÃO AVALIADOS. VOCÊ PODE RODAR OS TESTES LOCALMENTE E FAZER AS CORREÇÕES SE DESEJAR!** ⚠

</details>
  
<details>
<summary><strong>🛠 Testes</strong></summary><br />

Lembre-se de que sua página deverá conter semântica adequada e para isso verifique se a sua página está aprovada no [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/).

Todos os requisitos do projeto serão testados **automaticamente** por meio do `Cypress`.

## Cypress

O Cypress é uma ferramenta de teste de front-end desenvolvida para a web.

Antes de utilizá-lo, certifique-se de ter executado o comando `npm install` dentro do projeto.

Você pode rodar o cypress localmente para verificar se seus requisitos estão passando, para isso execute o um dos seguintes comandos:

Para executar os testes e vê-los rodando em uma janela de navegador:

```bash
npm run cypress:open
```

Após executar o comando acima, será aberta uma janela de navegador e então basta clicar no nome do arquivo de teste que quiser executar (project.spec.js).

Você também pode assistir a [este](https://vimeo.com/539240375/a116a166b9) vídeo 😉🎙

## Observações técnicas

Alguns requisitos devem seguir um padrão pré-estabelecido para que os testes automáticos funcionem corretamente, leia-os atentamente e siga à risca o que for pedido. Em particular, **atente-se para os nomes de _ids_ que alguns elementos do seu projeto devem possuir**.

- Os requisitos do seu projeto são avaliados automaticamente, sendo utilizada a resolução de tela de `1366 x 768` (1366 pixels de largura por 768 pixels de altura).

- ⚠️ Logo, recomenda-se desenvolver seu projeto usando a mesma resolução, via instalação [deste plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) do `Chrome` para facilitar a configuração da resolução.

- Atente-se para o tamanho das imagens que você utilizará neste projeto. **Não utilize imagens com um tamanho maior que _500Kb_.**

- ⚠️ Utilize uma ferramenta [como esta](https://picresize.com/pt) para redimensionar as imagens.

- Caso a avaliação falhe com alguma mensagem de erro parecida com `[409:0326/130838.878602:FATAL:memory.cc(22)] Out of memory. size=4194304`, provavelmente as imagens que você está utilizando estão muito grandes. Tente redimensioná-las para um tamanho menor.

- Para verificar se a sua avaliação foi computada com sucesso, você pode verificar os **detalhes da execução do avaliador**.

- Na página do seu _Pull Request_, acima do "botão de merge", procure por _**"Evaluator job"**_ e clique no link _**"Details"**_;
<img width="600" alt="evaluator-job" src="https://user-images.githubusercontent.com/42356399/166258020-e9f1d3c2-9530-4194-91be-c3983427d5f6.png">

- Na página que se abrirá, procure pela linha _**"Run Cypress Evaluator"**_ e clique nela;

<img width="600" alt="topico-run-cypress" src="https://user-images.githubusercontent.com/42356399/166258198-fca19bf0-64ac-4d82-ab81-e2860d255c76.png">
  
 - Desça a página até encontrar a mensagem _**"(Run Starting)"**_;
<img width="600" alt="Captura de Tela 2022-05-02 às 12 09 59" src="https://user-images.githubusercontent.com/42356399/166258577-23beeb14-bfcc-4e81-95a7-11cdcfda0d0b.png">

- Caso tenha dúvidas, consulte [este vídeo](https://vimeo.com/420861252);

- Você tem liberdade para adicionar novos comportamentos ao seu projeto, seja na forma de aperfeiçoamentos em requisitos propostos ou novas funcionalidades, **desde que tais comportamentos adicionais não conflitem com os requisitos propostos**.

</details>
  
# Requisitos do projeto

## 1. Adicione uma cor de fundo específica para a página

<details>

<summary>A página deve possuir uma cor de fundo <code>rgb(253, 251, 251)</code>
</summary><br/>

**O que será testado:**

- A página deve possuir cor de fundo: `rgb(253, 251, 251)`.

</details>

## 2. Adicione uma barra superior com um título

<details>

<summary>Essa barra superior deve possuir o <code>id</code> igual a <code>cabecalho</code> e deve ser fixa no topo da página com a propriedade <code>top</code> tendo <code>0</code>. O título deve estar dentro da barra e ser um elemento <code>h1</code> com <code>id</code> igual a <code>titulo</code>.
</summary><br/>

**Dica:** Para saber mais sobre posicionamento de elementos no CSS, consulte a documentação [aqui](https://www.w3schools.com/css/css_positioning.asp);<br/>

**O que será testado:**

- A barra deve possuir o ID `cabecalho`;
- A barra superior deve ser fixa no topo da página;
- A barra deve ter a propriedade `top` tendo o valor `0`;
- O título deve estar dentro da barra e possuir o ID `titulo`, além de ser uma tag `h1`.

</details>

## 3. Adicione uma foto sua à página

<details>

<summary>A foto deve ser inserida utilizando uma tag <code>img</code> com o ID <code>minha_foto</code>.
</summary><br/>

**O que será testado:**

- A foto deve ser uma tag `img` e possuir o ID `minha_foto`.

</details>

## 4. Adicione uma lista de lições aprendidas à página

<details>

<summary>A lista deve possuir <strong>10</strong> itens, ser numerada e possuir o ID <code>licoes_aprendidas</code>.
</summary><br/>

**O que será testado:**

- A lista deve ser numerada;

- A lista deve possuir o ID `licoes_aprendidas`;

- A lista deve possuir 10 itens.

</details>

## 5. Crie uma lista de lições que ainda deseja aprender para a página

<details>

<summary>A lista deve possuir <strong>10</strong> itens, não ser numerada e possuir o ID <code>licoes_a_aprender</code>.
</summary><br/>

**O que será testado:**

- A lista não deve ser numerada;
  
- A lista deve possuir o ID `licoes_a_aprender`;

- A lista deve possuir 10 itens.

</details>

## 6. Adicione um rodapé para a página

<details>

<summary>O rodapé deve utilizar a tag <strong>footer</strong> e possuir o ID <code>rodape</code>.
</summary><br/>

**O que será testado:**

- O rodapé deve possuir a tag `footer`;

- O rodapé deve possuir o ID `rodape`.

</details>

## 7. Insira pelo menos um link externo na página

<details>

<summary>O link deve redirecionar a pessoa usuária para uma nova aba do navegador.
</summary><br/>

**Dica:** Leia mais sobre redirecionamento de aba [aqui](https://www.horadecodar.com.br/2019/11/21/como-fazer-para-o-link-abrir-em-nova-aba-tag-a-do-html/)

**O que será testado:**

- O link deve ser aberto em nova aba no navegador.

</details>

## 8. Crie um artigo sobre o seu aprendizado

<details>

<summary>O artigo deverá ser uma tag html <code>article</code> e deve possuir mais de 300 <strong>caracteres</strong> e menos de 600.
</summary><br/>

**O que será testado:**

- O artigo deve possuir a tag `article`;
- O artigo deve ter mais de 300 caracteres e menos de 600.

</details>

## 9. Crie uma tag html `aside` que contenha uma breve descrição sobre você

<details>

<summary>A tag <code>aside</code> deverá possuir mais de 100 <strong>caracteres</strong> e menos de 300.
</summary><br/>

Lembre-se que tudo dentro da tag `aside` será contabilizado como caractere.

**O que será testado:**

- A tag `aside` deve ser utilizada;
- A sua descrição deve ter mais que 100 caracteres e menos que 300.


</details>

## 10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles

<details>

<summary>A sua página deve conter os seguintes elementos: <code>article</code>, <code>header</code>, <code>aside</code> e <code>footer</code>.
</summary><br/>

**O que será testado:**

- A página deve possuir um elemento `article`;
- A página deve possuir um elemento `header`;
- A página deve possuir um elemento `aside`;
- A página deve possuir um elemento `footer`.

</details>

## 11. Teste a semântica da sua página usando o site [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/)

<details>

<summary>Teste se a semântica da sua página está aprovada pelo site <a href="https://squizlabs.github.io/HTML_CodeSniffer/">CodeSniffer</a>.
</summary><br/>

**O que será testado:**

- A sua página deve passar com `0 errors` na verificação de semântica do site [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/).

</details>

---
 
# Requisitos Bônus

## 12. Adicione uma tabela à página

<details>

<summary>A página deve possuir uma tabela.
</summary><br/>

**Dica:** Você pode ler mais sobre tabelas no CSS [aqui](https://www.w3schools.com/html/html_tables.asp).

**O que será testado:**

- A página deve possuir um elemento `<table>`.

</details>

## 13. Utilize o Box model

<details>

<summary>Altere <code>margin</code>, <code>padding</code> e <code>border</code> dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes.
</summary><br/>

**O que será testado:**

- Algum elemento deve ter o atributo `margin` modificado;
- Algum elemento deve ter o atributo `padding` modificado;
- Algum elemento deve ter o atributo `border` modificado.

</details>

## 14. Altere atributos relacionados às fontes

<details>

<summary>Modifique o estilo da sua tipografia alterando o tamanho de letra, a cor, o espaçamento entre as linhas e a <code>font-family</code>.
</summary><br/>

**O que será testado:**

- O estilo da tipografia deve ter o tamanho da letra alterado;
- O estilo da tipografia deve ter a cor da letra alterada;
- O estilo da tipografia deve ter o espaçamento entre as linhas alterado;
- O estilo da tipografia deve ter o atributo `font-family`.

</details>

## 15. Posicione a tag `article` e a tag `aside` uma ao lado do outra

<details>

<summary>Adicione ao elemento posicionado no lado esquerdo a classe <code>lado-esquerdo</code> e ao elemento posicionado no lado direito a classe <code>lado-direito</code>.
</summary><br/>

**O que será testado:**

- O elemento posicionado à esquerda deve utilizar a classe `lado-esquerdo`;
- O elemento posicionado à direita deve utilizar a classe `lado-direito`;
- Os elementos com as classes `lado-direito` e `lado-esquerdo` estão posicionados corretamente.

</details>

---

