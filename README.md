# 🌙 MySweetHabit

<p align="center">
  <img src="https://img.shields.io/badge/MySweetHabit-Hábitos%20saludables-FF8FAB?style=for-the-badge" alt="MySweetHabit"/>
  <img src="https://img.shields.io/badge/ODS-03%20Salud%20y%20bienestar-4CAF50?style=for-the-badge" alt="ODS 3"/>
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-9370DB?style=for-the-badge" alt="Estado del proyecto"/>
</p>

<h3 align="center">Pequeños hábitos, grandes cambios.</h3>

<p align="center">
  Una plataforma web para descubrir tus hábitos, organizar tu tiempo y encontrar un mejor equilibrio entre el estudio y el descanso.
</p>

<p align="center">
  <a href="#-sobre-el-proyecto">Conocer el proyecto</a> ·
  <a href="#-funcionalidades">Funcionalidades</a> ·
  <a href="#-instalación">Instalación</a> ·
  <a href="#-hoja-de-ruta">Hoja de ruta</a>
</p>

---

## ✨ Sobre el proyecto

**MySweetHabit** es una plataforma web diseñada para ayudar a los estudiantes universitarios a registrar sus horas de sueño y estudio, comprender sus rutinas y visualizar sus hábitos mediante gráficos interactivos.

La vida universitaria puede implicar evaluaciones, trabajos, proyectos y largas jornadas de estudio. En ocasiones, el descanso queda en segundo plano. MySweetHabit busca que los estudiantes tengan una forma sencilla de observar cómo distribuyen su tiempo y reflexionar sobre sus hábitos cotidianos.

Además del seguimiento personal, la plataforma propone un dashboard con estadísticas anónimas y agregadas de la comunidad estudiantil, para conocer tendencias generales sin exponer la información individual.

> 🌱 El objetivo no es estudiar más horas a cualquier costo, sino encontrar un equilibrio más saludable entre el aprendizaje, el descanso y el bienestar.

## 🎯 Objetivo del proyecto

Desarrollar una herramienta digital accesible e intuitiva que promueva la conciencia sobre los hábitos de sueño y estudio de los estudiantes universitarios mediante el registro de información, la visualización de datos y la comparación anónima de estadísticas.

### 🌍 Objetivo de Desarrollo Sostenible

**ODS 3 — Salud y bienestar**

MySweetHabit se relaciona con el Objetivo de Desarrollo Sostenible 3 al fomentar la prevención, el bienestar y la reflexión sobre hábitos cotidianos relacionados con el descanso y la organización académica.

---

## 💡 ¿Por qué MySweetHabit?

<p align="center">
  <img src="https://img.shields.io/badge/01-REGISTRA-FF8FAB?style=flat-square" alt="Registra"/>
  <img src="https://img.shields.io/badge/02-ANALIZA-C4A1FF?style=flat-square" alt="Analiza"/>
  <img src="https://img.shields.io/badge/03-MEJORA-A8DADC?style=flat-square" alt="Mejora"/>
</p>

Muchos estudiantes organizan sus actividades académicas sin llevar un registro de cuánto tiempo dedican al estudio o al descanso.

MySweetHabit propone convertir esos datos cotidianos en información fácil de entender.

- 🌙 **Conoce tu descanso:** registra tus horas de sueño.
- 📚 **Organiza tu estudio:** observa cuánto tiempo dedicas a tus actividades académicas.
- 📊 **Visualiza tus hábitos:** interpreta tus registros mediante gráficos.
- 🌐 **Descubre tendencias:** consulta estadísticas generales de otros participantes.
- 🔒 **Protege tu privacidad:** utiliza comparaciones grupales sin mostrar información personal.

---

## 🚀 Funcionalidades

### 🌙 1. Registro de sueño

Registra las horas que duermes cada día para llevar un seguimiento de tus hábitos de descanso.

- Ingreso de horas de sueño.
- Registro organizado por fecha.
- Validación de los datos ingresados.
- Consulta de registros anteriores, según las funciones implementadas.

### 📚 2. Registro de estudio

Lleva un control sencillo del tiempo dedicado a tus actividades académicas.

- Registro de horas de estudio.
- Seguimiento diario.
- Comparación de las horas de sueño y estudio.
- Identificación de cambios en la rutina.

### 📊 3. Dashboard interactivo

Visualiza tus datos mediante gráficos que faciliten su interpretación.

Entre las visualizaciones propuestas se encuentran:

- Gráficos de barras para comparar sueño y estudio.
- Gráficos de líneas para observar cambios a lo largo del tiempo.
- Indicadores con promedios de horas registradas.
- Resúmenes visuales de los hábitos personales.

