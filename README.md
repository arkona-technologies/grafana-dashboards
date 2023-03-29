# grafana

This repository contains a set of shareable grafana dashboards, showing data collected by v//telemetry. The dashboards include reusable grafana library panels.

## Requirements

- [vtelemetry](https://hub.docker.com/r/arkonatechnologies/vtelemetry2)
- [Grafana](https://grafana.com/grafana/download)
- [InfluxDB](https://docs.influxdata.com/influxdb/v2.6/install/)

For further information of the setup process, read the chapter "monitoring" of our [quick start guide](https://www.dropbox.com/home/Public%20Downloads/VM/Guides/QuickStartGuide?preview=Quick_Start_Guide.pdf)

## Usage

To load a dashboard, go to your grafana homepage and select "dashboards -> import" in the menu.

<img src="./import_db_1.png" width="200">

Select the json to upload from your computer or copy the json content to the text area.

<img src="./import_db_2.png" width="300">

Select the database to which vtelemetry sends its data and click "import".

<img src="./import_db_3.png" width="300">

The dashboard is loading afterwards and should be presented to you.

![](./import_db_4.png)

More information on [Grafana - Manage Dashboards](https://grafana.com/docs/grafana/latest/dashboards/manage-dashboards/)
