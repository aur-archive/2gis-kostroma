# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-kostroma
pkgver=28
pkgrel=1
pkgdesc="Map of Kostroma for 2GIS, February 2013"
arch=('i686' 'x86_64')
url="http://kostroma.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Kostroma-28.orig.zip")
md5sums=('571eea40c4fbebef128def882702c0b5')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Kostroma.dgdat "${startdir}/pkg/opt/2gis/kostroma.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Kostroma.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Kostroma.dglf" || return 1
     
}

