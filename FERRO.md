# FerroLauncher Mobile — futura 2.0 📱

La versión de bolsillo de FerroLauncher: el mismo launcher de Minecraft Java,
con la misma identidad y los mismos servicios, en Android.

> **Base técnica**: fork de [TeamPojavLauncher/PojavLauncher](https://github.com/TeamPojavLauncher/PojavLauncher)
> ("Pojav Reborn": JRE en el móvil, LWJGL parcheado, renderers y controles táctiles).
> Licencia del fork: **LGPLv3** (heredada del proyecto base).

## Estado: fase 0 — investigación
- [x] Base elegida y fork creado
- [ ] Entorno Android listo (Android Studio + JDK 17 + SDK/NDK)
- [ ] Build base verificado (`:app_pojavlauncher:assembleDebug`)
- [ ] Rebrand Ferro (paquete, nombre, colores, icono)
- [ ] Servicios: Modrinth, CurseForge, Microsoft, backups, doctor, FerroBridge
- [ ] Betas públicas rumbo a la 2.0

## Mapa de rebrand
| Qué | Dónde |
|---|---|
| Paquete | `app_pojavlauncher/build.gradle` (`net.kdt.pojavlaunch` → `com.ferro.launcher`) + refactor de paquetes Java |
| Nombre | `app_pojavlauncher/src/main/res/values/strings.xml` (`app_name`) |
| Colores | `.../res/values/colors.xml` (paleta Brasa: `#FFB62E`, `#E23A1A`) |
| Icono | `.../res/mipmap-*/ic_launcher*` (arte FL ya disponible) |
| Español | `.../res/values-es/` (ya existe, revisar claves nuevas) |
