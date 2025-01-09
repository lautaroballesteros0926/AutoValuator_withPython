# **Predicción de Precios de Autos con Machine Learning**  

Este proyecto utiliza técnicas de Machine Learning para predecir el valor de mercado de vehículos en función de sus características. El modelo fue desarrollado como parte de un bootcamp y está optimizado para garantizar precisión, rapidez en predicciones y eficiencia en el entrenamiento.  

## **Descripción del Proyecto**  
El objetivo principal es crear un modelo capaz de predecir el precio de un vehículo con base en características como el tipo de carrocería, kilometraje, potencia, tipo de combustible, entre otras. Este proyecto fue desarrollado para **Rusty Bargain**, un servicio de venta de coches de segunda mano.  

## **Características del Proyecto**  
- **Calidad de predicción:** Evaluada con la métrica RMSE.  
- **Velocidad de predicción:** Optimizando el tiempo de respuesta del modelo.  
- **Eficiencia del entrenamiento:** Minimización del tiempo de entrenamiento.  

### **Modelos utilizados**  
Se compararon diferentes enfoques:  
1. **Regresión lineal**: Para pruebas de cordura.  
2. **Bosque aleatorio**: Algoritmo basado en árboles.  
3. **LightGBM**: Potenciación del gradiente.  
4. (Opcional) **CatBoost** y **XGBoost**: Potenciación del gradiente con codificación especial para características categóricas.  

## **Estructura de Archivos**  
- `car_data.csv`: Dataset con información de los vehículos.  
- `main.ipynb`: Notebook con el desarrollo del modelo.  
- `README.md`: Documentación del proyecto.  

## **Instalación y Ejecución**  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/tuusuario/PrediccionVehicularML.git
   cd PrediccionVehicularML
   ```  
2. Instala las dependencias:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Ejecuta el notebook:  
   ```bash
   jupyter notebook main.ipynb
   ```  

## **Resultados**  
El modelo final alcanzó un **RMSE de  1479.78 euros**  con tiempos de predicción inferiores a 6s .  

## **Tecnologías utilizadas**  
- Python  
- Jupyter Notebook  
- Scikit-learn  
- LightGBM  
- Pandas y Numpy  
- Matplotlib y Seaborn  
