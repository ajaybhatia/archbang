ArchBang source files:

Basically run

  sudo ./build -v

Ok it is not as simple as that, applications from aur (see aur_packages) will need to be built and setup in a local repo. The make-aur-packages script can help you do that, as it is set up for my system changes may need to be made for it too work correctly. Once 
done then iso should build without an issue.

Quick breakdown:

All the files in directory airootfs are an overlay of configs for ArchBang, it also includes scripts for getting system up and running live and our installer.

Build script is based on archlinuxs archiso scripts, modified too allow either a i686 or x86_64 (not dual iso). Archiso is the work of archlinux(tm).

Any questions please feel free to ask either either or at our forums via www.archbang.org

