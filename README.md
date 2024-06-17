# CODING CHALLENGE - DATA SCIENTIST

Ihre Aufgabe besteht in der Modellierung der zu erwartenden Schadenhöhe pro Versicherungsnehmer und Jahr anhand der Risikomerkmale der Kunden. Dieser Wert ist Basis für die Berechnung eines fairen Versicherungsbeitrags.

## Daten
Die zwei Datensätze sind auf den folgenden Webseiten zu finden. Um den Code durchzuführen, müssen sie in der Working Directory gespeichert sein.
[Versicherungsverträge](https://www.openml.org/d/41214)
[Schadenfälle](https://www.openml.org/d/41215)

## Benötigte Packages
Für den Download:
```
install.packages(c('farff', 'tidyverse', 'ggplot2', 'ggcorrplot', 'gridExtra', 'mlr3verse', 'tweedie', 'statmod', 'ranger', 'xgboost'))
options(repos = c(
  mlrorg = "https://mlr-org.r-universe.dev",
  CRAN = "https://cloud.r-project.org/"
))
install.packages('mlr3extralearners')
```
