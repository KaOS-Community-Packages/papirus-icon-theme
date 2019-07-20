pkgname=papirus-icon-theme
pkgver=20190720
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('3f734d1ff9f7d34677dda25216b3d9dd')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
