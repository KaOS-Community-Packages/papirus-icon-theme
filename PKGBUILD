pkgname=papirus-icon-theme
pkgver=20230104
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('ee1d8e5c8b9829322f3185f2f176f791')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
