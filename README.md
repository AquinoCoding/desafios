## Desafio

Precisamos desenvolver uma ferramenta para criação de Livros.

### 1. Interace HTTP REST API

Ações da API

- Criar livro
- Ler livro
- Remover livro
- Atualizar livro
- Listar livros
  - Filtrar por tags

Um livro possui os campos: 
```
{
  "id": // identificador
  "name" // texto do livro
  "tipo" // genero principal do livro
  "data_criacao" // data da criação do livro
  "data_modificacao" // data da última alteração do livro
  "tags" // tags vinculas ao livro acao
}
```

- Criar livro
- Ler livro
- Remover livro
- Atualizar livro

```
Uma tag possui os campos:
{
  "id" // identificador
  "name" // nome da tag
}
```

Temos uma estimativa de milhares de criações de livros diariamente. A preocupação com performance será avaliada.

### 2. CLI para importação dos livros

Necessitamos importar os conteúdos do nosso sistema de dados para gerar nossos livros e precisamos de uma ferramenta para auxiliar essa tarefa.


Dado um csv de "livros", faça um CLI (Command Line Interface) que importe os dados para o Insights.

CSV exemplo:

```
text,tag
Lorem ipsum dolor sit amet., tag1;tag2;tag3
Mauris fringilla non quam vel lacinia,tag3
Cras in tempus libero,
```

### 3. CLI para exportação dos livros

Necessitamos exportar os conteúdos do nosso sistema de dados para gerar nossos livros e precisamos de uma ferramenta para auxiliar essa tarefa.


Dado um csv de "livros", faça um CLI (Command Line Interface) que exporte os dados.

CSV exemplo:

```
text,tag
Lorem ipsum dolor sit amet., tag1;tag2;tag3
Mauris fringilla non quam vel lacinia,tag3
Cras in tempus libero,
```
