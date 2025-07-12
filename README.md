# Geospatial Course

This is a practical course covering:

- QGIS
- PyQGIS (Python in QGIS)
- PostgreSQL/PostGIS
- GeoServer
- Leaflet.js

💥 **Goal:** Learn how to build geospatial solutions from data preparation to web publication.

---

## 📦 Components

- `docker-compose.yml` → Dockerized PostGIS + GeoServer environment.
- `/week01-qgis-basics` → QGIS basics: loading data, symbology, projections.
- `/week02-pyqgis` → Automating QGIS with Python.
- `/week03-postgis` → Working with spatial databases.
- `/week04-qgis-postgis` → Connecting QGIS to PostGIS.
- `/week05-geoserver` → Publishing data via GeoServer.
- `/week06-leaflet` → Building web maps with Leaflet.js.
- `/project` → Final capstone project.

---

## 🚀 How to start

1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop).
2. Run:
    ```bash
    docker-compose up -d
    ```
3. Access:
    - PostGIS → `localhost:5432`, user `gisuser`, pass `gispass`, db `gisdb`
    - GeoServer → [http://localhost:8080/geoserver](http://localhost:8080/geoserver), admin/admin

---

## 🔗 Open data sources

See `/data/open_datasets.txt` for recommended open datasets.
---------------------------------------------------------------------------------------------------
# Геопространствен курс

Това е практически курс, който обхваща:

- QGIS
- PyQGIS (Python в QGIS)
- PostgreSQL/PostGIS
- GeoServer
- Leaflet.js

💥 **Цел:** Да се научиш как да изграждаш геопространствени решения — от подготовка на данни до публикуване в уеб.

---

## 📦 Компоненти

- `docker-compose.yml` → Docker среда с PostGIS + GeoServer.
- `/week01-qgis-basics` → Основи на QGIS: зареждане на данни, символизация, проекции.
- `/week02-pyqgis` → Автоматизация на QGIS с Python.
- `/week03-postgis` → Работа с пространствени бази данни.
- `/week04-qgis-postgis` → Връзка между QGIS и PostGIS.
- `/week05-geoserver` → Публикуване на данни чрез GeoServer.
- `/week06-leaflet` → Създаване на уеб карти с Leaflet.js.
- `/project` → Финален проект.

---

## 🚀 Как да започнеш

1. Инсталирай [Docker Desktop](https://www.docker.com/products/docker-desktop).
2. Стартирай:
    ```bash
    docker-compose up -d
    ```
3. Достъп:
    - PostGIS → `localhost:5432`, потребител `gisuser`, парола `gispass`, база `gisdb`
    - GeoServer → [http://localhost:8080/geoserver](http://localhost:8080/geoserver), admin/admin

---

## 🔗 Линкове към отворени данни

Виж `/data/open_datasets.txt` за препоръчани отворени набори от данни.
