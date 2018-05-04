![alt tag](readme/cambodia-banner-1024x166.png)

---

# Artifacts for the <br>_OpenMRS distribution for Cambodia_
This repository maintains the 'distro POM' for the _OpenMRS distribution for Cambodia_.
It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `bahmni_emr/`
<br/>The target version of the front-end apps that makes 'Bahmni EMR'.
* `bahmni_config/`
<br/>The bespoke Bahmni configuration (more [here](https://github.com/mekomsolutions/bahmni-config-cambodia)) to be consumed by Bahmni Apps.
* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/mekomsolutions/openmrs-config-cambodia)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.

---

# Background
http://www.mekomsolutions.com/news/#news_14-02-2017
>The aim of the _OpenMRS distribution for Cambodia_ is to be ready-to-use for Cambodian primary care facilities and to support standard terminology, standard code sets and standard work processes as well as adequate reporting analytics.