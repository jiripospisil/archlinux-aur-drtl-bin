# Maintainer: Jiri Pospisil <jiri@jpospisil.com>
#
pkgname=drtl-bin
pkgver=0.0.18
pkgrel=1
pkgdesc='Yet another tldr client written in Zig.'
url='https://github.com/jiripospisil/drtl'
source_x86_64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-x86_64-linux")
source_aarch64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-aarch64-linux")
arch=('x86_64' 'aarch64')
provides=('drtl')
conflicts=('drtl')
license=('MIT')
b2sums_x86_64=('4a913e00d34c4a31a52d5bb6454b38ea285137d0e63d166f57b7fe2b138335522ae61e0c9e43fed4146fcc6ce0b3280d66a51c108e546ed8848bb55674fef616')
b2sums_aarch64=('68127502062cc79125d4a77139b766e45e73731fbf0cf0fa83eef2390a52ba2a331e8dd8e39d50dff0294f889cb976f885d02d971ba6712c083bfef1a5b31b90')

package() {
  install -Dm755 "$srcdir/drtl-v$pkgver-$CARCH-linux" "$pkgdir/usr/bin/drtl"
}
