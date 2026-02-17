# Aprendendo Markdown e utilizando o mesmo repositório com várias pessoas no GitHub

## Github em conjunto
Nessa parte da aula nosso grupo composto por 4 pessoas precisou criar um repositório do zero e após isso cada um dos membros deveria adicionar um .txt com seu nome ao repositório, afim de praticar git pull e git push nos momentos que houvessem conflitos.

## Markdown
Abaixo a demonstração de como funcionam algumas funções do Markdown:

## Listas

podemos utilizar +, - ou *

+ primeiro
- segundo
* terceiro

para ordenar, utilizamos números

1. primeiro
2. segundo
3. terceiro

## Trechos de código
### Olá mundo em Java

```java
public class Ola{
    public static void main String[] args {
        System.out.println("Olá Mundo!")
    }
}
```
Para criar trechos de codigo ou texto, basta abrir ela com ```, digitar o conteudo do trecho e fechar ele com ```

# Formatação de texto e ALERTS
### Formatação de texto
Você pode indicar ênfase com negrito, itálico, strikethrough, subscrito ou texto sobrescrito em campos de comentário e .md ficheiros.

Bold	** ** or __ __ **teste**

Italic	* * or _ _ *teste*

Strikethrough	~~ ~~ or ~ ~ ~teste~

Bold and nested italic	** ** and _ _  **_teste_**

All bold and italic	*** ***

Subscript	< sub > < /sub >  <sub> teste </sub> 

Superscript	< sup > < /sup >    <sup> teste</sup>


Underline	< ins > < /ins >    <ins> teste</ins>


### ALERTS

Alertas, também às vezes conhecidos como callouts ou admoestações, são uma extensão Markdown baseada na sintaxe blockquote que você pode usar para enfatizar informações críticas. No GitHub, eles são exibidos com cores e ícones distintos para indicar o significado do conteúdo.

Use alertas apenas quando eles são cruciais para o sucesso do usuário e limitá-los a um ou dois por artigo para evitar sobrecarregar o leitor. Além disso, você deve evitar colocar alertas consecutivamente. Os alertas não podem ser aninhados em outros elementos.

Para adicionar um alerta, use uma linha de blockquote especial especificando o tipo de alerta, seguida das informações de alerta em uma blockquote padrão. Cinco tipos de alertas estão disponíveis:

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.



## Figuras

- Para adicionar uma imagem se deve utilizar o simbolo ! na frente. Para adicionar um comentário a imagem vocẽ deve colocalo entre [] e o link da imagem que vai ser carregada deve ser colocada entre ()

![Imagem do mascote do java](mascoteJava.jpeg)
