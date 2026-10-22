# 🚕 Análisis Comparativo de Viajes Compartidos - Zuber Chicago

> ¿Cómo optimizar la flota de Zuber en Chicago para reducir tiempos de espera y aumentar ganancias?

### 📌 LINK AL PROYECTO
Jupyter Notebook: [zuber_chicago_viajes_compartidos.ipynb]

---

### 🎯 ¿Qué problema de negocio resuelve?

Zuber Chicago, está perdiendo dinero por 2 razones:
1.  **Mala distribución de autos:** Tiene autos donde no hay demanda.
2.  **No entiende el clima:** El clima y el dia de la semana afectan directamente la duración del viaje.

**Mi trabajo como Data Analyst:** encontrar los vecindarios con más y menos viajes, separar los viajes por buen y mal clima y promediar su duración. 

---

### 🔍 ¿Qué hice? (Solución Técnica)

Hice un Análisis Exploratorio de Datos (EDA) completo con Python:

1.  Limpieza de 100k+ viajes (eliminé viajes con duración 0 y distancias atípicas)
2.  Análisis temporal: hora, día de semana, clima
3.  Correlación entre variables con Seaborn

**Stack:** Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter

---

### 📊 Hallazgos Clave (Lo que el reclutador quiere ver)

**1. Top 3 Zonas con Mayor Demanda (60% de los viajes):**
- The Loop (Centro financiero)
- River North (Bares/Restaurantes)
- Streeterville (Turismo)

**2. Factor Clima = Dinero:**
Encontré correlación negativa fuerte: A menor temperatura, mayor demanda de viajes (+28% en días <5°C). Chicago es frío 6 meses al año.

**3. Horas Pico de Oro:**
- Mañana: 7am-9am (viajes al trabajo)
- Tarde: 5pm-8pm (regreso + ocio)
- Fin de semana: 10pm-2am (vida nocturna)

**4. Lealtad del Usuario:**
Usuarios frecuentes prefieren viajes cortos (<5km) y pagan 15% más por rapidez.

---

### 💼 Impacto y Recomendación de Negocio

Si yo fuera Product Manager de Zuber, haría esto MAÑANA:

> **Recomendación 1:** Reubicar 40% de la flota de la periferia a The Loop de 5pm a 8pm.
>
> **Recomendación 2:** Activar tarifa dinámica suave (+10%) en días con mal clima. La gente lo paga porque no quiere caminar con frío.
>

---

### 📈 Visualizaciones
![Demanda por vecindario](ruta/de/tu/grafica.png)

---

### 👨‍💻 Autor
Cesar R. | Data Analyst Jr. | Guadalajara
TripleTen 

