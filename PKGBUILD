pkgname=papirus-icon-theme
pkgver=20190521
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('f1729af8821c6fd1c592275ae1cddd67')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
