# 中国地图数据集合 | China Map Data Collection

这个仓库包含了中国地图相关的 GeoJSON 数据，包括：
This repository contains GeoJSON data related to China maps, including:
- 省级行政区划数据 | Provincial administrative divisions
- 城市级行政区划数据 | City-level administrative divisions
- 国家边界数据 | National boundary data

## 数据说明 | Data Description

- `provinces.cn.geojson`: 中国省级行政区划数据 | China provincial administrative divisions
- `cities.cn/`: 中国城市级行政区划数据 | China city-level administrative divisions
- `countries.geojson`: 国家边界数据 | National boundary data

## 数据格式 | Data Format

所有数据均采用 GeoJSON 格式，这是一种用于表示地理要素的开放标准格式。GeoJSON 支持以下几何类型：
All data is in GeoJSON format, which is an open standard format for representing geographic features. GeoJSON supports the following geometry types:
- Point（点）| Point
- LineString（线）| LineString
- Polygon（多边形）| Polygon
- MultiPoint（多点）| MultiPoint
- MultiLineString（多线）| MultiLineString
- MultiPolygon（多边形集合）| MultiPolygon

## 使用说明 | Usage

1. 直接下载需要的 GeoJSON 文件 | Download the required GeoJSON files directly
2. 使用支持 GeoJSON 的地图库（如 Leaflet、Mapbox GL JS 等）加载数据 | Load data using map libraries that support GeoJSON (such as Leaflet, Mapbox GL JS, etc.)
3. 根据需要进行数据可视化或分析 | Perform data visualization or analysis as needed
