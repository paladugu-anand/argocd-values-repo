# ArgoCD Values Repository

This repository contains Helm values for multi-source applications.

## Structure
- `config/` - Application-specific values organized by app name
- `namespaces/` - Namespace-specific values  
- `env/` - Environment-specific values
- `multi/` - Multi-layer values (base + overlays)
- `dotpath/` - Test values with ./ path prefix
- `simple/` - Simple values file

## Test Scenarios
Each directory contains test scenarios for different variable substitution patterns.
