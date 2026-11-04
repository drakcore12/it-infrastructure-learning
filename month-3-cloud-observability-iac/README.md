# Mes 3 — Azure, Dynatrace y Terraform

**Resultado esperado:** diseñar infraestructura cloud básica, desplegarla con IaC y definir observabilidad.

## Calendario diario

### Semana 1 — Azure y fundamentos cloud
- [ ] Día 01: IaaS, PaaS, SaaS, nube pública, privada e híbrida.
- [ ] Día 02: Azure Portal, tenants, suscripciones y regiones.
- [ ] Día 03: Resource Groups, recursos y etiquetas.
- [ ] Día 04: Azure Virtual Machines: CPU, RAM, discos e imágenes.
- [ ] Día 05: VNet, subnets y direccionamiento.
- [ ] Día 06: NSG y reglas de entrada/salida.
- [ ] Día 07: repaso y arquitectura básica Azure.

### Semana 2 — Redes híbridas e identidad
- [ ] Día 08: Azure DNS y DNS privado.
- [ ] Día 09: VNet Peering.
- [ ] Día 10: VPN Gateway Site-to-Site y Point-to-Site.
- [ ] Día 11: Azure Firewall, NSG y segmentación.
- [ ] Día 12: Microsoft Entra ID, usuarios, grupos y tenants.
- [ ] Día 13: RBAC, roles y mínimo privilegio.
- [ ] Día 14: monitorización, backups y protección de recursos.

### Semana 3 — Dynatrace y observabilidad
- [ ] Día 15: métricas, logs y trazas.
- [ ] Día 16: monitorización, observabilidad y APM.
- [ ] Día 17: arquitectura Dynatrace y OneAgent.
- [ ] Día 18: host monitoring: CPU, RAM, disco y red.
- [ ] Día 19: APM, servicios y dependencias.
- [ ] Día 20: distributed tracing y latencia.
- [ ] Día 21: alertas, dashboards, SLI, SLO y SLA.

### Semana 4 — Terraform e IaC
- [ ] Día 22: IaC y Terraform.
- [ ] Día 23: CLI y ciclo init, validate, plan, apply.
- [ ] Día 24: HCL, providers y resources.
- [ ] Día 25: variables, outputs y locals.
- [ ] Día 26: data sources, dependencias y referencias.
- [ ] Día 27: state, remote state y locking.
- [ ] Día 28: modules y reutilización.
- [ ] Día 29: Terraform con Azure.
- [ ] Día 30: proyecto integrador.

## Proyecto integrador

Desplegar con Terraform:
- Resource Group.
- VNet y subnet.
- NSG con reglas de mínimo privilegio.
- VM de laboratorio.
- Documentación de arquitectura y plan de observabilidad.

## Validación de salida

- [ ] Puedo explicar el diseño de red e identidad.
- [ ] Puedo ejecutar init, validate, plan y apply.
- [ ] Puedo parametrizar recursos con variables.
- [ ] Comprendo state y riesgos de secretos.
- [ ] Puedo destruir recursos de laboratorio y verificar que no queden costos activos.

## Referencias oficiales

- [Microsoft Learn — Azure](https://learn.microsoft.com/training/azure/)
- [Terraform Tutorials](https://developer.hashicorp.com/terraform/tutorials)
- [Dynatrace Documentation](https://docs.dynatrace.com/)
