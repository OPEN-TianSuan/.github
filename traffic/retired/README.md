# Retired repositories

Audit copies of aggregates for repositories that were consolidated into the
current layers during the November 2026 restructuring. They are **not** read at
runtime: their daily totals were folded into the successor aggregate in
`traffic/<Repository>.csv`, and the badge script only scans `traffic/*.csv`.

| Retired repository | Successor |
| --- | --- |
| ApplicationSoftwareCode | ApplicationLayer |
| SatelliteResource, SoftwareEvaluationPlatform | EngineeringSupport |
| SatelliteOperatingSystem | InfrastructureLayer |
| SatelliteDataset | SatelliteData |
| SatelliteSimulationSoftware | SimulationPlatform |
| SatellitePaper | TechnicalLiterature |

Originals were taken from `9b3af8d:traffic/*.csv`, i.e. the last snapshot before
the restructuring. `SatelliteSoftware` was renamed to `InfrastructureLayer` and
`EngineeringTools` to `EngineeringSupport`; both had no recorded views, so no
data needed to move for them.