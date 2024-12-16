Los sistemas operativos actuales cuentan con herramientas incorporadas que facilitan la supervisión de recursos. Estas herramientas permiten recopilar información precisa sobre el desempeño y la condición del sistema.

# Monitorizacion de Procesos

## ps

· El comando `ps` muestra información sobre los procesos en ejecución.

- El comando `ps aux` permite visualizar detalles de todos los procesos pertenecientes a cualquier usuario, presentándolos en un formato extendido con información adicional:
![psaux](/img/psaux.png)
- Si necesitas obtener información específica sobre un proceso, puedes utilizar `ps -C <nombre>`:
![psnano](/img/pscnano.png)
- Si deseas ver los procesos que más recursos consumen, como los 5 que más memoria utilizan, puedes ejecutar `ps -eo user,pid,%cpu,%mem,time --sort=-%cpu`:
