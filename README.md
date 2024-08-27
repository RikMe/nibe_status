# Nibe heat pump status messages

This repository has the intent of mapping values in the 'current status' register of a Nibe heat pump to actual status messages. This allows me to display the status of the heat pump correctly in Home Assistant.

Heat pump used: S1155

| Status numerical  | Description | Used for |
| ------------- | ------------- | ------------- |
|  1  | Standby  ||
| 8 | Startup | Displayed when the heat pump is initializing|
| 9 | Standby ||
| 4139 | heating ||
| 8235 | Hot water ||
| 524329 | Passive cooling ||
| 4194305 | Smart Price Adaptation ||
| 4718633 | Smart Price Adaptation with cooling ||
