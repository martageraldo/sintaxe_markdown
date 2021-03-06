# SINTAXE MARKDOWN


# 1 - Títulos
<br>


Os títulos vão do h1 até o h6 e eles podem construídos com um até seis # para cada nível.

<br>

# h1 - O Navio Negreiro, de Castro Alves
## h2 - O Navio Negreiro, de Castro Alves
### h3 - O Navio Negreiro, de Castro Alves
#### h4 - O Navio Negreiro, de Castro Alves
##### h5 - O Navio Negreiro, de Castro Alves
###### h6 - O Navio Negreiro, de Castro Alves

<br>

Existe este outro método, porém ele está limitado a dois níveis.

<br>

h1 - O Navio Negreiro, de Castro Alves
=
h2 - O Navio Negreiro, de Castro Alves
-  
<br>
<br>

# 2 - Quebras de página
<br>


Para separar as sessões na página, basta que ponha três ou mais asteriscos, traços e underlines. Pode separá-los ou não por espaços.
<br>
______
-----
***

* * * *
- - - -

<br>

 # 3 - Estilos de texto

<br>
Os textos podem ser feitos em **negrito**, *italico* ou tachado: 
<br>

##  3.1 - Negrito
<br>

Para colocar alguma palavra, frase ou texto em **evidência**, basta inserir dois asteriscos ou dois underlines antes e depois do termo.
<br>

**Este texto está em negrito**  
__E este também.__

<br>

## 3.2 - *Italico*

<br>

Para colocar a palavra em *Itálico* basta colocar um asterisco ou um underline antes e depois do termo.
<br>

*Este texto está em itálico.*  
_E este também._

<br>

## 3.3 - Negrito e Italico

Também é possivel colocar negrito e itálico ao mesmo tempo.
<br>

***Conhecimento é poder!***  
**_Conhecimento é poder!_**  
*__Conhecimento é poder!__*  

## 3.4 Tachado

<br>

Em GitHub Flavored Markdown, que é usado para processar os arquivos Markdown é possível usar o tachado:

~~O Conhecimento é poder!~~

# 4 - Parágrafo

Para escrever um novo parágrafo, basta colocar dois espaços, após a última palavra.

Pouco conhecimento faz com que as pessoas se sintam orgulhosas. Muito conhecimento, que se sintam humildes.  
É assim que as espigas sem grãos erguem desdenhosamente a cabeça para o céu, enquanto que as cheias as baixam para a terra, sua mãe.

Leonardo da Vinci
___

# 5 - Citações


## 5.1 - Citação simples

<br>
As citações podem ser feitas com o símbolo de maior >.


>"Tudo o que um sonho precisa para ser realizado é alguém que acredite que ele possa ser realizado." - Roberto Shinyashiki
<br>

## 5.2 - Citação de citação
<br>

Se a citação tiver mais do que um parágrafo, é preciso colocar o sinal de  > em frente a cada frase.


>"Neste momento, penso em você e então quisera me transformar em vento.
>E se assim fosse, chegaria agora como brisa fresca e tocaria leve sua janela.
>E se você me escuta e me permite entrar, em você vou me enroscar quase sem o tocar.
>Vou roçar nos seus cabelos, soprar mansinho no ouvido, beijar sua boca macia, o embalar no meu carinho
>Mas eu não sou vento... Agora sou só pensamento e estou pensando em você.
>E se abrir sua janela, eu estou chegando aí, agora...
neste momento, em pensamento... no vento." - Roberto Shinyashiki

Quando houver citação dentro de citação é possível concatenar vários símbolos >>.

>"Citação acima de 40 palavras deve ser apresentada em nova linha, num
bloco independente, com recuo de 0,3 cm do parágrafo da margem esquerda, sem
aspas, com espaçamento simples entre linhas e a fonte segue o tamanho normal do
texto Times New Roman 12. As linhas subsequentes devem acompanhar o recuo.  

>Observe o exemplo abaixo:  

>>"de modo racional referente a fins, por expectativas quanto ao comportamento
de objetos do mundo exterior e de outras pessoas, utilizando estas
expectativas como condições ou meios para alcançar fins próprios,
ponderados e perseguidos racionalmente, com sucesso; de modo racional
referente a valores, pela crença consciente no valor — ético, estético,
religioso ou qualquer que seja sua interpretação — absoluto e inerente a
determinado comportamento como tal, independentemente do resultado; de
modo afetivo, especialmente emocional, por afetos ou estados emocionais
atuais; de modo tradicional, por costume arraigado." (Weber, 1994, p. 15)." - ANPAD

