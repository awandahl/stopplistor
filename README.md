# Stopplistor

Stopplistor för DiVA-kontroller och importer

#### Nordita SU
Söker i organisationsfältet + fritext efter strängen "nordita su" eller "nordita, su" och skapar en csv med PID, DOI, ISI, ScopusID samt innehållet i anmärkningsfältet. Strängen "nordita su" i en post anger att vi bedömt att publikationen inte har en identifierad KTH-författare (KTH-id kan hittas) och därför inte tillhör KTH.   

````
https://kth.diva-portal.org/smash/export.jsf?format=csv&addFilename=true&aq=[[{"organisation":"nordita su"}],[{"organisation":"nordita, su"}],[{"freeText":"nordita su"}],[{"freeText":"nordita, su"}],[]]&aqe=[]&aq2=[[]]&onlyFullText=false&noOfRows=9999&sortOrder=title_sort_asc&sortOrder2=title_sort_asc&csvType=publication&fl=PID,DOI,ISI,ScopusId,Notes
````

#### Syskonposter

````
https://kth.diva-portal.org/smash/export.jsf?format=csv&addFilename=true&aq=[[{"freeText":"syskonpost"}],[]]&aqe=[]&aq2=[[]]&onlyFullText=false&noOfRows=9999&sortOrder=title_sort_asc&sortOrder2=title_sort_asc&csvType=publication&fl=PID,DOI,ISI,ScopusId,Notes

````

