# prometheus-grafana

<b>Настроить дашборд с 4-мя графиками:</b>

<b>память;</b>

<b>процессор;</b>

<b>диск;</b>

<b>сеть.</b>
___

В рамках задачи использовалась система мониторинга Prometheus и система визуализации Grafana.

Настроен мониторинг метрик двух виртуальных серверов.

Для запуска <a href="https://github.com/Arkady1996/prometheus-grafana/blob/main/prometheus.service">Prometheus</a> и <a href="https://github.com/Arkady1996/prometheus-grafana/blob/main/node_exporter.service">Node Exporter</a> написаны Unit файлы.

![img_1](https://github.com/Arkady1996/prometheus-grafana/blob/main/images/Prometheus.PNG)

![img_2](https://github.com/Arkady1996/prometheus-grafana/blob/main/images/Grafana.PNG)
