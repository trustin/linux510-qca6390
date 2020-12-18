# Maintainer: Philip Müller <philm[at]manjaro[dot]org>
# Maintainer: Bernhard Landauer <bernhard[at]manjaro[dot]org>
# Maintainer: Helmut Stult <helmut[at]manjaro[dot]org>

# Arch credits:
# Tobias Powalowski <tpowa@archlinux.org>
# Thomas Baechler <thomas@archlinux.org>

# Cloud Server
_server=ccx51

pkgbase=linux510
pkgname=('linux510' 'linux510-headers')
_kernelname=-MANJARO
_basekernel=5.10
_basever=510
pkgver=5.10.1
pkgrel=5
arch=('x86_64')
url="http://www.kernel.org/"
license=('GPL2')
makedepends=('bc'
    'docbook-xsl'
    'elfutils'
    'git'
    'inetutils'
    'kmod'
    'xmlto'
    'cpio'
    'perl'
    'tar'
    'xz')
options=('!strip')
source=("https://www.kernel.org/pub/linux/kernel/v5.x/linux-${_basekernel}.tar.xz"
        "https://www.kernel.org/pub/linux/kernel/v5.x/patch-${pkgver}.xz"
        # the main kernel config files
        'config' 'config.anbox'
        # ARCH Patches
        '0001-ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-CLONE_NEWUSER.patch'
        '0002-Bluetooth-Fix-LL-PRivacy-BLE-device-fails-to-connect.patch'
        '0003-Bluetooth-Fix-attempting-to-set-RPA-timeout-when-unsupported.patch'
        # MANJARO Patches
        '0101-i2c-nuvoton-nc677x-hwmon-driver.patch'
        '0102-iomap-iomap_bmap-should-accept-unwritten-maps.patch'
        '0103-futex.patch'
        '0104-revert-xhci-Add-support-for-Renesas-controller-with-memory.patch'
        '0106-ucsi-acpi.patch'
        '0106-ucsi.patch'
        # Lenovo + AMD
        '0302-lenovo-wmi2.patch'
        # Bootsplash
        '0401-revert-fbcon-remove-now-unusued-softback_lines-cursor-argument.patch'        
        '0402-revert-fbcon-remove-no-op-fbcon_set_origin.patch'
        '0403-revert-fbcon-remove-soft-scrollback-code.patch'
        '0501-bootsplash.patch'
        '0502-bootsplash.patch'
        '0503-bootsplash.patch'
        '0504-bootsplash.patch'
        '0505-bootsplash.patch'
        '0506-bootsplash.patch'
        '0507-bootsplash.patch'
        '0508-bootsplash.patch'
        '0509-bootsplash.patch'
        '0510-bootsplash.patch'
        '0511-bootsplash.patch'
        '0512-bootsplash.patch'
        '0513-bootsplash.gitpatch'
        # Temp Fixes
        )
sha256sums=('dcdf99e43e98330d925016985bfbc7b83c66d367b714b2de0cbbfcbf83d8ca43'
            '1b5ca3683e8ae99eee357d11a2f2bfe21561883d6288e29d7bddf3eb0e007fcd'
            '55f52c78603e0577a08a97e6fb3a3be8f2348fd9de6ce992da343ba392d44bae'
            'fc896e5b00fad732d937bfb7b0db41922ecdb3a488bc1c1b91b201e028eed866'
            '986f8d802f37b72a54256f0ab84da83cb229388d58c0b6750f7c770818a18421'
            '3c1c63194dc808b63166646d71c9fc2e690605178527bdd5528084613990207a'
            'e216346f7c7761a53b76dea0638898e52aac9e4527a64893c9dfa9936b3c5a0d'
            '7823d7488f42bc4ed7dfae6d1014dbde679d8b862c9a3697a39ba0dae5918978'
            '95745075edd597caa92b369cfbcd11a04c9e3c88c0c987c70114924e1e01df5c'
            'b302ba6c5bbe8ed19b20207505d513208fae1e678cf4d8e7ac0b154e5fe3f456'
            '83b5684223309809393bdffc5122924cb9940403d682a887b0aa6524015df973'
            'e9ca3a8398360fa5d8d0deb5f0c0ca3d174865bd13c91eb6e0232cdbcdb2258b'
            '6446e388c0e13290fd99137539c6d3089994313a3a0c00305dea83faf4951137'
            '1d58ef2991c625f6f0eb33b4cb8303932f53f1c4694e42bae24c9cd36d2ad013'
            '2b11905b63b05b25807dd64757c779da74dd4c37e36d3f7a46485b1ee5a9d326'
            '94a8538251ad148f1025cc3de446ce64f73dc32b01815426fb159c722e8fa5bc'
            '37a221c12b40122167b0a30b5a9f2fc99e2aeb94e4db58a719c2b30171c5aeb5'
            '59202940d4f12bad23c194a530edc900e066866c9945e39748484a6545af96de'
            'e096b127a5208f56d368d2cb938933454d7200d70c86b763aa22c38e0ddb8717'
            '8c1c880f2caa9c7ae43281a35410203887ea8eae750fe8d360d0c8bf80fcc6e0'
            '1144d51e5eb980fceeec16004f3645ed04a60fac9e0c7cf88a15c5c1e7a4b89e'
            'dd4b69def2efacf4a6c442202ad5cb93d492c03886d7c61de87696e5a83e2846'
            '028b07f0c954f70ca37237b62e04103e81f7c658bb8bd65d7d3c2ace301297dc'
            'c8b0cb231659d33c3cfaed4b1f8d7c8305ab170bdd4c77fce85270d7b6a68000'
            '8dbb5ab3cb99e48d97d4e2f2e3df5d0de66f3721b4f7fd94a708089f53245c77'
            'a7aefeacf22c600fafd9e040a985a913643095db7272c296b77a0a651c6a140a'
            'e9f22cbb542591087d2d66dc6dc912b1434330ba3cd13d2df741d869a2c31e89'
            '27471eee564ca3149dd271b0817719b5565a9594dc4d884fe3dc51a5f03832bc'
            '60e295601e4fb33d9bf65f198c54c7eb07c0d1e91e2ad1e0dd6cd6e142cb266d'
            '035ea4b2a7621054f4560471f45336b981538a40172d8f17285910d4e0e0b3ef')

