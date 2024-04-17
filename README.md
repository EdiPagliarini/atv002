# Guia Basico de marcacao markdown
Este guia oferece um passo a passo detalhado sobre como utilizar a marcação Markdown para
formatação de texto em documentos. Iniciando desde os conceitos básicos, como títulos
parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada tópico
é acompanhado por uma descrição simples e exemplos práticos em Markdown, permitindo que os
usuários aprendam e apliquem rapidamente a marcação Markdown em seus próprios documentos.

Exemplo:
# titulo 1
## titulos 2
### titulo 3

## paragráfos
Simplesmente escreva seu texto como paragráfos normais. não é necessário nenhum tipo de marcação.

Exemplo:
Aqui eu tenho um Paragráfo.

## Listas
Permitem criar listas oredenadas ou não ordenadas.

Exemplo:
Lista não ordenada

* Item 1
* Item 2
* Item 3

  Lista Ordenada:

  1. Primeiro item
  2. Segundo item
  3. Terceiro item
     

## Links
Criam links para outras páginas da web.

Exemplo:

[Texto do link](URL). para criar um link.

## imagens
Insererem imagens em um documento Markdown.

Exemplo:

![imagem](URL_da_imagem).

## Ênfase
permitam enfatizar texto, como itálico, negretito, tachando, subrescrito.

Exemplo:
*texto

## Citações em bloco
são usadas para destacar uma citação ou bloco de texto.

Exemplo:
> Isso é uma citação em bloco.

## Linhas horizontais
são usadas para criar uma linha horizontal para separar seções do documento

Exemplo:

------

## códigos
Permitem inserir blocos de código ou destacar código dentro do texto.

Exemplo:

Use Creases (/`) para inserir codigo ´inline´.
'''
idade= 18
print(f" a idade é{18}").


## Tabelas
Criam tabelas organizadas em colunas e linhas.

Exemplo:

| Cabeçalho 1 | Cabeçalho 2 |
| ----------- | ------------|
| dado 1      | dado 2      |
| dado 3      | dado4       |

## Listas de Tarefas
Criam listas de tarafefas que podem marcados como concluidas ou pendentes.

Exemplo:

-[X] Tarefa concluída
-[] Tarefa Pendente

## Referências
permitem adicionar notas de rodapé para fornecer mais informações sobre conteúdo do documento.

Exemplo:
Aqui é um exemplo de marcação em rodapé[^1].

A aula é com o Ricardo[^2]

[^1] Rodapé: contudo 

## Notas de rodapé
## Alertas 
São usados para destacar informações importantes, com notas, avisos ou mensagens.

Exemplo: 
>**Note**
>esta é uma Nota


>[!NOTE]
>Destaca informaçôes que os usuários devem levar em cosideração, mesmo durante a leitura superficial.

>[!IMPORTANT]
>Informações cruciais necessárias para o sucesso do usuario.
