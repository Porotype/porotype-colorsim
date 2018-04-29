# \<porotype-colorsim\>

This element applies a color blindness simulation filter to it's content or a given element.

```
<porotype-colorsim target="#bar" simulation="Protanomaly" severity="7"/>
<img id="bar" src="..."/>

<porotype-colorsim simulation="Deuteranomaly" severity="10">
    <img src="..." />
</porotype-colorsim>
```

## Color vision deficiency simulation

This element can simulate 10 levels of severety for Protanomaly, Deuteranomaly, and Tritanomaly, using pre-calculated color matrixes as detailed in "A Physiologically-based Model for Simulation of Color Vision Deficiency" by
Gustavo M. Machado, Manuel M. Oliveira, and Leandro Fernandes.
http://www.inf.ufrgs.br/~oliveira/pubs_files/CVD_Simulation/CVD_Simulation.html

Please note that all color vision simulations are approximations, and may not reprecent how a person actually percieves the image. Instead, you can use the simulations to detect potential problems with color use.

## Licence
Apache Licese, Version 2.0
https://www.apache.org/licenses/LICENSE-2.0