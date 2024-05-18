# Maintainer: Jiri Pospisil <jiri@jpospisil.com>
#
pkgname=drtl-bin
pkgver=0.0.20
pkgrel=1
pkgdesc='Yet another tldr client written in Zig.'
url='https://github.com/jiripospisil/drtl'
source_x86_64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-x86_64-linux")
source_aarch64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-aarch64-linux")
arch=('x86_64' 'aarch64')
provides=('drtl')
conflicts=('drtl')
license=('MIT')
b2sums_x86_64=('25efc92d1e6b2f1d6fe410206268bf1436d6a9571d0d255ce6fb73423a67334d55767fb360683277647e0304e9807afc8fbf339477f699a86a41112c5b517a69')
b2sums_aarch64=('c14b264ac916622fd586a61f4d67466862abe74042f91c678661cbf5575d704157240c4fe3861aec3254ffdb7b38c86ac63d157d5f6a68194b2bdff38695da32')

package() {
  install -Dm755 "$srcdir/drtl-v$pkgver-$CARCH-linux" "$pkgdir/usr/bin/drtl"
}
