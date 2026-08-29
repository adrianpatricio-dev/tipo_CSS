# TIPOS DE CSS

## 📌 Sobre o projeto

Este projeto apresenta os três principais tipos de aplicação de **CSS (Cascading Style Sheets)** em páginas HTML:

* **CSS Inline**
* **CSS Interno**
* **CSS Externo**

O objetivo é demonstrar, de forma prática, como cada tipo de CSS funciona e como ele pode ser utilizado para estilizar elementos de uma página web.

## 🎯 Objetivo

Compreender as diferentes formas de aplicar CSS em um documento HTML, identificando suas características, diferenças e formas de utilização.

## 📚 Tipos de CSS

### 1. CSS Inline

O **CSS Inline** é aplicado diretamente dentro da tag HTML, utilizando o atributo `style`.

Exemplo:

```html
<p style="color: blue;">Texto em azul</p>
```

É indicado para alterações específicas em um único elemento.

---

### 2. CSS Interno

O **CSS Interno** é definido dentro da própria página HTML, geralmente utilizando a tag `<style>` dentro do `<head>`.

Exemplo:

```html
<style>
    p {
        color: blue;
    }
</style>
```

Esse método permite aplicar estilos a vários elementos presentes na mesma página.

---

### 3. CSS Externo

O **CSS Externo** utiliza um arquivo separado, normalmente com a extensão `.css`, que é conectado ao documento HTML por meio da tag `<link>`.

Exemplo no HTML:

```html
<link rel="stylesheet" href="style.css">
```

Exemplo no arquivo `style.css`:

```css
p {
    color: blue;
}
```

É uma abordagem bastante utilizada em projetos maiores, pois facilita a organização e a manutenção dos estilos.

## 📊 Comparação

| Tipo    | Localização             | Principal característica               |
| ------- | ----------------------- | -------------------------------------- |
| Inline  | Dentro da tag HTML      | Estilização de um elemento específico  |
| Interno | Dentro da tag `<style>` | Estilos aplicados à página             |
| Externo | Arquivo `.css` separado | Organização e reutilização dos estilos |

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
