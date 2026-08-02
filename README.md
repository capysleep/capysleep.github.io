# CapySleep documentation

Engineering and product docs for the CapySleep iOS app. The public privacy/terms/support site pages also live under this folder (`index.html`, `privacy.html`, etc.).

Root essentials stay at the repository root: [`README.md`](../README.md), [`AGENTS.md`](../AGENTS.md).

## Setup

Platform capabilities and configuration:

| Doc | Topic |
|-----|--------|
| [setup/healthkit.md](./setup/healthkit.md) | HealthKit entitlement, types, testing |
| [setup/app-group.md](./setup/app-group.md) | App Group `group.com.capysleep.shared` |
| [setup/live-activity.md](./setup/live-activity.md) | Widgets and Live Activities |
| [setup/time-sensitive-notifications.md](./setup/time-sensitive-notifications.md) | Alarm / reminder interruption level |
| [setup/capysleep-pro.md](./setup/capysleep-pro.md) | StoreKit 2 subscription setup and test matrix |

## Features

| Doc | Topic |
|-----|--------|
| [features/get-started.md](./features/get-started.md) | Post-onboarding Get Started checklist |
| [features/alarm-stop-snooze.md](./features/alarm-stop-snooze.md) | Alarm slide-to-stop and snooze button |
| [features/weekly-sleep-chart.md](./features/weekly-sleep-chart.md) | Weekly duration area chart |
| [features/audio-categorization-training.md](./features/audio-categorization-training.md) | On-device audio calibration |

## Architecture

| Doc | Topic |
|-----|--------|
| [architecture/sleep-stage-detection.md](./architecture/sleep-stage-detection.md) | Shipped motion + audio staging |
| [architecture/sleep-stage-detection-on-device-sensors.md](./architecture/sleep-stage-detection-on-device-sensors.md) | Research/sensor context (+ [PDF](./architecture/sleep-stage-detection-on-device-sensors.pdf)) |
| [architecture/sleep-hypnogram.md](./architecture/sleep-hypnogram.md) | Hypnogram UI structure |
| [architecture/performance.md](./architecture/performance.md) | Caching and performance hotspots |

## Agent workflow

Contributor and agent rules, including which docs to read before coding: [`AGENTS.md`](../AGENTS.md).
