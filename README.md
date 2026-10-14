# Detective de Datos

Juego de investigación para encontrar problemas de diseño en tablas relacionales.

Son ocho expedientes que se abren en orden. En cada uno, el jugador busca la evidencia en las tablas: semántica de los atributos, redundancia, anomalías de modificación, inserción y eliminación, valores NULL, tuplas espurias y dependencias funcionales (trivial, completa, parcial y transitiva).

## Características

- Si la respuesta no es correcta, se explica por qué esa elección no sirve, sin mostrar la correcta, y se vuelve a intentar. Las estrellas cuentan el primer intento.
- Todo el contenido va cifrado y en cadena: cada paso se abre solo después de resolver bien el anterior.
- Funciona en el navegador del celular o del computador, sin cuentas ni instalación.
- El avance se guarda en el mismo navegador.
- Al cerrar los ocho expedientes se genera un certificado imprimible.

## Ejecutar en local

Es un sitio estático. Desde la carpeta del repositorio:

```
python -m http.server 8000
```

y abrir `http://localhost:8000`.
