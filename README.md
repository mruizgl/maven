# Instalación de Maven en el SO


## Título de la tarea

 - __Instalación de MAVEN en el Ubuntu__


## Introducción

 Apache Maven es una herramienta de gestión y comprensión de proyectos de código abierto que se utiliza principalmente para proyectos Java. Maven usa un modelo de objetos de proyecto (POM), que es esencialmente un archivo XML que contiene información del proyecto, detalles de configuración, dependencias del proyecto y más.

## Instalar Apache Maven

### Instalar Apache Maven con apt

 Instalar Maven en Ubuntu usando apt es un proceso simple y directo.

 Actualice el índice del paquete e instale Maven ingresando los siguientes comandos:

```
 sudo apt update
```
SALIDA EN MI CONSOLA: 
```
melissa@melissa-linux:~$ sudo apt update
[sudo] contraseña para melissa:     
Des:1 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]
Obj:2 http://archive.ubuntu.com/ubuntu jammy InRelease                         
Ign:3 http://packages.linuxmint.com victoria InRelease                         
Des:4 http://archive.ubuntu.com/ubuntu jammy-updates InRelease [119 kB]        
Des:5 http://packages.linuxmint.com victoria Release [24,2 kB]
Des:6 http://security.ubuntu.com/ubuntu jammy-security/main amd64 Packages [896 kB]
Des:7 http://packages.linuxmint.com victoria Release.gpg [833 B]               
Des:8 http://security.ubuntu.com/ubuntu jammy-security/main i386 Packages [353 kB]
Des:9 http://security.ubuntu.com/ubuntu jammy-security/main amd64 DEP-11 Metadata [43,0 kB]
Des:10 http://security.ubuntu.com/ubuntu jammy-security/main amd64 c-n-f Metadata [11,4 kB]
Des:11 http://security.ubuntu.com/ubuntu jammy-security/universe i386 Packages [562 kB]
Des:12 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 Packages [793 kB]
Des:13 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 DEP-11 Metadata [55,0 kB]
Des:14 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 c-n-f Metadata [16,7 kB]
Des:15 http://archive.ubuntu.com/ubuntu jammy-backports InRelease [109 kB]
Des:16 http://packages.linuxmint.com victoria/upstream amd64 Packages [48,4 kB]
Des:17 http://archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages [516 kB]
Des:18 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages [1.104 kB]
Des:19 http://archive.ubuntu.com/ubuntu jammy-updates/main Translation-en [240 kB]
Des:20 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 DEP-11 Metadata [101 kB]
Des:21 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 c-n-f Metadata [16,1 kB]
Des:22 http://archive.ubuntu.com/ubuntu jammy-updates/universe i386 Packages [660 kB]
Des:23 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 Packages [995 kB]
Des:24 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 DEP-11 Metadata [305 kB]
Des:25 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 c-n-f Metadata [22,0 kB]
Des:26 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 DEP-11 Metadata [940 B]
Des:27 http://archive.ubuntu.com/ubuntu jammy-backports/main amd64 DEP-11 Metadata [4.920 B]
Des:28 http://archive.ubuntu.com/ubuntu jammy-backports/universe amd64 DEP-11 Metadata [17,9 kB]
Descargados 7.124 kB en 3s (2.601 kB/s)              
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
Se pueden actualizar 222 paquetes. Ejecute «apt list --upgradable» para verlos.

``
```
 sudo apt install maven
```
SALIDA EN MI CONSOLA: 
```
melissa@melissa-linux:~$ sudo apt install maven
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
Se instalarán los siguientes paquetes adicionales:
  libaopalliance-java libapache-pom-java libatinject-jsr330-api-java
  libcdi-api-java libcommons-cli-java libcommons-io-java libcommons-lang3-java
  libcommons-parent-java libgeronimo-annotation-1.3-spec-java
  libgeronimo-interceptor-3.0-spec-java libguava-java libguice-java
  libhawtjni-runtime-java libjansi-java libjansi-native-java libjsr305-java
  libmaven-parent-java libmaven-resolver-java libmaven-shared-utils-java
  libmaven3-core-java libplexus-cipher-java libplexus-classworlds-java
  libplexus-component-annotations-java libplexus-interpolation-java
  libplexus-sec-dispatcher-java libplexus-utils2-java libsisu-inject-java
  libsisu-plexus-java libslf4j-java libwagon-file-java
  libwagon-http-shaded-java libwagon-provider-api-java
