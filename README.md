Lab 2 – Container Security
I denna labb arbetade jag med container-säkerhet genom att skanna en sårbar Docker image med Trivy och förbättra säkerheten genom att härda Dockerfile.
Jag använde Trivy för att hitta sårbarheter och generera rapporter före och efter förbättringar. Jag skapade även en SBOM för att visa alla beroenden i imagen.
Dessutom använde jag OPA Gatekeeper för att införa policy-regler i Kubernetes, till exempel krav på labels.
Verktyg:
Docker
Trivy
OPA Gatekeeper
Kubernetes
Screenshots:
