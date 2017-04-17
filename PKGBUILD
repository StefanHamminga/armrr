# Maintainer: Stefan Hamminga <stefan@prjct.net>

pkgname=armrr-silent
provides=('armrr')
conflicts=('armrr')
pkgver=1.0
pkgrel=1
pkgdesc='Script that downloads a ranked mirrorlist from the Arch Linux Mirrorlist Generator.'
url='https://github.com/StefanHamminga/armrr'
arch=('any')
license=('GPL')
# depends=()
# optdepends=()

source=("armrr")
noextract=("armrr")

sha512sums=('51caa87daf070d03119cd0dc73b0d7a9cded721d423cf1e22d504e5f2bef1b7c604f82bc7c107c11e0fd22f601ad59cd0796bf47fd4cff7081da9cb114b5edfa')

package() {
	cd "${srcdir}"
	#install -d ${DESTDIR}/usr/bin
	#install -m 755 armrr ${DESTDIR}/usr/bin/armrr
	install -Dm 755 armrr ${pkgdir}/usr/bin/armrr
}
