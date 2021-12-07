# Grafana-0day
Grafana 任意文件读取漏洞poc  基于nuclei验证，比较全的组件，同时验证linux与win，防止遗漏


## 扫描组件
alertGroups、alertlist、icon、alertmanager、annolist、barchart、bargauge、canvas、cloudwatch、dashboard、dashlist、debug、elasticsearch、gauge、geomap、gettingstarted、grafana-azure-monitor-datasource、grafana、graph、graphite、heatmap、histogram、influxdb、jaeger、live、logs、loki、mixed、mssql、mysql、news、nodeGraph、opentsdb、piechart、pluginlist、postgres、prometheus、stat、state-timeline、status-history、table-old、table、tempo、testdata、text、timeseries、welcome、xychart、zipkin、grafana-clock-panel

## 使用
```
/nuclei -t 0day-grafana.yaml -u http://www.test.com
```

## 结果
![image](https://user-images.githubusercontent.com/50769953/145013049-71c2389b-d2f4-44ba-84ed-20e61f13b83f.png)


