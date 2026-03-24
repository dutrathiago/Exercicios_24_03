# Guia Básico de CSS

Este projeto demonstra conceitos essenciais de CSS (Cascading Style Sheets), incluindo:

## 1. CSS Interno

O CSS interno é definido dentro da própria página HTML, utilizando a tag `<style>` dentro da seção `<head>`.

Exemplo:

```html
<style>
  p {
    color: blue;
  }
</style>
```

✔ Vantagem: fácil para testes rápidos
❌ Desvantagem: não reutilizável em outras páginas

---

## 2. CSS Externo

O CSS externo é colocado em um arquivo separado (`.css`) e vinculado ao HTML.

Exemplo:

```html
<link rel="stylesheet" href="styles.css" />
```

✔ Vantagem: reutilização e organização
❌ Desvantagem: requer arquivo adicional

---

## 3. Seletores CSS

Seletores definem quais elementos HTML receberão estilos.

### 5 Tipos de Seletores:

### 1. Seletor de Elemento

Aplica estilo a todas as tags de um tipo.

```css
p {
  color: red;
}
```

---

### 2. Seletor de Classe

Aplica estilo a elementos com uma classe específica.

```css
.titulo {
  font-size: 24px;
}
```

---

### 3. Seletor de ID

Aplica estilo a um único elemento.

```css
#principal {
  background: gray;
}
```

---

### 4. Seletor Descendente

Seleciona elementos dentro de outros elementos.

```css
div p {
  color: green;
}
```

---

### 5. Seletor de Atributo

Seleciona elementos com base em atributos.

```css
input[type="text"] {
  border: 1px solid black;
}
```

---

## Conclusão

O CSS permite estilizar páginas web de forma poderosa e organizada. Com o uso correto de seletores e tipos de aplicação (interno, externo e inline), é possível criar interfaces modernas e eficientes.
