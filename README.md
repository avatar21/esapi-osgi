# OWASP ESAPI OSGi

This bundle encapsules the third party dependencies into an OSGi bundle exporting only the [OWASP ESAPI](https://www.owasp.org/index.php/Category:OWASP_Enterprise_Security_API) packages in its MANIFEST.MF

To create the bundle just type ``mvn install`` and take a look in your target folder.

## Create manifest

- library biz.aQute.bnd:biz.aQute.bnd:4.3.0

```sh
bnd print -manifest org.jdom-1.1.2.jar
```
