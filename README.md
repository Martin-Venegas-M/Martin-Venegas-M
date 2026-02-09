# Hi! ¡Hola! 🎈
```r
martin_in_english <- tibble::tibble(
  hi = c("Hello World!", "Welcome to my profile", ":)")
)

martin_en_espanol <- tibble::tibble(
  hola = c("¡Hola Mundo!", "Bienvenido a mi perfil", ":)"
  )
)

```

## A bit about me in [english](#about-me) y un poco sobre mí en [español](#sobre-mi) :)

### About me

```r
about_me <- martin_in_english |>
  dplyr::mutate(
    name = "Martín Venegas Márquez",
    located_in = "Santiago, Chile",
    current_job = "Socioeconomic Analyst | Survey Analyst",
    education = c(
      "Graduate Diploma in Statistics",
      "Professional degree in Sociology",
      "Bachelor's degree in Sociology"
    ),
    company = "Instituto Nacional de Estadísticas de Chile (INE)",
    fields_of_interests = c(
      "Applied Statistics",
      "Survey Methodology",
      "R"
    ),
    background = c(
      "Socioeconomic Analyst of Time Use Survey and Micro-entrepreneurship Survey",
      "Research and Technical assistant at COES, FONDECYT and other types of projects",
      "Teaching asisstant in quantitative methods and statistics related courses"
    ),
    currently_learning = "R Packages, Advanced R stuff and more statistics and survey methodology :)",
    goals_2026 = "Create a new R package and learn new things!",
    hobbies = "Climbing, outdoors and some reading"
  )

```

### Sobre mi

```r
sobre_mi <- martin_en_espanol |>
  mutate(
    nombre = "Martín Venegas Márquez",
    lugar_redicencia = "Santiago de Chile",
    trabajo_actual = "Analista Socioeconómico | Analista de Encuestas",
    educacion = c(
      "Diplomado en Estadística",
      "Título profesional en Sociología",
      "Licenciatura en Sociología"
    ),
    compania = "Instituto Nacional de Estadísticas de Chile (INE)",
    intereses = c(
      "Estadística Aplicada",
      "Metodología de Encuestas",
      "R"
    ),
    antecedentes = c(
      "Analista socioeconómico en la Encuesta de Uso del Tiempo y la Encuesta de Microemprendimiento",
      "Asistente de investigación y técnico en proyectos COES, FONDECYT y otros",
      "Ayudante docente en cursos de métodos cuantitativos y estadística"
    ),
    aprendiendo_actualmente = "Paquetes de R, R avanzado y más estadística y metodología de encuestas :)",
    metas_2026 = "Crear un nuevo paquete en R y seguir aprendiendo cosas nuevas",
    hobbies = "Escalada, actividades al aire libre y algo de lectura"
  )
```
