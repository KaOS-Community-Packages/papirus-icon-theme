pkgname=papirus-icon-theme
pkgver=20211201
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('116f2c89ebe5fa4930033724122b04c9')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
