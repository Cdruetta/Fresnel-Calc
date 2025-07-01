
# Fresnel-Calc - Zona Fresnel (HTML)

Este proyecto es una calculadora visual para determinar la **Zona de Fresnel** entre dos puntos, útil para evaluar la visibilidad en enlaces inalámbricos (Wi-Fi, microondas, etc.). Se trata de una herramienta simple en HTML, CSS y JavaScript que permite ingresar parámetros de distancia, altura y frecuencia para visualizar el perfil de la zona de Fresnel.

## 📐 ¿Qué es la zona de Fresnel?

La **Zona de Fresnel** es un área elíptica alrededor de la línea de visión directa entre un transmisor y un receptor. Si hay obstáculos dentro de esta zona, pueden producirse interferencias o pérdida de señal. Esta herramienta ayuda a calcular y visualizar esa zona para mejorar el diseño de enlaces inalámbricos.

## 🔧 Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (puro, sin frameworks)
- Canvas para el gráfico
- Math.js para cálculos matemáticos

## 🚀 Cómo usarlo

1. Cloná el repositorio o descargá los archivos:

```bash
git clone https://github.com/Cdruetta/Fresnel-Calc.git
```

2. Ingresá a la carpeta del proyecto:

```bash
cd "Fresnel-Calc/zona fresnal html"
```

3. Abrí el archivo `index.html` en tu navegador:

```bash
# O bien abrilo desde tu explorador de archivos
start index.html  # En Windows
xdg-open index.html  # En Linux
```

4. Ingresá los siguientes datos en el formulario:
   - **Distancia entre antenas (km)**
   - **Altura de la antena A (m)**
   - **Altura de la antena B (m)**
   - **Frecuencia (MHz)**

5. Hacé clic en **"Calcular"** para ver la gráfica de la zona de Fresnel.

## 📸 Captura de pantalla

<!-- Podés agregar una imagen llamada screenshot.png aquí -->
<!-- ![captura](screenshot.png) -->

## 📁 Estructura de archivos

```
zona fresnal html/
├── index.html        # Página principal
├── style.css         # Estilos del proyecto
├── script.js         # Lógica de cálculo y renderizado
└── math.min.js       # Librería matemática externa
```

## 📚 Fuentes consultadas

- https://es.wikipedia.org/wiki/Zona_de_Fresnel
- Documentación técnica sobre enlaces inalámbricos
- Fórmula de la zona de Fresnel:  
  ![Fórmula](https://wikimedia.org/api/rest_v1/media/math/render/svg/26326f09dc196556c80937f8269c708a3a3e6a1a)

## 🧑‍💻 Autor

**Cristian Druetta** – [@Cdruetta](https://github.com/Cdruetta)  
Proyecto creado con fines educativos y de práctica personal.

## 📄 Licencia

Este proyecto está licenciado bajo la [MIT License](../LICENSE).
