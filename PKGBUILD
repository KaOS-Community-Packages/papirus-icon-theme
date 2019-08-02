pkgname=papirus-icon-theme
pkgver=20190802
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('d84efbf2abd4c36614555275aa1d7ff3')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