### 🌐 4. Estadísticas de la comunidad

Consulta información estadística anónima obtenida de los registros de los participantes.

Ejemplos de indicadores que podría mostrar la plataforma:

| Indicador | Información presentada |
|---|---|
| 🌙 Promedio de sueño | Horas promedio de descanso registradas |
| 📚 Tiempo de estudio | Promedio de horas de estudio |
| 📉 Descanso insuficiente | Porcentaje de participantes por debajo de un umbral definido |
| 📊 Comparación grupal | Diferencias entre grupos con suficientes respuestas |

*Los porcentajes y promedios se calcularán a partir de datos disponibles. No se presentarán cifras ilustrativas como resultados reales.*

### 🧭 5. Recomendaciones de hábitos

En futuras versiones, la plataforma podrá ofrecer sugerencias generales para organizar mejor el tiempo, mantener horarios regulares y prestar atención a los hábitos de descanso.

Estas recomendaciones serán educativas y no sustituirán una evaluación médica.

---

## 🖥️ Vista conceptual de la plataforma

La interfaz de MySweetHabit busca combinar simplicidad, claridad y una estética moderna.

```text
┌──────────────────────────────────────────────┐
│  🌙 MySweetHabit              Inicio  Perfil  │
├──────────────────────────────────────────────┤
│                                              │
│       Tus hábitos, en equilibrio.            │
│                                              │
│   Comprende tu rutina. Cuida tu bienestar.   │
│                                              │
│           [ Registrar mis hábitos ]          │
│                                              │
├──────────────────────────────────────────────┤
│                                              │
│  🌙 Sueño       📚 Estudio       📊 Progreso  │
│                                              │
│  [ Horas ]      [ Horas ]       [ Gráfico ]  │
│                                              │
├──────────────────────────────────────────────┤
│                                              │
│           Estadísticas de la comunidad       │
│                                              │
│        [ Gráficos y datos anónimos ]         │
│                                              │
└──────────────────────────────────────────────┘
```

*Este esquema es una representación conceptual del diseño esperado, no una captura de una aplicación terminada.*

---

## 🛠️ Tecnologías

Las siguientes herramientas se proponen para desarrollar el proyecto. Su incorporación dependerá de la implementación final.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js"/>
</p>

| Tecnología | Función |
|---|---|
| HTML5 | Estructura de las páginas y formularios |
| CSS3 | Diseño visual, colores, tarjetas y adaptación a pantallas |
| JavaScript | Lógica, validación y procesamiento de datos |
| Chart.js | Creación de gráficos interactivos |
| Firebase o Supabase | Almacenamiento compartido opcional |

### 🎨 Propuesta visual

La identidad visual de MySweetHabit puede utilizar una paleta pastel para crear una experiencia agradable y consistente.

| Color | Código | Aplicación sugerida |
|---|---|---|
| Rosa pastel | `#FF8FAB` | Botones y detalles destacados |
| Lavanda | `#C4A1FF` | Elementos secundarios |
| Celeste suave | `#A8DADC` | Indicadores y gráficos |
| Fondo claro | `#FFF9FB` | Fondo general |
| Texto oscuro | `#34313A` | Lectura y títulos |

---

## 📂 Estructura del proyecto

Una posible organización de los archivos es la siguiente:

```text
mysweethabit/
│
├── index.html
├── README.md
│
├── css/
│   └── styles.css
│
├── js/
│   ├── app.js
│   ├── tracker.js
│   └── dashboard.js
│
├── assets/
│   ├── images/
│   └── icons/
│
└── screenshots/
    └── dashboard.png
```

**Descripción de los archivos:**

- `index.html`: página principal de la plataforma.
- `css/styles.css`: estilos y diseño adaptable.
- `js/app.js`: lógica general de la aplicación.
- `js/tracker.js`: registro y validación de hábitos.
- `js/dashboard.js`: cálculos y visualizaciones.
- `assets/`: recursos gráficos.
- `screenshots/`: capturas de pantalla para documentar la aplicación.

*Esta estructura es una propuesta inicial y puede ajustarse al código real del proyecto.*

---

## ⚙️ Instalación

### Requisitos

- Un navegador web moderno.
- Visual Studio Code u otro editor de código.
- Git, si deseas clonar el repositorio.

### 1. Clonar el repositorio

```bash
git clone https://github.com/BeyondNate/MySweetHabit.git
```

Reemplaza `TU-USUARIO` por tu nombre de usuario de GitHub.

### 2. Entrar en la carpeta

```bash
cd mysweethabit
```

### 3. Abrir el proyecto

