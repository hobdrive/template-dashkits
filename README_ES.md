# Plantilla HobDrive Dashkit

[English](README.md) | [Русский](README_RU.md) | [Español](README_ES.md)

Este es un repositorio de plantilla para crear tus propios dashkits personalizados para HobDrive.

## Primeros pasos

1. **Clona este repositorio:** 
   Clónalo a través del botón "Fork" en GitHub.
   Renombra el repositorio directamente en GitHub, si lo deseas.

   O por línea de comandos:
   ```bash
   git clone https://github.com/hobdrive/template-dashkits.git my-dashkit
   cd my-dashkit
   ```

2. **Renombra la carpeta template al nombre deseado de tu panel**
   ```bash
   cd community
   mv template my-dashkit-name
   cd my-dashkit-name
   ```

3. **Edita el archivo community/my-dashkit-name/info.json:**
   - Actualiza los campos `name`, `description` y `author`
   - Establece el número de versión deseado

4. **Personaliza tu diseño:**
   - Edita `user.layout` para crear el diseño personalizado de tu panel
   - Agrega imágenes personalizadas a la carpeta `images/`

5. **Prueba tu dashkit:**
   - Sube tu repositorio a GitHub
   - En **Hobdrive**, elige "Manage DashKits"
   - Cambia `Repo name` al id de tu repositorio (`your-login/repo-name`)
   - Cambia `Branch` si es necesario
   - Presiona `Update` - esto cargará tu repositorio
   - Presiona el botón `Install` en tu DashKit
  
6. **Actualiza tu dashkit:**
   - Después de instalado, puedes actualizar directamente el panel ya instalado.

## Qué está incluido

- **community/template/** - Un dashkit simple y funcional con un diseño básico
- **info.json** - Archivo de metadatos para tu dashkit
- **user.layout** - El archivo de diseño principal donde defines las pantallas de tu panel
- **images/** - Carpeta para imágenes y gráficos personalizados

## Creando tu diseño

El archivo `user.layout` utiliza el lenguaje de diseño basado en XML de HobDrive. Conceptos clave:

## Recursos

- **Documentación completa:** Ver [LAYOUT_SPEC.md](https://github.com/hobdrive/hobdrive-dashkits/LAYOUT_SPEC.md) para la referencia completa del diseño
- **Repositorio principal:** [hobdrive-dashkits](https://github.com/hobdrive/hobdrive-dashkits) para más ejemplos
- **Comunidad:** ¡Comparte tus dashkits con la comunidad de HobDrive!

## Consejos

1. **Empieza simple:** Comienza con la plantilla incluida y agrega complejidad gradualmente
2. **Prueba frecuentemente:** Prueba tu diseño en HobDrive después de cada cambio
3. **Usa condicionales:** Usa atributos `if` para mostrar elementos solo cuando los sensores estén disponibles
4. **Vista previa primero:** La plantilla incluye un ejemplo funcional que puedes modificar
5. **Optimización de imágenes:** Mantén los archivos de imagen pequeños para un mejor rendimiento
6. **Múltiples secciones:** Puedes crear múltiples pantallas de panel en un solo archivo de diseño

## Estructura de archivos

```
my-dashkit/
├── README.md (este archivo)
├── LAYOUT_SPEC.md (referencia completa de sintaxis)
└── community/
    └── your-dashkit-name/
        ├── info.json (metadatos del dashkit)
        ├── user.layout (el diseño de tu panel)
        ├── README.md (opcional: describe tu dashkit)
        └── images/ (opcional: gráficos personalizados)
```

## Publicando tu dashkit

Cuando estés listo para compartir tu dashkit:

1. Actualiza el README en la carpeta de tu dashkit con capturas de pantalla y descripción
2. Asegúrate de que tu info.json tenga información precisa
3. Considera enviar un pull request al repositorio principal hobdrive-dashkits
4. ¡Comparte con la comunidad!

## Licencia

Esta plantilla se proporciona tal cual para crear dashkits de HobDrive. Consulta la licencia de HobDrive para los términos de distribución.

## ¿Necesitas ayuda?

- Consulta LAYOUT_SPEC.md para documentación detallada
- Mira ejemplos en el repositorio principal hobdrive-dashkits
- Únete a la comunidad de HobDrive para obtener soporte

¡Feliz creación de paneles! 🚗📊
