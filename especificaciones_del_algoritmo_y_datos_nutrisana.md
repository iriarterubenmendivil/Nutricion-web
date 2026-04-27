# Especificaciones Técnicas del Algoritmo NutriSana

## 1. Fuentes de Datos (Data Ingestion)
- **BEDCA (Base de Datos Española de Composición de Alimentos):** Fuente primaria para alimentos genéricos y locales.
- **Open Food Facts API:** Integración para productos procesados y escaneo de códigos de barras.
- **USDA FoodData Central:** Backup para ingredientes internacionales.

## 2. Motor de Equivalencias (Macro-Matching Engine)
El sistema no busca solo "calorías similares", sino una coincidencia en la densidad de macronutrientes:
- **Tolerancia de Desviación:** +/- 5% en proteínas, +/- 10% en grasas e hidratos.
- **Categorización de Alimentos:** Clasificación por índice glucémico, origen (animal/vegetal) y micronutrientes clave (fibra, potasio, etc.).

## 3. Lógica de Recálculo Dinámico
- **Trigger A (Imprevisto):** Si el usuario consume 500kcal extra en el almuerzo, el sistema aplica una "amortización negativa" repartida en las siguientes 3-4 comidas (o hasta el final del día siguiente si es tarde).
- **Trigger B (Actividad):** Integración con HealthKit/Google Fit para ajustar el TDEE (Gasto Energético Total Diario) en tiempo real.

## 4. Módulo "Comer Fuera" (Eating Out Logic)
- **Estimación por Categoría:** Si el usuario no conoce el plato exacto, elige "Hamburgesa Gourmet" o "Ensalada César". 
- **Penalización por Grasas Ocultas:** El algoritmo suma automáticamente un 15-20% de grasas adicionales (aceites de cocina, salsas) para evitar el infra-registro calórico típico de las comidas fuera de casa.
- **Base de Datos de Cadenas:** Menús precargados de las principales cadenas de restauración en España.

## 5. Panel de Control Administrador
- **Gestor de Reglas:** Ajuste de coeficientes de actividad y fórmulas (Mifflin-St Jeor vs Katch-McArdle).
- **Curaduría de Recetas:** Validación por nutricionistas colegiados antes de la publicación en la App.
