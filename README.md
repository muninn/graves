# graves
An ontology to markup information on human remains, graves, cemeteries, monuments and cenotaphs.

This is the public development github for the ontology, the in-use version is located [here](https://rdf.muninn-project.org/ontologies/graves).

## Version history

### 1.0

* Fix documentation on deprecated properties.
* Add Shipwreck class.
* Add ObjectState class to track the state or health of monuments.
* Add hasState property to link to state.
* Reworked precedence and start / end dates for classes.

### 0.5

* #commemorates can commemorate pretty much anything, remove range from property.
* #obfuscated is deprecated in favor of new sub-property #locationObfuscated.
* Added #denomination property to Dead_people_place.
* Added <foaf:name> to all classes to keep pretty print code happy. (Ticket #34)
* Replaced #monument_name with a combination of #inscription and #site_name.

### 0.2

* Fixed both mass-graves and empty-graves properties by making them sub-classes.
* Added crypt class.
* Removed represents property.
* Added moved_from Object Property.
* Fixed inverse properties.

### 0.1 
* Initial unstable release.
