# Radar-VHDL

## Descripción
El proyecto consiste en un radar elaborado en VHDL. Este radar trabaja en un rango de 0 a 20 cm en un área de aproximadamente 135°. Se hace uso de una pantalla en donde se muestran los grados y la distancia en la que se encuentra el objeto detectado, así como un mapa que muestra un aproximado de la posición.

## Material utilizado
- Tarjeta DE10 Lite
- Sensor ultrasónico
- Servomotor
- Pantalla con entrada VGA
- Cable VGA a VGA
- Jumpers

## Restriccionesce
1. El sensor únicamente considera de 1 a 20 cm de distancia entre el objeto y radar. Cualquier distancia fuera de este rango es considerada como 0 (cero).
2. El área en la que se trabaja es la que alcanza a cubrir el servomotor (135° aproximadamente).