Paquetes sugeridos:
  libaopalliance-java-doc libatinject-jsr330-api-java-doc
  libcommons-io-java-doc libcommons-lang3-java-doc libasm-java libcglib-java
  libjsr305-java-doc libmaven-shared-utils-java-doc liblogback-java
  libplexus-classworlds-java-doc libplexus-sec-dispatcher-java-doc
  libplexus-utils2-java-doc junit4 testng libcommons-logging-java
  liblog4j1.2-java
Se instalarán los siguientes paquetes NUEVOS:
  libaopalliance-java libapache-pom-java libatinject-jsr330-api-java
  libcdi-api-java libcommons-cli-java libcommons-io-java libcommons-lang3-java
  libcommons-parent-java libgeronimo-annotation-1.3-spec-java
  libgeronimo-interceptor-3.0-spec-java libguava-java libguice-java
  libhawtjni-runtime-java libjansi-java libjansi-native-java libjsr305-java
  libmaven-parent-java libmaven-resolver-java libmaven-shared-utils-java
  libmaven3-core-java libplexus-cipher-java libplexus-classworlds-java
  libplexus-component-annotations-java libplexus-interpolation-java
  libplexus-sec-dispatcher-java libplexus-utils2-java libsisu-inject-java
  libsisu-plexus-java libslf4j-java libwagon-file-java
  libwagon-http-shaded-java libwagon-provider-api-java maven
