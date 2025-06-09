# Sistema Experto Turístico para Río Grande

Este proyecto tiene como objetivo desarrollar un **sistema experto** capaz de recomendar lugares turísticos de la ciudad de **Río Grande, Tierra del Fuego**, según las preferencias de los usuarios.

## 📌 Objetivos del sistema

- Brindar recomendaciones personalizadas a turistas y locales.
- Clasificar lugares por tipo de entorno, valor histórico, accesibilidad, etc.
- Utilizar reglas de producción para inferir recomendaciones inteligentes.
- Implementar una interfaz sencilla tipo chatbot para interactuar con los usuarios.

## 🧠 Componentes

- `src/rules.py`: contiene las reglas del sistema experto.
- `src/main.py`: punto de entrada del sistema.
- `data/lugares.csv`: base de datos con lugares turísticos y sus características.
- `tests/test_rules.py`: pruebas automáticas para validar el funcionamiento.

## 🔧 Tecnologías sugeridas

- Python 3.10+
- Pandas
- Sistema de inferencia simple basado en reglas

## 🚀 Próximos pasos

1. Cargar base de datos en `data/lugares.csv`
2. Implementar lógica de inferencia en `rules.py`
3. Crear una interfaz básica en `main.py`
4. Probar el sistema con distintos perfiles de usuario

## 📂 Estructurasistema-experto-turismo/
├── README.md
├── .gitignore
├── data/
│ └── lugares.csv
├── docs/
├── src/
│ ├── main.py
│ └── rules.py
└── tests/
└── test_rules.py


## ✨ Autoría
Proyecto para la materia "Desarrollo de Sistemas de Inteligencia Artificial" – Tecnicatura en Ciencia de Datos e IA (TSCDIA)
