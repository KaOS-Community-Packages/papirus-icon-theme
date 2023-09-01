pkgname=papirus-icon-theme
pkgver=20230901
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('e7a0b5abe256435842dbe426f26b6a5b')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
