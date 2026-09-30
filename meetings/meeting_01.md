# PHYS3116 Computational Assessment
## Meeting 1
**Date:** 30 September 2026  
**Time:** 12:00pm  
**Location:** Teams  

## Attendance
- Sarah Lawler
- Christian McCarthy
- Hanna Bridges

## Agenda
1. Choose project option
2. Define the main research question
3. Review the available datasets
4. Decide coding language and workflow
5. Allocate tasks for this week
6. Set next meeting time

### Project Option
**Selected option:** Option 1

**Reason for selection:** We selected Option 1 because it provides a clearly defined research question and analysis pathway using age, metallicity and dynamical information, while still allowing scope for additional investigation beyond the minimum requirements.

### Research Question
**Primary research question:** Can we identify candidate accreted Milk Way globular clusters using their age, metalicity and dynamical properties? 

**Possible secondary questions:** 
- What might these candidate accreted clusters imply about the assembly hisotry of the Milk Way? 
- What information can be ascertained pertaining towards the Milky Way's formation and globular cluster accretions by quantity within the Milky Way? 

### Dataset Review
**Files available:** CSV files on moodle 

**Important variables/columns:**  
*HarrisPartI.csv*
- (1) Cluster identification number
- (2) Other commonly used cluster name
- (3,4) Right ascension and declination (epoch J2000)
- (5,6) Galactic longitude and latitude (degrees)
- (7) Distance from Sun (kiloparsecs)
- (8) Distance from Galactic center (kpc), assuming R_0=8.0 kpc
- (9-11) Galactic distance components X,Y,Z in kiloparsecs, in a
    Sun-centered coordinate system; X points toward Galactic center, 
    Y in direction of Galactic rotation, Z toward North Galactic Pole

*HarrisPartIII.csv*
- (1) Cluster identification
- (2) Metallicity $[Fe/H]$
- (3) Weight of mean metallicity; essentially the number of independent $[Fe/H]$
	measurements averaged together.  See bibliography for full description
- (4) Foreground reddening
- (5) V magnitude level of the horizontal branch (or RR Lyraes)
- (6) Apparent visual distance modulus
- (7) Integrated V magnitude of the cluster
- (8) Absolute visual magnitude (cluster luminosity),  M_V,t = V_t - (m-M)V
- (9-12) Integrated color indices (uncorrected for reddening)
- (13) Spectral type of the integrated cluster light
- (14) Projected ellipticity of isophotes, e = 1-(b/a)

*Krause21.csv*
- (1) Class is Gobular clusters
- (2-3) Identifer and Common Name
- (4) Stellar Mass of the cluster 10^5 solar masses
- (5) Half-mass radius in parsec
- (6) Compactness index (dimensionless)
- (7) Cluster age in Gigayears
- (8) Metallicity $[Fe/H]$

*vandenBerg_table2.csv*
- (1-2) Cluster identification number and name 
- (3) Metallicity $[Fe/H]$
- (4) Age in Gigayears
- (5) Age uncertanity 
- (6) Method - how cluster is detemined (vertical, horizontal, average of the two method)
- (7) Figures
- (8) Range - the ranges of ages obtained by the three resarchers DAV, KB and RL when they fitted each cluster 
- (9) HBtype - horizontal branch morphology/type 
- (10) Galactocentric distance
- (11) Absolute integrated V-band magnitude
- (12) Central escape velocity, in km/s
- (13) Surface density of stars at the cluster centre

**Potential issues or questions:**  
- Different varaible naming across CSV files
- How are we supposed to combine the same measurements? 

**Notes:**
- VandenBerg gives us age and metallicity
- Harris I gives us position and galatocentric distance 
- Harris III gives us kinematics 
- Krause give us mass/size/compactness and metallicity

### Coding and Workflow
**Coding language:** Python

**Planned tools/packages:** 
- pandas - reading CSV files, inspect tables, filtering data, merge datasets
- numpy - numerical calcs and arrays
- matplotlib.pyplot - plotting help
- scipy - useful for finding stats
- Jupyter Notebook - put in code, plots and markdowns together

## Action Items

| Team Member | Task | Due Date |
|---|---|---|
| Sarah | Clean Data | Monday 5th of October |
| Christian | Age-Metalicity Analysis | Wednesday 7th of October |
| Hanna | Kinematics  | Wednesday 7th of October |

**Due Date:** Monday 26th October (Wk 7)  
**Video Date:** Thursday 22nd of October (Wk 6)  
**Data Analysis Due Date:** Monday 19th of October (Wk 6)  

## Next Meeting
**Date:** Tuesday 6th of October  
**Time:** 2pm   
**Planned focus:** Start analysis of cleaned data.   