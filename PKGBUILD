# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-kostroma
pkgver=29
pkgrel=1
pkgdesc="Map of Kostroma for 2GIS, March 2013"
arch=('i686' 'x86_64')
url="http://kostroma.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.2.2')
source=("http://download.2gis.ru/arhives/2GISData_Kostroma-29.orig.zip")
md5sums=('29a5aa8234a931d279e45dd9c577bcd4')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Kostroma.dgdat "${startdir}/pkg/opt/2gis/kostroma.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Kostroma.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Kostroma.dglf" || return 1
     
}

