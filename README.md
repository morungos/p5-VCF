### VCF.pm

A repackaged version of the core Vcf.pm from vcftools (see: https://github.com/vcftools/vcftools).

I've done this as vcftools is distributed from Sourceforge and doesn't have a
CPAN version, so it can't be a dependency for other CPAN-based components. This makes deployment very much more awkward.

### Changes

#### Version 1.0 - 7th March 2016

 * Refactored into multiple files for easier maintenance.
 * Modified package capitalization to `VCF` for Perlishness and to avoid confusion. 
 * Original code pulled from Github: https://github.com/vcftools/vcftools

### Authors

 * Originally: Petr Danecek <petr.danecek@sanger>
 * Amendments: Stuart Watt <stuart@morungos.com>
