<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Li Shizhen and Bencao Gangmu" 
       banner="https://upload.wikimedia.org/wikipedia/commons/d/d9/Li_Shizhen.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Li Shinzhen

This is a visual essay informing the aud.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Bencao Gangmu_ (English: Compendium of  Materia Medica) is a phamacopeia of Chinese medicinal knowledge, written by Li Shizhen (1518-1593) during the Ming Dynasty (1368-1644)[^1].  The phamacopeia also includes international materials brought to China via European trade.[^2]
<param ve-image 
       label="Bencao Gangmu" 
       description="Pages in the pharmacopeia: Bencao Gangmu" 
       license="public domain" 
       url="https://retrospectmagazinehca.files.wordpress.com/2021/04/kj2.jpeg?w=1024&h=580&crop=1">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Chinaknowledge.de:Bencao gangmu 本草綱目](http://www.chinaknowledge.de/Literature/Science/bencaogangmu.html)
[^2]: [Retrospectmagazine: Bencao Gangmu](https://retrospectmagazinehca.files.wordpress.com/2021/04/kj2.jpeg?w=1024&h=580&crop=1)
