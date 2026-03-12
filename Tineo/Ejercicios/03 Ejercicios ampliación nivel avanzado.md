Perfecto, Belén.  
Aquí tienes **los ejercicios para las alumnas más avanzadas**, uno por cada día del curso, junto con **sus plantillas listas para imprimir**.  
Estos ejercicios están diseñados para:

- Retar a las alumnas que ya dominan Word a nivel avanzado.  
- Profundizar en automatización, diseño, macros, referencias complejas, datos externos, HTML, etc.  
- Mantener el hilo conductor del vivero y del mundo rural.  
- Permitir que trabajen de forma autónoma mientras el resto del grupo avanza.

Todo está en **Markdown**, limpio y listo para GitHub.

---

# 🌱 EJERCICIOS PARA ALUMNAS AVANZADAS  
## (Con plantillas imprimibles)

---

# 🌼 **DÍA 1 – Tablas avanzadas con cálculos, estilos y vínculos**

## 🧩 **Ejercicio avanzado**
Crear un **inventario inteligente del vivero** que incluya:

- Tablas con estilos personalizados  
- Fórmulas dentro de la tabla (SUMA, PROMEDIO)  
- Celdas con formato condicional manual (colores según stock)  
- Hipervínculos internos a fichas de plantas  
- Imágenes alineadas dentro de celdas  
- Tablas anidadas para variedades  

### 📄 **Plantilla imprimible**

```
INVENTARIO AVANZADO – VIVERO “LA FLOR DEL NARCEA”

1. PLANTAS DE HUERTA
───────────────────────────────────────────────
| Variedad     | Precio | Stock | Total (€) | Ficha |
|--------------|--------|--------|-----------|--------|
| Lechuga      | 1,20   |   50   | =1,20*50  | [Ver]  |
| Tomate       | 1,50   |   40   | =1,50*40  | [Ver]  |
| Pimiento     | 1,80   |   30   | =1,80*30  | [Ver]  |

TOTAL STOCK: =SUMA(C2:C4)
PRECIO MEDIO: =PROMEDIO(B2:B4)

2. VARIEDADES DETALLADAS (TABLA ANIDADA)
───────────────────────────────────────────────
| Variedad | Tipo | Imagen |
|----------|------|--------|
| Cherry   | Tomate | [img] |
| Roma     | Tomate | [img] |

3. HIPERVÍNCULOS INTERNOS
───────────────────────────────────────────────
Crear un marcador para cada ficha y enlazar desde la tabla.
```

---

# 🌼 **DÍA 2 – Folleto profesional con diseño editorial**

## 🧩 **Ejercicio avanzado**
Diseñar un **folleto profesional** del vivero con:

- 3 columnas equilibradas  
- Portada con imagen a toda página  
- Tipografías combinadas (títulos, subtítulos, cuerpo)  
- Autoformas con degradados  
- Cuadros de texto flotantes  
- Numeración de página personalizada  
- Encabezado y pie con logotipo  

### 📄 **Plantilla imprimible**

```
FOLLETO PROFESIONAL – VIVERO “LA FLOR DEL NARCEA”

PORTADA
───────────────────────────────────────────────
[Imagen a toda página]
Título grande:
CAMPAÑA DE PRIMAVERA 2024

INTERIOR – 3 COLUMNAS
───────────────────────────────────────────────
Columna 1:
Descripción general del vivero.

Columna 2:
Autoforma con degradado:
“OFERTAS ESPECIALES”

Columna 3:
Cuadro de texto flotante:
“Horario: 9:00–14:00”

PIE DE PÁGINA
───────────────────────────────────────────────
[Logotipo] – Página X de Y
```

---

# 🌼 **DÍA 3 – Informe avanzado con gráficos combinados y SmartArt complejo**

## 🧩 **Ejercicio avanzado**
Crear un **informe de ventas del vivero** con:

- Gráfico combinado (líneas + columnas)  
- Gráfico de dispersión para comparar crecimiento  
- SmartArt jerárquico con imágenes  
- Diagrama de flujo con conectores personalizados  
- Estilos de gráfico modificados manualmente  

### 📄 **Plantilla imprimible**

```
INFORME AVANZADO DE VENTAS – VIVERO

1. GRÁFICO COMBINADO
───────────────────────────────────────────────
Datos:
| Mes | Ventas | Temperatura media |
|-----|--------|-------------------|
| Ene |  120   |        8°C        |
| Feb |  180   |       10°C        |
| Mar |  260   |       14°C        |

2. GRÁFICO DE DISPERSIÓN
───────────────────────────────────────────────
Comparar crecimiento de plantas:
| Planta | Altura (cm) | Días |
|--------|--------------|------|

3. SMARTART JERÁRQUICO
───────────────────────────────────────────────
Organigrama con imágenes de cada responsable.

4. DIAGRAMA DE FLUJO
───────────────────────────────────────────────
[Pedido] → [Preparación] → [Control] → [Entrega]
```

---

# 🌼 **DÍA 4 – Documento maestro con subdocumentos y referencias complejas**

## 🧩 **Ejercicio avanzado**
Crear un **manual técnico del vivero** con:

- Documento maestro  
- 5 subdocumentos  
- Referencias cruzadas entre capítulos  
- Notas al pie y notas al final  
- Tabla de contenido + tabla de ilustraciones  
- Encabezados distintos por sección  

### 📄 **Plantilla imprimible**

