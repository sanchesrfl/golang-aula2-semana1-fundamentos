
- conversao entre tipos de dados

```go
var x int16 = 10
var y int64 = int64(x)
```


-  conversao entre floats

```go	
var a float32 = 3.14
var b float64 = float64(a)
```


- conversao entre float e inteiro

```go
var c float32 = 2.5
var d int16 = int16(c)

```

- conversao string para inteiro

```go	
strQualquer := "777"

numQualquer, err := strconv.Atoi(strQualquer)

-control de exceções
-se houver um erro
if err != nil {
	fmt.Println("Erro durante conversão de string em inteiro: ", err)
	return
}

fmt.Println("Numero inteiro: ", numQualquer)

```
