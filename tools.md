---
title: Unix Tools
permalink: tools/
seo:
  type: Collection
last_modified_at: 2024-09-15T13:04:17+00:00
---
# Open Source by Tonkünstler-on-the-Bund

## Unix Tools

&nbsp;  
Current sources on this subject are either [outdated](https://www.cs.toronto.edu/~maclean/csc209/unixtools.html) or [indiscriminate](https://github.com/ibraheemdev/modern-unix). In some places, obsolete knowledge is being [purveyed to students](https://www.cl.cam.ac.uk/teaching/2122/UnixTools/unixtools-slides.pdf). This page presents a selection of modern tools as used at TKB.

&nbsp;  
- s/grep/**ripgrep**/
  - [benchmarks](https://blog.burntsushi.net/ripgrep/)
- s/find/**fd**/
  - [benchmarks](https://github.com/sharkdp/fd?tab=readme-ov-file#benchmark)
- s/sed/**sd**/
  - [benchmarks](https://github.com/chmln/sd#benchmarks)
- s/awk/**frawk**/
  - [benchmarks](https://github.com/ezrosent/frawk/blob/master/info/performance.md)
- **xsv**
  - [benchmarks](https://github.com/BurntSushi/xsv/blob/master/BENCHMARKS.md)

&nbsp;  
- s/sudo/**sudo-rs**/
- s/md5sum/**b3sum**/
- **mosh**+**tmux**
- **sponge**
  - part of [moreutils](https://joeyh.name/code/moreutils/)
- s/cat/**bat** -p/
  - its chief improvement is in adding syntax highlighting for the ['main use'](https://github.com/t18d/t18d.github.io/raw/main/assets/unix_prog_design.pdf) of `cat`, which is to print on the terminal without using a pager.
- s/cd/**zoxide**+**fzf**/
  - [algorithm](https://github.com/ajeetdsouza/zoxide/wiki/Algorithm)

&nbsp;  
- s/fortune-mod/**fortuna**/
  - [t18d/fortuna](https://github.com/t18d/fortuna)
