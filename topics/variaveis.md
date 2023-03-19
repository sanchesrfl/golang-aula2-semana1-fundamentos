### declaração de variaveis e suas diferentes formas

- declaração tipada sem atribuição de valor inicial

```go
var x int
```

- atribuindo valor a variavel inicializada anteriormente

```go
var x int
x = 5
```

- declaração tipada com atribuição de valor inicial

```go
var y int = 3
```

- declarações curtas de variaveis

```go	
a := 20
b, c := "go", "lang"
```


- declaração do tipo + declação da variavel

```go	
type idade int
var x idade = 5
fmt.Println(x)
```


- declaração de variaveis em bloco

```go
var (
	x int    = 3
	y string = "golang"
	z bool   = true
)
```
	
