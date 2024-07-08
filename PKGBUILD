# Maintainer: Jiri Pospisil <jiri@jpospisil.com>
#
pkgname=drtl-bin
pkgver=0.0.21
pkgrel=1
pkgdesc='Yet another tldr client written in Zig.'
url='https://github.com/jiripospisil/drtl'
source_x86_64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-x86_64-linux")
source_aarch64=("https://github.com/jiripospisil/drtl/releases/download/v$pkgver/drtl-v$pkgver-aarch64-linux")
arch=('x86_64' 'aarch64')
provides=('drtl')
conflicts=('drtl')
license=('MIT')
b2sums_x86_64=('65ceab54283d621f057b651034583b0aabc93b25415da8a00e6db885ca001fef77aaf964daac713b28bf51e907df138f139a204debf5da453cb211241eff2b10')
b2sums_aarch64=('f000fc8b6d6648e2d620f3b12eb23e746e1017fa3fbb1a379eabf2d3f7bf20c54e3d1e235697b2eeb3f26cfbad7d00aa78901e154541a5d7680367036bc323f3')

package() {
  install -Dm755 "$srcdir/drtl-v$pkgver-$CARCH-linux" "$pkgdir/usr/bin/drtl"
}
