pkgname=papirus-icon-theme
pkgver=20200430
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
md5sums=('82298e348701e1478b60c2c9253dc32a')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
