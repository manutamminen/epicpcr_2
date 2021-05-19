# epicPCR experiment December 18 2020 

This sequencing run was primarily about testing the effect of freezing on wastewater samples.

The following samples were included:

- Rhodomonas only
- Waste water (frozen, 100 µm filtered)
- Rhodomonas + waste water (frozen, 100 µm filtered)
- Waste water (not frozen, 100 µm filtered)
- Waste water (not frozen, 30 - 100 µm fraction)
- Waste water (not frozen, 10 - 100 µm fraction)

Raw data available at https://zenodo.org/record/4771697

Summary of the results available at 

# Building

## Dependencies

- Snakemake
- VSEARCH
- SINA
- FastTree
- Tidyverse

Download the raw data into data/raw.

Start the processing pipeline by invoking `snakemake --cores all report`.



