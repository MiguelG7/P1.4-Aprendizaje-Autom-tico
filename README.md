# P1.4-Aprendizaje-Autom-tico

[README.md en elaboración, disculpe las molestias...]

Programa de predicción de tipo de sueño respaldado por el algoritmo de Weka "J48".
Predicciones basadas en la siguiente base de datos: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Instalación

Clone el repositorio en su área de trabajo mediante el siguiente comando:
```bash
git clone https://github.com/MiguelG7/P1.4-Aprendizaje-Autom-tico.git
```
## Uso

Una vez haya clonada el repositorio, ábralo desde la terminal y ejecute los siguientes comandos:
```bash
make jar
java -jar aprendizaje.jar
```
La predicción impresa dependerá del lugar de colocación del signo "?" en el archivo "./test_data/test.arff"
```bash
...
@DATA
Female,30,Nurse,6.4,5,35,7,'Normal Weight',130/86,78,4100,?
```
Conviene recordar que el algoritmo J48 está diseñado para elegir entre opciones y no dar un valor específico como puede ser un "float" o un "int",entre otros.

## Licencia
Este proyecto está bajo la Licencia MIT - vea el archivo [LICENSE](LICENSE) para más detalles.

## Contacto
Miguel Gamboa Sánchez
[Correo](mailto:miguel.gamboasanchez@usp.ceu.es)
[GitHub](https://github.com/MiguelG7)
