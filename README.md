DE BASIS:
---------
Standaard wordt een CSS file ingelezen in de index.html (infrabel/final-css/infrabel.css).

In deze file zit standaard:
1) Bootstrap        (infrabel/scss/basics/_load.scss)
2) Fontawesome      (infrabel/scss/basics/_load.scss)
3) Eigen stylen     (infrabel/scss/basics/_changes.scss)
4) [...]


INDIEN de CSS file niet aanwezig is (TODO)
1) Ga naar de root folder
2) npm run build (doet achter de schermen "sass --watch infrabel/scss/basics/infrabel.scss:infrabel/final-css/infrabel.css")


ADVANCED (other company):
---------
1) Verander de (infrabel/scss/basics/infrabel.scss) naar uw gekozen naam.
2) Verander de gewenste kleuren in (infrabel/scss/basics/_variables.scss).
3) Indien gewenst herstyle uw componentjes in hun eigen files  -> Indien er bijgemaakt worden moet men deze ook in de (infrabel/scss/basics/_changes.scss) vermelden.




Semantic versioning explenation:
--------------------------------
//1.x.x     > Not stable for release 
//1.1.1     > GOOD
//x.x.1     > When you make a change that not break anything (a bug fix) = Patch release
//x.1.x     > New feature  = Minor release  > When someone update it will not break your code
//2.x.x     > When there are new things that will break others (backwords-incompatible) = Major release

1) Only patch 
    1.0
    1.0.x
    ~1.0.4  >4 or higher

2) Only new features but backwords-incompatible: only minor verion
    1
    1.x
    ^1.0.4
