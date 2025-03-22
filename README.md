# Proyecto-7-Ciencia-de-Datos-e-IA-UDD
Ciencia de Datos e Inteligencia Artificial
# 🩺 Clasificación de Neumonía en Rayos X con Deep Learning

Este proyecto implementa una red neuronal convolucional (CNN) entrenada con imágenes de rayos X de tórax para clasificar casos normales o con neumonía. Se desplegó una API REST accesible desde Postman para simular el uso en tiempo real.

## 🧪 Para probar el modelo de predicción de neumonía, puedes usar Postman:

📥 **[Descargar Postman](https://www.postman.com/downloads/)**

### 🔁 Configuración en Postman

1. Método: `POST`
2. URL de la API: https://d850-34-75-159-163.ngrok-free.app/predict
3. Ir a la pestaña **Body**
4. Seleccionar **form-data**
5. En el campo **Key**, escribir `imagen`
6. En el tipo de valor, seleccionar `File`
7. Subir una imagen del dataset (por ejemplo `person9_bacteria_38.jpeg`)
8. Clic en **Send** para obtener el diagnóstico

### 📸 Resultado esperado

Una respuesta tipo:
{
"resultado": "PNEUMONIA",
"probabilidad": 0.9813
}
### 🧪 Ejemplo visual del uso en Postman

A continuación, se muestra una imagen referencial del uso de la API desde Postman:
![image](https://github.com/user-attachments/assets/d6bcb4a7-a43d-4843-886a-4c85e6d4e28a)

