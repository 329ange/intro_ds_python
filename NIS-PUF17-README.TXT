2017 National Immunization Survey-Child (NIS-Child) 
Public-Use Data File (PUF)



WARNING - DATA USE RESTRICTIONS - READ CAREFULLY BEFORE USE!

The Public Health Service Act (Section 308(d)) provides that the 
data collected by the National Center for Immunization and 
Respiratory Diseases (NCIRD), Centers for Disease Control and 
Prevention (CDC), may be used only for the purpose of health 
statistical reporting and analysis.

Any effort to determine the identity of any reported case is 
prohibited by this law.

NCIRD does all it can to ensure that the identity of data subjects 
cannot be disclosed.  All direct identifiers, as well as any 
characteristics that might lead to identification, are omitted 
from the data files.  Any intentional identification 
or disclosure of a person or establishment violates the assurances 
of confidentiality given to the providers of the information.

Therefore, users will:

1. Use the data in these data files for statistical reporting and 
   analysis only.

2. Make no use of the identity of any person or establishment 
   discovered inadvertently and advise the Director, NCIRD, of 
   any such discovery (1 (800) 232-4636).

3. Not link these data files with individually identifiable data 
   from other NCIRD or non-NCIRD data files.

By using these data, you signify your agreement to comply with 
the above requirements.



INTRODUCTION

The National Immunization Survey - Child (NIS-Child) is sponsored by the 
National Center for Immunization and Respiratory Diseases 
(NCIRD) and conducted by NCIRD. The NIS-Child is a list-assisted 
random-digit-dialing telephone survey of households followed by a 
mailed survey to children’s immunization providers that began 
data collection in April 1994 to monitor childhood 
immunization coverage.

The target population for the NIS-Child is children between the ages of 
19 and 35 months living in the United States at the time of the interview. 
Data from the NIS-Child are used to produce timely estimates of vaccination 
coverage rates for all childhood vaccinations recommended by the Advisory 
Committee on Immunization Practices (ACIP). A public-use data file (PUF) is
available for each year beginning with 1995.

See this website for more information:
http://www.cdc.gov/vaccines/imz-managers/nis/about.html



CONTENT OF THE 2017 NIS-CHILD PUF

The files listed below can be found at this location:
http://www.cdc.gov/vaccines/imz-managers/nis/datasets.html

The overall package consists of eight computer files, as follows:

---------------------------------------------------------------------------------
NAME.TYPE                 File                 Description	
                          Size (KB)           	
---------------------------------------------------------------------------------
NISPUF17README.TXT           9       2017 Readme File (this text)

NISPUF17DUG.PDF 	 4,202       2017 NIS-Child PUF Data User's Guide 
                                     (Adobe Acrobat format)

NISPUF17CODEBOOK.PDF     3,500       2017 NIS-Child PUF Data Documentation,
                                     Codebook, and Frequencies
                                     (Adobe Acrobat format)

NISPUF17.DAT            23,267       2017 NIS-Child PUF Dataset (ASCII format)
                                     
NISPUF17.SAS                67       2017 SAS Input Statements (ASCII format)

NISPUF17.R                  88       2017 R Input Statements (ASCII format)

NISPUF17HHQUEX.PDF         421       2017 NIS-Child Household Questionnaire 
                                     (Adobe Acrobat format)

NISPUF17IHQ.PDF            844       2017 NIS-Child Immunization History Questionnaire 
                                     (Adobe Acrobat format)
                
                                     
---------------------------------------------------------------------------------

The 2017 NIS-Child public-use data file is available in ASCII format. 
A SAS program (in ASCII format) is provided to facilitate reading
the ASCII data file and creating a SAS dataset. The SAS program
contains, for each variable in the ASCII file, the variable name,
its starting position and end position, labels, and formats.
An R program (in ASCII format) is also provided to facilitate
reading the ASCII data file and creating an R dataset. The R
program contains, for each variable in the ASCII file, the
variable name, its starting position and end position, labels,
and formats. 

