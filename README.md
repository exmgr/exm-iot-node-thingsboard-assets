# Thingsboard-assets
Thingsboard widgets, dashboards, rules used by the sensor node or to assist debug / development.

* Dashboards
    * **Device Management** Device remote control, attributes and log views.
    * **Debug** Main debug dashboard with raw value graphs
    * **SDI12 Logs** Raw SDI12 communication logs (when SDI12 debug flag is enabled)

* Widgets
    * **Sensor Node Control** Helper widget for Sensor Node remote control (setting remote config, OTA etc.)
    
* Rules
    * **Expand Logs** Converts various log messages received from Sensor Node, into telemetry to assist debugging.
    * **FO Sensor Alert** Detects inactivity of FO weather station (when in RF mode) and sends alert.