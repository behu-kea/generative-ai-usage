# Teacher Generative AI usage



<!--

### Hvilke opgaver har jeg som underviser?

- Skriver lektoranmodning
- Kan jeg bruge det at jeg kan simulere studerende? Eller undervisere? 



### Should i even automate this?
- Giver generel feedback på projekter
	- Hmm men mon ikke jeg skal være inde over her? Der er jo her blandt andet at jeg løbende evaluerer dem
- Laver læringsplaner
  - Det er ret personligt

-->




## Prompts/GPT's



### Generer billede til et slide

**Problem:** Jeg står tit og mangler et billede til en slide eller nogle billeder til nogle slides. Ofte når jeg bruger ChatGPT bliver billederne grimme, gnidrede og med masser af tekst. Det problem løser den her prompt.



**Løsning:** Skriv teksten til en slide eller upload dit slide som et billede. Derefter laver den et billede der passer til teksten/slidet

- Link til GPT: [https://chatgpt.com/g/g-lVg2WIj8o-slidevisuals-create-images-for-your-slideshow](https://chatgpt.com/g/g-lVg2WIj8o-slidevisuals-create-images-for-your-slideshow)

- Link til Prompt: [slide-image.txt](prompts/slide-image.txt)



### Generer en podcast til en ressource

**Problem:** Jeg har tit en masse artikler/links/nyhedsbreve jeg gerne vil læse, men ikke har tid til. Det problem løser NotebookLM for mig



 **Løsning:** Få en podcast genereret ud fra en ressource man uploader (link, pdf, html dokument). Man kan lave en podcast til en ressource, men det kan også være flere ressourcer man uploader og den laver en podcast til de ressourcer

- Link: [https://notebooklm.google.com/](https://notebooklm.google.com/)



### Producer læringsmateriale til en enkelt gang

**Problem:** At lave læringsmateriale som dokumentation, kode-eksempler, analogier, forklaringer og opgaver tager lang tid og kan være en kæmpe opgave især for nye kurser der ikke har været lavet før.



**Løsning:** Få genereret læringsmateriale og opgaver baseret på nogle læringsmål. Materialet bliver skrevet i Markdown og laver man prompten i ChatGPT, gemmer den endda markdown filen direkte. Man skal specificere programmingssprog, længde af klasse, emnerne og læringsforudsætningerne

- Link til Prompt: [lesson-plan-generator.txt](prompts/lesson-plan-generator.txt)



**Forbedringer:**

- Skal teste den mere. Den er et udgangspunkt, men er meget straight forward
- Måske mere chain of thought ville være godt til den



### Exercise generator - Basic software development

**Problem:** Creating exercises for software development can take a long time and be quite cumbersome 



**Løsning:** This prompts generates exercises for software developement basics. That means it works best with exercises about variables, for loops, if sentences, arrays, objects, classes, lists, inheritance, etc. It does not do great when the software is used to build frameworks like fx react, DOM, app development, backend, server and api. 

- Link til prompt: [exercise-generator.txt](prompts/exercise-generator.txt)



### Exercise generator - Fun exercises

**Løsning:** Den her GPT har mere fokus på lidt mere spændende opgaver der er mere kreative og måske også lidt skøre:

- Link til GPT: [https://chatgpt.com/g/g-SXk9BLMbf-fun-exercise-creator](https://chatgpt.com/g/g-SXk9BLMbf-fun-exercise-creator)

- Link til Prompt: [fun-exercise-generator.txt](prompts/fun-exercise-generator.txt)



### Quiz generator

**Problem:** I min klasse laver jeg små quizzer til at teste om de studerende har forstået forberedelsen til timen. De quizzer tager en del tid at lave. 



**Løsning:** Generer en quiz indenfor et specifikt emne. Man skal specificere emner, programmeringssprog, sværhedsgrad og antal spørgsmål man vil have genereret

- Link til GPT: [https://chatgpt.com/g/g-eixxhYrsp-software-developments-quiz-generator](https://chatgpt.com/g/g-eixxhYrsp-software-developments-quiz-generator)

- Link til prompt: [quiz-generator.txt](prompts/quiz-generator.txt)



### Learning accellerator

**Problem:** Som underviser indenfor softwareudvikling skal man altid lære nye emner/teknologier. Det kan tage tid at finde ud af hvor man er god eller ikke så god



**Løsning:** Løsningen er en prompt der først spørger hvad du gerne vil lære og hvilke læringsforudsætniner du har. Derefter stiller den dig nogle spørgsmål for at finde ud af dit niveau indenfor emnet. Når du har svaret på spørgsmålene får du en rapport der highlighter hvor du er stærk og hvor du kunne forbedre dig. Til sidst laver den en læringsplan for dig ift at lære det den vurderer du ikke har så godt styr på. Virker bedst med OP1.

- Link til GPT: [https://chatgpt.com/g/g-VKLlaWNHb-software-development-learning-accellerator](https://chatgpt.com/g/g-VKLlaWNHb-software-development-learning-accellerator)
- Link til prompt:  [learning-accellerator.txt](prompts/learning-accellerator.txt) 

GPT'en kan kobles med Materiale produktion. Så man tager rapporten og laver materiale udfra det.



**Forbedringer**

- Måske skal det bare være en prompt til at finde læringshuller og få lavet læringsmål til en selv. Selve læringsplanen kunne man så få fra en anden



### Discussing learning challenges

**Problem:** At finde på løsninger til en problemstilling i klassen kan være svært. 



**Løsning:** Jeg har linket til hvordan jeg har brugt ChatGPT til at løse et konkret problem i min klasse: https://chatgpt.com/c/66e44c51-5d8c-8008-8446-a4cb8e2fc5ed



### Find focus as a knowledge worker

**Problem:** At finde et fokus som vidensmedarbejder efter lektoranmodning kan være lidt svært.



**Løsning:** Jeg har linket til en prompt jeg har brugt til at indgå i en samtale med ChatGPT omkring fokus. 

- Link til prompt: [focus-as-knowledge-worker.txt](prompts/focus-as-knowledge-worker.txt)



### Create icon for a GPT

**Problem:** Det er lidt niche det her, men de ikoner GPT'erne selv laver er super grimme. 



**Løsning:** En GPT man kan give enten en beskrivelse af sin GPT eller prompten til ens GPT. Nu brainstormer den først, vælger en ide og genererer et ikon til GPT'en

- Link til GPT: [https://chatgpt.com/g/g-8Y3peNSgU-image-for-gpt-creator/](https://chatgpt.com/g/g-8Y3peNSgU-image-for-gpt-creator/)

