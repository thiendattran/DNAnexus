# DNAnexus
Documents the steps to run epi project on UKB-RAP DNAnexus platform

# Creating the field in the UK Biobank
system("dx ls 'Showcase metadata'")

system("dx ls")

## Select fields of interest using command line
Run this code on the command line on R Studio/Jupyter

```dx extract_dataset project-xxxx:record-yyyy -ddd --delimiter ","  # where project-xxxx:record-yyyy is ID of your Dataset```

Example: 

```dx extract_dataset project-Gq3P5vQJ7xvB1F5PGq0xv9k6:record-Gq3V0g8JFx909X6XJJJXqBKF -ddd --delimiter ","```
