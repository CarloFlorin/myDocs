# Runbook: Incident Triage (First 15 Minutes)

## Goal
Impact einschätzen, Stabilisierung starten, klare Kommunikation.

## Quick checks
1) Was ist kaputt? (Symptome, Scope, Zeitpunkt)
2) Monitoring / Logs prüfen
3) Recent changes (Deploys/Config/Infra)

## Procedure
1. **Scope**: nur ein Service oder mehrere? Nur ein Env oder alle?
2. **User Impact**: Anzahl betroffene Nutzer/Transaktionen
3. **Health**:
   ```bash
   curl -I https://<service-host>/

