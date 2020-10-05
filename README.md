# GrafanaDashboard
Using this, you can recreate the dashboard I currently run in my own homelab. 
This is based upon a TIG (Telegraf - InfluxDB - Grafana) stack.

## Telegraf
Using the Telegraf config in the [telegraf.conf](https://github.com/DB-Vincent/GrafanaDashboard/blob/main/telegraf.conf)  file you get most of the data into the dashboard.
Note: You'll have to edit some things before you can use this configuration.

## PfSense
For the PfSense metrics, you'll have to set up telegraf on you PfSense instance (with the basic settings).

## Climate
These are gathered by an ESP8266, these configuration and software files I won't be sharing unfortunately.
