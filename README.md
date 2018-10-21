# MBR.md
# ¿Qué es MBR?
_MBR(MasterBootRecord), es el primer sector de un dispositivo de almacenamiento de datos como un disco duro._

Puede ser utilizado para:

·El arranque de sistema operativo con bootstrap.

·Almacenar una tabla de particiones.

·Identificar un dispositivo de disco individual.(Poco común)

# ¿Qué contiene MBR?

__Gestor de arranque__

__El registro de arranque maestro (MBR) está en el primer sector del disco.__

_Se utiliza para almacenar la tabla de particiones y en el arranque del sistema operativo con bootstrap que se encuentra en la memoria de solo lectura del BIOS._

__Tabla  de Particiones__

La información de las particiones se almacena en la tabla de particiones, para la cual hay 2 formatos en uso hoy en día.

__El clásico Master Boot Record y la moderna GUID Partition Table__

·__Master Boot Record__

MBR originalmente solo admitía hasta 4 particiones. Más tarde, se ampliaron al introducir particiones lógicas para superar esta limitación.

Existen tres tipos de particiones de disco:

Primaria

Extendida

Lógica

·__GUID Partition Table__

Existe un solo tipo de partición, primaria. La cantidad de particiones por disco o volumen RAID es ilimitado.

__Firma de unidad arrancable__

"55h AAh" en hexadecimal.
