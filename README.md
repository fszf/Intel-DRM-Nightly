### Linux Intel DRM Nightly Branch

For my Dell XPS 13 9350, I feel as though Intel is bringing quite a few patches for stability/performance/powersaving.  
Instead of waiting for them to be merged to Mainline, why not just use the Intel DRM branch?

I've added the NVME power saving patches to this.

This branch is highly recommended for those using docks and other peripherals that aren't working too well on mainline.

### Recommended Install
git clone https://github.com/frank604/Intel-DRM-Nightly

makepkg -s

sudo pacman -U linux...pkg.tar.xz linux...-headers...pkg.tar.xz

Note: Please use proper package names for above.
