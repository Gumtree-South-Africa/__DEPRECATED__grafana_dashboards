# Grafana dashboards

This repository contains backup archive of Grafana dashboards nested on 
```https://grafana.phx.ops.prod.bt.ecg.so``` and ```https://grafana.ix5.ops.prod.bt.ecg.so```.
Dashboards - JSON files, are generated and uploaded by ```grafana_simple_backup.py script``` (located on Grafana host).

# Backup details:
Script and its dependencies managed by Puppet: see ```https://gerrit.ecg.so/#/c/53883``` for details.
Dashboard will not be deleted from repository even if it deleted from Grafana.
Dashboards from different Grafana hosts tagged with domain prefix in it's name.

# Import (restore) details:
To import a dashboard open dashboard search and then hit the import button.
From here you can paste dashboard 'json text' directly into the text area.
'Json text' here is raw content of any archived dashboard file.

Example: 
``` https://github.corp.ebay.com/bt-siteops/grafana_dashboards/raw/master/phx.ops.prod.bt.ecg.so.capi-phx ```
