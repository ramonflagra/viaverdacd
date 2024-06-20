# Proposta de via verda Cambrils-Mont-roig-l'Hospitalet de l'Infant :bicyclist:
## Tema :leaves:
La proposta de crear una via verda que connecti els municipis de Cambrils, Mont-roig i Vandellòs i l'Hospitalet de l'Infant sorgeix de la necessitat de donar una nova utilitat a l'antic traçat ferroviari, que va quedar en desús després de la posada en marxa del corredor mediterrani. Aquesta iniciativa aprofita l'abandonament de l'antiga infraestructura ferroviària per generar nous atractius turístics i promoure noves activitats a la zona. La transformació de l'antic traçat en una via verda no només revitalitzarà l'espai, sinó que també fomentarà el turisme sostenible, l'oci a l'aire lliure i la mobilitat no motoritzada, contribuint així al desenvolupament econòmic i social dels municipis implicats. En el projecte es proposen 5 accions diferents per a complementar la ruta de la via verda i complir amb els objectius establerts.
## Continguts :card_index_dividers: 
En aquest apartat s'explica la procedència de les dades i fotografies utilitzades.
### Dades :page_with_curl:
Per tal de recollir les dades necessàries, s'ha utilitzat un estudi previ realitzat en el marc del Grau de Geografia, Anàlisi Territorial i Sostenibilitat. Aquest estudi va fer servir diverses fonts per recopilar la informació presentada. Les fonts utilitzades inclouen recursos oficials com la capa de zones humides extreta de l'ICGC (Institut Cartogràfic i Geològic de Catalunya), així com dades proporcionades pel Departament de Política Territorial i Obres Públiques de la Generalitat de Catalunya i l'Agència Catalana de Turisme.
### Imatges :page_facing_up:
A continuació, s'explica breument l'origen de cada imatge utilitzada:
<li>Logotip: El nostre logotip ha estat creat amb les eines d'intel·ligència artificial de Bing, proporcionant un disseny únic i creatiu que s'adapta a la identitat de la marca.</li>

![](Picsart_24-06-18_15-40-50-790.png)

<li>Imatge de Capçalera: La imatge de capçalera ha estat extreta del lloc web surdecasa.cat, mostrant una escena del municipi de Mont-roig que encaixa amb el tema i l'estètica del nostre lloc web.</li>
<li> Fotos dels Membres: Les fotos dels membres del nostre equip han estat elaborades i seleccionades per l'autor.</li>

## Estructura de la web :books: 
La pàgina s'articula a partir de 5 seccions diferents:
1. Inici: Aquesta secció consta d'una breu introducció de la proposta, explica que són les "vies verdes", destacant els avantatges de la mobilitat sostenible i les oportunitats turístiques que poden generar i fixa els objectius de la iniciativa.
2. Membres: S'hi presenten els diferents membres que han participat en el projecte i es detalla en quin àmbit han actuat.
3. Projectes: S'enumeren i es defineixen els diversos projectes i accions que es poden dur a terme per a complementar la iniciativa.
4. Mapa: Aquest apartat mostra el recorregut de la via verda i les zones humides properes. Aquest recurs serveix per a visualitzar els espais on es duran a terme gran part de les accions definides anteriorment a l'apartat de "projectes".
5. Contacte: Per acabar, a través de la secció de contacte els visitants de la pàgina web poden posar-se en contacte amb els responsables del projecte. Això ajuda a una comunicació més directa i fluida que proporciona una via per a propostes i col·laboracions futures.

## Web responsive :desktop_computer:
Per aconseguir que la pàgina web sigui "responsive", s'han aplicat diverses tècniques. Una d'elles ha estat l'ús de CSS, en particular les regles de "media query". Amb les "media query", s'han establert regles i condicions que permeten ajustar la mida d'elements com imatges o contenidors segons la mida de la pantalla del dispositiu. Això assegura que el disseny i la mida del contingut canviïn de manera adequada per adaptar-se a diferents resolucions de pantalla.

#### Ajustament media query caixes de membres 

```
 @media (max-width: 768px) {
    .card {
      width: 100%;
    }
  }
```

#### Ajustament media query projectes 

```
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
  width: 100%;
  padding: 0;
  }
```

## Cartografia :world_map:
La cartografia s'ha realitzat a partir del software QGIS. En ell s'ha digitalitzat la via verda resseguint les antigues vies del tren a través d'una capa en format línia. Aquesta es pot observar representada en el mapa a través de la línia verda. A continuació s'ha digitalitzat també una capa de punts amb el nom i ubicació de cada zona humida propera a la ruta. Per tal de simbolitzar-les s'ha substituït el format punt per una imatge SVG. La capa utilitzada per al fons del mapa és una imatge satèl·lit del QMS de ESRI.

Un cop s'ha completat el mapa, a partir del plugin QGIS2web s'ha exportat a un format web. A continuació, es va obtenir una carpeta amb els elements css, js, data, etc. Aquests elements es van integrar a la pàgina web, unificant-los amb el codi ja elaborat.

Finalment, es van retocar algunes parts dels css d'aquest mapa, per a poder modificar la presentació d'aquest i ajustar-lo a les nostres necessitats perquè la visualització fos més agradable.

