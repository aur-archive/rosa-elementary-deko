pkgname=rosa-elementary-deko
_pkgname=kde4-windeco-dekorator
pkgver=0.5.1
_pkgver=0.5.1-10
pkgrel=2
pkgdesc="Window decorations as seen in Rosa Desktop 2012"
arch=('i686' 'x86_64')
url='http://www.rosalab.ru/'
license=('GPL')
depends=('dekorator')
provides=('rosa-elementary-deko')
source=("http://mirror.yandex.ru/rosa/rosa2012lts/repository/x86_64/main/release/${_pkgname}-${_pkgver}-rosa.lts2012.0.x86_64.rpm")
sha1sums=('ad7b3837a0abcb29d98c3c9184c47e0d700ee8ab')

package() {
	cd ..
	mkdir -p ${pkgdir}/usr/share/apps/deKorator/themes/Elementary
	cp -R ${srcdir}/usr/share/apps/deKorator/themes/Elementary ${pkgdir}/usr/share/apps/deKorator/themes/
}