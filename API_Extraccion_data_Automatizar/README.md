# 📂 Proyectos con APIs
Este repositorio reúne proyectos de práctica con **consumo y manejo de APIs en Python**, aplicados al análisis de datos.  
Cada proyecto refleja un nivel de complejidad diferente, desde el consumo básico hasta la implementación de trazabilidad en las solicitudes. Cabe precisar que estos proyecto usa una API pública de prueba para demostrar habilidades aplicables en un entorno real, esto con la finalidad de proteger la confidencialidad de los datos.

## 🎯 Objetivo
Estos proyectos me permiten **afianzar mis habilidades como Analista de Datos** mientras evoluciono hacia un perfil más técnico en **programación y automatización con Python**.

## 🛠️ Tecnologías usadas
- Python  
- Requests  
- JSON  
- Pandas
-----------

**📊PROYECTO API: Extracción de Datos desde API REST y Exportación a Excel**
Este proyecto demuestra como automatizar la extracción y transformación de datos desde una API REST pública usando Python y pandas. 

**🔑 Funcionalidad**
* Conexión a API REST con requests.
* Uso de parámetros dinámicos (userId) para filtrar datos.
* Transformación de la respuesta JSON en un DataFrame de pandas.
* Exportación de los datos a Excel para consumo de negocio.

**📂 Estructura de salida**: posts_data.xlsx contiene los registros extraídos y consolidados.

Capturas de resultado - documento exportado:

<img width="450" height="100" alt="image" src="https://github.com/user-attachments/assets/fdeea33b-6b62-4987-8fb4-574faf2193a8" />
<img width="395" height="73" alt="image" src="https://github.com/user-attachments/assets/c2e82bd7-e53c-40aa-9544-ac686d1c4e88" />
<img width="1913" height="628" alt="image" src="https://github.com/user-attachments/assets/493e2d0e-bd34-4496-b5b6-2b920da9cb6f" />

-----------

**📊 Proyecto API con Trazabilidad**

Este proyecto consiste en el **consumo de una API simulada** con Python, aplicando **buenas prácticas de trazabilidad** en el registro de solicitudes y respuestas.  

El objetivo es demostrar cómo un **Analista de Datos** puede evolucionar hacia un perfil más técnico, aplicando programación para **automatizar, validar y documentar** cada interacción con una API.  

## 🚀 Flujo del Proyecto

1. **Consumo de la API**:   - Uso de **requests.get()** para acceder a endpoints. - Manejo de parámetros en la URL.  
2. **Transformación de datos**: - Lectura de la respuesta con **response.json()** -  Estructuración con **pandas.DataFrame**. 
3. **Trazabilidad (Logging)**: Registro de cada petición realizada - Guardado de códigos de estado - Log de actividades  
4. **Exportación de resultados**: Datos limpios a **CSV/Excel**. Log de solicitudes a un archivo de texto.  

Capturas de resultado - documento exportado: 

<img width="463" height="66" alt="image" src="https://github.com/user-attachments/assets/b2a220f8-0744-486d-a82b-ffc61d9d6569" />
<img width="1389" height="595" alt="image" src="https://github.com/user-attachments/assets/9a08d3ca-436c-448c-b479-a9babee96437" />

⚠️ Nota: Se utilizó una API pública de prueba con fines prácticos, a fin de cuidar la confidencialidad de los datos. El objetivo de este script es demostrar el proceso completo de automatización. 
