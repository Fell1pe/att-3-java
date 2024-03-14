
# ANÁLISE DE CÓDIGO EM JAVASCRIPT

## [exemplo.html](exemplo.html)
### Função do Código

Este código JavaScript exibe a URL completa da página atual no navegador.

### Como Funciona

O código funciona em duas etapas:

1. **Obter a URL:**
    - A propriedade `href` do objeto `window.location` é acessada. Essa propriedade contém a URL completa da página.
2. **Exibir a URL:**
    - A função `document.write()` é utilizada para escrever o valor da URL no corpo da página, onde o código está presente.

### Exemplo

Se a URL da página for `https://www.exemplo.com/pagina`, o código irá gerar a seguinte saída:

```
https://www.exemplo.com/pagina
```

## [exemplo2.html](exemplo2.html)

### Função do Código

Este código JavaScript exibe a data e hora atual na página web.

### Como Funciona

O código funciona de duas maneiras:

**Usando `document.write()`:**

* A função `document.write()` escreve a data e hora atual diretamente no corpo da página HTML.
* Esta é uma maneira simples de exibir a data e hora, mas não é recomendada para uso em projetos modernos.

### Código

```html
<div id="current-date-time"></div>
```


