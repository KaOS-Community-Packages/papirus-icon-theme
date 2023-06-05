pkgname=papirus-icon-theme
pkgver=20230601
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('1bb8fffc5775b3b6035adcec77d34d26')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
