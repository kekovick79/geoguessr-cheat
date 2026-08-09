# Privacy and Chrome permissions

GeoBoost is published as a Chrome Manifest V3 extension. Its permissions are used for the side-panel workflow, saved settings and supported game-page interaction.

## Chrome permissions

| Permission | Product purpose |
|---|---|
| `sidePanel` | Displays the GeoBoost interface beside the active round |
| `storage` | Saves extension settings and local product state |
| `scripting` | Runs supported interactions on active game pages |
| `alarms` | Schedules limited extension maintenance tasks |

Host access is limited to the supported game sites, `geoboost.win`, and the OpenStreetMap Nominatim service used for readable place names.

## Data boundaries

- The extension does not store third-party API keys.
- Screenshots are not sent for AI analysis.
- A readable place name can depend on reverse-geocoding availability.
- Billing, access restoration and support use GeoBoost's public service endpoints.

For the complete legal description, retention rules and contact details, read the official [GeoBoost Privacy Policy](https://geoboost.win/privacy) and [Terms of Service](https://geoboost.win/terms).

Questions can be sent to [support@geoboost.win](mailto:support@geoboost.win).
