# IberOS — respaldo web independiente

Este repositorio sirve para preservar una **copia estática publicada de la web IberOS** anterior al cambio de dominio a `iberos-ia.com`.

- Origen: [IberOS](https://github.com/estebanmolinaruiz-art/IberOS).
- Versión fuente fijada: `a2015d575f03871819b1d5522a666efe01b27419`.
- Publicación de respaldo prevista: https://estebanmolinaruiz-art.github.io/IberOS-respaldo/
- Coste de GitHub Pages para repositorios públicos: 0 € en los límites del servicio.
- La copia publicable estará en `site-snapshot/` una vez completado el flujo de captura; los ficheros estáticos permanecerán en **este repositorio**, independientes del original.
- No contiene dominio personalizado; no modifica el DNS, la página anterior ni la nueva.
- El sitio de respaldo se declara `noindex` para no crear duplicidades en buscadores.

## Activación inicial
1. Abrir **Settings → Pages** del repositorio y seleccionar **GitHub Actions** como fuente de publicación.
2. Abrir **Actions → Publicar copia congelada de IberOS**.
3. Elegir **Run workflow**, opción `capturar`.
4. Comprobar el estado verde del flujo y la URL pública de respaldo.
5. Confirmar que portada, Corpus, fichas, datos JSON e imágenes responden antes de iniciar la migración del dominio principal.

## Recuperación posterior
Con la captura guardada, desde **Actions** ejecutar el mismo flujo con la opción `republicar`. **No requiere que el repositorio IberOS original siga disponible**, porque publica la instantánea ya guardada en `site-snapshot/`.

**Estado:** el repositorio fue creado vacío. La copia solo está completada cuando el flujo de captura termine correctamente y los archivos aparezcan en `site-snapshot/`. No confundir la existencia del repositorio con un respaldo verificado.

## Licencias y procedencia
Los materiales conservan las licencias, atribuciones, metadatos y referencias que traen desde el sitio fuente. El código IberOS sigue disponible en el repositorio canónico. No modificar el significado científico de las fichas.
