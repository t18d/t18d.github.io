---
title: Unix Tools
permalink: tools/
seo:
  type: Collection
  name: Unix Tools
last_modified_at: 2025-10-02T11:19:57+00:00
description: A selection of modern tools as used at TKB
---
# Open Source by Tonkünstler-on-the-Bund

## Unix Tools

&nbsp;  
Current sources on this subject are either 
[outdated](https://www.cs.toronto.edu/~maclean/csc209/unixtools.html) or 
[indiscriminate](https://github.com/ibraheemdev/modern-unix). In some places, 
obsolete knowledge is being [purveyed to 
students](https://www.cl.cam.ac.uk/teaching/2122/UnixTools/unixtools-slides.pdf).
This page presents a selection of modern tools as used at TKB.

&nbsp;  
- s/grep/**ripgrep**/
  - [benchmarks](https://blog.burntsushi.net/ripgrep/)
- s/find/**fd**/
  - [benchmarks](https://github.com/sharkdp/fd?tab=readme-ov-file#benchmark)
- s/find/**bfs**/
  - [benchmarks](https://tavianator.com/2023/bfs_3.0.html)
- s/sed/**sd**/
  - [benchmarks](https://github.com/chmln/sd#benchmarks)
- s/npm/**bun**/
  - [benchmarks](https://github.com/edbzn/package-manager-benchmarks)
- s/pip/**uv**/
  - [benchmarks](https://github.com/astral-sh/uv/blob/main/BENCHMARKS.md)
- **qsv**
  - [performance
    tuning](https://github.com/dathere/qsv/blob/master/docs/PERFORMANCE.md)
- s/bc/**bc-gh**/
  - [benchmarks](https://git.gavinhoward.com/gavin/bc/src/branch/master/manuals/benchmarks.md)

&nbsp;  
- s/sudo/**sudo-rs**/
- s/sudo -u/**s6-setuidgid**/
  - [FGA](https://jdebp.uk/FGA/dont-abuse-su-for-dropping-privileges.html)
- s/md5sum/**b3sum**/
- **mosh**+**tmux**
- **cwebp**+**zopflipng**
- s/xargs\|while read/**parallel**/
  - [differences with
    `xargs`](https://www.gnu.org/software/parallel/parallel_alternatives.html#differences-between-xargs-and-gnu-parallel)
- **sponge**
  - part of [moreutils](https://joeyh.name/code/moreutils/)
- s/cat/**bat** -p/
  - its chief improvement is in adding syntax highlighting for the ['main
    use'](https://github.com/t18d/t18d.github.io/raw/main/assets/unix_prog_design.pdf) of `cat`, which is to print on the terminal without using a pager.
- s/cd/**zoxide**+**fzf**/
  - [algorithm](https://github.com/ajeetdsouza/zoxide/wiki/Algorithm)

&nbsp;  
- s/fortune-mod/**fortuna**/
  - [t18d/fortuna](https://github.com/t18d/fortuna)
