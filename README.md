<p align="center"> <img src="https://imgur.com/mIBmcEL.png" alt="Javascript: validando formulários"> </p>

<hr>

<p align="center"> <img src="https://github.com/MonicaHillman/aluraplay-requisicoes/blob/main/img/logo.png" alt="Logo da Alura"> </p>
<p align="center">Formulário de criação de contas para o banco virtual MoniBank.</p>

## Tecnologias utilizadas durante o curso
* JavaScript

## Tecnologias utilizadas no projeto
* HTML
* CSS

## O que estou aprendendo?

### Pattern
```
    \d{3}\.?\d{3}\.?\d{3}-?\d{2}
```
`\d{3}\`: Encontra um número de 0-9 por 3 vezes.  
`.?`: Seguido por um ponto opcional.  
`-?`: Seguido por um hífen opcional.  
`\d{2}`: Encontra um número de 0-9 por 2 vezes.  

### Modularização
Separaremos cada motivação em um arquivo diferente, que serão unidos em um único script. Esta técnica se chama **modularização**. Para que ela funcione corretamente, precisamos especificar o tipo `module`.
```
    <script src="../js/script.js" type="module"></script>
```

### replace()
1º parâmetro: O que queremos substituir.  
2º parâmentro: Pelo o que queremos substituir.  

```
    replace(,"");
```

### Validity State
Usando o método `setCustomValidity()` altera o valor de `customError`.