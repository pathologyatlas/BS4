









```
r language BS4, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis kahverengi yağ doku , echo = (language == "TR")
## BS4 - kahverengi yağ doku {#sec-BS4 }
```


```
asis brown fat , echo = (language == "EN")
## BS4 - brown fat {#sec-BS4 }
```






```
r BS4 screenshot HE1, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS4-HE1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS4/HE1.html",
  file = "./screenshots/BS4-HE1_screenshot.png"
)
}
```






```
r BS4 screenshot HE2, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS4-HE2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS4/HE2.html",
  file = "./screenshots/BS4-HE2_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link







```
asis, echo = (language == "TR")

**kahverengi yağ doku**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS4-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS4/HE1.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS4/HE1.html)
```

```
asis, echo = (language == "EN")

**brown fat**

[![Click for Full Screen WSI](./screenshots/BS4-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS4/HE1.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS4/HE1.html)

```






```
asis, echo = (language == "TR")

**kahverengi yağ doku**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS4-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS4/HE2.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS4/HE2.html)
```

```
asis, echo = (language == "EN")

**brown fat**

[![Click for Full Screen WSI](./screenshots/BS4-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS4/HE2.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS4/HE2.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS4/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS4/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```







```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS4/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS4/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

kahverengi yağ doku

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

brown fat

:::

```









:::::

<hr>
