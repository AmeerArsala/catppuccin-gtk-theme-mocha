# Maintainer: spookyintheam <spookyintheam@protonmail.com>

pkgname=catppuccin-gtk-theme-mocha
pkgver=0.7.3
pkgrel=1
pkgdesc='Soothing pastel theme for GTK3 - Mocha'
arch=('any')
license=('GPL3')
url='https://github.com/catppuccin/gtk'
source=("$pkgname-$pkgver-blue.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Blue-Dark.zip"
        "$pkgname-$pkgver-flamingo.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Flamingo-Dark.zip"
        "$pkgname-$pkgver-green.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Green-Dark.zip"
        "$pkgname-$pkgver-lavender.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Lavender-Dark.zip"
        "$pkgname-$pkgver-maroon.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Maroon-Dark.zip"
        "$pkgname-$pkgver-mauve.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Mauve-Dark.zip"
        "$pkgname-$pkgver-peach.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Peach-Dark.zip"
        "$pkgname-$pkgver-pink.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Pink-Dark.zip"
        "$pkgname-$pkgver-red.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Red-Dark.zip"
        "$pkgname-$pkgver-rosewater.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Rosewater-Dark.zip"
        "$pkgname-$pkgver-sapphire.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Sapphire-Dark.zip"
        "$pkgname-$pkgver-sky.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Sky-Dark.zip"
        "$pkgname-$pkgver-teal.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Teal-Dark.zip"
        "$pkgname-$pkgver-yellow.zip::$url/releases/download/v$pkgver/Catppuccin-Mocha-Standard-Yellow-Dark.zip")
sha256sums=('1fd1b42282db2bbfdc0a6316217c348ee47fc3d4b5cfff71fdb235ae05493b92'
            'a3bcfb63ff419e104fafe0f65458450ccd9eae77a1a372c2b216db160f7c7df8'
            '7d5dd42b15fb5338a9d500b2f9ed1a85e3a4c8786a73c441faf4de3e9eb88c67'
            'edff5a4be48886234712d4de80a449ded70979c322b1cf417c23127bd32c59fd'
            'ec7b80d9ccb844efd72ee0af62351f2a93d82845a2cc05a7e789bf10aa77aaea'
            '9de9c7bbe89e16027473c32a82733a6d7f50c3b6db412f94c337556d44bca3b7'
            'cb36825cb6a93ff7f6121b58b7c2e65bb4b6567aa8f1bb32e2241d8a6ee59515'
            '9310baa5aaf4d5b4a13517c7c57092907a9d2d8a842d82f5c161c74b7d014975'
            'cd9674f4e73c0fd1d5a50a044db8643644d21ca8224ccf383684620c625a7721'
            'bb992f59678c760390c45a95a8d74c40a266b03603b6b017c98a925b5e9444d3'
            'fa3b111886ecee1a7832f09e1555010ff3b10071e923a6c438dcc765df27f756'
            'b31a61131306ff2165e8d63683e17deb77f011e8fdf80acdae9f40ff83aad5f7'
            '3bc2cea4fb8094db356b8ce8a1098aff88ef4404331b40c3578962e3f3871369'
            '24cd2963517add8a6e17fc07626fac6af309d5a13f280f44c11b9a9ff268495b')

package() {
	install -d "$pkgdir/usr/share/themes/"
	cp -r -a --no-preserve=ownership \
    Catppuccin-Mocha-* "$pkgdir/usr/share/themes"
}
