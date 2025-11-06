# SolarEdge Modules integration

> [!WARNING]
> **This repository is archived and no longer maintained.**
>
> The functionality of this custom component has been merged into the official [SolarEdge integration](https://www.home-assistant.io/integrations/solaredge/) in Home Assistant.

This feature is included in Home Assistant core release **2025.11.0** and newer, as part of pull request [#152581](https://github.com/home-assistant/core/pull/152581).

## For Existing Users

If you have this custom component installed, you should remove it to use the official core integration.

1.  Remove the `solaredge_modules` integration via HACS or by deleting the `custom_components/solaredge_modules` directory from your configuration folder.
2.  Restart Home Assistant.
3.  Ensure you are running Home Assistant version `2025.11.0` or later.
4.  The official SolarEdge integration will now provide the module, string, and inverter level statistics.
