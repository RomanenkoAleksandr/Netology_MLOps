# Домашняя работа к занятию “Мониторинг”
### Перечислите алерты, которые настроены в Prometheus alerts.
jenkins_down, jenkins_high_cpu, jenkins_high_memory, high_cpu_load, high_memory_load, high_storage_load, monitor_service-down
***
### Перечислите количество dashboards в Grafana, для какого ПО они?
4 дашборда: Docker Containers, Docker Host, Monitor Services, Nginx. Для docker, prometheus и nginx
***
### Сделайте скриншот работающего dashboards docker containers grafana, перечислите метрики, которые там есть.
![изображение](https://github.com/user-attachments/assets/1f3ff4ac-1eae-4aa8-9073-1074e81de14a)
на дашборде отображаются следующие метрики: нагрузка на ЦП, кол-во ядер, нагрузка на оперативную память, используемый объем оперативной памяти, нагрузка на дисковую систему, используемый объем накопителя
