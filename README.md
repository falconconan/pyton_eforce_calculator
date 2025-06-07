# pyton efforts calculator
## ¿ de que se trata ? 
se hara una calculadora de esfuerzo normal (para cargas axiales) y cortante ademas que se hace un apartado para factor de seguridad
### funcionalidades
- ver y editar la lista de los materiales (EDITABLE EN CSV)
- ingreso manual de carga aplicada, area de seccion trasversal, y eleccion de material
- eleccion de calculo de esfuerzo (con o sin factor de seguridad)
- da la imprecion de los reultados 
## seudocodigo

```
inicio
    definir control=true
    escribir ("Que desea hacer: 1. ver/editar la lista de materiales y sus propiedades mecanicas 2.calculo de esfuerzos(uniaxiales o cortantes))
    leer A 
    para control==true 
        si A==1 
            mientras b 
                escribir (desea ver o editar? para ver digite 1 para editar 2 para volver al menu 3)
                leer edicion_csv
                si edicion_csv==1
                    funcion de revicion csv
                si-sino edicion_csv==2
                    funcion de edicion del csv
                si-sino edicion_csv==3
                    control=falce
                sino
                    escrivir dato no valido vuelve a intentar
        sino A==2 

```