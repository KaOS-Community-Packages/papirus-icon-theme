pkgname=papirus-icon-theme
pkgver=20191201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('8dac0dd213c64de82b2ab99713562a50')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
