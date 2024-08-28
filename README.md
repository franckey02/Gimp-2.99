#  GIMP (GNU Image Manipulation Program) 
es un software de edición de imágenes de código abierto, muy popular entre profesionales y aficionados por su versatilidad y capacidad para realizar tareas complejas de retoque fotográfico, diseño gráfico y creación de imágenes. La versión 2.99 representa un gran avance en la historia de GIMP, introduciendo nuevas características y mejoras significativas en su interfaz y rendimiento.

# Características Destacadas de GIMP 2.99
Interfaz Moderna: GIMP 2.99 adopta una interfaz de usuario más intuitiva y moderna, facilitando el flujo de trabajo y la exploración de sus herramientas.

Rendimiento Mejorado: Se han realizado optimizaciones significativas para acelerar el procesamiento de imágenes, especialmente en tareas intensivas como el filtrado y la composición.

Nuevas Herramientas: Se han incorporado nuevas herramientas y funciones para ampliar las posibilidades creativas de los usuarios, como herramientas de selección más precisas y filtros avanzados.

Extensibilidad: GIMP se puede personalizar y ampliar mediante plugins, lo que permite adaptar la aplicación a necesidades específicas.

# He compilado y empaquetado GIMP 2.99 para DEBIAN y derivados 
- instalacion sencilla solo copia y pega este comando en el terminal
```
wget https://github.com/franckey02/Gimp-2.99/releases/download/2.99.16/installer-gimp-2.99.sh
chmod +x installer-gimp-2.99.sh
bash installer-gimp-2.99.sh
```

link del paquete: https://github.com/franckey02/Gimp-2.99/releases/tag/2.99.16

dependencias:
- appstream-glib 0.7.7
- ATK 2.4.0
- babl 0.1.98 https://download.gimp.org/babl/0.1/babl-0.1.108.tar.xz
- cairo 1.14.0
- Fontconfig 2.12.4
- freetype2 2.1.7
- GDK-PixBuf 2.30.8
- GEGL 0.4.48 https://download.gimp.org/gegl/0.4/gegl-0.4.48.tar.xz
- gexiv2 0.14.0
- GIO
- GLib 2.70.0
- glib-networking
- GTK 3.24.0
- gvfs (on Linux)
- HarfBuzz 1.0.5
- libbzip2
- libjpeg
- liblzma 5.0.0
- libmypaint 1.3.0
- libpng 1.6.25
- libpoppler-glib 0.69.0
- librsvg 2.40.6
- libtiff 4.0.0
- Little CMS 2.8
- mypaint-brushes-1.0
- pangocairo 1.50.0
- poppler-data 0.4.9
- zlib