___

# 6 - Listas

<br>

## 6.1 - Listas desordenadas

Para criar lista desordenada podemos utilizar símbolos de asterisco(*), traço(-) e o de soma(+)

 Lista de Compras
- Leite 
- açúcar
- feijão
+ arroz
+ farinha
* óleo
* carne
<br>

## 6.2 - Lista demarcada

<br>

Para gerar uma lista dentro de outra, é preciso colocar quatro espaços em branco antes do símbolo de asterisco, traço e soma.

* Teste
* Teste
* Teste
   * subitem
   * subitem
* teste
- teste (pode ser tracinho)
        
## 6.3 - Lista numerada

É preciso colocar um número + um ponto + espaço.

1. Teste 1
2. Teste 2
1. Teste 3
6. Teste 4

A numeração permanece normal, mesmo que coloque números desordenados.

1. teste
   1. teste (3 espaços: subitem 1)
   2. teste
   3. teste
   4. teste
   999. teste
0. teste
8. teste

<br>

## 6.4 - Lista com caixas de marcação

<br>

 É preciso colocar um traço + espaço + abrir e fechar colchetes com um espaço interno, e se quiser marcar na caixa o que já foi realizado, colocar um x em seu interior:(- [x] Criar a página principal).

- [x] Criar a página principal
- [ ] Criar a página da loja
- [ ] Finalizar a reunião com o cliente
- [ ] Receber pagamento

<br>

# 7 - Blocos de códigos separados
<br>

É possível criar blocos de código separados, colocando-se três crases para linguagens, antes e depois do bloco de código.


 Não entendo direito para que serve o comando `document.getElementById()` da linguagem JavaScript

 Olha meu programa em Python (três crases para linguagens)

```
num = int(input('Digite um valor: ')
if num %2== 0:
    print(f'O valor{num} é PAR')
else:
    print(f'O valor {num} é Impar')
    
```
## 7.1 - Realce da Sintaxe
<br>

 É possível incluir um identificador de linguagem para habilitar  o realce de sintaxe no bloco de código isolado.


```python
num = int(input('Digite um valor: ')
if num %2== 0:
    print(f'O valor{num} é PAR')
else:
    print(f'O valor {num} é Impar')
    
```

```ruby
class Pagamento
  def update( funcionario )
    puts("Aumentando salário do #{funcionario.nome}!")
    puts("Seu novo salário é #{funcionario.salario}!")
  end
```
# 8 - Links
<br>

##  8.1 - Link externo
<br>

Para colocar link externo, o texto a ser exibido deve ser colocado entre colchetes [] seguido pela url em parênteses ().
 <br>

GitHub: [martageraldo](https://github.com/martageraldo)  
Linkedin: [marta-geraldo](www.linkedin.com/in/marta-geraldo)  
Twitter: [@martageraldo](https://twitter.com/home)  


Gustavo Guanabara ensina linguagens de programação no site do [curso em video](https://www.cursoemvideo.com), no seu canal do [youtube](https://www.youtube.com/user/cursosemvideo) e também no [Estudonauta e no Apoie-me](https://apoie.me/cursoemvideo).

## 8.2 - Link automático
<br>

 Para criar link automáticos basta colocar a url entre os símbolos < >.

<http://www.google.com>  


# 9 - Imagens
<br>

As imagens são feitas da mesma forma que os links, mas com um ponto de exclamação na frente.

![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png)
<br>
# 10 - Tabelas
<br>

Para fazer tabelas é preciso colocar  o texto + os símbolo (|) para fazer as colunas da tabela e (---) para fazer as linhas da tabela.

Nome  |Idade | Função
---|---|---
Pedro |  30 | aux. administrativo
Maria |  25 | programador
Joana | 90 | aposentado
Marcelo| 40 | eletricista


Num | Nome | Nota
---|---|---
1 | Gustavo| 8,5
2 | José| 10
3 | Maria|9,0
4 | João | 5,5
5 | Lúcia | 7,5
6 | Vanessa | 9,5















       


















