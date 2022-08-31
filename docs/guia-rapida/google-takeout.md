# Google Export y Google Transfer

Son las herramientas de exportación y respaldo de datos de Google.

[Google Takeout][GTakeout]
:   - Es para exportar los datos en un zip para descargarlos
      o transferirlos a otro servicio, como Dropbox, OneDrive y Box.
    - Exporta y transforma los datos en un formato estándar, como
    `docx`, `xlsx`, `csv`, `json`, `pdf`, `txt`. Archivos que no pueden
    ser transformados (como links de Drive) se exportan como `html`.

[Google Transfer][GTransfer]
:   - Es para transferir los datos de una cuenta a otra.
    - Solo permite transferir datos de GMail y Drive que tengas.
    - Dado que los datos se mantienen en Google, metadatos como etiquetas,
      a quienes se les comparte los documentos, etc. se mantienen.

[GTakeout]: https://takeout.google.com/
[GTransfer]: https://takeout.google.com/transfer


## Comparativa

|                                Característica |                        Google Takeout                        |                      Google Transfer                       |
| --------------------------------------------: | :----------------------------------------------------------: | :--------------------------------------------------------: |
|                  Archivos personales de Drive | :material-checkbox-marked-circle:{.green} <br> transformados | :material-checkbox-marked-circle:{.green}  <br> originales |
|                 Unidades compartidas de Drive |                :material-close-circle:{.red}                 |               :material-close-circle:{.red}                |
|             Mails y los documentos adjuntados |   :material-checkbox-marked-circle:{.green} <br> como MBOX   | :material-checkbox-marked-circle:{.green} <br> originales  |
|           Filtros y otros meta-dados de Gmail |          :material-checkbox-marked-circle:{.green}           |              :material-help-circle:{.yellow}               |
|                                   Calendarios |          :material-checkbox-marked-circle:{.green}           |               :material-close-circle:{.red}                |
|                                     Contactos |  :material-checkbox-marked-circle:{.green} <br> vCard o CSV  |               :material-close-circle:{.red}                |
|                         Notas (keep) y Tareas |          :material-checkbox-marked-circle:{.green}           |               :material-close-circle:{.red}                |
|                      Lugares guardados (Maps) |    :material-checkbox-marked-circle:{.green} <br> geoJSON    |               :material-close-circle:{.red}                |
|             Videos y Música creada en YouTube |          :material-checkbox-marked-circle:{.green}           |               :material-close-circle:{.red}                |
|                                 Google Photos |          :material-checkbox-marked-circle:{.green}           |               :material-close-circle:{.red}                |
| Cuentas asociadas (iniciar sesión con Google) |                :material-close-circle:{.red}                 |               :material-close-circle:{.red}                |


## Uso

### Exportar datos con Google Export

-  Ve a [Google Takeout][GTakeout]
-  Elige que datos y como quieres exportarlos.

### Transferir datos con Google Transfer

- Ten una cuenta de Google con los datos que quieres transferir.
- Sigue los pasos de [Google Transfer][GTransfer].
- Elige el método de entrega (vínculo de descarga o agregar a otro servicio).
- Selecciona si quieres exportar una vez o periódicamente, y si usar `.zip` o `.tgz`.
- Una vez creada la exportación, debes esperar a que llegue el correo de descarga.
  Esto no es inmediato, y depende de la cantidad de datos que se exportan.

## Referencias

- [Copiar contenido de tu cuenta de centro educativo a otra cuenta](https://support.google.com/accounts/answer/6386856)
- [Cómo descargar datos de Google](https://support.google.com/accounts/answer/3024190?hl=es)
