# netbeansConfig
Configuraciones preferidas para Netbeans:
  - Version Dark (dark/dark.zip) Require tener instalado el plugin Dark Look And Feel Themes
  - Version White (white/white.zip)

Tambien es recomendable utilizar la siguiente configuracion en: netbeans-8.1/etc/netbeans.conf

netbeans_default_options="-J-client -J-Xss2m -J-Xms350m -J-Xmx750m -J-Xverify:none -J-XX:CompileThreshold=100 -J-XX:+AggressiveOpts -J-Xverify:none -J-Dapple.laf.useScreenMenuBar=true -J-Dapple.awt.graphics.UseQuartz=true -J-Dsun.java2d.noddraw=true -J-Dsun.java2d.dpiaware=true -J-Dsun.zip.disableMemoryMapping=true"

esta configuracion funciona con la JVM de Oracle.

Para reducir el uso de memmoria y hacelo eficiente para esta configuracion se recomienda usar la JVM de 32 bits.


