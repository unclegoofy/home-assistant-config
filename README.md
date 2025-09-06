# 🏠 Home Assistant Config Repo

This repo contains the full configuration for my Home Assistant instance, including automations, scenes, scripts, helpers, and blueprints. It’s designed for modularity, clarity, and CI/CD deployment.

## 🔧 Structure

- `automations/`: YAML-based automations grouped by function
- `scenes/`: Static and dynamic scenes for lighting, routines, and alerts
- `scripts/`: Reusable logic blocks triggered by automations
- `helpers/`: Input booleans, numbers, and datetimes for state tracking
- `blueprints/`: Reusable automation templates
- `packages/`: Optional domain bundles (e.g. bedtime, security)
- `.github/workflows/`: CI/CD validation pipeline
- `secrets.yaml`: Optional secrets file for sensitive values

## 🚀 Goals

- Maintain a clean, documented, and deploy-grade smart home stack
- Use GitHub for version control, rollback, and collaboration
- Enable automation testing and YAML linting via GitHub Actions
- Modularize logic for clarity and future extensibility

## 📦 Deployment

Changes are committed via Git and validated through CI/CD workflows. Scene snapshots and automation logic are tested in staging before merging to `main`.

## 🧠 Philosophy

Every automation, scene, and helper should have a clear purpose, be documented, and support future growth. This stack is built for clarity, tactical control, and competitive edge — just like my fantasy ops suite.