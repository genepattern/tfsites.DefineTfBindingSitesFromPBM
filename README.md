# tfsites.NormalizeTfDNAAffinityData

Normalizes the median fluorescence intensity (MFI) values in a raw protein-binding microarray (PBM) data file for a transcription factor of interest. The k-mer with the maximum MFI that conforms to the IUPAC definition of a binding site is normalized to 1.0 and all other k-mers are normalized relative to that MFI value. For example, a normalized value of 0.1 is 10% of the maximum MFI.

Created in collaboration with the Emma Farley lab (UCSD).

See documentation at [https://genepattern.github.io/tfsites.DefineTfSites/v1/](https://genepattern.github.io/tfsites.DefineTfBindingSitesFromPBM/)
