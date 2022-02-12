# 1º) O que é Markdown?

- Linguagem de Marcação
- Composta por símbolos
- Compatível com pacotes office e GitHub (readme, issues e pull requests)
- Conversão de Markdown para HTML por meio da Commonmark (versão padronizada da Markdown)
- John Gruber e Aaron Swartz (criadores)

# 2º) Markdown Simples:

## Itálico:

* _exemplo_ ou *exemplo*

## Negrito:

* __exemplo__ ou **exemplo**

## Riscado:

* ~~exemplo~~

## Misturando:

* _**~~exemplo~~**_

# 3º) Listas:

## Ordenadas:

1. Brasil
2. Chile
    1. Santiago
3. Peru

## Não Ordenadas:

* One Piece:
* Bleach
    * Espadas
* Dragon Ball Z

## De Tarefas:

[ ] Pão
[x] Leite
[ ] Manteiga

# 4º) Títulos e Linha Horizontal:

* exemplo:
    # Título Principal
    ## Título Secundário
    ***
    Texto comum

# 5º) Imagens:

![Super-Choque](https://kanto.legiaodosherois.com.br/w760-h398-gnw-cfill-q80/wp-content/uploads/2020/06/legiao_emIVgKQofcnd.jpg.jpeg)

# 6º) Links:

[Clique aqui!](https://www.youtube.com/watch?v=QNJL6nfu__Q)

# 7º) Trechos de Código:

## Comando Isolado:

Impressão de dados em Python: `print("Olá, Mundo!")`

## Trecho de Código:

Par ou Ímpar em Python:

```
numero = int(input("Digite um número: "))

if numero % 2 == 0:
    print(f"{numero} é par!")
else:
    print(f"{numero} é ímpar!")
```

# 8º) Ligações entre conteúdos:

## Citação:

Sócrates disse:
> Só sei que nada sei.

## Menções a usuários e issues:

Analisando a issue _**#3**_ que foi feita pelo nosso amigo _**@fulano.ciclano**_.

# 9º) Símbolos:

## Tirando efeitos de formatação:

* Podemos criar títulos usando \# antes do texto.
* Podemos criar citações usando \> antes do conteúdo.
* Podemos adicionar imagens usando \!\[descrição]\(url).

## Emojis:

* Aplausos :clap:
* Olhos :eyes:
* Bíceps :muscle:
* Like :+1:

- **acesse o repositório: [ikatyang/emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet)**

# 10º) Tabelas:

Livros | Autores | Gênero
:--- | :---: | ---:
Percy Jackson e o Ladrão de Raios | Rick Riordan | Aventura / Mitologia (Grega)
O código da Vinci | Dan Brown | Policial / Suspense
It | Stephen King | Terror

## Alinhamento:

* \--- padrão (à esquerda)
* :--- à esquerda
* :---: ao centro
* ---: à direita