# Selección de Áreas Óptimas para un Centro de Conservación de Tortugas Marinas 🐢🌍

## Objetivo:  
- Definir las áreas potenciales para la Construcción de un centro de conservación de tortugas marinas en el departamento del Magdalena, Colombia.
- Implementar herramientas de automatización de procesos GIS para la identificación del área optima de interes.

## Insumos: 
La capas utilizadas como insumos geograficos se obtuvieron de bases de datos geográficos de uso publico y de caracter oficial, es decir, producidos por entidades del estado o instituciones cientificas con el fin de garantizar la veracidad de la información primaria.

1. Registros de avistamientos de tortugas marinas y sitios de anidación.Fuente: Homepage - UNEP-WCMC(unep-wcmc.org) y siam.invemar.org.coinformacion-geografica 
2. Ecosistemas marinos (manglares, arrecifes de coral, pastos marinos, lagunas). Fuente: Siam (invemar.org.co)  
3. Estado de las playas (erosión costera).Fuente: http://geonodesiam.invemar.org.co/layers/geonode%3Aerosion_2 
4. Información sobre sitios poblados.Fuente: www.colombiaenmapas.gov.co  
6. Usos del suelo.Fuente: www.colombiaenmapas.gov.co
7. Ubicación de áreas protegidas. Fuente: www.colombiaenmapas.gov.co 
8. Zonas portuarias: Fuente: www.colombiaenmapas.gov.co
9. Zonas climáticas o de pisos térmicos: Se construyó a partir de datos de temperatura, altura y clima para cada municipio 
   del Magdalena.  
10. Geomorfología de la costa (roca, lodo, plata, etc.): Fuente:www.colombiaenmapas.gov.co

## Criterios de selección: 
La zona para la construcción del centro de conservación y monitoreo de tortugas marinas 
debe cumplir con las siguientes condiciones:
1. Debe tener registros de avistamiento y sitios de anidación de tortugas marinas en 
     la costa a mínimo 1 km.
2. No estar dentro de un PNN o una reserva forestal. 
3. Tener una temperatura mayor a los 21°C y una altura no mayor a los 1000 
     m.s.n.m. 
4. Geomorfología de Playas que no estén en  en erosión. 
5. No puede ubicarse en un área residencial, de infraestructura y transporte, ni de 
     explotación para construcción, tampoco en una zona portuaria (Mínimo a 1 Km) 
6. Debe ser un área con una densidad poblacional de 2,5 a 73,9 personas por Km 
     (DP_Km) 
7. No estar a menos de 200 m de un ecosistema de manglar, ni a menos de 500 m de la línea de costa.
8. Elegir la zona de mayor tamaño,que cumplan los criterios anteriores. 

## Modelo de geoprocesamiento

Se utilizón la herramienta Model Builder para automatizar la selección del área de interes según los criterios definidos previamente.

![Modelo-ModelBuilder](https://github.com/samijalin/GisVoyage/blob/main/Cartograf%C3%ADa/TortugasMarinas_ModelBuilder.jpg)

## Salida Gráfica - Mapa

En el siguiente mapa se resaltan las área potenciales para la construcción del centro de conservación de tortugas marinas, los ecosistemas marinos aledaños y el área de mayor tamaño. 
Se muestran los ecosistemas marinos, debido a su importancia ecologica para el exito de la conservación de tortugas.
Finalmente, el área de mayor tamaño que consta de 31 Km2. 

![Mapa-SeaTurtles](https://github.com/samijalin/GisVoyage/blob/main/Cartograf%C3%ADa/SeaTurtles.jpg)


