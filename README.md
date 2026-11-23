# Synthea Hospital — Data Analitikası

Simulyasiya olunmuş klinik məlumatlar əsasında hazırlanmış R Shiny tətbiqi. Müraciət trendlərini, pasiyent qruplarını və ARIMA proqnozlarını göstərir.

[Canlı R Shiny tətbiqi](https://rashidjafarov.shinyapps.io/synthea)

## İşə salmaq

R konsolunda repozitoriyanın qovluğundan aşağıdakı əmrləri işlədin.

```r
install.packages(c("shiny", "bs4Dash", "data.table", "plotly", "shinycssloaders", "DT"))
shiny::runApp()
```

Tətbiq hazır yekun göstəricilərlə açılır. Uyğun sintetik `patients.rds` və `encounters.rds` faylları mövcuddursa, onları `app.R` ilə eyni qovluğa yerləşdirərək yerli hesablamaları aktivləşdirə bilərsiniz.
