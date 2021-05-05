# docker-compose-laravel
* Laravel application with the following features 
  * Integrates Laravel queues & cronjob
	* Mysql (application database)
	* Redis (for Laravel queues)
	* Elastic search & Kibana (to visualise logs from the Laravel application).
# EXPOSED PORTS
* nginx - :8080
* mysql - :3306
* php - :9000