# biol3207_workshop6

The generally workflow of the study utilises the dataset "OA_activitydat_20190302_BIOL3207.csv". Initially the dataset is loaded in in Task 3. This is to load the dataset object into the R studio space allowing more data wrangling and manipulation of the dataset. Github was used to track changes to the R studio document throughout the study and saved to my person Github account.

The dataset is on ocean acidification effects on fish behaviour that was published in Nature in 2020. The dataset includes several columns including loc, species, treatment, animal_id, sl, size, activity and a comment. More details can be found below:

loc - Location, and year, where the data were collected. AIMS = Australian Institute of Marine Science; LIRS = Lizard Island Research Station

species - Species name: acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis

treatment - 	Elevated CO2 [CO2] (850-1,050 µatm) or control [Control] (400 - 450 µatm) groups

animal_id - Fish identity

sl - Standard length of the fish in mm

size - Size grouping of the fish, separated at 15 mm standard length into ‘big’ or ‘small’

activity - 	Number of seconds the fish was active per minute, averaged across the duration of the trial
comment - Comment with notes on the origin of the data

The data was initially cleaned up by removing missing data and dropping out irrelevant columns (loc and comment). The data was used to calculate the necessary statistics for study and for t-test analysis in Task 4-9.

The study uses a range of different libraries including pacman, dplyr and flextable.

Note: Fish standard length (SL) data were measured directly in some experiments (e.g., 2016) and estimated from regression relationships in others.  
For example, the Acanthochromis polyacanthus used in choice flume experiments in 2015 arrived in the lab at a very uniform size, and batches of fish 
were sacrificed from holding tanks at various timepoints throughout the study.  Regressions of SL vs. time were then used to estimate the SL of each 
of the fish used in experimental trials, as we did not want to risk harming these fragile fish by taking length measurements.  Fish SL in the 2014 flume 
data was measured from the video footage and then a post hoc calibration relationship was formulated for measured SL and footage-derived SL, to enable 
an estimate of the former from the latter for each of the experimental fish.  Excess decimal places have been retained in the dataset in instances where 
SL has been calculated rather than measured. This also explains the repeat values of SL for different individuals with excess decimal places.

Data, analysis script and associated files for:"			
"Clark TD, Raby GD, Roche DG, Binning SA, Speers-Roesch B, Jutfelt F, Sundin J (in prep) Ocean acidification does not impair the behaviour of coral reef fishes"			
"Data collected by TDC, GDR, DGR, SAB, BSR, FJ and JS. Please refer to the manuscript for data collection methods and statistical analyses. For questions or to notify the authors if any errors are identified in the data, please contact Tim Clark (t.clark@deakin.edu.au), Graham Raby (graham.d.raby@gmail.com), and/or Dominique Roche (dominique.roche@mail.mcgill.ca)."			
