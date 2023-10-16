## Python FHIR

Python-based FHIR implementation project from [FHIR Connectathon 17](http://wiki.hl7.org/index.php?title=FHIR_Connectathon_17).

Proposes a `fhir` namespace and for Python FHIR implementations and includes an example implementation of a bulk data client using SMART Backend Services authorization protocol.

### Installation

It's best to install using [``virtualenv``](https://virtualenv.pypa.io/en/stable/):

```
virtualenv fhir-client
cd fhir-client && . ./bin/activate
git clone https://github.com/hasagar97/python-fhir
pip install -e ./python-fhir
```

### Usage

The bulk data client is available for use in Python applications as a library. See example in ``./demo/BulkDataDemo.ipynb``.