Si utilizas Visual Studio Code:

```bash
code .
```

### 4. Ejecutar la página

Si el proyecto utiliza HTML, CSS y JavaScript sin un servidor especial, abre `index.html` en tu navegador o utiliza la extensión Live Server.

> Nota: estos pasos corresponden a una estructura web básica. Si posteriormente se incorpora un backend o una base de datos, será necesario configurar sus credenciales y dependencias.

---

## 🔄 ¿Cómo funcionará?

El flujo principal de la plataforma se plantea de la siguiente manera:

**Paso 1 — Registrar**

El usuario introduce sus horas de sueño y estudio.

**Paso 2 — Validar**

La aplicación verifica que los valores ingresados sean válidos.

**Paso 3 — Procesar**

Los registros se utilizan para calcular promedios y otros indicadores.

**Paso 4 — Visualizar**

Los resultados se muestran mediante gráficos e indicadores.

**Paso 5 — Comparar**

Cuando exista suficiente información, el dashboard presenta estadísticas anónimas de la comunidad.

---

## 🔐 Privacidad y uso responsable de los datos

La privacidad será una consideración importante en el diseño de MySweetHabit.

- No solicitar nombres ni códigos universitarios para las funciones básicas.
- Informar claramente para qué se recopilan los datos.
- Solicitar consentimiento antes de recoger información personal.
- Limitar el acceso a los registros individuales.
- Presentar estadísticas comunitarias de forma agregada.
- Evitar mostrar resultados de grupos demasiado pequeños.
- No utilizar datos simulados como si fueran resultados reales.
- Permitir que los participantes conozcan cómo se utiliza su información.

MySweetHabit es una herramienta educativa de seguimiento de hábitos. No diagnostica trastornos del sueño ni determina el estado de salud de sus usuarios.

---

## 🗺️ Hoja de ruta

El desarrollo se realizará progresivamente, priorizando las funciones esenciales.

- [ ] 🎨 Diseñar la landing page y la interfaz principal.
- [ ] 📝 Crear el formulario de registro.
- [ ] 🌙 Implementar el seguimiento de horas de sueño.
- [ ] 📚 Implementar el seguimiento de horas de estudio.
- [ ] 📊 Crear gráficos con Chart.js.
- [ ] 🧮 Calcular estadísticas básicas.
- [ ] 🌐 Implementar estadísticas anónimas de la comunidad.
- [ ] 🔒 Revisar la privacidad y la validación de datos.
- [ ] 🧪 Probar el prototipo con usuarios voluntarios.
- [ ] 📱 Mejorar la adaptación a celulares y computadoras.
- [ ] 🚀 Evaluar la publicación de la plataforma en línea.

---

## 🧪 Pruebas y evaluación

Para evaluar el prototipo, se propone observar los siguientes indicadores:

| Indicador | ¿Qué permite evaluar? |
|---|---|
| Registros completados | Si el formulario resulta fácil de utilizar |
| Errores de validación | Si los datos se procesan correctamente |
| Gráficos generados | Si los indicadores se muestran correctamente |
| Opinión de los participantes | Si la interfaz es comprensible y útil |
| Protección de datos | Si se evita exponer información individual |

La evaluación inicial será exploratoria y permitirá identificar mejoras antes de ampliar el proyecto.

---

## 🤝 Contribuciones

¡Las ideas y sugerencias son bienvenidas!

Si deseas contribuir al proyecto:

1. Haz un fork del repositorio.
2. Crea una rama para tu modificación.
3. Realiza tus cambios.
4. Envía un pull request explicando tu propuesta.

Las contribuciones pueden incluir mejoras visuales, nuevas gráficas, correcciones, documentación o ideas para promover hábitos saludables.

---

## 📌 Alcance académico

MySweetHabit es un proyecto tecnológico relacionado con el **ODS 3: Salud y bienestar**.

Su propósito es desarrollar un prototipo web funcional que facilite el registro de hábitos de sueño y estudio y permita comprender datos agregados de la comunidad estudiantil.

El proyecto prioriza una solución accesible, de bajo costo y realizable con tecnologías web.

---

## 📄 Licencia

La licencia del proyecto está pendiente de definición.

Si deseas permitir que otras personas utilicen, modifiquen y distribuyan el código, puedes evaluar una licencia de código abierto, como MIT, antes de publicarlo formalmente.

---

<p align="center">
  <b>🌙 MySweetHabit</b>
  <br/>
  Pequeños hábitos. Mejores decisiones. Más bienestar.
  <br/><br/>
  <i>Desarrollado con dedicación para una vida universitaria más equilibrada.</i>
</p>
