# AI is here … now what?
Dystopische beelden van Blade Runner, treurige muziek van Radiohead. Is dit de toekomst waar AI ons heen brengt?
Hoe dan ook, AI is here! Zo begon de 2-daagse World Summit AI 2026 in Zaandam. Een congres waar verschillende disciplines samenkwamen.
Deze mix van mensen heeft AI ook nodig om het te vormen naar wat wij als mensheid willen dat het heen gaat. Of hebben de grote techbedrijven
alle touwtjes in handen en is dat bij voorbaat kansloos? 

# Control your tiger and tell about it
Volgens Marietje Schaake (Stanford University’s Institute for Human-Centered AI) is er nu sprake van een tech coupe die gepleegd is door de grote techbedrijven uit de US. Ze is ook heel verbaasd dat in het incident met de ‘onbedoelde’ hack van OpenAI op de Australische overheidswebsite het bleef bij slechts excuses van OpenAI. Wij krijgen als burgers kleine ‘information drops’, terwijl deze bedrijven al veel verder zijn in ontwikkeling en er op los experimenteren. Haar visie is dat Trump beperkt houdbaar is en dat daarom de Europese regulerende en transparante manier om AI te implementeren over zal blijven. Deze manier zal ook uiteindelijk overslaan naar de US denkt zij.

Er werd gesproken over de grote knowledge gap tussen het publiek en de techbedrijven. Deze gap moet je kleiner maken door veel transparanter te vertellen over dat je een ‘tijger’ hebt. Bovendien zorgen dat die tijger niet meer losgeslagen hacks doet op websites zoals die van Hugging Face en overheden. De zorg is alleen dat al deze bedrijven in een race zijn om het heilige doel van Artificial General Intelligence te halen en degene die het meeste risico neemt waarschijnlijk als eerste over de streep komt. 

Zico Kolter (board member OpenAI) werd verder gevraagd naar transparantie, maar zat hierdoor vaak te draaien in zijn stoel. Waarom individuele modellen vertraagd waren in het publiceren, wilde hij ook niet verder op in gaan. Ook kon hij eigenlijk alleen zijn eigen persoonlijke opvatting geven en niet die van OpenAI. De presentator vond dit wel erg teleurstellend, omdat het al veel moeite had gekost om überhaupt een board member op het podium te krijgen.

# Your processes are legacy
Als we AI blijven zien als slechts een tool die we kunnen inzetten in onze dagelijkse bestaande werkzaamheden dan is de gain mogelijk minder hoog dan we hadden gehoopt. 
Het meten van AI-maturity in een bedrijf zal moeten gaan over hoeveel werk er toevertrouwt wordt aan AI. In plaats van te meten op welke plekken we het gebruiken voor lokale optimalisaties in bestaande processen. Het formuleren van goals en intents van een organisatie worden daarom veel belangrijker die dienen als input voor AI.

Dit thema vond ik ook terug in de presentatie van Camunda over het nieuwe product ProcessOS[1]. Vrijwel alle processen die wij bij klanten kennen zijn legacy, omdat ze ontwikkeld zijn pre-AI. De reflex is om dan de huidige processen lokaal te optimaliseren. Maar de echte value gain zit in het echt reengineeren van het proces. Alleen de ontwikkeling van AI capabilities gaat veel sneller dan de reengineering van een kritiek legacy proces. Deze gap heeft Camunda met ProcessOS gedicht. 

Dit product brengt met behulp van een Discovery Agent het as-is proces in kaart. Dit gebeurt door het raadplegen van alle aangegeven bronnen over het proces. Vervolgens zal dit als context gebruikt worden om het proces met behulp van een Design Agent naar een to-be proces te brengen. Het gevolg is dat er bijvoorbeeld veel minder onpraktische touchpoints en handoffs zijn in een proces, maar veel meer gestuurd wordt op user engagement via krachtige communicatiekanalen. Ook ingewikkelde decision points en flow-steps in BPMN[5] worden omgebogen door de agents naar goals. Waarbij AI in de driverseat is om dat proces via de juiste flow uit te voeren aan de hand van de gestelde doelen. Uiteraard met de nodige Human In The Loop approvals en guardrails. Het is een veelbelovend product (in closed beta) dat voor onze klanten ook potentieel echt waarde kan gaan opleveren.

# The future of agents & models
Improvements in een AI-oplossing kunnen op meerdere plekken plaatsvinden. Bijvoorbeeld je context aanscherpen, het model zelf finetunen of door middel van observability toe te passen op je AI-agents die het model gebruiken. Dat laatste genereert de observability data van de toekomst volgens LangChain. Het kunnen tracen van je agents wat ze doen en welke reasoning wordt toegepast en hierop verbeteren. De oplossing om deze data op te kunnen slaan en tegenaan te queryen heet LangChain’s SmithDB[2].

Het kunnen evalueren van een AI-oplossing was vroeger echter makkelijker in termen van bias, volgens Alice Xiang (Global Head AI Governance, Sony Group). De gebruikte modellen waren simpeler en meer toegespitst op de taak. Nu hebben we LLMs met generic capabilities waar dit niet eenvoudig te meten is en zijn de use cases erop veel diverser.
Sinds begin 2023 is ook het aantal basismodellen daarin sterk gestegen. Inmiddels is meer dan de helft een open-weight model[3]. Modellen waarvan de getrainde modelgewichten publiek toegankelijk zijn. De Verenigde Staten lopen voorop in de ontwikkeling ervan, gevolgd door China en Frankrijk. Voordelen van het vrijgeven van modelgewichten zijn onder andere grotere transparantie (externe toetsing), versnelling van innovatie en onderzoek en meer concurrentie. De snelle vooruitgang brengt ook risico's met zich mee. Kwaadwillenden kunnen publieke modelgewichten aanpassen (fine-tuning) om ingebouwde veiligheidsmaatregelen te omzeilen. Dit vergroot het risico op onder meer deepfakes, cyberaanvallen en het genereren van schadelijk materiaal.

Ook zorgt AI voor het mergen van research op verschillende gebieden. Voorheen kenden we aparte wetenschappelijk modellen voor bijvoorbeeld biologie, chemie en natuurkunde. Met de komst van AI-modellen zijn ze een stap dichterbij om deze gebieden te verenigen in 1 model en zo beter research te kunnen doen.

# Cognitive offloading
Is het allemaal dystopisch? Gelukkig meldde Trena Minudri (Chief Learning Officer, Coursera)[4] dat Nederland, Frankrijk en Duitsland in de top 10 van landen stond waarin het stijgende aantal AI-trainingen gelijk op liep met een stijging van human skills trainingen. Het leren en echt begrijpen van nieuwe dingen moet frictie opleveren en een tip was om AI niet gelijk het antwoord te geven, maar een vraag te stellen aan je. Als we zo’n gezonde relatie houden met AI en cognitief niet alles willen offloaden dan kunnen er mooie dingen ontstaan.

# Referenties
\[1\] <https://camunda.com/platform/process-os/>

\[2\] <https://langchain.com/blog/introducing-smithdb>

\[3\] <https://oecd.org/content/dam/oecd/en/publications/reports/2025/08/ai-openness_958d292b/02f73362-en.pdf>

\[4\] <https://coursera.org>

\[5\] <https://bpmn.org>
