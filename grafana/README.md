# Grafana Dashboards

This directory contains Grafana JSON formated dashboard files that can be added to Grafana running in a FABRIC slice.

* up.json  A simple example with a single panel that shows jobs up status.


## Creating Your Own Dashboards

### Tips/Gotchas
The id of the dashboard must be set to null. Otherwise the dashboard may fail to install due to conflicts with an existing dashboard