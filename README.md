# Hi! 🎈
```r
martin <- tibble::tibble(
  hi = c("Hello World!", "Welcome to my profile", ":)")
)
```

## A bit about me :)

```r
about_me <- martin |>
  dplyr::mutate(
    name = "Martín Venegas Márquez",
    located_in = "Santiago, Chile",
    current_job = "Socioeconomic Analyst | Survey Analyst",
    education = c(
      "Graduate Diploma in Statistics",
      "Professional degree in Sociology",
      "Bachelor's degree in Sociology"
    ),
    company = "National Institute of Statistics of Chile (INE)",
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
