# Datos enlazados - Tena, Olivia

Este repositorio contiene una representación en RDF/XML conforme al RDA Registry de la obra:

**"Cuando los hijos se quedan"** de **Olivia Tena**.

## Estructura del RDF

El archivo `tena_olivia.rdf` incluye:

- **Agente** (`A1`): Tena, Olivia — con nombre autorizado, variantes, identificadores (ISNI, ORCID), afiliación institucional y ocupaciones enlazadas a Wikidata.
- **Obra** (`W1`): Con título autorizado, año de creación, autor enlazado y punto de acceso autorizado.
- **Expresión** (`E1`): Idioma y tipo de contenido, enlazada a la obra.
- **Manifestación** (`M1`): Con título, mención de responsabilidad, editorial, ISBN, tipo de soporte, modo de emisión, y enlace a la expresión.

## Visualización

Para visualizar el grafo RDF, puedes usar herramientas como:

- **RDF Grapher (Zazuko)**: https://zazuko.com/rdf-grapher/
- **YASGUI SPARQL**: https://yasgui.triply.cc/
- **W3C RDF Validator**: https://www.w3.org/RDF/Validator/

Sube o proporciona el enlace al archivo `.rdf` ubicado en tu repositorio GitHub.

## Créditos

- **Autor original**: Olivia Tena  
- **Datos estructurados por**: Omar Hernández  
- **Modelo de metadatos**: RDA Registry (http://rdaregistry.info)

---
Este proyecto forma parte de un ejercicio académico sobre modelado de datos enlazados en bibliotecas.

## Validación RDF

Puedes validar este archivo RDF usando el validador oficial del W3C:

🔗 [Validador W3C de RDF](https://www.w3.org/RDF/Validator/rdfval)

### Cómo validar

1. Abre el [validador RDF del W3C](https://www.w3.org/RDF/Validator/rdfval)
2. En el campo “Enter a URI”, pega esta URL:

```
https://raw.githubusercontent.com/Omarherdez/tena_olivia/main/tena_olivia.rdf
```

3. Haz clic en **Parse RDF** o **Parse & Check**