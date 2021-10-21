# library-exhibition-test
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://www.bl.uk/britishlibrary/~/media/bl/global/medieval%20england%20and%20france/collection%20items/arundel_ms_91_f107r.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://api.bl.uk/metadata/iiif/ark:/81055/vdc_100056009767.0x000001/manifest.json">

# Basic usage

## Image

From the early Middle Ages onwards many monasteries produced libelli (small books), each of which contained the life of their patron saint. This illustrated copy includes the Life and Miracles of St Nicholas (d. c. 343), a bishop saint from Myra who was extremely popular in the East. When his relics were transferred from Myra to Bari in southern Italy in 1087, he became a popular saint in the West as well. 

The deluxe manuscript was made towards the end of the 11th century, perhaps in the priory of St Arnoul de Crépy, north of Paris, founded between 935 and 943 by the lords of Crépy. Although most of its buildings have been destroyed, the priory is known to have had a chapel dedicated to St Nicholas.

This manuscript was digitised with the support of The Polonsky Foundation.[^1]
<param ve-image 
       label="The Life and Miracles of Saint Nicholas" 
       description="Manuscript, 4th quarter of the 11th century" 
       license="public domain" 
       url="https://www.bl.uk/britishlibrary/~/media/bl/global/medieval%20england%20and%20france/collection%20items/bnf_latin_18303_f001v.jpg">

## Map

This item was made in Paris.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://api.bl.uk/metadata/iiif/ark:/81055/vdc_100056038199.0x000001/manifest.json">
<param ve-map center="Q36600" zoom="11">

https://www.google.com/maps/@48.8589466,2.2769948,12z

# References

[^1]: [Medieval England and France, 700-1200](https://www.bl.uk/collection-items/bnf-the-life-and-miracles-of-st-nicholas)