0 actualizados, 33 nuevos se instalarán, 0 para eliminar y 222 no actualizados.
Se necesita descargar 10,2 MB de archivos.
Se utilizarán 13,3 MB de espacio de disco adicional después de esta operación.
¿Desea continuar? [S/n] S
Des:1 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libapache-pom-java all 18-1 [4.720 B]
Des:2 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libatinject-jsr330-api-java all 1.0+ds1-5 [5.348 B]
Des:3 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libgeronimo-interceptor-3.0-spec-java all 1.0.1-4fakesync [8.616 B]
Des:4 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libcdi-api-java all 1.2-3 [54,3 kB]
Des:5 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libcommons-cli-java all 1.4-2 [55,8 kB]
Des:6 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libcommons-parent-java all 43-1 [10,8 kB]
Des:7 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libcommons-io-java all 2.11.0-2 [297 kB]
Des:8 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libcommons-lang3-java all 3.11-1 [526 kB]
Des:9 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libgeronimo-annotation-1.3-spec-java all 1.3-1 [11,2 kB]
Des:10 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libjsr305-java all 0.1~+svn49-11 [27,0 kB]
Des:11 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libguava-java all 29.0-6 [2.418 kB]
Des:12 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libaopalliance-java all 20070526-6 [9.084 B]
Des:13 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libguice-java all 4.2.3-2 [1.434 kB]
Des:14 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libhawtjni-runtime-java all 1.17-1 [28,8 kB]
Des:15 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libjansi-native-java all 1.8-1 [23,8 kB]
Des:16 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libjansi-java all 1.18-1 [56,8 kB]
Des:17 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libmaven-parent-java all 31-2 [5.140 B]
Des:18 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-utils2-java all 3.3.0-1 [250 kB]
Des:19 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libwagon-provider-api-java all 3.3.4-1 [48,5 kB]
Des:20 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libmaven-resolver-java all 1.4.2-3build1 [555 kB]
Des:21 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libmaven-shared-utils-java all 3.3.0-1 [149 kB]
Des:22 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-cipher-java all 1.8-2 [15,1 kB]
Des:23 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-classworlds-java all 2.6.0-1 [49,4 kB]
Des:24 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-component-annotations-java all 2.1.0-1 [6.564 B]
Des:25 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-interpolation-java all 1.26-1 [76,8 kB]
Des:26 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libplexus-sec-dispatcher-java all 1.4-4 [28,1 kB]
Des:27 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libslf4j-java all 1.7.32-1 [141 kB]
Des:28 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libsisu-inject-java all 0.3.4-2 [347 kB]
Des:29 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libsisu-plexus-java all 0.3.4-3 [181 kB]
Des:30 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libmaven3-core-java all 3.6.3-5 [1.535 kB]
Des:31 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libwagon-file-java all 3.3.4-1 [7.928 B]
Des:32 http://archive.ubuntu.com/ubuntu jammy/universe amd64 libwagon-http-shaded-java all 3.3.4-1 [1.855 kB]
Des:33 http://archive.ubuntu.com/ubuntu jammy/universe amd64 maven all 3.6.3-5 [17,8 kB]
Descargados 10,2 MB en 3s (3.785 kB/s)
Extrayendo plantillas para los paquetes: 100%
Seleccionando el paquete libapache-pom-java previamente no seleccionado.
(Leyendo la base de datos ... 526688 ficheros o directorios instalados actualmen
te.)
Preparando para desempaquetar .../00-libapache-pom-java_18-1_all.deb ...
Desempaquetando libapache-pom-java (18-1) ...
Seleccionando el paquete libatinject-jsr330-api-java previamente no seleccionado
.
Preparando para desempaquetar .../01-libatinject-jsr330-api-java_1.0+ds1-5_all.d
eb ...
Desempaquetando libatinject-jsr330-api-java (1.0+ds1-5) ...
Seleccionando el paquete libgeronimo-interceptor-3.0-spec-java previamente no se
leccionado.
Preparando para desempaquetar .../02-libgeronimo-interceptor-3.0-spec-java_1.0.1
-4fakesync_all.deb ...
Desempaquetando libgeronimo-interceptor-3.0-spec-java (1.0.1-4fakesync) ...
Seleccionando el paquete libcdi-api-java previamente no seleccionado.
Preparando para desempaquetar .../03-libcdi-api-java_1.2-3_all.deb ...
Desempaquetando libcdi-api-java (1.2-3) ...
Seleccionando el paquete libcommons-cli-java previamente no seleccionado.
Preparando para desempaquetar .../04-libcommons-cli-java_1.4-2_all.deb ...
Desempaquetando libcommons-cli-java (1.4-2) ...
Seleccionando el paquete libcommons-parent-java previamente no seleccionado.
Preparando para desempaquetar .../05-libcommons-parent-java_43-1_all.deb ...
Desempaquetando libcommons-parent-java (43-1) ...
Seleccionando el paquete libcommons-io-java previamente no seleccionado.
Preparando para desempaquetar .../06-libcommons-io-java_2.11.0-2_all.deb ...
Desempaquetando libcommons-io-java (2.11.0-2) ...
Seleccionando el paquete libcommons-lang3-java previamente no seleccionado.
Preparando para desempaquetar .../07-libcommons-lang3-java_3.11-1_all.deb ...
Desempaquetando libcommons-lang3-java (3.11-1) ...
Seleccionando el paquete libgeronimo-annotation-1.3-spec-java previamente no sel
eccionado.
Preparando para desempaquetar .../08-libgeronimo-annotation-1.3-spec-java_1.3-1_
all.deb ...
Desempaquetando libgeronimo-annotation-1.3-spec-java (1.3-1) ...
Seleccionando el paquete libjsr305-java previamente no seleccionado.
Preparando para desempaquetar .../09-libjsr305-java_0.1~+svn49-11_all.deb ...
Desempaquetando libjsr305-java (0.1~+svn49-11) ...
Seleccionando el paquete libguava-java previamente no seleccionado.
Preparando para desempaquetar .../10-libguava-java_29.0-6_all.deb ...
Desempaquetando libguava-java (29.0-6) ...
Seleccionando el paquete libaopalliance-java previamente no seleccionado.
Preparando para desempaquetar .../11-libaopalliance-java_20070526-6_all.deb ...
Desempaquetando libaopalliance-java (20070526-6) ...
Seleccionando el paquete libguice-java previamente no seleccionado.
Preparando para desempaquetar .../12-libguice-java_4.2.3-2_all.deb ...
Desempaquetando libguice-java (4.2.3-2) ...
Seleccionando el paquete libhawtjni-runtime-java previamente no seleccionado.
Preparando para desempaquetar .../13-libhawtjni-runtime-java_1.17-1_all.deb ...
Desempaquetando libhawtjni-runtime-java (1.17-1) ...
Seleccionando el paquete libjansi-native-java previamente no seleccionado.
Preparando para desempaquetar .../14-libjansi-native-java_1.8-1_all.deb ...
Desempaquetando libjansi-native-java (1.8-1) ...
Seleccionando el paquete libjansi-java previamente no seleccionado.
Preparando para desempaquetar .../15-libjansi-java_1.18-1_all.deb ...
Desempaquetando libjansi-java (1.18-1) ...
Seleccionando el paquete libmaven-parent-java previamente no seleccionado.
Preparando para desempaquetar .../16-libmaven-parent-java_31-2_all.deb ...
Desempaquetando libmaven-parent-java (31-2) ...
Seleccionando el paquete libplexus-utils2-java previamente no seleccionado.
Preparando para desempaquetar .../17-libplexus-utils2-java_3.3.0-1_all.deb ...
Desempaquetando libplexus-utils2-java (3.3.0-1) ...
Seleccionando el paquete libwagon-provider-api-java previamente no seleccionado.
Preparando para desempaquetar .../18-libwagon-provider-api-java_3.3.4-1_all.deb 
...
Desempaquetando libwagon-provider-api-java (3.3.4-1) ...
Seleccionando el paquete libmaven-resolver-java previamente no seleccionado.
Preparando para desempaquetar .../19-libmaven-resolver-java_1.4.2-3build1_all.de
b ...
Desempaquetando libmaven-resolver-java (1.4.2-3build1) ...
Seleccionando el paquete libmaven-shared-utils-java previamente no seleccionado.
Preparando para desempaquetar .../20-libmaven-shared-utils-java_3.3.0-1_all.deb 
...
Desempaquetando libmaven-shared-utils-java (3.3.0-1) ...
Seleccionando el paquete libplexus-cipher-java previamente no seleccionado.
Preparando para desempaquetar .../21-libplexus-cipher-java_1.8-2_all.deb ...
Desempaquetando libplexus-cipher-java (1.8-2) ...
Seleccionando el paquete libplexus-classworlds-java previamente no seleccionado.
Preparando para desempaquetar .../22-libplexus-classworlds-java_2.6.0-1_all.deb 
...
Desempaquetando libplexus-classworlds-java (2.6.0-1) ...
Seleccionando el paquete libplexus-component-annotations-java previamente no sel
eccionado.
Preparando para desempaquetar .../23-libplexus-component-annotations-java_2.1.0-
1_all.deb ...
Desempaquetando libplexus-component-annotations-java (2.1.0-1) ...
Seleccionando el paquete libplexus-interpolation-java previamente no seleccionad
o.
Preparando para desempaquetar .../24-libplexus-interpolation-java_1.26-1_all.deb
 ...
