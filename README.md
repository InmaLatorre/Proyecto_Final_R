# Proyecto_Final_R
Entrega final de la asignatura R del Máster en Big Data & Analytics, impartida por [Carlos J. Gil Bellosta](https://www.datanalytics.com/bio/)


El proyecto consta de tres partes:

1. Comparativa de dos fuentes de recursos de Regex:
    - RPubs
    - Riptutorial
2. Comparativa de dos fuentes de recursos de Markdown:
    - RStudio
    - R4ds
3. Estudio descriptivo del _dataset_ contenido en R `ChickWeight`


Con ello, demostraré haber interiorizado los conceptos estudiados durante el periodo lectivo.

_Nota:_ Para ver correctamente el trabajo, necesitarás tener instalados los siguientes paquetes:

- ggplot
- ggthemes
- knitr
- reshape2
- data.table

Para comprobarlo, puedes hacer lo siguiente:

<CENTER>
`pk_instalados <- installed.packages(fields = c("Package", "Version")) 
%>% as.data.frame()`</CENTER>


```{r}

polluelos2 <- polluelos1 + ggtitle("Aumento de peso según las diferentes dietas")

library(ggthemes)

polluelos2 + theme_economist(base_size = 10, base_family = "sans", horizontal = TRUE,
                dkpanel = FALSE) + scale_color_economist()
```

polluelos2 + theme_economist(base_size = 10, base_family = "sans", horizontal = TRUE,
                dkpanel = FALSE) + scale_color_economist()

_Inma Latorre_