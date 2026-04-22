# mi-ide-cloud
Tarea Formativa

## ⚙️ Transformaciones Aplicadas

Durante la ejecución del pipeline, los datos en bruto pasan por un proceso de limpieza y transformación para asegurar su calidad y utilidad:

* **Dataset Titanic:** Se aplica un filtro de limpieza que elimina los registros de pasajeros menores de 10 años, conservando únicamente las filas donde la edad es igual o superior a 10 (`Age >= 10`).
* **Datos de Clima (Tiempo Real):** Se recolectan 5 lecturas consecutivas del clima. Posteriormente, se concatenan y se calcula el **promedio de la temperatura**. Este cálculo matemático se almacena como una nueva tabla de resumen (`Resumen_Clima`) disponible en el orquestador.
