# ⚽ FIFA World Cup 2022 — Data Analysis

Análisis exploratorio del Mundial Qatar 2022 usando Python y datos oficiales de la FIFA.
El proyecto examina el rendimiento de los equipos desde múltiples ángulos: goles, posesión, estilo de juego, y estadísticas avanzadas partido a partido.

---

## 📋 Contenido del análisis

### 🏆 Análisis 1 — Argentina campeón (rendimiento ofensivo)
- Goles a favor y en contra por partido
- Evolución del rendimiento a lo largo del torneo
- Visualización de líneas por instancia (Grupos → Final)

### 🎮 Análisis 2 — Dominio del juego (posesión)
- Posesión promedio de Argentina vs rivales en cada partido
- Comparativa de posesión: Argentina vs el resto del torneo

### 🛣️ Análisis 3 — Estilo de juego del campeón
- Distribución de ataques por carril (izquierdo, central, derecho)

### 📊 Análisis exploratorio general
- Promedio de goles por partido en Qatar 2022
- Top 10 equipos por eficiencia ofensiva (goles por partido)
- Partidos más goleadores del torneo
- Equipo con más goles totales
- **Anomalías tácticas**: Alemania remató 25 veces y perdió; España tuvo 78% de posesión y perdió
- Top 10 partidos con más remates desde afuera del área
- Top 10 partidos con más presiones defensivas
- Top 10 partidos con más pérdidas forzadas (forced turnovers)
- Partido con más córners / menos córners
- Partido con más goles combinados (Inglaterra 6 - Irán 2)
- Equipo con más pases completados en un solo partido (España vs Costa Rica: 1070)

---

## 🛠️ Tecnologías utilizadas

| Librería | Uso |
|---|---|
| `pandas` | Limpieza y transformación de datos |
| `matplotlib` | Visualizaciones personalizadas |
| `seaborn` | Estilo y gráficos estadísticos |
| `numpy` | Cálculos auxiliares |

---

## 📁 Estructura del proyecto

```
worldcup2022-data-analysis/
│
├── data/
│   └── worldcup_2022.csv       # Dataset principal (FIFA)
│
├── notebooks/
│   └── 02_worldcup_2022_integration.ipynb  # Análisis completo
│
├── images/
│   └── (gráficos exportados)
│
├── README.md
└── LICENSE
```

---

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/facuasudata/worldcup2022-data-analysis.git
cd worldcup2022-data-analysis
```

2. Instalar dependencias:
```bash
pip install pandas matplotlib seaborn numpy jupyter
```

3. Abrir el notebook:
```bash
jupyter notebook notebooks/02_worldcup_2022_integration.ipynb
```

---

## 💡 Hallazgos destacados

- **Eficiencia ≠ posesión**: España (78% posesión vs Japón) y Alemania (25 remates vs Japón) perdieron, demostrando que dominar el juego no garantiza el resultado.
- **Argentina campeón sin dominar la pelota**: en las fases eliminatorias, Argentina tuvo posesión inferior al rival en varios partidos clave (44% vs Países Bajos, 34% vs Croacia).
- **Marruecos**: el equipo con más presiones defensivas del torneo, marca del estilo que los llevó a semifinales.
- **España vs Costa Rica**: el récord de pases completados del torneo (1070), sin traducirse en dominio de toda la competencia.

---

## 📂 Dataset

Los datos corresponden a estadísticas oficiales del Mundial Qatar 2022 (FIFA), incluyendo métricas de posesión, remates, pases, córners, presiones defensivas y pérdidas forzadas para los 64 partidos del torneo.

---

## 👤 Autor

**facuasudata**  
[GitHub](https://github.com/facuasudata) · Proyecto de análisis de datos deportivos

---

*Proyecto desarrollado con fines educativos y de portfolio.*
