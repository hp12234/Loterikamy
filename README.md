# Loterikamy
Simulador de loteria que o usuario escolhe sei numeros e o programa sorteria outro seis numeros e após isso verificica a quantide de acertos!!!

## Tecnologias Utilizadas 
- **HTML:** Estrutura do SITE
- **CSS:** Estilos do Site
- **JS:** Funções do Site
- ~~;BootStrap~~: Não foi utilizada


### Melhorias Possiveis 

1. [x] Subir no github pages
2. [ ] Trocar o Alert pro mensagens mais amigaveis
3. [ ] Realizar test para descobrir bugs 🐱‍👤

#### disponivel em:
[GitHubPage](https://hp12234.github.io/Loterikamy/)


### Prints da Tela do WebApp

| Tela inicial | Primeira Rodada |
|------------- |-----------------|
| ![tela inicial do site](/img/minhatela.png)     | 
 
 ![tela inicial do site](https://raw.githubusercontent.com/hp12234/Loterikamy/master/img/tela%202.png)    |   


### codigo principal

``` js:
function verificaAcertos() {
    let cont = 0
    numDig.forEach(function (valor, index) {
        if (numSort.includes(valor)) {
            cont = cont + 1

        }

    });
    document.getElementById("total").innerText = cont
}

```