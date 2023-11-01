pkgname=papirus-icon-theme
pkgver=20231101
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('2c42e8eb7477055ed09e6a700baa4a6f')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
