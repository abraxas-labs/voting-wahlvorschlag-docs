# VOTING Wahlvorschlag - Quality Reports

The product [SonarQube](https://www.sonarqube.org/) is used for static code analysis.

The quality profiles used for this are stored in the [sonar-quality-profiles](./sonar-quality-profiles/) directory.

## Component Metrics

| Metric | Service | WebApp |
| --- | --- | --- |
| Type | Backend | Frontend |
| Version | `v2.12.21` | `v4.6.2` |
| Used Quality Profiles | [C# v1.4](./sonar-quality-profiles/CSharp%20Quality%20Profile%20-%20Abraxas%20v1.4.xml)<br>[XML v1.2](./sonar-quality-profiles/XML%20Quality%20Profile%20-%20Abraxas%20v1.2.xml)<br>[YAML v1.0](./sonar-quality-profiles/YAML%20Quality%20Profile%20-%20Abraxas%20v1.0.xml) | [CSS v1.1](./sonar-quality-profiles/CSS%20Quality%20Profile%20-%20Abraxas%20v1.1.xml)<br>[TypeScript v1.6](./sonar-quality-profiles/TypeScript%20Quality%20Profile%20-%20Abraxas%20v1.6.xml)<br>[HTML v1.2](./sonar-quality-profiles/HTML%20Quality%20Profile%20-%20Abraxas%20v1.2.xml) |
| Quality Gate | `OK` | `OK` |
| Vulnerabilities | 0 | 0 |
| Bugs | 0 | 0 |
| Code Smells | 35 | 24 |
| Accepted Issues | 17 | 0 |
| Security Hotspots | 0 | 0 |
| Coverage | 57.3% | 0.0% |
| Duplicated Lines | 1.5% | 0.8% |
| Lines to Cover | 3,977 | 1,197 |
| Lines of Code (ncloc) | 7,498 | 8,770 |
| Maintainability Rating | A | A |
| Reliability Rating | A | A |
| Security Rating | A | A |
