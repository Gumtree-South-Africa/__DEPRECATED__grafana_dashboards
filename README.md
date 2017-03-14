# grafana_dashboards

This repository contains backup archive of Grafana dashboards nested on https://grafana.phx.ops.prod.bt.ecg.so
Dashboards - JSON files, are generated and uploaded by grafana_simple_backup.py script (located on Grafana host).

Backup script and its dependencies managed by Puppet. 
Please see gerrit.ecg.so:29418/ecg-puppet.git for details.

To import a dashboard open dashboard search and then hit the import button.
From here you can paste dashboard json text directly into the text area.
Json text here is raw content of any archived dashboard (for example: https://github.corp.ebay.com/bt-siteops/grafana_dashboards/raw/master/node-app-ix5).
