pkgname=2gis-kostroma
pkgver=47
pkgrel=1
pkgdesc="Map of Kostroma for 2GIS, September 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/kostroma/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Kostroma-47.orig.zip")
md5sums=('97c1482effd087e922c402c017225008')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Kostroma.dgdat" "${pkgdir}/opt/2gis/2gis-kostroma.dgdat" || return 1
  
}
