# Optativos de Profundización OPR's

## Introducción:

Este Notebook está hecho para visualizar los optativos de profundización de la carrera, según los ramos aprobados del usuario. La idea es que cualquier persona, independiente del semestre y sus ramos aprobados, pueda hacer un filtro sin tomarse la tediosa tarea de buscar cada `OPR` en catálogo uc.

Se espera que este Notebook acompañe a cada uno en su trayectoria académica, que sea único al igual que el usuario y sea moldeable a cada cambio que efectue la unidad académica (`IMC`).

Toda la información presentada en los archivos que se usan en este Notebook fueron obtenidos de la página oficial de la Pontificia Universidad Católica de Chile: https://catalogo.uc.cl.

## Archivo `malla_licd.xlsx`:
---
En la carpeta `Data` adjunta a este Notebook se encuentra el archivo excel `malla_licd` con todos los ramos de la carrera, es deber del usuario modificar `EXCLUSIVAMENTE` el atributo de `aprobado` de cada ramo de la malla, en caso contrario simplemente el código va a dejar de funcionar correctamente.

Notese que los datos de cada semestre poseen más datos que los que se usarán para este Notebook, la idea es teminar de perfilar estos datos para crear más herramientas parecidas a este Notebook.

## Archivo `oprs.csv`:

Este archivo `.csv` guarda los datos de los optativos de profundización que se pueden elegir a lo largo de la carrera, todo `opr` presenta:
* Sigla
* Nombre
* Unidad Académica a Cargo
* Nivel (PR: Pregrado, MG: Magister, DT: Doctorado)
* Pre-requisitos 

Idealmente no modificar este archivo, cualquier actualización de este será infomado y subido al repositorio. Si se encuentra algún error en los datos, por favor contactarse a la brevedad por mail.

**Autor:** Matías Armando Pineda<br>
**Mail:** matias.pineda@uc.cl.

**Licenciatura en Ingeniería en Ciencia de Datos - PUC**
