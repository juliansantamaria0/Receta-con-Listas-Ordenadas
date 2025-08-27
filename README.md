# Autor
Julian Andres Santamaria Bustamante

# 🍰 Receta con Listas Ordenadas HTML
## 🎯 Objetivo
Crear una receta sencilla utilizando **listas ordenadas (`<ol>`)**, aplicando diferentes atributos (`type`, `start`, `reversed`) y explorando listas **anidadas**.

## 📋 Instrucciones

### 1. Crear archivo base
```html
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>Receta de Pastel</title>
</head>
<body>
  <h1>Receta de Pastel de Chocolate</h1>
</body>
</html>
```

### 2. Lista ordenada básica
```html
<h2>Pasos principales</h2>
<ol>
  <li>Preparar los ingredientes</li>
  <li>Mezclar la masa</li>
  <li>Hornear el pastel</li>
  <li>Decorar y servir</li>
</ol>
```

### 3. Cambiar estilo con `type`
```html
<ol type="I">
  <li>Preparar los ingredientes</li>
  <li>Mezclar la masa</li>
  <li>Hornear el pastel</li>
  <li>Decorar y servir</li>
</ol>
```

### 4. Crear sublista anidada
```html
<ol type="I">
  <li>Preparar los ingredientes
    <ol type="a">
      <li>Harina</li>
      <li>Huevos</li>
      <li>Leche</li>
      <li>Chocolate</li>
    </ol>
  </li>
  <!-- resto de elementos... -->
</ol>
```

### 5. Continuar numeración con `start`
```html
<h2>Pasos extra</h2>
<ol start="5">
  <li>Dejar enfriar el pastel</li>
  <li>Añadir toppings adicionales</li>
</ol>
```

### 6. Lista regresiva con `reversed`
```html
<h2>Tiempo de espera (minutos)</h2>
<ol reversed>
  <li>5 minutos</li>
  <li>4 minutos</li>
  <li>3 minutos</li>
  <li>2 minutos</li>
  <li>1 minuto</li>
</ol>
```

## 🔧 Atributos de `<ol>`

| Atributo | Valores | Descripción |
|----------|---------|-------------|
| `type` | `1`, `A`, `a`, `I`, `i` | Tipo de numeración |
| `start` | Número entero | Número inicial |
| `reversed` | - | Orden descendente |

## ✅ Checklist
- [ ] Archivo HTML creado
- [ ] Lista ordenada básica
- [ ] Atributo `type` aplicado
- [ ] Sublista anidada creada
- [ ] Atributo `start` usado
- [ ] Lista `reversed` implementada