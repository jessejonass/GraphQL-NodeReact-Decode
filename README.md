# Decode GraphQL

- Linguagem para criação de Queries -> operações de escrita ou leitura
- O Graph vem de Grafo -> pontos que se conectam
- Serve pra realizar operações de escrita e leitura através
  da comunicação do Front com o Back _Tipo o Rest_
- é um conjunto de padrões meio diferentão de comunicação Front <-> Back

### Problemas que o GraphQL resolve

    - Overfetching
    - Underfetching
    - Backend quem diz pro Frontend quais dados ele vai ter

```GQL quem diz pro Backend quais dados quer
query {
	users {
		id
		nome
		github

		adresses {
			city
			state
			country
		}
	}
}
```

### Problemas do GraphQL

    - Maior complexidade por conta de padrões e primeiros passos
    - Trabalhar com cache é mais difícil no GraphQL do que com o REST
    - Erros retornados são mais difíceis de serem tratados
