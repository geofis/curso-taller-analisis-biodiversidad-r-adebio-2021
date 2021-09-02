%&gt;%
================

Tomado Tw [@andrewheiss](https://twitter.com/andrewheiss)

URL:
<https://evalsp21.classes.andrewheiss.com/projects/01_lab/slides/01_lab.html#116>

``` r
leave_house(get_dressed(get_out_of_bed(wake_up(me, time = "8:00"), side = "correct"), pants = TRUE, shirt = TRUE), car = TRUE, bike = FALSE)

me %>%
  wake_up(time = "8:00") %>%
  get_out_of_bed(side = "correct") %>%
  get_dressed(pants = TRUE, shirt = TRUE) %>%
  leave_house(car = TRUE, bike = FALSE)
```

Adaptado por [@geografiard](https://twitter.com/geografiard) al
dominicano:

``` r
salir_de_la_casa(cambiarme(jondiarme_de_la_cama(despertar(yo, hora = "8:00, con suerte"), lado = "izquierdo, pa'empezá bien"), pantalones = TRUE, camisa = TRUE), carro = FALSE, bicicleta = FALSE, motol = TRUE)

# Aplicando la guía de estilos:
salir_de_la_casa(
  cambiarme(
    jondiarme_de_la_cama(
      despertar(yo, hora = "8:00, con suerte"), lado = "izquierdo, pa'empezá bien"),
    pantalones = TRUE, camisa = TRUE),
  carro = FALSE, bicicleta = FALSE, motol = TRUE)

yo %>% 
  despertar(hora = "8:00, con suerte") %>% 
  jondiarme_de_la_cama(lado = "izquierdo, pa'empezá bien") %>% 
  cambiarme(pantalones = TRUE, camisa = TRUE) %>% 
  salir_de_la_casa(carro = FALSE, bicicleta = FALSE, motol = TRUE)
```
