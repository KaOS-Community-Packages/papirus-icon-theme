pkgname=papirus-icon-theme
pkgver=20191101
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('aff32de8ba79cece700d863b0cb74cd1')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
