# SolarEdge Modules integration

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)

The SolarEdge Modules integration allows you to retrieve energy production data per inverter, string, and module from your SolarEdge solar power setup and insert it into Home Assistant statistics.

This repository will be deleted once <https://github.com/home-assistant/core/pull/146036> makes it in core.

See the [SolarEdge Modules integration documentation](https://deploy-preview-39361--home-assistant-docs.netlify.app/integrations/solaredge_modules/).

## Installation

### HACS

1. [Add](http://homeassistant.local:8123/hacs/integrations) custom integrations repository: https://github.com/tronikos/solaredge_modules
2. Select "Solaredge Modules" in the Integration tab and click download
3. Restart Home Assistant
4. Enable the integration

### Manual

1. Copy directory `custom_components/solaredge_modules` to your `<config dir>/custom_components` directory
2. Restart Home-Assistant
3. Enable the integration

### Enable the integration

1. Go to [Settings / Devices & Services / Integrations](http://homeassistant.local:8123/config/integrations). Click **+ ADD INTEGRATION**
2. Search for "Solaredge Modules" and click on it
3. Restart Home Assistant
