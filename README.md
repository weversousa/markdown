# Nível de Titulos
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
***

# Negrito
```
**Texto**
__Texto__
```
**Texto**  
__Texto__

***

# Itálico
```
*Texto*
_Texto_
```
*Texto*  
_Texto_

***

# Negrito e Itálico
```
**_Texto_**
__*Texto*__
```

***

# Riscado
```
~~Texto~~
```
~~Texto~~

***

** 2 espaços** quebram a linha.  
`***` criam uma linha divisória horizontal.

***

# Lista **enumerada**:
1. Frutas
   1. Banana
   2. Maçã
   3. Uva 
2. Legumes
3. Bebidas

Obs: Não importa o valor numérico, e sim o padrão de **um número e um ponto**. O padrão sendo seguido mesmo que você insira tudo como número 1, ele vai criar uma lista ordenada quando renderizado. E se na próxima linha você inserir **3 espaços** antes do **número e ponto** será criada uma sublista para o valor de cima.  
```
1. São Paulo
1. Santos
1. Palmeiras
1. Corinthians
```
1. São Paulo
1. Santos
1. Palmeiras
1. Corinthians

***

# Lista **demarcada**:
```
* Preta
* Branca
* Vermelha
* Azul
   * Marinho
```
* Preta
* Branca
* Vermelha
* Azul
   * Marinho

***

# Lista de Tarefas:
```
- [ ] Estudar Python
- [x] Estudar ECMAScript
- [ ] Estudar Java
```
- [ ] Estudar Python
- [x] Estudar ECMAScript
- [ ] Estudar Java

***

# Link
```
[Criando um link para a página principal do meu Github](https://github.com/weversousa.github.io)
```
[Criando um link para a página principal do meu Github](https://github.com/weversousa.github.io)

***

# Tabelas:
```
Classificação | Time | Pontos
--- | --- | ---
1º | São Paulo | 30
2º | Santos | 26
3º | Palmeiras | 20
4º | Corinthians | 15
```
Classificação | Time | Pontos
--- | --- | ---
1º | São Paulo | 30
2º | Santos | 26
3º | Palmeiras | 20
4º | Corinthians | 15

```
Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3
:--- | :---: | ---:
Esquerda | Centralizado | Direita
```
Cabeçalho 1 | Cabeçalho 2 | Cabeçalho 3
:--- | :---: | ---:
Esquerda | Centralizado | Direita

***

# Usar crases para destacar comandos
```
Esse é um comando em Python `print("Olá mundo!")`
```
Esse é um comando em Python `print("Olá mundo!")`

***

# Inserir trechos de códigos
```
\```python
from flask import Flask

app = Flask(__name__)
\```
```
**Obs**: A barra invertida `\` é somente para escapar as **crases** que estão dentro de outra **crase**. Não usar.  
```python
from flask import Flask

app = Flask(__name__)
```

```javascript
const buttonLogin = docomunt.getElementById("buttonLogin")
```

***
Para inserir Emojis, utilize `:nome_emoji:` 🖖  
[Perfil da ikatyang que possui todos os Emojis](https://github.com/ikatyang/emoji-cheat-sheet)

***

# Imagem
Para inserir imagens podemos usar uma URL existente, ou também arrastar uma imagem nossa para o campo abaixo onde está escrito: **Attach files by dragging...**  
![spfc](https://user-images.githubusercontent.com/69995549/138879665-4aa8bcb9-bf58-4218-b236-4f530a2a6353.png)  

O código abaixo é criado pelo github caso a gente arraste um aimagem para campo informado na explicação acima.
```
![spfc](https://user-images.githubusercontent.com/69995549/138879665-4aa8bcb9-bf58-4218-b236-4f530a2a6353.png)
```

Caso a gente queira usar uma imagem com URL da web é só seguir o mesmo padrão abaixo.
```
![Texto](URL)
```

Não usar imagens grandes (recomendado), passando de 400 de largura já não é "muito recomendado".
