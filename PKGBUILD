pkgname=papirus-icon-theme
pkgver=20191009
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('05bf0a2e6144b0f8dff5d718e4636471')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