The data file NISPUF17.DAT can be used for processing by 
statistical software packages that accept ASCII-formatted input, 
or it can be transferred to another computer for processing.

For more information about the 2017 NIS-Child PUF, data users should 
consult the 2017 NIS-Child PUF Data User's Guide and the 2017 NIS-Child 
PUF Data Documentation, Codebook, and Frequencies. Users of these 
data must review that descriptive and explanatory documentation to 
analyze the data correctly.  These documents are available in PDF 
format.

The 2017 NIS-Child PUF Data User's Guide provides detailed information 
about the design of the 2017 NIS-Child sample, the questionnaires, the 
weighting and estimation procedures, and other important 
information needed for analyzing these data.  

The 2017 NIS-Child PUF Data Documentation, Codebook and Frequencies 
contains indexes of the variables (in both data-file-position 
order and alphabetical order), the variable responses, and 
either unweighted frequencies of categorical variables or 
unweighted summary statistics for continuous variables.

The 2017 NIS-Child files are large.  Please use caution and check the 
capacity of your disk drive before downloading them.
     

Documents in PDF format can be viewed with Adobe Acrobat software.
The Adobe Acrobat Reader can be downloaded from the Adobe Acrobat 
website at:

http://get.adobe.com/reader     



UNIQUE IDENTIFIERS AND WEIGHTING

The unique household identification number is SEQNUMHH.
The unique child identification number is SEQNUMC.  

SEQNUMC consists of 6 digits: the first five digits are 
SEQNUMHH and the sixth digit uniquely 
identifies the child within the household.

In 2017, the NIS-Child PUF contains interviews collected both by landline
telephones and by cell phones. To produce estimates for the U.S. proper,
the RDD-phase sampling weights are called RDDWT_D, and the provider-phase
sampling weights for children with adequate provider data are called PROVWT_D.
Data for the U.S. territories are not included on the 2017 NIS-Child PUF. 



IMMUNIZATION COVERAGE RATES

Estimates of vaccination coverage rates from the 2017 NIS-Child are 
available at:

http://www.cdc.gov/vaccines/imz-managers/coverage/childvaxview/index.html



GUIDELINES FOR CITATION OF DATA

With the goal of mutual benefit, the National Center for Immunization and 
Respiratory Diseases (NCIRD) request that recipients of data files 
cooperate in certain actions related to their use.  Any published 
material derived from these data should acknowledge CDC (NCIRD) 
as the original data source and use "NIS-Child" in the title or as a 
keyword in the abstract. The suggested citation to appear at the 
bottom of all tables is as follows:

       Source: CDC, NCIRD (2018), 2017 National Immunization
       Survey - Child.

The reference for the 2017 NIS-Child data file is:

       U.S. Department of Health and Human Services (DHHS).  
       National Center for Immunization and Respiratory Diseases. 
       The 2017 National Immunization Survey - Child.  
       Atlanta, GA: Centers for Disease Control and Prevention, 2018.

       http://www.cdc.gov/vaccines/imz-managers/nis/datasets.html

Published material should also include a disclaimer that 
attributes any analyses, interpretations, or conclusions reached 
to the author (recipient of the data file) and not to NCIRD, 
which is responsible only for the initial data.  Consumers who 
wish to publish a technical description of the data should 
ensure that the description is consistent with that published 
by NCIRD.

Although the data files have been edited carefully, errors may be 
detected.  Please notify NCIRD staff (1 (800) 232-4636) of any errors 
in the 2017 NIS-Child data or documentation and refer to the NCIRD 
website at http://www.cdc.gov/vaccines/imz-managers/nis/index.html
for updates to the NIS-Child data files.

For additional information on the NIS-Child public-use data file, please 
contact the NCIRD Information Dissemination staff:

Information Dissemination Staff, NCIRD
1600 Clifton Road
Atlanta, GA  30333

Phone:       1 (800) 232-4636
Email:       cdcinfo@cdc.gov
Internet:    http://www.cdc.gov/vaccines/imz-managers/nis/index.html