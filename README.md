# 📡 ConnectaTel — Análisis de Clientes de Telecomunicaciones

> Proyecto Final | Análisis de Datos | Sprint 7

---

## 🎯 Objetivo del Proyecto

Analizar el comportamiento de uso de los clientes de **ConnectaTel**, empresa de telecomunicaciones con operaciones en México y Colombia, para identificar patrones de consumo, detectar outliers y construir segmentos accionables que permitan optimizar la oferta comercial y mejorar la experiencia del usuario.

---

## 📂 Estructura del Repositorio

```
análisis-ejecutivo-ConnectaTe/
│
├── datasets/
│   ├── plans.csv
│   ├── users_latam.csv
│   └── usage.csv (descarga desde Google Drive)
│
├── notebooks/
│   └── ConnectaTel_Analisis_Completo.ipynb
│
└── README.md
```

---

## 📊 Datasets Utilizados

| Archivo | Descripción | Variables clave |
|---|---|---|
| `plans.csv` | Catálogo de planes disponibles | plan, precio, minutos, GB, costo extra |
| `users_latam.csv` | Información de clientes | user_id, age, city, reg_date, plan, churn |
| `usage.csv` | Actividad de uso real | user_id, date, type (call/text), duration, length |

---

## 🔄 Etapas del Análisis

| Paso | Descripción | Resultado |
|---|---|---|
| 1 | Carga y exploración | Estructura y tipos de datos de cada dataset |
| 2 | Identificación de problemas de calidad | Nulos, sentinels, fechas fuera de rango |
| 3 | Limpieza básica | Datos consistentes y listos para análisis |
| 4 | Summary statistics | Perfil de uso por usuario (mensajes, llamadas, minutos) |
| 5 | Visualización y outliers | Histogramas, boxplots, método IQR |
| 6 | Segmentación | Grupos por nivel de uso y edad |
| 7 | Insight ejecutivo | Conclusiones y recomendaciones para el negocio |

---

## 🛠️ Tecnologías y Librerías

- **Python 3.x**
- `pandas` — manipulación y limpieza de datos
- `numpy` — operaciones numéricas
- `matplotlib` — visualización base
- `seaborn` — visualización estadística
- `Jupyter Notebook` / **Google Colab**

---

## 🚀 Cómo ejecutar el proyecto

1. Descarga los **2 archivos CSV pequeños** desde este repositorio de GitHub.

2. Descarga el **archivo CSV grande** desde Google Drive.
   Descarga:
   🔗 https://drive.google.com/file/d/1IqrH33OLzJgqNrA8TxbqfOupbYjn3cXr/view?usp=drive_link

3. Abre el notebook en Google Colab.

4. Sube los tres archivos CSV cuando Colab lo solicite (o desde el panel de archivos).

5. Ejecuta todas las celdas del notebook.

## 💡 Hallazgos Clave

- **Mayoría de usuarios son de bajo a medio uso**: oportunidad de plan "Esencial" más económico.
- **Outliers de alto uso**: posibles Power Users o fraude — requieren investigación adicional.
- **Adultos (30–59 años)** son el segmento dominante; Adultos Mayores están subutilizados.
- **Plan Premium** muestra mayor consumo en llamadas y mensajes vs. Plan Básico.

---

## 👩‍💻 Autor

**[Jefferson Velasco Rincon]**  
Estudiante de Análisis de Datos  
[LinkedIn](https://www.linkedin.com/in/jefferson00velasco/) | [GitHub](https://github.com/velascojeff040-lab)
