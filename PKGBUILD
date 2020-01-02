pkgname=papirus-icon-theme
pkgver=20200102
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('971d0faa3361855c55125f8c69f77691')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