```
MANUAL TÉCNICO – VIVERO “LA FLOR DEL NARCEA”

DOCUMENTO MAESTRO
───────────────────────────────────────────────
Subdocumentos:
1. Preparación del terreno
2. Siembra
3. Riego
4. Control de plagas
5. Cosecha

REFERENCIAS
───────────────────────────────────────────────
Insertar referencia cruzada:
“Ver sección ‘Riego’ en la página ___.”

NOTAS
───────────────────────────────────────────────
Nota al pie:
_______________________________________________

Nota al final:
_______________________________________________

TABLAS AUTOMÁTICAS
───────────────────────────────────────────────
• Tabla de contenido
• Tabla de ilustraciones
```

---

# 🌼 **DÍA 5 – Macros avanzadas y automatización**

## 🧩 **Ejercicio avanzado**
Crear un sistema automatizado para el vivero:

- Macro que genera una ficha de planta desde cero  
- Macro que inserta imagen automáticamente desde una carpeta  
- Macro que aplica formato profesional  
- Macro que guarda el archivo con nombre automático  
- Botones personalizados en la cinta  

### 📄 **Plantilla imprimible**

```
MACROS AVANZADAS – SISTEMA DE FICHAS

1. MACRO “CrearFicha”
───────────────────────────────────────────────
Debe:
• Crear título
• Insertar tabla
• Aplicar estilo
• Insertar fecha automática

2. MACRO “InsertarImagen”
───────────────────────────────────────────────
Ruta sugerida:
C:\Vivero\Imagenes\«Variedad».jpg

3. MACRO “GuardarFicha”
───────────────────────────────────────────────
Guardar como:
Ficha_«Variedad».docx

4. BOTONES PERSONALIZADOS
───────────────────────────────────────────────
Crear grupo:
“Fichas del vivero”
```

---

# 🌼 **DÍA 6 – Revisión avanzada y seguridad profesional**

## 🧩 **Ejercicio avanzado**
Revisar un documento complejo con:

- Control de cambios con colores personalizados  
- Comparación de 3 versiones  
- Combinación de revisiones  
- Protección con contraseña y restricciones por sección  
- Comentarios encadenados  
- Panel de revisiones  

### 📄 **Plantilla imprimible**

```
REVISIÓN AVANZADA – DOCUMENTO DE PROYECTO

1. ACTIVAR CONTROL DE CAMBIOS
───────────────────────────────────────────────
Color personalizado: Verde

2. COMPARAR VERSIONES
───────────────────────────────────────────────
Versiones:
• Proyecto_v1
• Proyecto_v2
• Proyecto_v3

3. COMBINAR CAMBIOS
───────────────────────────────────────────────
Resultado final:
_______________________________________________

4. PROTECCIÓN
───────────────────────────────────────────────
• Contraseña
• Secciones bloqueadas
```

---

# 🌼 **DÍA 7 – Correspondencia avanzada con múltiples orígenes de datos**

## 🧩 **Ejercicio avanzado**
Crear un sistema de correspondencia para el vivero:

- Origen de datos en Excel  
- Segundo origen de datos en Outlook  
- Filtros avanzados (por localidad, tipo de planta, gasto)  
- Campos condicionales (IF…THEN…ELSE)  
- Sobres y etiquetas personalizadas  
- Combinación en lote  

### 📄 **Plantilla imprimible**

```
CORRESPONDENCIA AVANZADA – VIVERO

1. ORIGEN DE DATOS (EXCEL)
───────────────────────────────────────────────
| Nombre | Email | Localidad | Gasto | Tipo |

2. ORIGEN DE DATOS (OUTLOOK)
───────────────────────────────────────────────
Lista de contactos del vivero.

3. FILTROS AVANZADOS
───────────────────────────────────────────────
• Localidad = Tineo
• Gasto > 50 €

4. CAMPOS CONDICIONALES
───────────────────────────────────────────────
IF Tipo = “Aromática”
THEN “Gracias por comprar aromáticas”
ELSE “Gracias por su compra”
```

---

# 🌼 **DÍA 8 – HTML avanzado e IA aplicada**

## 🧩 **Ejercicio avanzado**
Crear una **minipágina web profesional** del vivero:

- Hipervínculos internos y externos  
- Anclas y navegación  
- Estilos CSS básicos  
- Conversión a HTML  
- Revisión con IA (resumen, reescritura, mejora de estilo)  

### 📄 **Plantilla imprimible**

```
PÁGINA WEB AVANZADA – VIVERO

TÍTULO
───────────────────────────────────────────────
<h1>Vivero La Flor del Narcea</h1>

SECCIONES
───────────────────────────────────────────────
<a name="huerta"></a>
<h2>Plantas de Huerta</h2>

<a name="aromaticas"></a>
<h2>Aromáticas</h2>

ENLACES
───────────────────────────────────────────────
<a href="#huerta">Ir a Huerta</a>
<a href="https://www.tineo.es">Ayuntamiento</a>

CSS BÁSICO
───────────────────────────────────────────────
<style>
h1 { color: green; }
p { font-family: Calibri; }
</style>
```

---

# 🌻 ¿Quieres que prepare también…?

- Las **versiones en Word con estilos aplicados**  
- Los **archivos base del vivero**  
- Un **cuaderno completo del curso** con todos los ejercicios  
- Las **rúbricas de evaluación**  

Solo dímelo y lo preparo encantada.
