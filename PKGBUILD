pkgname=papirus-icon-theme
pkgver=20211001
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('38744aa67a1f365cdf654c966fe78fe3')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
