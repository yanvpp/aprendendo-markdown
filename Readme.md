# Aprendendo Markdown 

## Figuras

![mascote do java](./img.png)
- Hiago 
- Yan
- Vinicius

## Trechos de código

``` bash

# Criar um diretorio
mkdir aprendendo-markdown
cd aprendendo-markdown

# Iniciando repositório
git init

# Criando um arquivo
echo "nome" > nome.txt

# Adicionando arquivo para ir para o commit
git add nome.txt

# Fazendo commit
git commit -m "Criando arquivo nome.txt"

# Adicionando texto no arquivo
echo "Olá, nome!" >> nome.txt

# Adicionando arquivo para commmit
git add nome.txt

# Fazendo commit
git commit -m "Adicionando nome ao arquivo nome.txt"
```
## Listas

Esse são exemplos de listas não ordenadas
- George Washington
* John Adams
+ Thomas Jefferson

Esse são exemplos de listas ordenadas 
1. James Madison
2. James Monroe
3. John Quincy Adams

Exemplo de lista aninhada
1. First list item
   - First nested list item
     - Second nested list item

Exemplo de check list
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
