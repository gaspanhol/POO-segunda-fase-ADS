# Markdown
- introdução
- segundo
- terceiro

## Lista numerada

1. primeiro
1. segundo
1. terceiro

## trechos de códigos

```bash
# Criando diretório
mkdir primeiro
cd primeiro

# Iniciando repositório
git init
git branch -m master main
git config --global user.name GabrielSpanholAbreu
git config --global user.email gabriel.a2004@aluno.ifsc.edu.br
git config --global alias.tree "log --oneline --graph --decorate --all"

#Criando arquivo e aplicando commit
echo "ola, mundo!" > ola.txt
ls -l
cat ola.txt
git status
git add ola.txt
git commit -m "Criação do ola.txt"
git status
git tree

```

### Olá mundo em java
```java
public class Ola {
    IO.print("Olá, mundo!");
}

```