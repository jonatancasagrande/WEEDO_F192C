# WEEDO_F192C

*** Hello! ***

The information here will help you to update the WEEDO F192C.

The .HEX files were extracted from the official software. In order to save them you need to use the AVRDUDE software with the command :

avrdude -C avrdude.conf -c stk500v1 -P com8 -b 57600 -D -Uflash:w: "flash.hex":i -pm1280 -v -v -v -v -v -v

Note: note the path to the avrdude executable and the flash.hex file.

Remember: any FLASH process may result in the destruction of your board , do it in case it is extremely necessary .

SPANISH EDITION:

*** Hola! ***

La información aqui vertida les servira para poder actualizar la WEEDO F192C.

Los ficheros .HEX fueron extraido desde el software oficial. Para poderlo grabar es necesario utilizar el software AVRDUDE con el comando :

avrdude -C avrdude.conf -c stk500v1 -P com8 -b 57600 -D -Uflash:w:"flash.hex":i -pm1280 -v -v -v -v

Nota: tenga en cuenta la ruta al ejecutable avrdude y al fichero flash.hex .

