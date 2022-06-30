# stopplistor

Stopplistor för DiVA-kontroller och importer

#### Nordita SU
Söker i organisationsfältet + fritext efter strängen "nordita su" eller "nordita, su" och skapar en csv med PID, DOI, ISI, ScopusID samt anmärkningsfältet:    

````
https://kth.diva-portal.org/smash/export.jsf?format=csv&addFilename=true&aq=[[{"organisation":"nordita su"}],[{"organisation":"nordita, su"}],[{"freeText":"nordita su"}],[{"freeText":"nordita, su"}],[]]&aqe=[]&aq2=[[]]&onlyFullText=false&noOfRows=9999&sortOrder=title_sort_asc&sortOrder2=title_sort_asc&csvType=publication&fl=PID,Notes,DOI,ISI,ScopusId
````

