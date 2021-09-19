# dgkiss

My personal [GKISS](https://github.com/gkisslinux/grepo) repository.

Packages here assume you're running Wayland (as is standard now for most people using KISS linux and derivatives),
and GKISS means I assume you're runing glibc. If packages here do not work with musl libc or X11, they will be
considered working as intended.

Some highlights:

- [entr](https://eradman.com/entrproject/)
- [chrony](https://chrony.tuxfamily.org/)
- [openjdk11-hotspot-bin](https://adoptium.net/?variant=openjdk11&jvmVariant=hotspot)
- [openjdk16-hotspot-bin](https://adoptium.net/?variant=openjdk16&jvmVariant=hotspot)
- [glfw](https://www.glfw.org/) (+ Minecraft [patches](https://github.com/Admicos/minecraft-wayland))
- [mesa](https://gitlab.freedesktop.org/mesa/mesa) + [libglvnd](https://github.com/NVIDIA/libglvnd) (depends on packages from [kiss-xorg](https://github.com/ehawkvu/kiss-xorg))
- [MultiMC](https://multimc.org/)
- [libslirp](https://gitlab.freedesktop.org/slirp/libslirp)
- [libepoxy](https://github.com/anholt/libepoxy)

Things I need to get around to fixing, or are in an unknown state:

- [melonDS](http://melonds.kuribo64.net/) (build errors)
- [fftw](https://www.fftw.org/)
