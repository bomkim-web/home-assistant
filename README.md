# Home Assistant Configuration

This repository contains the configuration files for my Home Assistant setup.
You can refer to my setup to configure your own Home Assistant.

## Folder Structure

```
home-assistant/
├── configuration.yaml
├── groups.yaml
├── LICENSE
├── README.md
├── templates.yaml
├── automations/
│   ├── alarms.yaml
│   ├── appliances.yaml
│   ├── curtains.yaml
│   ├── hvac.yaml
│   ├── lights.yaml
│   ├── notifications.yaml
│   ├── remotes.yaml
│   ├── sensors.yaml
```

## Usage

### `configuration.yaml`

This is the main configuration file for Home Assistant. It includes various settings and integrations:

- **Default Config**: Loads the default set of integrations.
- **Frontend Themes**: Loads themes from the `themes` folder.
- **YAML Configuration**: Includes additional configuration files for scripts, scenes, shell commands, templates, and groups.
- **Proxy Configuration**: Configures HTTP proxy settings.
- **Automations**: Includes handmade automations from the `automations` folder and UI-created automations from `automations.yaml`.
- **Notification Grouping**: Groups notifications for multiple devices.

### `groups.yaml`

Contains group configurations for Home Assistant.

### `templates.yaml`

Contains template configurations for Home Assistant.

### `automations/`

This folder contains various automation configurations, each in its own YAML file:

- `alarms.yaml`
- `appliances.yaml`
- `curtains.yaml`
- `hvac.yaml`
- `lights.yaml`
- `notifications.yaml`
- `remotes.yaml`
- `sensors.yaml`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.