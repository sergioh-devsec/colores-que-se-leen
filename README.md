# Colores que se leen

Soy Serch, de CyberSerchMX. El diseño me interesa cuando también facilita la lectura. Preparé esta utilidad para comprobar una decisión pequeña que afecta mucho a una interfaz.

Este proyecto forma parte de mi práctica como ingeniero en diseño de software y redes y entusiasta de la ciberseguridad. Estoy reuniendo ejercicios que ya tenía y utilidades nuevas en repositorios pequeños, con un objetivo concreto y límites visibles. No presento esta muestra como un trabajo contratado ni como un resultado de clientes.

## Para qué lo uso
Convierte colores sRGB a luminancia relativa y calcula contraste según WCAG.

## Cómo probarlo
Abre index.html. Pruebas: node --test tests/app.test.cjs

## Qué revisé al construirlo
Separé la lógica de la interfaz o de la entrada de archivos para probar los casos de error. Mi enfoque de seguridad es reducir permisos y dependencias, validar datos antes de trabajar con ellos y no prometer más de lo que el código hace.

**Nivel:** Básico a intermedio. Las pruebas incluidas son reproducibles; no equivalen a una auditoría independiente.

## Límites y siguiente paso
Solo compara colores sólidos, sin transparencias, fotos ni degradados. No sustituye revisión de accesibilidad. Siguiente paso: evaluar paletas completas.

No incluyas credenciales ni datos reservados en incidencias públicas. El repositorio no incorpora analítica. Código publicado para consulta; no se concede una licencia adicional de reutilización.

— Serch · [CyberSerchMX](https://github.com/sergioh-devsec)
