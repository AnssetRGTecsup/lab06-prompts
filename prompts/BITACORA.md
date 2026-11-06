# Bitacora de prompts
Laboratorio 06: Fundamentos de Ingenieria de Prompts.

Herramienta de IA usada: (escribe aqui cual usaste)
## Ejercicio 2: Tokens y ventana de contexto
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 34 |7 |
| The students program in Java. | 29| 6|
| desafortunadamente | 18|4 |

**Resultado esperado elaborar . . .**
## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100% | BiblioTec|
| 0.5 | 65.3% | BiblioTec, LibroYa, LectoGo, PaginaLibre, NubeDeTinta|
| 1.0 | 44.5% | BiblioTec, LibroYa, LectoGo, PaginaLibre, NubeDeTinta|
| 1.8 | 32.2% | BiblioTec, LibroYa, LectoGo, PaginaLibre, NubeDeTinta|
## Ejercicio 4: Prompt vago vs estructurado
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |SI| SI |
| Menciona a los usuarios principales | SI| SI |
| Tiene exactamente 3 funcionalidades | SI| SI |
| Esta en 3 parrafos | NO | SI |
| Lo usaria en un informe real | | |

## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Java Senior Developer|
| Instruccion | Create a Java program|
| Contexto | Managing products on a virtual store|
| Ejemplo | Using a Product class with the attributes Code, Name, Price, Stock|
| Formato | Methods: getPrice(), setPrice(double price)|