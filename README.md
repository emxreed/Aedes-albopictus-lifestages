# Aedes-albopictus-lifestages
Associated data for "Life-history stage and the population genetics of the tiger mosquito Aedes albopictus at a fine spatial scale" by EMX Reed, MH Reiskind, MO Burford Reiskind (submitted to Medical and Veterinary Entomology). We have included the raw plink file using the STACKS de novo pipeline and population pipeline parameters highlighted in the manuscript. We have also included the RAW post-process radtag data files and a population map.

Project Files

REED_PostPopulationsPipeline: Contains data for all sequenced individuals after running the STACKS v1.09 Populations pipeline (r = 0.75, p = 2)

1. REED_PostPopulationsPipeline.ped: 
PLINK PED file with site/life stage ID, individual ID, and genotypes. Each row is an individual.

2. REED_PostPopulationsPipeline.map:
PLINK MAP file with SNP identifier. Each row is a SNP.

REED_PostPlinkFiltering: Contains data for individuals post-PLINK filtering (maf = 0.01; geno = 0.25; mind = 0.75)

3. REED_PostPlinkFiltering.ped: 
PLINK PED file with site/life stage ID, individual ID, and genotypes. Each row is an individual.

4. REED_PostPlinkFiltering.map:
PLINK MAP file with SNP identifier. Each row is a SNP.

STACKS v 1.09 manual: https://catchenlab.life.illinois.edu/stacks/manual-v1/
PLINK reference website: https://zzz.bwh.harvard.edu/plink/index.shtml
