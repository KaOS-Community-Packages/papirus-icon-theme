pkgname=papirus-icon-theme
pkgver=20211101
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('0affc004e1207c395577aabb2b8d6be1')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
