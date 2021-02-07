# Local tests (Norsk)

Dett er mappen som skal inneholde alle de testene som utelukkende kan kjøres fra inni DAPLA systemet.
Noen ganger er det nødvendig og bruke de Skarpe data strømmen evåre i tester av funksjoner. 
Dette kan skyldes dataenes komplexitet som gjør det umulig og gjennskape som generative data.
Det kan skyldes at det dreier seg innlesings tester, som krever de systemen vi har På Dapla.

Uansett grunn så befinner du deg i en situajson det du har tester som ikke kan kjøres i CI (Continouse integrasjons) systemet vårt.
Disse testene legges i denne mappen, og vil da ikke plukkes opp av Aure pipelines og testes for. 

Det er ikke laget noen undermapper her, da det ikke er fastsatte test regimer.
Det anbefales imidelrtid at du lager undermapper. Gjerne for hvert subassembly, eller Test typer, enhet, volum, innlasint etc.