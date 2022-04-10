# La Preuve De Garfield

## Arrière-plan

Aux nombreuses preuves du théorème de Pythagore, s'ajoute la contribution du 20ème président des États-Unis d'Amérique **James Garfield**, un diplomé du collège universitaire **Williams College** qui fut de suite enseignant de la langue grecque, du latin, de l'histoire, de la philosophie, de la rhétorique et enfin des mathématiques à l'institut **Western Reserve Ecletic**, aujourd'hui connu sous le nom de **Hiram College**.

<img title="James A. Garfield" src="https://github.com/omedkane/Travail/blob/master/images/Garfield.jpg" alt="" width="426" data-align="center">***James Abram Garfield*** *(November 19, 1831 – September 19, 1881), Président des États-Unis du 4 Mars 1881 jusqu'à son décès le 19 septembre 1881.*



Garfield a avancé sa preuve du théorème de **Pythagore** en 1876 étant membre du Congrès. Sa preuve fut publiée en le 1er Avril 1876 dans le journal **New-England Journal Of Education**.

![](https://github.com/omedkane/Travail/blob/master/images/MergedImages.jpg)

<p align="justify">Les Éléments d'Euclide d'Isaac Barrow (1686), de la collection du Dr Sid Kolpas.</p>

## Démonstration

La démarche de Garfield invite à assembler trois triangles rectangles, en superposant deux triangles aux dimensions égales et en projetant un troisième de sorte à obtenir un trapèze.

### Étape 1 :

Considèrons un triangle <img src="https://render.githubusercontent.com/render/math?math=ABC"> et un autre triangle <img src="https://render.githubusercontent.com/render/math?math=A'B'C'"> de même dimensions mais ce dernier ayant subi une rotation de **90°** vers la droite et placé au dessus du triangle <img src="https://render.githubusercontent.com/render/math?math=ABC"> en superposant  les extrémités hautes de <img src="https://render.githubusercontent.com/render/math?math=B'"> et <img src="https://render.githubusercontent.com/render/math?math=A"> ;

<img title="" src="https://github.com/omedkane/Travail/blob/master/Fig%201.svg" alt="" data-align="center" width="383">

<img title="" src="https://github.com/omedkane/Travail/blob/master/Fig%202.svg" alt="" data-align="center" width="313">

### Étape 2 :

En effectuant une évidente projection du troisième triangle, nous obtenons un trapèze <img src="https://render.githubusercontent.com/render/math?math=T"> :

<img title="" src="https://github.com/omedkane/Travail/blob/master/Fig%203.svg" alt="" data-align="center" width="319">

En effectuant cette projection, nous notons que la surface <img src="https://render.githubusercontent.com/render/math?math=S_T"> du trapèze <img src="https://render.githubusercontent.com/render/math?math=T"> est égale à la somme des surfaces des trois triangles, or rappellons que la surface d'un trapèze est aussi égale à sa hauteur multiplée par la moyenne de ses deux bases, dans notre cas, nous avons :

$$
S_t = (a+b) + \frac{(a+b)}{2}
$$

Rappellons aussi que la surface d'un triangle est égale à la moitié du produit de sa base et hauteur; Soient <img src="https://render.githubusercontent.com/render/math?math=S_{ABC}"> la surface du triangle <img src="https://render.githubusercontent.com/render/math?math=ABC"> et <img src="https://render.githubusercontent.com/render/math?math=S_P"> celle du triangle projété, nous avons :

$$
S_{ABC} = \frac{ab}{2} \hspace{0.2cm} et \hspace{0.2cm} S_P = \frac{c^2}{2} 
$$

La surface <img src="https://render.githubusercontent.com/render/math?math=S_T"> du trapèze étant égale à la somme des surfaces des triangles, nous obtenons l'équation suivante dont la simplification aboutit au théorème de **Pythagore** :

$$
\begin{align}
 S_T = 2 \times S_{ABC} + S_P \\[1em]
(a+b) + \frac{(a+b)}{2} = 2 \times \frac{ab}{2} + \frac{c^2}{2} \\
\frac{(a+b)^2}{2} = ab + \frac{c^2}{2} \\
2 \times (\frac{(a+b)^2}{2}) = 2 \times (ab + \frac{c^2}{2}) \\
(a+b)^2 = 2ab + c^2 \\
a^2 + 2ab + b^2 = 2ab + c^2 \\
-2ab + (a^2 + 2ab + b^2) = -2ab + (2ab + c^2) \\[1em]
\boxed{a^2 + b^2 = c^2}
\end{align}

$$


