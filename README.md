# Singularity definition files
Collection of def files for building some bioinformatics software I commonly use.

## inStrain v1.2.14
https://github.com/MrOlm/inStrain

Also contains these functioning binaries:
- [samtools v1.10](https://github.com/samtools/samtools)
- [prodigal v2.6.3](https://github.com/hyattpd/Prodigal)
- [bwa v0.7.17-r1198-dirty](https://github.com/lh3/bwa)
- [minimap2 v2.17 (r941)](https://github.com/lh3/minimap2)
- [Dashing v0.4.8-1-g47e6](https://github.com/dnbaker/dashing)
- [FastANI v1.3](https://github.com/ParBLiSS/FastANI)
- [CoverM v0.4.0](https://github.com/wwood/CoverM)

[Image at Sylabs](https://cloud.sylabs.io/library/slhogle/base/instrain)\

Download with:\
```singularity pull library://slhogle/base/instrain```

## Octopus development branch version v0.7.0 (develop 2bde0433)
https://github.com/luntergroup/octopus

Built with:
- patchelf v0.10
- openssl v1.1.1g
- pkg-config v0.29.2
- gpatch v2.7.6
- ncurses v6.2
- cmake v3.17.3
- htslib v1.10
- boost v1.72.0
- GNU C/C++ compiler v9.3.0

Target: x86_64 Linux 5.3.0-7642-generic\
SIMD extension: AVX2\

[Image at Sylabs](https://cloud.sylabs.io/library/slhogle/base/octopus)\

Download with:\
```singularity pull library://slhogle/base/octopus```

