pkgname=papirus-icon-theme
pkgver=20210501
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('a03ca3a7d37267b5043b4d4cd45b5111')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
