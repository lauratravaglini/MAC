# DEVELOPMENT

## **The MAC App: presentation.**

It is now time to present the MAC App.&#x20;

We made use of two tools:&#x20;

* **Balsamiq** to create a mockup describing the structural components**;**&#x20;
* **Figma** to elaborate some graphical proposals for the implementation.

## The user diagram.

The following diagram resumes what we have just exposed about the app’s structure and  describes the users’ interaction with it, how they will approach it and what they will be able to do.

## The interactive guide.

Now that we have outlined a general overview of the MAC App, we will discuss the main focus of our design: the interactive guide. As we have just shown, when the users choose this type of guide over the traditional one, three symbols will be displayed: without further explanation, blindly, one must be picked. That's where the fun begins.

Once they click on it, depending on the chosen symbol, an avatar will appear and their path will start. This fictional character will guide the users in their visit by keeping them entertained by  telling their own story and by engaging them in a treasure hunt across the museum’s holdings. When all the sought-after objects are collected and the path is over, the user will be rewarded with the possibility to see the character’s tomb as it was at the time of burial. The grave will be reconstructed via AR exploiting the 3D rendering project that is currently carried out by the University of Salerno. The AR experience will either take place in the Museum, where the 1:1 chamber tomb reconstruction is, or – better – in the archaeological site itself. In fact, it is reachable with a ten-minute walk from the MAC.

## **The characters.**

The three fictional characters of our App were designed drawing inspiration from three extant tombs found in the Addolorata necropolis. By analysing the burials’ contents as they were unearthed by the archaeologists, and by studying Samnites’ history and customs, we reconstructed the profiles of our avatars: Maio Vestricio Surreone, Nilde Velina, and Enclopio Ponzio. In addition, we resorted to our own creativity and imagination, and to a collective repertoire of archetypes, as will be detailed in the following pages. For the actual character design, we made use of The Sims 4, a life simulation video game. Once we built the three “Sims”, we made them interact and took pictures of their expressions. Each of them is shown with two different looks: one when she/he was alive, and one dead.

## **Implementation: Maio Vestricio Surreone.**

Let us now focus on Maio Vestricio Surreone for a moment. When it came to prototyping, we decided to implement the interactive path of one specific character, our protagonist Maio. In doing so, we tried to bring our cognitive focuses to the foreground. In particular, among our goals was to make the user feel engaged, challenged, amused, and intrigued. To achieve this, we designed Maio’s personality to be realistic, genuine, and strongly characterised: he has his own language, gestures, passions, and concerns. He has a story of his own and interacts with the user asking him for help in order to restore his tomb.

{% embed url="https://www.figma.com/proto/8ohNVSPg3yLp6kqsNd5zZJ/CARDS?node-id=180%3A43&page-id=0%3A1&scaling=contain&show-proto-sidebar=1&starting-point-node-id=402%3A59&viewport=241%2C48%2C0.08" %}

## **Scenario.**

Do you remember Chiara, the teenage loner girl? In order to understand if our App actually complied with our intended users and their goals, we discussed and wrote a brief scenario titled _The school trip_.

> “After the first hour of school, Chiara and her class exit the building to reach Carife, where they will visit the local archeological museum. On the bus, the girl takes her seat and immediately puts her headphones on, trying to kill the – albeit brief – time of the trip with music. Once at the museum, the teacher invites her students to download the MAC application, where they will find a small team game: as she explains, it consists of a treasure hunt across the museums’ holdings. When the research is over, the players will be rewarded with a surprise. Tickets in their hands, the fifteen present students – divided in three groups and supervised by their teacher and by the two museum’s volunteers – find their way to the app’s section containing the game. Each of the groups chooses one of the three available paths by clicking on the symbol they are most curious about: at the end of the game, each group will explain to the class what they have found and learned. Chiara freezes when her team chooses her as their captain. “You have the highest score both in Art and History, you must lead us in this!”. Her worst nightmare – public speaking – is real! But how could she say no to such a heartfelt plea? Although initially sceptical, she will soon make up her mind: the interactive route her group has chosen is so stimulating, the game so challenging, and the character so fun, that Chiara and her squad forget what a burden it is to talk in public and tell their story. They can’t wait to share it and find out what the other groups found instead… and they are so curious about the final reward that they put as much effort as possible in discovering and finding all the treasures that the museum hides.”

## Requirements and foreseen workflow.&#x20;

We identified some steps and related professional figures needed to actually implement the MAC App:&#x20;

* A software developer in charge of the back-end;&#x20;
* A user experience expert and/or a designer for the front-end and all the aesthetic aspects of the app;&#x20;
* A professional, such as an archeologist in this specific case, to verify the scientific accuracy of the contents;&#x20;
* For the interactive guide a game designer, a game developer, a sound engineer, an Italian voice actor (and at least an English one too) will be involved, and a 3D modeller for the Augmented Reality part.

In the foreseen workflow, all these professionals will be needed and will be asked to cooperate. In the specific case of the MAC, some institutions and professionals are already collaborating with the Museum. In particular, as we have already pointed out, the University of Salerno is carrying out a digitization project (3D scanning) on some of the Museum’s holdings. The resulting 3D models could be effectively included in the AR reconstruction of the archaeological sites.&#x20;

Moreover, the _ABAP Superintendence of Salerno and Avellino_ and the Municipality of Carife should cooperate and play a role in order to dissolve any bureaucratic obstacles regarding the necropolis linked to the Museum. During our interview with Mr. Castaldo, we had the opportunity to get to know an archaeologist who is currently working on Carife and nearby archaeological areas. She and a number of her colleagues would be at disposal for a sound reconstruction of the historical background.

## Further development and maintenance issues.&#x20;

As we have already mentioned, the MAC is looking forward to expanding its exhibition both by including remains currently stored in its deposit and by acquiring new holdings from the Hellenistic and Byzantine sites. The MAC App could thus be enriched with new contents and materials by creating new thematic paths and interactive stories.
