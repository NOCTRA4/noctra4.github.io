# Repo de Noctra

Repositorio de tweaks para iOS 14 – 17.

    https://noctra4.github.io/

| Tweak | Qué es |
|---|---|
| **Hyaline** | El material Liquid Glass de iOS 26, en iOS 14–16 |
| **Vitral** | El Centro de Control de iOS 26 |
| **Carillón** | Los sonidos y hápticos de iOS 27, en iOS 15–17 |
| **Vectis** | Puntos persistentes que responden al movimiento |
| **Nacre** | Apariencia renovada para Siri |

## Cómo publicar una actualización

1. Copia el `.deb` nuevo dentro de `debs/`.
2. Súbelo (arrastrar y soltar en la web de GitHub vale).
3. Ya está. La Action regenera `Packages` y el repo queda vivo en menos de un minuto.

No hay que tocar `Packages` ni `Release` a mano nunca. Si alguna vez quieres
reindexar sin subir nada, en la pestaña **Actions** → *Indexar el repo* → *Run workflow*.

## Licencia

Proyecto no comercial. Cada paquete lleva la suya en su propia descripción.
