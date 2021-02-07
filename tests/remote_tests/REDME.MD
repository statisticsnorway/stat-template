# Remote Tests (Norsk)

Denne mappen skal inne hodlde alle tester som knyttes seg til dette produskjons løpes kilde kode.
Alle funksjoner, skal være enhets testet, for å sikkre at funksjonaliteten fungerer som den skal. 
Hvis du er usikker på hvordan tester fungerer, ta deg gjeren tid til å søke på nett etter unit tests.

Alternativt kan du se på Byrånettet på artikler rundt dette.

TEster som legges i denne mappen er tester som basserer seg på generative data.
Vi har ikke muligheten til å legge data i selve kode repoet av sikkerhets messige grunner. 
men du kan legge inn kode i test scriptene som genererer datene som skal bruke i testene. 

Tester som ligger i denne mappen vil bli kjørt med Komandoen `make test` lokalt.
De vil også bli plukket opp av CI (Continouse Integration) verktøyet vårt og kjørt remote.
Vi bør streve å ha som amnge som mulig av testene vår i denne mappen, 
da det vill al oss se på muligheter for å effitivisere og distribuere testene våre på ett sikkert vis.