Desempaquetando libplexus-interpolation-java (1.26-1) ...
Seleccionando el paquete libplexus-sec-dispatcher-java previamente no selecciona
do.
Preparando para desempaquetar .../25-libplexus-sec-dispatcher-java_1.4-4_all.deb
 ...
Desempaquetando libplexus-sec-dispatcher-java (1.4-4) ...
Seleccionando el paquete libslf4j-java previamente no seleccionado.
Preparando para desempaquetar .../26-libslf4j-java_1.7.32-1_all.deb ...
Desempaquetando libslf4j-java (1.7.32-1) ...
Seleccionando el paquete libsisu-inject-java previamente no seleccionado.
Preparando para desempaquetar .../27-libsisu-inject-java_0.3.4-2_all.deb ...
Desempaquetando libsisu-inject-java (0.3.4-2) ...
Seleccionando el paquete libsisu-plexus-java previamente no seleccionado.
Preparando para desempaquetar .../28-libsisu-plexus-java_0.3.4-3_all.deb ...
Desempaquetando libsisu-plexus-java (0.3.4-3) ...
Seleccionando el paquete libmaven3-core-java previamente no seleccionado.
Preparando para desempaquetar .../29-libmaven3-core-java_3.6.3-5_all.deb ...
Desempaquetando libmaven3-core-java (3.6.3-5) ...
Seleccionando el paquete libwagon-file-java previamente no seleccionado.
Preparando para desempaquetar .../30-libwagon-file-java_3.3.4-1_all.deb ...
Desempaquetando libwagon-file-java (3.3.4-1) ...
Seleccionando el paquete libwagon-http-shaded-java previamente no seleccionado.
Preparando para desempaquetar .../31-libwagon-http-shaded-java_3.3.4-1_all.deb .
..
Desempaquetando libwagon-http-shaded-java (3.3.4-1) ...
Seleccionando el paquete maven previamente no seleccionado.
Preparando para desempaquetar .../32-maven_3.6.3-5_all.deb ...
Desempaquetando maven (3.6.3-5) ...
Configurando libslf4j-java (1.7.32-1) ...
Configurando libplexus-utils2-java (3.3.0-1) ...
Configurando libplexus-classworlds-java (2.6.0-1) ...
Configurando libjsr305-java (0.1~+svn49-11) ...
Configurando libaopalliance-java (20070526-6) ...
Configurando libcommons-cli-java (1.4-2) ...
Configurando libplexus-component-annotations-java (2.1.0-1) ...
Configurando libplexus-cipher-java (1.8-2) ...
Configurando libgeronimo-annotation-1.3-spec-java (1.3-1) ...
Configurando libgeronimo-interceptor-3.0-spec-java (1.0.1-4fakesync) ...
Configurando libapache-pom-java (18-1) ...
Configurando libatinject-jsr330-api-java (1.0+ds1-5) ...
Configurando libplexus-interpolation-java (1.26-1) ...
Configurando libplexus-sec-dispatcher-java (1.4-4) ...
Configurando libwagon-http-shaded-java (3.3.4-1) ...
Configurando libcdi-api-java (1.2-3) ...
Configurando libhawtjni-runtime-java (1.17-1) ...
Configurando libwagon-provider-api-java (3.3.4-1) ...
Configurando libmaven-parent-java (31-2) ...
Configurando libcommons-parent-java (43-1) ...
Configurando libsisu-inject-java (0.3.4-2) ...
Configurando libsisu-plexus-java (0.3.4-3) ...
Configurando libmaven-resolver-java (1.4.2-3build1) ...
Configurando libguava-java (29.0-6) ...
Configurando libcommons-lang3-java (3.11-1) ...
Configurando libjansi-native-java (1.8-1) ...
Configurando libwagon-file-java (3.3.4-1) ...
Configurando libcommons-io-java (2.11.0-2) ...
Configurando libguice-java (4.2.3-2) ...
Configurando libjansi-java (1.18-1) ...
Configurando libmaven-shared-utils-java (3.3.0-1) ...
Configurando libmaven3-core-java (3.6.3-5) ...
Configurando maven (3.6.3-5) ...
update-alternatives: utilizando /usr/share/maven/bin/mvn para proveer /usr/bin/m
vn (mvn) en modo automático

```

 Para verificar la instalación, ejecute mvn -version:
```
 mvn -version
```
SALIDA EN MI CONSOLA: 

```
melissa@melissa-linux:~$ mvn -version
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.19, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: es_ES, platform encoding: UTF-8
OS name: "linux", version: "5.15.0-76-generic", arch: "amd64", family: "unix"

```


### Instalar una versión concreta de Apache Maven

Descargue Apache Maven en el directorio /tmp:

```
wget https://www.apache.org/dist/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz -P /tmp
```
SALIDA EN MI CONSOLA: 
```
melissa@melissa-linux:~$ wget https://www.apache.org/dist/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz -P /tmp
--2023-10-29 19:48:03--  https://www.apache.org/dist/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz
Resolviendo www.apache.org (www.apache.org)... 151.101.2.132
Conectando con www.apache.org (www.apache.org)[151.101.2.132]:443... conectado.
Petición HTTP enviada, esperando respuesta... 302 Found
Ubicación: https://downloads.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz [siguiente]
--2023-10-29 19:48:04--  https://downloads.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz

```
