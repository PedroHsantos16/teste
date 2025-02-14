## <p>Introdução</p>

* O que é Markdown e por que utilizá-lo no GitHub?  
    * Markdown é uma linguagem de marcação simples, facilita a documentação de códigos.

* Vantagens do Markdown para documentação e publicações.

    * Markdown é uma liguagem mais simples e fácil de trabalhar, agilizando o processo de documentação dos códigos.
<br><br>

## Elementos básicos

   
Para realizar um paragrafo digite ```<p>``` para começar o paragrafo e ```</p>``` para finaliza-lo

Para quebrar uma linha precione espaço duas vezes "_ _"

Pra realizar uma linha na horizontal precisa de três asteriscos ("***"), traços (-) ou underline (_) ao início da linha todos geram a mesma linha 
***  
***

Para realizar um código invisivel faça ``<!--e para finalizalo apenas -->`` tudo q adicionar dentro dos "<>" ficará invisivel 
<!-- isso é um comentario invisivel ele nao aparece no preview somente no código --> 
<br>

## Formatação de texto 

1. Ênfase:
   
* ```Negrito:``` Para colocar uma palavra em negrito, basta colocar dois asteriscos.  
   ```Por exemplo:``` 
    
    ** palavra **, isso fará com que a "**palavra**" fique em negrito
<br><br>
* ```Itálico:``` Para colocar uma palavra em Itálico basta colocar um asterisco.  
```Por exemplo:``` 

     
    \* palavra *, isso fará com que a "*palavra*" fique em itálico
<br><br>
* ```Riscado:``` para colocar uma palavra riscad, basta colocar dois tios.  
  ```Por exemplo:``` 
    
    \~~ palavra \~~, isso fará com que a ~~palavra~~ fique riscada.
<br><br>


2. ``Citação em bloco:`` Para fazer uma citação em bloco, basta colocar "\>" no começo da frase, e fará uma citação em bloco.
   Por exemplo:  

   \> esta é uma citação em bloco  
  
   Resultado:
   >esta é uma citação em bloco
<br><br>


1. ``exibição de comando:`` para exibir um comando do markdown, basta colocar uma \, essa barra faz com que o markdown interprete como um caracter ao invés de processar como parte da formatação.

<br><br>

## Trabalhando com Listas
---

Para realizar uma lista ordenada precisa apenas adicionar um ponto final no numero q queira  que queira fazer uma lista, após isso precione ```ENTER``` para dar continuidade na lista como por exemplo: 

1. Exmplo 
2. Exmplo exemplo 

E a não ordenada adicione um mais ``"+"`` como por exemplo:

+  2 Exemplo
+  4 Exemplo  
+  8 Exemplo   
+  7 Exemplo 

Começar uma lista de tarefas é bem simples somente adicionando ``"- [] Item da lista"`` se adicionar um "X"dentro dos ccolchetes marcara o item com realizado, como por exemplo:

- [ ] Comprar pão
- [x] Estudar para a prova
- [ ] Lavar a roupa
- [x] Ir à academia

Para listas com numeraçao não sequencial utilize uma barra invertida ``"\"``
<br><br>

## Links e Referências
---

Para realizar um link faça ``[AQUI](ehttps://www.markdownguide.org/)`` onde está escrito "AQUI" é utilizado para redirecionar para o site desejado, e a outra parte você cola o LINK do site q deseja como por exemplo 

[Isso é um exemplo](https://www.youtube.com/)


e com referencia é assim ``([Exemplo ][1] [1]: https://www.google.com)`` os "1" são como atalhos para facilitar a codificação como por exemplo:

[Exemplo ][1]

[1]: https://www.youtube.com/

como realizar âcoras crie um paragrafo e adicione assim ``"[qualquer coisa](#nome-do-pragrafo)"``

[Ir para a Seção de Introdução](#Introdução)

<br><br>

## Imagens e mídias

Para inserir uma imagem, basta usar o seguinte comando:  

![Texto Alternativo]\(caminho/para/imagem.extensao)  
ou  
![Texto Alternativo]\(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsTfXwY_1HFsyuMhX0ajaCCv_ZsKlUb9k0kA&s)

o que está entre colchetes [] é o texto alternativo, caso a imagem não apareça, já o que está entre parênteses () é o caminho para imagem. O caminho pode ser uma pasta do seu computador, ou um link que redirecione para a imagem

<br>esta imagem está dentro da pasta imagens
![Texto Alternativo](imagens/images.png)

<br>Já esta imagem, está na internet, o que está entre parênteses é o link que leva a imagem

![Texto Alternativo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTsTfXwY_1HFsyuMhX0ajaCCv_ZsKlUb9k0kA&s)

<br>

uma imagem clicável, basta fazer o mesmo do tópico acima, porém adicionando um parênteses com o link da página web que será redirecionada  <br>

``Por exemplo:``

[![Texto Alternativo](imagens/github.png)](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


``comando usado para msotrar a imagem do github acima:``<br>
[\![Texto Alternativo]\(imagens/github.png)]\(https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

<br>

## Códigos

Para mostrar códigos, basta colocar três crases ``` e a linguagem do código, e depois escrever os comandos.
``Por exemplo:`` 

\```python  
 
print("Olá, Mundo!")  
\```

``resultado:``

```python

print("Olá, Mundo!")
```
<br>

## Elementos avançados

1. **Notas de rodapé:** Para fazer uma nota de rodapé, basta colocar  
\[^1] na frase.

``Por exemplo:``  
[^1]: este é um exemplo de rodapé


[^1]: coloque no começo da frase para fazer um rodapé  
coloque no meio de uma [^1] frase para fazer um rodapé



1. **Emojis:** PAra colocar emojis, basta colocar o nome do emoji entre <>.

``Por exemplo:`` 

:fire:




