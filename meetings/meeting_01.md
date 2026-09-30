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



**Potential issues or questions:**  
- Different varaible naming across CSV files

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
| Sarah |  |  |
| Christian |  |  |
| Hanna |  |  |

## Next Meeting
**Date:**  
**Time:**  
**Planned focus:**  