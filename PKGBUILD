pkgname=papirus-icon-theme
pkgver=20221201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('e28d7d5d47ab2e100be6a2ed96549685')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
