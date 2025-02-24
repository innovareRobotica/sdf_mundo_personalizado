# Primer Mundo en SDF para Gazebo

# sdf_mundo_personalizado
Este repositorio contiene la definición de un entorno simple en formato SDF (Simulation Description Format) para su uso en Gazebo, proporcionando una base para la creación y prueba de simulaciones.

## Archivos incluidos

1. **mundo_vacio.sdf**: Un entorno vacío con suelo e iluminación básica.
2. **robot_diferencial.sdf**: Incluye un robot diferencial modelado manualmente.
3. **robot_con_plugin.sdf**: Extiende el robot diferencial con un plugin que le permite moverse.

## Uso

Para utilizar estos archivos en **Gazebo**, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
   ```  
2. Ejecuta Gazebo con el archivo deseado:
   ```bash
   gz sim mundo_vacio.sdf
   ```  
   o  
   ```bash
   gz sim robot_diferencial.sdf
   ```  
   o  
   ```bash
   gz sim robot_con_plugin.sdf
   ```  

## Requisitos

- **Gazebo** instalado en tu sistema.
- Dependencias adicionales según el plugin utilizado.
