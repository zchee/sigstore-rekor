# Pluggable Types

## Description

Rekor supports pluggable types (aka different schemas) for entries stored in the transparency log.

### Currently supported types

- Alpine Packages [schema](alpine/alpine_schema.json)
  - Versions: 0.0.1
- Helm Provenance Files [schema](helm/helm_schema.json)
  - Versions: 0.0.1
- In-Toto Attestations [schema](intoto/intoto_schema.json)
  - Versions: 0.0.1
- Java Archives (JAR Files) [schema](jar/jar_schema.json)
  - Versions: 0.0.1
- Rekord *(default type)* [schema](rekord/rekord_schema.json)
  - Versions: 0.0.1
- RFC3161 Timestamps [schema](rfc3161/rfc3161_schema.json)
  - Versions: 0.0.1
- RPM Packages [schema](rpm/rpm_schema.json)
  - Versions: 0.0.1

Refer to [Rekor docs](https://docs.sigstore.dev/rekor/pluggable-types) for adding support for new types.
