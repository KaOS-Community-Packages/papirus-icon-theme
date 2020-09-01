pkgname=papirus-icon-theme
pkgver=20200901
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('4c29569c9bb14d627b441bb1785f39b1')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
