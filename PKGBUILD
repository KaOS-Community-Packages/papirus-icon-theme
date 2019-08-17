pkgname=papirus-icon-theme
pkgver=20190817
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('4b5b3b57805c4e9f572c6bda96daeda3')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
