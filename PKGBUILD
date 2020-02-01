pkgname=papirus-icon-theme
pkgver=20200201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('b5efbcd69d67a2261eea2ac61eecab07')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
