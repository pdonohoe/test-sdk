# Disclaimer
This project is currently under development. We may update the current version and replace it with a new version at any time. In this case, we recommend you retrieve the latest version in order to ensure technical compliance. The Publications Office cannot guarantee the accuracy, adequacy, validity, reliability, availability or completeness of this information and accepts no responsibility for any use you may make of this project’s component parts.

# Summary
This project is managed by the Publications Office of the European Union to enable implementation of the European legislation for publication of notices for public procurement on the [TED website](https://ted.europa.eu/TED/). For more information, see the [DG GROW eForms](https://ec.europa.eu/growth/single-market/public-procurement/digital/eforms_en) page.

This project aims to provide the necessary tools for being able to build valid eForms notices.
It is composed of the following:
- `schemas`: This folder contains a provisional release of the schemas. There are currently based on an interim version of Pre-Award UBL 2.3 document types and is therefore not yet ready for use.
The adopted approach is to keep the whole set of UBL elements but only support the use of a subset. It provides the advantage of having the rules outside of the schema. Adding extra fields for which a UBL element already exists will not require the definition of a new schema.
- `docs`: This folder contains documentation in English which provides explanations and snippets in addition to the schema.
- `schematrons`: This folder contains Schematron rules which are used to check the validity of notices as per the eForms regulation. Any kind of rule or constraint is implemented in Schematron.
- `examples`: This folder contains some notice examples together with their validation report in SVRL.

# Versioning

Provisional releases of the eForms schema and documentation that were provided during 2020 via SIMAP had a different versioning scheme and are being replaced with this SDK that combines them into one bundle with one version number.
