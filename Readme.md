# Conceitos de CSS

## CSS Interno

O CSS interno é definido dentro da própria página HTML, utilizando a tag `<style>` dentro da seção `<head>`. Ele serve para estilizar apenas aquela página específica.

### Exemplo:

```html
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
```

---

## CSS Externo

O CSS externo é feito em um arquivo separado (com extensão `.css`) e conectado ao HTML através da tag `<link>`. Ele permite reutilizar estilos em várias páginas.

### Exemplo:

```html
<head>
  <link rel="stylesheet" href="style.css">
</head>
```

---

## Seletores CSS

Seletores CSS são usados para definir quais elementos HTML receberão estilos.

### 1. Seletor de elemento

Seleciona todos os elementos de um tipo.

```css
p {
  color: red;
}
```

---

### 2. Seletor de classe

Seleciona elementos com uma classe específica.

```css
.destaque {
  background-color: yellow;
}
```

---

### 3. Seletor de ID

Seleciona um elemento único.

```css
#titulo {
  color: blue;
}
```

---

### 4. Seletor descendente

Seleciona elementos dentro de outros elementos.

```css
div p {
  font-style: italic;
}
```

---

### 5. Pseudo-classe

Seleciona elementos em um estado específico.

```css
a:hover {
  color: green;
}
```

---

## Conclusão

O CSS permite estilizar páginas web de forma organizada. O uso correto dos seletores facilita a aplicação dos estilos.