prepare() {
  cd "${srcdir}/linux-${_basekernel}"

  # add upstream patch
  msg "add upstream patch"
  patch -p1 -i "${srcdir}/patch-${pkgver}"

  local src
  for src in "${source[@]}"; do
      src="${src%%::*}"
      src="${src##*/}"
      [[ $src = *.patch ]] || continue
      msg2 "Applying patch: $src..."
      patch -Np1 < "../$src"
  done

  msg2 "0513-bootsplash"
  git apply -p1 < "${srcdir}/0513-bootsplash.gitpatch"  

  msg2 "add config.anbox to config"
  cat "${srcdir}/config" > ./.config
  cat "${srcdir}/config.anbox" >> ./.config

  if [ "${_kernelname}" != "" ]; then
    sed -i "s|CONFIG_LOCALVERSION=.*|CONFIG_LOCALVERSION=\"${_kernelname}\"|g" ./.config
    sed -i "s|CONFIG_LOCALVERSION_AUTO=.*|CONFIG_LOCALVERSION_AUTO=n|" ./.config
  fi

  msg "set extraversion to pkgrel"
  sed -ri "s|^(EXTRAVERSION =).*|\1 -${pkgrel}|" Makefile

  msg "don't run depmod on 'make install'"
  # We'll do this ourselves in packaging
  sed -i '2iexit 0' scripts/depmod.sh

  msg "get kernel version"
  make prepare

  # load configuration
  # Configure the kernel. Replace the line below with one of your choice.
  #make menuconfig # CLI menu for configuration
  #make nconfig # new CLI menu for configuration
  #make xconfig # X-based configuration
  #make oldconfig # using old config from previous kernel version
  # ... or manually edit .config

  msg "rewrite configuration"
  yes "" | make config >/dev/null
}

build() {
  cd "${srcdir}/linux-${_basekernel}"

  msg "build"
  make ${MAKEFLAGS} LOCALVERSION= bzImage modules
}

