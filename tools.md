---
title: Unix Tools
permalink: tools/
seo:
  type: Collection
  name: Unix Tools
last_modified_at: 2025-10-25T08:08:36+00:00
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
- s/grep/**ripgrep**/g
  - [benchmarks](https://blog.burntsushi.net/ripgrep/)
- s/find/**fd**/g
  - [benchmarks](https://github.com/sharkdp/fd?tab=readme-ov-file#benchmark)
- s/find/**bfs**/
  - [benchmarks](https://tavianator.com/2023/bfs_3.0.html)
- s/sed/**sd**/
  - [benchmarks](https://github.com/chmln/sd#benchmarks)
- s/npm/**bun**/
  - [benchmarks](https://github.com/edbzn/package-manager-benchmarks)
- s/pip/**uv**/g
  - [benchmarks](https://github.com/astral-sh/uv/blob/main/BENCHMARKS.md)
- s/jekyll/**hugo**/
  - [the million pages release](https://github.com/gohugoio/hugo/releases/tag/v0.123.0)
- **qsv**
  - [performance tuning](https://github.com/dathere/qsv/blob/master/docs/PERFORMANCE.md)
- s/bc/**bc-gh**/
  - [benchmarks](https://git.gavinhoward.com/gavin/bc/src/branch/master/manuals/benchmarks.md)

&nbsp;  
- s/sudo/**sudo-rs**/g
- s/sudo -u/**s6-setuidgid**/g
  - [FGA](https://jdebp.uk/FGA/dont-abuse-su-for-dropping-privileges.html)
- s/md5sum/**b3sum**/g
- **mosh**+**tmux**
- **cwebp**+**zopflipng**
- s/xargs\|while read/**parallel**/
  - [differences with `xargs`](https://www.gnu.org/software/parallel/parallel_alternatives.html#differences-between-xargs-and-gnu-parallel)
- **sponge**
  - part of [moreutils](https://joeyh.name/code/moreutils/)
- s/cat/**bat** -p/g
  - its chief improvement is in adding syntax highlighting for the ['main use'](https://github.com/t18d/t18d.github.io/raw/main/assets/unix_prog_design.pdf) of `cat`, which is to print on the terminal without using a pager.
- s/cd/**zoxide**+**fzf**/g
  - [algorithm](https://github.com/ajeetdsouza/zoxide/wiki/Algorithm)
- s/vim.lua/**alabester.nvim**/g

&nbsp;  
- s/fortune-mod/**fortuna**/
  - [t18d/fortuna](https://github.com/t18d/fortuna)
