# Compatibility and driver verification policy

This document describes how community evidence is reviewed before the project makes compatibility claims.

## Status labels

- **Not tested:** no adequate evidence is available. This does not mean incompatible.
- **Community reported:** a user has reported a result; it has not yet been independently reviewed.
- **Under review:** evidence is being checked for completeness and consistency.
- **Experimental (read-only):** observations may be incomplete and are limited to read-only research.
- **Verified for listed capability:** repeatable evidence supports only the specific model/year, display/controller/firmware combination and capability documented.

A status never applies automatically to every model in a product family.

## Minimum evidence

Record, when safe and available:
- Bike make, exact model and model year.
- Display and controller model/firmware, if known and safe to disclose.
- E-Bike Companion app version/build and Android version.
- Connection method and a concise repeatable test procedure.
- Observed output, repeatability and limitations.
- Whether the observation is direct evidence or an inference.

Do not request or publish GPS routes, exact location, serial numbers, account tokens or unnecessary device identifiers.

## Read-only boundary

Experimental drivers and research procedures remain read-only. Compatibility evidence must not be used to justify unreviewed write commands or safety-critical controls. No issue, pull request, screenshot or single successful connection is proof that a bike's throttle, motor, braking or speed-limit controls are safe or supported.

## Publication

A maintainer should review the evidence, document limitations, and record exactly which capabilities were tested before changing a public status. Conflicting or incomplete evidence should remain labelled accordingly.
