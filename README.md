# Liana_decay_experiment1
This R script records Njoroge et al 2024 field experiment examining the effect of woody debris size, soil fauna status and phylogenetic signals on lianas wood decomposition. The experiment was carried out in Xishuangbanna Tropical Botanical Garden,  Chinese Academy of Sciences (XTBG/CAS) in a common garden. In the experiment 30 species of lianas were used (see below for the phylogeny tree). To test for the diameter effect we used 2.0 cm and 4.0 cm woody debris diameter. To test for soil fauna effect we used litterbags of different mesh sizes to include or exclude soil fauna based on their size in order to evaluate the effect of soil fauna on wood decomposition. We have thirteen initial chemical traits including carbon, nitrogen, lignin, etc. from both wood and bark.


This contains xx files. 
## species_phylogeny_exp1
This file contains the list of liana species used in our experiment. It has 3 columns. The first one named "species" contains the names of species (both genus and species). The second column contains the "genus" information and the last column called "family" records the the family unto which that particular species belongs to.

## Exp1_initial_chemistry
In this file, apart from the header row, the rows contain species chemistry information. In total we measured thirtheen traits. The first 6 columns contain basic information of the samples such as “species_label” from 1 to 30 depicting each species of lianas. "species" columns records the full name of each particular species. "diameter_class" gives the information about diameter class of the woody debris from which the sample comes from. "wood_bark" helps to differentiate to which tissue either wood or bark the sample belongs to. Unique samples label and lab assigned labels columns follow later with the columns that records each measured trait.

## Experiment1_data_sheet
This file records all the initial physical traits measured to characterize the woody debris used in the experiment. The file starts with a cloumn entitled "species_label" ranging from 1 to 30 representing species used in the experiment. 
"species" lcolumn records full name of species.
"family" includes the family name of each species.
"Tag" represents the unique alphanumeric identifies of each woody debris.
"mesh_size" actually records whethere the woody debris was put in 5 mm mesh size to allow soil fauna access in which case we have a record of "soil fauna access" otherwise, the soil fauna are blocked with a use of 0.45 mm mesh size and recorded as "soil fauna blocked".
"diameter_class" givies the information about the diameter to which this particular woody debris belongs to.
The following 3 columns record the diameter of the woody debris at three different positions (both ends (1 and 3) and at the middle (2)). The unit of measurment is cm.
Later on, there are four columns that capture the thickness of bark at both ends measured with a calliper after drawing a straight diamter line throught the woody debris pith at each end. Two bark thickness measurement were subsequently measured in cm. Making the thickness measurements to be four.
"length_cm" records the length of the woody debris in cm.
"Wet_weight_of_wood_block_g" records the entire woody debris fresh weight in gram. 
The next following measurments refer to disk cut to measure water content and wood density.
"Wet_weight_of_small_pieces_of_wood_g" fresh weight of small pieece (or disk) in gram.
"Volume_of wet_small_pieces" records the fresh volume of the small piece (or disk) in gram through water displacement method.
"Dry_weight_of_small_block_g" represents the dry weight of small piece (or disk) after drying it in an oven for 48 hours at 105 degrees Celcius.
"Dry_volume_of_small_wood_blocks" records the dry volume of small piece (or disk) after the small piece was dried and the measurement employed water displacement method.

## Experiement1_hav1_2_3_4
This files records the woody debris characteristics after harvest at 6, 12, 18, 24 months post incubation in the forest. The following represents the description of the columns:
"Dates" records harvest dates.
"block" represnts the specific at where the woody debris was placed in the field.
"Tag" a unique alphanumeric identifier of woody debris.
"log_fresh_weight" the fresh weight of the woody derbis after cleaning off any dirt and any animal frass.
"Subsection“ records the disk ID cut from the harvested woody debris. 
"disk_fresh_weight" represents the fresh weight of disk in g.
"disk_fresh_volume" represents the fresh volume of the disk measured via water displacement method.
"disk_dry_weight" dry weight after drying for 48 h at 105 degrees celcius.
"Harvest" depicts the harvest number.
"Time_months" represents the number of months after incubation.
"Incubation_time" number of month after incubation.
"wd_status" gives the status of the woody debris at the time of harvest. When "bark" it means only bark remains. if "wd_bark" then it means both wood and bark remains, or "none" means neither bark nor wood remains.

## seibold_tropical
This file is from https://figshare.com/s/ffc39ee0724b11bf450c and records the decomposition of woody debris published in Seibold et al 2021 in Nature. We only subset to use the tropical biome data to compare the decomposition of the trees woody debris with our lianas decomposition data.



