pkgname=papirus-icon-theme
pkgver=20210201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('35d32790affb5829be657ce1a34d96f8')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
