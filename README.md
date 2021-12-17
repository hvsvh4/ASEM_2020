# Rcode description
IMPORTANT: Please read till the end.
Rcode for study presented at the American Society for Engineering Management 2020 conference.


### About the project
A between-subjects experiment to find the effects of AI recommendations.
The experiment used online participants.
Task was to identify the subject shown in an image which AI help.
Participants were asked to identify every image with the help of AI recommendations.
We analyzed the effects of varying levels of AI recommendations on user performance.


### ASEM_106_submit.docx
Final peer-reviewed article published at the conference.


### Final_code_ASEM_2020
Includes all the datasets and RStudio files used to analyze the data.
Download this entire folder and simply open the RStudio project.

  1. Final_code_ASEM_2020.Rproj
  Name of the RStudio project. 
  Simply open this and run the cleaning.rmd file and then the analysis.rmd file.
  Clean dataset is also attached. So, you can directly run the analysis as well.
  
  2. Qualtrics_data_05.13.2020.csv
  Raw data.
  Data was gathered from Prolific, an online survey platform.
  286 participants were included in the survey. 
  The experiment included 24 stimuli.
  
  3. Data_cleaned_person.csv
  Each row (observation) is one person. 
  Each column (variables) is the responses of every individual.

  4. Data_cleaning.Rmd
  Rcode used to cleanup the raw data (Qualtrics_data_05.13.2020.csv).
  Final output is a clean dataset (Data_cleaned_person.csv). 
  "Data_cleaned_person.csv" was used for analyzing.
  
  5. Stimuli_response_coding.R
  RStudio file that includes all the responses provided by the participants in the survey.
  Please read the methods section in "ASEM_106_submit.docx" to understand how these open-text box responses were converted to numerical accuracy.
  
  6. Analysis.Rmd
  Rcode used for analyzing the data. Analysis include -
    a. Exploratory Data Analysis
    b. One-way ANOVA
    c. Block ANOVA
    d. Post-Hoc Test
    e. QQ Plots
    f. Tukey-interaction measures
    g. Correlation Matrices
    h. Two-way ANOVA
    i. Graphical output of results using GGPLOT package.
#####

END
    
    
    
    
    
    
    
    
    
    
  
  