package_linux510() {
  pkgdesc="The ${pkgbase/linux/Linux} kernel and modules"
  depends=('coreutils' 'linux-firmware' 'kmod' 'mkinitcpio>=27')
  optdepends=('crda: to set the correct wireless channels of your country')
  provides=("linux=${pkgver}" VIRTUALBOX-GUEST-MODULES WIREGUARD-MODULE)

  cd "${srcdir}/linux-${_basekernel}"

  KARCH=x86

  # get kernel version
  _kernver="$(make LOCALVERSION= kernelrelease)"

  mkdir -p "${pkgdir}"/{boot,usr/lib/modules}
  make LOCALVERSION= INSTALL_MOD_PATH="${pkgdir}/usr" INSTALL_MOD_STRIP=1 modules_install

  # systemd expects to find the kernel here to allow hibernation
  # https://github.com/systemd/systemd/commit/edda44605f06a41fb86b7ab8128dcf99161d2344
  cp arch/$KARCH/boot/bzImage "${pkgdir}/usr/lib/modules/${_kernver}/vmlinuz"

  # Used by mkinitcpio to name the kernel
  echo "${pkgbase}" | install -Dm644 /dev/stdin "${pkgdir}/usr/lib/modules/${_kernver}/pkgbase"
  echo "${_basekernel}-${CARCH}" | install -Dm644 /dev/stdin "${pkgdir}/usr/lib/modules/${_kernver}/kernelbase"

  # add kernel version
  echo "${pkgver}-${pkgrel}-MANJARO x64" > "${pkgdir}/boot/${pkgbase}-${CARCH}.kver"

  # make room for external modules
  local _extramodules="extramodules-${_basekernel}${_kernelname:--MANJARO}"
  ln -s "../${_extramodules}" "${pkgdir}/usr/lib/modules/${_kernver}/extramodules"

  # add real version for building modules and running depmod from hook
  echo "${_kernver}" |
    install -Dm644 /dev/stdin "${pkgdir}/usr/lib/modules/${_extramodules}/version"

  # remove build and source links
  rm "${pkgdir}"/usr/lib/modules/${_kernver}/{source,build}

  # now we call depmod...
  depmod -b "${pkgdir}/usr" -F System.map "${_kernver}"

  # add vmlinux
  install -Dt "${pkgdir}/usr/lib/modules/${_kernver}/build" -m644 vmlinux
}

package_linux510-headers() {
  pkgdesc="Header files and scripts for building modules for ${pkgbase/linux/Linux} kernel"
  depends=('gawk' 'python' 'libelf')
  provides=("linux-headers=$pkgver")

  cd "${srcdir}/linux-${_basekernel}"
  local _builddir="${pkgdir}/usr/lib/modules/${_kernver}/build"

  install -Dt "${_builddir}" -m644 Makefile .config Module.symvers
  install -Dt "${_builddir}/kernel" -m644 kernel/Makefile

  mkdir "${_builddir}/.tmp_versions"

  cp -t "${_builddir}" -a include scripts

  install -Dt "${_builddir}/arch/${KARCH}" -m644 "arch/${KARCH}/Makefile"
  install -Dt "${_builddir}/arch/${KARCH}/kernel" -m644 "arch/${KARCH}/kernel/asm-offsets.s"
  #install -Dt "${_builddir}/arch/${KARCH}/kernel" -m644 "arch/${KARCH}/kernel/macros.s"

  cp -t "${_builddir}/arch/${KARCH}" -a "arch/${KARCH}/include"

  install -Dt "${_builddir}/drivers/md" -m644 drivers/md/*.h
  install -Dt "${_builddir}/net/mac80211" -m644 net/mac80211/*.h

  # http://bugs.archlinux.org/task/13146
  install -Dt "${_builddir}/drivers/media/i2c" -m644 drivers/media/i2c/msp3400-driver.h

  # http://bugs.archlinux.org/task/20402
  install -Dt "${_builddir}/drivers/media/usb/dvb-usb" -m644 drivers/media/usb/dvb-usb/*.h
  install -Dt "${_builddir}/drivers/media/dvb-frontends" -m644 drivers/media/dvb-frontends/*.h
  install -Dt "${_builddir}/drivers/media/tuners" -m644 drivers/media/tuners/*.h

  # add xfs and shmem for aufs building
  mkdir -p "${_builddir}"/{fs/xfs,mm}

  # copy in Kconfig files
  find . -name Kconfig\* -exec install -Dm644 {} "${_builddir}/{}" \;

  # add objtool for external module building and enabled VALIDATION_STACK option
  install -Dt "${_builddir}/tools/objtool" tools/objtool/objtool

  # remove unneeded architectures
  local _arch
  for _arch in "${_builddir}"/arch/*/; do
    [[ ${_arch} == */x86/ ]] && continue
    rm -r "${_arch}"
  done

  # remove files already in linux-docs package
  rm -r "${_builddir}/Documentation"

  # Fix permissions
  chmod -R u=rwX,go=rX "${_builddir}"

  # strip scripts directory
  local _binary _strip
  while read -rd '' _binary; do
    case "$(file -bi "${_binary}")" in
      *application/x-sharedlib*)  _strip="${STRIP_SHARED}"   ;; # Libraries (.so)
      *application/x-archive*)    _strip="${STRIP_STATIC}"   ;; # Libraries (.a)
      *application/x-executable*) _strip="${STRIP_BINARIES}" ;; # Binaries
      *) continue ;;
    esac
    /usr/bin/strip ${_strip} "${_binary}"
  done < <(find "${_builddir}/scripts" -type f -perm -u+w -print0 2>/dev/null)
}
