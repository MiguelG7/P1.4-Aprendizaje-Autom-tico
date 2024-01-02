# P1.4-Aprendizaje-Autom-tico

Programa de predicción de tipo de sueño respaldado por el algoritmo de Weka "J48".
Predicciones basadas en la siguiente base de datos: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

El modelo ha sido entrenado con la siguiente distribución de resultados:

![](https://i.ibb.co/7jPc9gw/imagen-2023-12-13-213750217.png)

![](https://i.ibb.co/rcGcxf0/image.png)

Resultados mediante otros algoritmos (descartados por una menor precisión de predicción):

Clasificador de redes bayesianas, también conocido como clasificador BayesNet

![](https://i.ibb.co/PMyPySv/imagen-2024-01-02-112746895.png)


Clasificador LWL, que significa "Locally Weighted Learning" (Aprendizaje Ponderado Localmente)

![](https://i.ibb.co/hXLb708/imagen-2024-01-02-113022628.png)

Clasificador HoeffdingTree, también conocido como Very Fast Decision Tree (VFDT)

![](https://i.ibb.co/6JT6gys/imagen-2024-01-02-113236500.png)

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

Los derechos del código no me pertenecen ya que fue proporcinado por el profesor y la base de datos es de dominio público.

[Licencia base de datos](https://creativecommons.org/publicdomain/zero/1.0/) (link extraído de su página de descarga citada anteriormente).

## Contacto
Miguel Gamboa Sánchez
[Correo](mailto:miguel.gamboasanchez@usp.ceu.es)
[GitHub](https://github.com/MiguelG7)
