pkgname=papirus-icon-theme
pkgver=20180601
pkgrel=1
pkgdesc="Papirus icon theme"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/papirus-icon-theme"
license=("LGPL3")
depends=('gtk-update-icon-cache')
source=("$pkgname-$pkgver.tar.gz::https://github.com/PapirusDevelopmentTeam/$pkgname/archive/$pkgver.tar.gz")
sha512sums=('171b03f4cb59aa2edf5313105a921709ec99ae4a9a669a5490ddae593c768cfa08add55a232c07dd17a0563aa0f278edbb1e588de66c0cb5937c479a28304e64')

package() {
  cd $pkgname-$pkgver
  make DESTDIR="$pkgdir" install
}
