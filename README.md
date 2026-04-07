# Ubiquiti SNMP YAML Generator

### Initial version
Generates Home Assistant YAML code for SNMP-enabled selected Ubiquiti devices.
Select device type, enter its IP or hostname, fill out the SNMP details (username, auth key, private password). Default values for Auth protocol and private protocol are known to work with Ubiquiti devices. Optional: Edit your chosen device label (used to generate sensor names) and Entity ID prefix (used to generate internal sensor ID names).

You can customize SNMP scan intervals per category, as well as which categories and sensor types you want to add. By default, all possible sensors are pre-selected. The tool will then generate YAML code for that device.

The YAML code can then be pasted into your configuration.yaml file for Home Assistant. 

*Note*: The data for existing devices was obtained via snmpwalk.
