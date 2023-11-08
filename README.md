# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

# [1.0.1] - 08.11.2023
- Check for additional MAC prefixes ("008045","080023","0080F0","BCC342","4C364E","D42DC5") when identifying i-PRO cameras (previously the check was for "D42DC5" only)

# [1.0.0] - 19.09.2023
- Added "Update alarm sending on all cameras" button and functionality in the Management Client plugin
- Added "Custom Event Mapping" button and functionality in the Management Client plugin and in the service
- Camera alarm fields changes (state=New, event Type = i-PRO Maximizer)
- Service tray app design changes
- Fixed the request path, display names of several commands
- Fixed displaying a camera in multiple groups in the Management Client plugin
- Fixed commands buttons states in the Management Client plugin
- Hidden plugin button when the camera is not i-PRO in the Smart Client plugin
- Service starts with DelayedAutoStart 
- Plugin names changes

# [0.9.6] - 25.08.2023
- Added "Configure alarm sending" as a command accesible from the Management Client
- Changed how the scene schedules and privacy guard schedules are stored in the plugin (Issues #10 and #3)
- Changed the sending of commands to Smart Client -> Maximizer Service -> Camera (this should not have any visible effect)
  
# [0.9.5] - 02.08.2023
- Fixed Privacy Guard appId in the Plugins
- Set requested ExecutionLevel to requireAdministrator on Maximizer Service Tray app

# [0.9.4] - 26.07.2023
- Fixed issue #9 - Use https when it's enabled in Management Client hardware settings
- Fixed issue #10 - Exception in the Privacy Guard menu
- Fixed issue #3 - Exception in the Change Scene menu
- Added Enable menu item in the Privacy Guard menu
- Added install id 286 in addition to existing install id 273 when looking for Privacy Guard app
- Chaged UI for Management Client command configure window.

# [0.9.3] - 18.07.2023
- Fixed issue #2 - Display all cameras for a single hardware entry
- Fixed issue #4 - Commands used on Rules
- Fixed issue #5 - Underscores in commands name not shown on Smart Client
- Fixed issue #7 - Display name clears out on Management Client
- Fixed issue #8 - Focus commands with POST instead of GET
- Fixed orientation on Focus buttons

# [0.9.1] - 05.06.2023
- Added: First delivery to i-PRO for testing

