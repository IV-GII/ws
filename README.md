ws
==

Servicios web para IV-GII alojados en OpenShift

The OpenShift `nodejs` cartridge documentation can be found at:

https://github.com/openshift/origin-server/tree/master/cartridges/openshift-origin-cartridge-nodejs/README.md

Descripción
--

Teniendo en cuenta que los objetivos son una lista ordenada, lo que hace el programa es hacer scraping del wiki de la asignatura usando el ID de la página correspondiente y devolverlo en varios formatos.

Uso
---

Por lo pronto, esto está instalado en [OpenShift](http://objiv-jmerelo.rhcloud.com). 

* Bajarse los objetivos en texto `http://objiv-jmerelo.rhcloud.com/get/<fecha>`, donde fecha es, por ejemplo, 4112013, que correspondería a la clase del, bueno [8 de noviembre de 2013](https://github.com/IV-GII/GII-2013/wiki/Clasedel4112013), por ejemplo [http://objiv-jmerelo.rhcloud.com/get/4112013](http://objiv-jmerelo.rhcloud.com/get/4112013).
* En JSON: `http://objiv-jmerelo.rhcloud.com/get/<fecha>/JSON`, por ejemplo  [http://objiv-jmerelo.rhcloud.com/get/4112013/JSON](http://objiv-jmerelo.rhcloud.com/get/4112013/JSON).
* En JSONP:  `http://objiv-jmerelo.rhcloud.com/get/<fecha>/JSON/<funcion>`, por ejemplo  [http://objiv-jmerelo.rhcloud.com/get/4112013/JSONP/obj](http://objiv-jmerelo.rhcloud.com/get/4112013/JSONP/obj).
