pkgname=papirus-icon-theme
pkgver=20210401
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('19606bb8b3fe98e133d8e7cf28c78155')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
