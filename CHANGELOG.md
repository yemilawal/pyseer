# CHANGELOG
v1.3.0 (June 2019)
- Handle missing variants as missing (with new `--max-missing` option to control maximum allowed)
- Unit testing for enet functionality
- Added option to perform midpoint rooting on tree used by `phylogeny_distance.py`
- Updated docs with a new section about the use of unitigs
- Various bugfixes
   - Checks on phenotypes file
   - Improved BWA command and results handling
   - New optimizer for `fit_null`
   - Avoid deprecation warnings from pandas
   - Report to user if multiple chromosome/contigs are found while mapping
   - Use the correct samples order when using lineages and covariates

v1.2.0 (November 2018)
- Added elastic net functionality
- Avoid exiting with error in python 3.7+
- Allow spaces in Rtab's COG names
- Make unit tests compatible with python 2

v1.1.2 (October 2018)
- Bugfix for sample names interpreted as integers
- Bugfix for user-defined lineages
- Small fixes in docs and README

v1.1.1 (June 2018)
- Further bugfixes for the annotation of kmers
- Platform specific pandas bugfix with LMM
- Test kmers annotation
- Improved README

v1.1.0 (May 2018)
- New option (--no-distances) to run fixed effects associations without a distance matrix
- New option (--print-filtered) allowing to print variants not passing filters
- Check for consistency between lmm and lineage samples
- Add lineage to phandango mapping output
- annotate_hits_pyseer: properly parse GFF3 entries
- annotate_hits_pyseer: map all possible kemrs for reference genomes
- Update docs
- Tests are less dependent on machine precision

v1.0.2 (Mar 2018)
- Better dependencies definition

v1.0.1 (Mar 2018)
- Check for missing values in VCF entries

v1.0.0 (Feb 2018)
- First release
