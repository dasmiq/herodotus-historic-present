# Syntax and Narrative: The Historic Present in Herodotus

A thesis presented

David Arthur Smith

to

The Department of the Classics in partial fulfillment of the requirements for the degree with Honors of Bachelor of Arts in the subject of Classics (Greek)

Directed by Professor Gregory Nagy

Harvard University

Cambridge, Massachusetts

March, 1994


## Introduction

Speakers and writers use the historic present when they describe past events with the present tense. Some narratives in Ancient Greek have no instances of the historic present, some have a scattered few, and some have long strings of them. However they are distributed, a general consensus holds that historic presents occur in "lively or dramatic narration" (Smyth, 1956: 422). The only serious challenge to this theory of the "vividness" of the historic present came in 1968, when Paul Kiparsky published "Tense and Mood in Indo-European Syntax" in _Foundations of Language_.[^1] This article presented the argument that the historical present construction was not, in archaic Greek, a marker of vivid narrative, but rather the heir of the Indo-European injunctive as an unmarked narrative tense. One year after Kiparsky's article appeared, Saul Levin, writing in the same journal, offered his approval of Kiparsky's analysis, along with some corrections and refinements of his own. Five years later, K. L. McKay dismissed the arguments of Kiparsky and Levin on the grounds that they did not pay due regard to the function of aspect.

Though I will later consider these arguments of these three men on their merits, for now, the arguments are less important than the evidence that they used. This controversy was founded on thirty sentences of Greek, of which twenty were directly quoted. A few sentences might be enough to support or reject a claim about syntax on the sentence level, but these few sentences are woefully inadequate for analysis at the narrative level. Specifically, one sentence may suffice to refute Kiparsky's claim that the inherited functions of the injunctive account for all instances of the historic present, but we cannot assert without looking at a substantial body of evidence that the historic present generally marks vivid narrative, nor that it is a narrative tense unmarked for time, nor that it is used in synopses of events. In fact, we cannot, on the basis of such limited evidence as has been offered, propound any theory that has been advanced as to the historic present's discourse function. Since the historic present is optional, as Kiparsky and Wolfson (1982) have observed, we cannot simply examine a few out-of-context examples of this construction. We must train our sights on both the situations where it is used and those where it seems to be prohibited.

[^1]: "Tense and Mood in Indo-European Syntax" appeared in _Foundations of Language_ 4, pp. 30-57. A note on the article states that Kiparsky's work was supported by various government agencies, including the NSF, NIH, NASA, and the U.S. Air Force. It makes one yearn for the days when the space program could support research in Ancient Greek, Sanskrit, and Old Irish.

Why then did I choose to study this grammatical feature in Herodotus? First and foremost, the Histories are the first complete work of Greek prose that we have. That is to say, Herodotus is the first author for whom we may avoid the considerations of meter. Secondly, as a historian, he provides a generous sample of narrative passages on which to test a hypothesis. And thirdly, Herodotus' narrative structure is precisely what makes him so interesting as an author. In contrast, Denniston (1952: 2) characterizes prose writing before Herodotus thus:

> These writers made little attempt at organized structure. And the cause of that lies in the quality of their thought. They expound truth in oracles rather than proceed to it by the ordered march of logic. Hence their writing gives the effect of stiffly piled-up masses: it is static, not dynamic. And it is safe to say, though no continuous passage of any great length has survived, that its unit was the sentence rather than the paragraph.

Herodotus is the first testing-ground for theories about narrative, for the _Histories_ in my opinion are, rather than "stiffly piled-up masses", a vast and intricate edifice.

The description of a grammatical construction in an author is the domain of stylistics. Close studies of an author's diction have often been carried out, to great success at the lexical level (e.g. K. J. Dover's study of the _corpus Lysiacum_ or Mark Griffith's of _Prometheus Bound_) and at the level of the larger narrative, or _logos_ (e.g. Immerwahr's _Form and Thought in Herodotus_). The Intermediate stage of syntax, however, is often ignored as a marker of style, partly due to lack of resources and partly due to the impressive success of lexical stylistics.

I propose, therefore, to examine one syntactic construction — the historic present — as it appears in all of Herodotus. So great a labor would it be for a team of scholars that an undergraduate might well despair. Nevertheless, armed with basic morphological data and the tools to apply these data to a large body of text, I believe that I have produced some interesting results. Yet any amount of data stands idle without a theory for its application, and in this I owe a great debt to one of the few practitioners of syntactic stylistics, Albert Rijksbaron of the University of Amsterdam. His work on the discourse function of the imperfect in Herodotus (1988) was particularly helpful in clarifying some of my ideas on the relation of syntactic structures to narrative events.

In the following chapters, I will first outline some previous theories of the historic present and some theories of narrative in general. Specifically, I will present the concept of narrative grounding as an amenable framework for syntactic analysis. In the second chapter, I will describe the data and research tools at my disposal and the additional tools that I built to handle the data. In the third chapter, I will relate the evidence found by my programs to a formulation of the historic present based on narrative grounding, and I will argue that the historic present functions not so much as a marker of vivid action but rather as a marker of structurally foregrounded events.

While this thesis concentrates, to a great extent, on a particular construction in Ancient Greek, it is also a case study in computational linguistics. The individual processes described herein are not at all complex, but automation of morphological and syntactic analysis allows us to ask questions about large corpora that would have been previously impractical. More importantly, the simple methods used in this thesis, which shed light on such an important syntactic feature and its narrative context, should be a warning to all who would use computers for linguistic research. Never start with a difficult question when a simple one can produce the same insights.

As this thesis is intended for the general classicist, many of the methodological explanations will seem superfluous to a more technically-trained reader; likewise, the scholar of Greek may pass over the sketches of Greek syntax and morphology, which were included for the benefit of specialists in computational linguistics. Any reader who wishes to see my direct application of narrative grounding to the historic present in Herodotus should turn to Chapter Three.


<!-- ## Chapter One -->
## Syntax and Narrative

The historic, or narrative, present exhibits more clearly than any other construction the interaction of syntax and style. It has often been stated that an author, or embedded narrator, should seek to increase the vividness of his narrative by casting it into the present and creating what Rijksbaron calls an "eyewitness-effect".[^2] Smyth (1956: 422) goes even farther and says that the historic present "may be used to represent a past action as going on at the moment of speaking or writing." It is also apparent that a special vividness is called for at climactic points in the narrative. Rijksbaron (1984: 22), however, hints at another function of the historic present.

> When occurring among imperfects and aorist indicatives the historic present often highlights decisive actions, turning-points in the story, which introduce a new series of actions.

His examples, however, are confined to "decisive actions" or "turning-points" within individual narratives.[^3] While these internal usages form the bulk of the occurrences of the historic present, we can extend Rijksbaron's concept of turning-points to cover events that link two different narratives, and find historic presents also used for these. For it is surely these linking events that most surely "introduce a new series of actions".

[^2]: See (pseudo-)Longinus, [_On the Sublime_ 25.1](http://data.perseus.org/citations/urn:cts:greekLit:tlg0560.tlg001.perseus-grc1:25): Ὅταν γε μὴν τὰ παρεληλυθότα τοῖς χρόνοις εἰσάγῃς ὡς γινόμενα καὶ παρόντα, οὐ διήγησιν ἔτι τὸν λόγον, ἀλλ̓ ἐναγώνιον πρᾶγμα ποιήσεις. (Loeb translation): "If you introduce events in past time as happening at the present moment, the passage will be transformed from a narrative into a vivid actuality." See also Longacre and Levinsohn (1977: 109) on the historic present at narrative peaks.

[^3]: Rijksbaron (1984: 22-24) cites the messenger speech from _Medea_ and the Gyges story in Herodotus. In the former, Glauke puts on her new clothes and crown in aorists, but the messenger switches to the historic present when she does up her hair and parades through the palace. In the latter example, Kandaules' wife sees Gyges leaving the bedroom in the historic present. Rijksbaron incorrectly identifies this as the only historic present in the Gyges narrative.

Other theories of the historic present, besides the traditional vividness explanation, have been proposed. Perhaps the most intriguing and controversial is Paul Kiparsky's conjunction reduction theory. Kiparsky set out specifically to refute the idea that "the narrator...wished to convey to the listener the dramatic feeling of being an eyewitness." Instead, he insists on "the impossibility of adequately characterizing the so-called historical present on a semantic basis alone. Rather, a syntactic solution is called for." (Kiparsky, 1968: 33) Thus far, I agree with Kiparsky, for all data point to a broader function for the historic present than increased vividness. But then comes the (supposed) linguistic knock-out blow.

> Everything points to \[the historic present's] being an underlying past tense, and its conversion into the present tense in the surface structure must be governed by a syntactic rule, evidently some form of conjunction reduction, which optionally reduces repeated occurrences of the same tense to the present...Schematically the sequence ..Past...and...Past... is reduced to ...Past...and...zero..., and since it is the present which is the zero tense, the reduced structure ...Past...and...zero... is realized morphologically as ...Past...and...Present....\
> (Kiparsky, 1968: 33-5)

Kiparsky then adduces some examples from Sanskrit and Old Irish to show that in Indo-European, such conjunction reduction occurred from past to injunctive.[^4]

Avoiding this diachronic issue, I will try to determine whether conjunction reduction is (synchronically) valid for Herodotus. Unfortunately for Kiparsky's tidy theory, Herodotus offers many examples to refute conjunction reduction. Saul Levin (1969: 386) presents us with the refutation _par excellence_ of conjunction reduction.[^5]

[^4]: The injunctive is the term for Indo-European forms "which in effect neutralize the verbal categories of tense and mood, expressing only person, number, and voice." (Kiparsky, 1968: 36)

[^5]: Ironically, Levin was writing to strengthen Kiparsky's case, but one of his first examples does the exact opposite. Levin (1969: 386) justifies this sentence by saying that "such usages of the present form have been recognized by grammarians of modern times to have no connotation of drama or vividness." Granted, this is a good refutation of vividness, but does that mean that conjunction reduction is true? See the discussion of the annalistic present in Chapter Three.

> Δαρείου καὶ Παρυσάτιδος <ins>γίγνονται</ins> παῖδες δύο, πρεσβύτερος μὲν Ἀρταξέρξης, νεώτερος δὲ Κῦρος.\
> Two children of Darius and Parysatis <ins>are born</ins> — the elder, Artaxerxes; the younger, Cyrus.\
> ([Xen. Anab. 1.1.1](http://data.perseus.org/citations/urn:cts:greekLit:tlg0032.tlg006.perseus-grc1:1.1.1))

Since this is the first sentence of the _Anabasis_, there is no opportunity for conjunction reduction, yet we find a past event (the birth of Artaxerxes and his brother) told in the present tense. Within Herodotus, we find not only the sequence past-conjunction-present but present-conjunction-past. Surely a language cannot eliminate information as redundant before it appears! We may illustrate this point with a few examples.

> αὐτός τε τῷ ἑταίρῳ, τοῦ ἦν ἡ γυνὴ αὕτη, <ins>ὑποδέκεται</ins> δωτίνην δώσειν τῶν ἑωυτοῦ πάντων ἕν, τὸ ἂν αὐτὸς ἐκεῖνος ἕληται, καὶ τὸν ἑταῖρον ἑωυτῷ ἐκέλευε ὡσαύτως τὴν ὁμοίην διδόναι\
> He <ins>promises</ins> to give to his comrade (whose wife she was) any one thing out of all he owned, whatever Agetus might choose, and he bade his comrade make him the same promise.\
> ([Hdt. 6.62.1](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:6.62.1))

> καὶ τοῦτο μὲν ἐν τούτῳ τῷ πόνῳ ὁ πολέμαρχος <ins>διαφθείρεται</ins>, ἀνὴρ γενόμενος ἀγαθός, ἀπὸ δ᾽ ἔθανε τῶν στρατηγῶν Στησίλεως ὁ Θρασύλεω\
> In this labor Callimachus the polemarch <ins>is slain</ins>, a brave man, and of the generals Stesilaus son of Thrasylaus died.\
> ([Hdt. 6.114.1](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:6.114.1))

> τῶν δὲ κατύπερθέ οἱ προγόνων τὰ οὐνόματα εἴρηται ἐς Λεωνίδην: ὡυτοὶ γάρ σφι τυγχάνουσι ἐόντες. <ins>ἀποθνήσκει</ins> δὲ Μαρδόνιος ὑπὸ Ἀειμνήστου ἀνδρὸς ἐν Σπάρτῃ λογίμου...\
> I have named the rest of Pausanias' ancestors in the lineage of Leonidas; for they are the same for both. As for Mardonius, he <ins>is slain</ins> by Aeimnestus, a Spartan of note...\
> ([Hdt. 9.64.2](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:9.64.2))

The first passage comes from the very beginning of a narrative, so there is no past tense from which to reduce. The second passage is drawn from the middle of a narrative, but the parallel structure assures us that if conjunction reduction were to occur at all, it would have to be in the reverse order.[^6] In the third passage, we see that narrative and not syntactic context determines the use of the historic present, for the present of Herodotus' aside is directly followed by the historic present of Mardonius death. Were the historic present simply a zero-tense, zero-aspect formation, we would expect an aorist after the aside in order to resume the narrative in the past. The historic present suffices to indicate the resumption of the story. In the narrative contexts, where past, completed events are the norm, the past perfective (arist) forms are unmarked whereas imperfective (present, imperfect) forms are marked (Comrie, 1976: 120-22; Fleischman, 1990: 54-5). These narrative contexts, therefore, rather than universal syntactic laws, provide the foundation on which any theory of the historic present must be built.

[^6]: Compare Comrie (1985: 104) on verbs with neutralized tense: "its time reference is simply location at the time established by the immediately preceding sentence-internal context; the requirement that there be a preceding sentence-internal context excludes this category from occurring sentence-initially," By Comrie's reasoning, therefore, the present in the second example cannot be a result of conjunction reduction.

Before we let narrative enter the fray, we must outline general linguistic theories of syntax and narrative and their application to Herodotus. The results of pragmatic linguistics may be summarized by the remark of Longacre and Levinsohn (1977: 107).

> Significant chunks of the whole verb system of a language can be classified in terms of functions in discourse and paragraph. Thus, each discourse type has its favored tense/aspect for the mainline of its development and other tense/aspects for other functions. The occurrence of a given tense/aspect immediately tells us something about the classification of the text as to discourse type, provides cohesion throughout that text, and may tell us roughly what part of the discourse or paragraph we are looking at.

We should note two points of this analysis. Firstly, the pragmatic functions of tense and aspect operate at both the micro- and macro-level, and, secondly, the interpretation of a given tense or aspect cannot be divorced from its context. Verb forms do, of course, bring a certain amount of "baggage" to a context, for part of the shock of a historic present lies in finding a tense, whose normal reference is the moment of discourse, referring to past narrative time. These expectations for the present tense are, nevertheless, built up by the multitude of sentences in which it does refer to the moment of discourse. We should say, then, that a tense or aspect possesses an inherent meaning defined by its general usage but that an occurrence of that tense or aspect in discourse reserves the right to alter its meaning for pragmatic effect.[^7]

[^7]: Comrie (1985: 26) phrases this give-and-take of general meaning and context thus: "It is...possible that a tense will receive particular interpretations in particular contexts, but these are always explainable in terms of the interaction of context-independent meaning and context, and do not therefore form part of the meaning of the tense category in question." Of course, Comrie's "context-independent meaning" is defined in a particluar language by context. Even if there be a language-independent notion of discourse time reference, the context of many sentences must be consulted to determine that the morphological present tense in Greek can have discourse time reference.

For the purposes of narrative analyses, an important pragmatic concept is the distinction between foreground and background. As Hopper and Thompson (1980: 280) define them, foreground "supplies the main point of the discourse," whereas background "merely assists, amplifies, or comments on it. Linguistic features associated with the distinction between foreground and background are referred to as grounding."[^8] How do languages indicate the distinction between background and foreground? Hopper (1979: 213-6) cites languages that accomplish this with separate particles for foreground and background passages, but he also observes that "it is quite common for languages to realize the foreground-background distinction with specialized verb morphology." He goes on to consider the evidence of French and Russian to associate perfective aspect with foreground and imperfective aspect with background. Hopper and Thompson (1980: 284-8) consider not just aspect but nine other features that indicate narrative grounding. These features are: participants, the tendency for foregrounding to be associated with transitive verbs (two participants) and for backgrounding to be associated with intransitive verbs (one participant); kinesis, a change of place or condition in the foreground; punctuality, the distinction between single actions (foreground) and lasting or iterative actions (background); volitionality, the expression of wishes or intentions that predominates in the foreground; agency, the presence of a human actor in the foreground; mode, the predominance of indicative verbs in the foreground; affirmation, the absence of negations in the foreground; affectedness, the greater change that the object undergoes in the foreground; and individuation, the tendency for foreground objects to be definite and referential rather than abstract. Most of these criteria are difficult to validate mechanically, but, with the proper morphological information, aspect, punctuality, and mood are easily determined.

[^8]: What Hopper and Thompson refer to as "foreground" and "background," Longacre and Levinsohn (1977: 107) call "on-eventline" and "off-eventline" or "progression" and "digression."

Let me make a brief digression on the nature of aspect, for this linguistic concept will be important in my analysis of the historic present. Hopper and Thompson's categories distinguish between aspect and punctuality, where the former represents the telic/atelic spectrum and the latter represents various degrees of punctuality or durativity. Telicity is the degree to which an action points toward some final goal, regardless of the amount of time that that action takes. Comrie (1976: 44) gives a good example of this antithesis with the two sentences, 'John is singing," and 'John is making a chair." If at any point in singing, John breaks off, we may truthfully say, 'John has sung," but if John stops working on the chair before it is completed, we cannot say, "John has made a chair." The former action is therefore atelic and the latter telic. Note that both actions are morphologically imperfective; telicity applies only at the level of semantics. Similarly, punctuality is a semantic concept associated with aspect. A punctual action is one that occurs at a moment in time and is not repeated whereas a durative action is one that occurs over a span of time. Note that punctual actions may be represented by imperfective verbs, but that their sense is then iterative. "She coughed" is a punctual event, and "She is coughing" is a series of punctual events represented by an imperfective aspect. In analyzing narrative grounding, we must pay attention not only to perfective and imperfective aspect but also to the telicity and punctuality of situations. Telicity and punctuality are harder to characterize than pure syntactic aspect, but examination of the inherent meanings of verbs can provide substantial information.

It is an easy step to apply these linguistic principles to the study of Greek texts. In past narrative, imperfective aspect is represented by the imperfect tense and perfective aspect by the aorist indicative and the pluperfect. Although authors tend to employ imperfective verbs in backgrounded passages, the pluperfect presents an exception. In conventional analysis, the pluperfect possesses the temporal role of "past of the perfect" (Smyth, 1956: 435) or "past-in-the-past" (Rijksbaron, 1984: 37). This role can be expanded to include "explanatory background situations that took place before the events of the current narrative plane" (Fleischman, 1990: 24), but even this definition is too restrictive. I have argued in an earlier paper that, while a verb in the pluperfect usually indicates background, it need not represent an event that occurred before the events around it in the narrative.[^9]

[^9]: My junior tutorial paper in Classics, "The Pluperfect and the Narrative Strand of Herodotus," presented the view of the pluperfect as a pure backgrounding marker. It is a good example of what can be done with a simple morphology-driven word-search program, without the benefit of the programs I have written for this thesis.

Albert Rijksbaron's article, "The Discourse Function of the Imperfect," provides an impressive example of the power of narrative grounding theory applied to Greek — to Herodotus, no less. Rijksbaron argues that the Greek imperfect tense provides a "time anchor" in the background which situates all the foregrounded aorist events in time. This anchoring process occurs not just at the level of the sentence but at the level of book-length narratives, and Rijksbaron demonstrates this with a detailed tense map of the Scythian expedition (Hdt. 4.1.1-5.23.1). With great regularity, imperfect verbs delimit ("anchor") the various sections of this _logos_, for in addition to structuring a narrative, the imperfect virtually defines it (Rijksbaron, 1988: 249). Aorists and, of course, presents occur quite frequently in non-narrative contexts, but the imperfect almost always indicates a narrative by situating events squarely in the past. Events that follow an imperfect verb are thus indicated as also taking place in the past.[^10] The nub of Rijksbaron's argument is that the imperfect, while is does represent incomplete actions, serves the equally important discourse function of introducing and structuring narrative.

Such a description of the imperfect tense in terms of narrative structure leads us to ask similar questions about the historic present. What are its syntactic and semantic characteristics? How does it fit into the framework of narrative grounding? What functions does it serve in discourse? Before we can answer these questions about historic presents, we must find a way to locate and classify them efficiently.

[^10]: One may say that this is a theory of "narrative reduction." One imperfect "time anchor" serves to locate a series of events in the past, and the following aorists and presents need not duplicate this "pastness" infortation.


<!-- ## Chapter Two -->
## Resources and Methodology

On an abstract level, the three resources necessary for linguistic computing are a text base, a means for generating information about that text base, and a means for interpreting that information. Obviously, these needs are interdependent in numerous ways.

For this research, I have used the textual materials accumulated and tagged by the Perseus Project and the Morpheus morphological aralyzer. To tie these resources together, I have written tagging, scanning, and data analysis programs, primarily in the C language, but also in Unix utilities such as lex and awk. I chose C for two reasons. Firstly, it allowed me to scan through the entire text of Herodotus in about five minutes, thus allowing me to ask and answer questions about a particular textual feature in a short time. Secordly, I had already, as a part of my duties at Perseus, written quite a substantial library of lex code, which is an extension of the C language; it was more economical and elegant to link this existing code with a compatible language.[^11] All the programs that I wrote served essentially the same function: scanning throush the input text and detecting a specified syntactic pattern. In the following pages, "the program" is shorthand for any version of this scanning program.

[^11]: What lex does, in essence, is to build regular expression and finite automaton capabilities into C. One writes input to lex as a series of regular expressions, perhaps with some specified state conditions, and a series of C routines to execute when the input matches those regular expressions. Regular expressions are patterns for matching text. For example, one uses the expression `a*b*` to match any number of a's followed by any number of b's. The vagaries of regular expressions are not, however, important here. The lex program itself acts as a preprocessor and generates a C program that scans the input, matches it against the regular expressions, and performs the user-specified C routines. One may insert a routine that adds one to a section counter every time the lex program finds a `<SECTION>` tag. Most of my programs were written in Vern Paxson's lex dialect, flex 2.1.

Thankfully, one of the most arduous tasks in any computational linguistic research has been completed for Herodotus and other classical Greek historians. The Perseus Project possesses on-line texts of the vast majority of ancient Greek literature (in the original and in translation) down to the death of Alexander the Great, along with a good deal of later literature. The Greek text itself is represented in ASCIl with formatting conventions as in Beta Code.[^12] All this text has been tagged for basic structural and content features in the Standard Generalized Markup Language (SGML).[^13] In general tags are ma:kers inserted in the text in order to delimit certain structural features. For example, a section that begins with `<SECTION N="1">` would end with `</SECTION>`. Since SGML is rigorously hierarchical in the allowed order of tags, one can determine all the tags containing the current piece of text simply by knowing the tag that most immediately contains the current text. The basic structure of a book of Herodotus, or of any author who is referenced by `<book>.<chapter>.<section>` is as follows:

```
<DIV1 TYPE="book" N="1">
<DIV2 TYPE="chapter" N="1">
<SECTION N="0"> ... </SECTION>
<SECTION N="1"> ... </SECTION>
...                 </SECTION></DIV2>
<DIV2 TYPE="chapter" N="2">
...
<DIV2 TYPE="chapter"N= "216">
...
<SECTIONN"4>    ... </SECTION></DIV2></DIV1>
```

[^12]: For the sake of readability, all Greek in this paper has been converted into standard minuscule type. In reality, all the programs described herein processed the Greek texts in their Beta Code representation. Beta Code represents Greek with the standard US character set; the correspondences are intuitive with the following exceptions.\
  h η\
  c ξ\
  w ω\
  q θ\
  y ψ\
  v ϝ\
  A slash ("/"), represents an acute accent, a backslash ("\\") a grave accent, an equals sign represents a circumflex, a vertical bar ("|") an iota subscript, and left and right parentheses represent rough and smooth breathings, respectively. An asterisk represents a capital letter and an apostrophe indicates an elision. Thus, the opening sentence of Herodotus in Beta Code would be: `*(hrodo/tou *(alikarnhsse/os i(stori/hs a)po/decis h(/de, w(s mh/te ta geno/mena e)c a)nqrw/pwn tw=| xro/nw| e)ci/thla ge/nhtai, mh/te e)/rga mega/la te kai\ qwmasta/, ta\ me\n *(/ellhsi ta\ de\ barba/roisi a)podexqe/nta, a)klea= ge/nhtai, ta/ te a)/lla kai\ di' h(\n ai)ti/hn e)pole/mhsan a)Ilh/loisi.`

[^13]: Not only are the Perseus texts SGML-conformant, but the text tagging team has also tried as far as possible to follow the guidelines of the Text Encoding Initiative for literary material. For general literature on SGML, see Charles F. Goldfarb, _The SGML Handbook_, and Eric van Herwijnen, _Practical SGML_; for more on the TEI and related projects, see _Guidelines for the Encoding and Interchange of Machine-Readable Texts_, Sperberg-McQueen and Burnard, eds.

The tags contained in angle brackets define the various chunks of the text. A section begins with `<SECTION N="section number">` and ends with `</SECTION>`, and analogous tags serve to mark chapters and books.[^14] Note that a section must end — i.e., a `</SECTION>` must be encountered — before a chapter may end, and similarly a `</DIV2>` must come before any `</DIV1>`. This description of the tagging of the structure of texts should make later references to tagging more comprehensible.

[^14]: Sections have their own tags named after them, whereas chapter and book are merely attributes of the generic DIV x tags, because of an artifact of Greek prose formatting. All prose authors are divided by section, but not all possess chapter and book divisions. Thus the DIV1 for the text of the orators is of type "speech".

Let me digress for a moment about what information we can derive from a classical text. When Herodotus wrote his _Histories_, all letters were upper-case and there were neither word breaks nor diacritical marks nor pur.ctuation. An entirely naive study of Herodotus, therefore, would not use any riodern typographical information. Nevertheless, I have used the word breaks and diacriticals as they appear in the Godley's Loeb text (1926), for reconstructing them all _de novo_ is beyond the scope of this thesis. On the other hund, l ignore the editorial information conveyed by punctuation and structural breaks such as books, chapters, and sections. I do not, for example, conclude that Herodotus ends his sentences wherever a full stop appears in the text, nor that sentences in parentheses may automatically be treated as background material.[^15] This is not to say that this information is not usually accurate, but there are enough examples of grammatical constructions breaking the barriers of m.odern punctuation and structural segmentation to justify ignoring these barriers.[^16] From a formal standpoint, therefore, I will treat the text of Herodstus as an uninterrupted stream of words.

[^15]: A study of the sentences that the editor has parenthesized is not totally with. out merit, especially as it is trivial to perform once the text is on-line.

[^16]: We find, for example, a string of historic presents crossing the boundary between books five and six.

Even with the tagged text of Herodotus and other authors on-line, one cannot work seriously on Greek syntax without considering the complex problem of Greek morphology.[^17] For my research, I have used the Morpheus morphological analyzer developed by Gregory Crane, which was later incorporated into the Perseus Project.[^18] Obviously, since the corp us under consideration is fixed, one could imagine a finite solution to mor hological analysis, consisting of a database containing all the unique strings in Greek and their parses. The corpus, nevertheless, is so large that creating such a database would be virtually impracticable. Morpheus relies, instead, on generating strings from its tables of stems and affixes and a set of rules for their euphonic combination. This representation of morphology is not only more concise than a table of forms but also infinite, for all practical purposes, in its generative powers.[^19] In fact, Morpheus recognizes strings by generating the possible forms based on its current knowledge of the stem and endings.[^20] Since we are interested primarily in recognition of existing morphemes, many of these generative capabilities are superfluous.

[^17]: Greek morphology may be classified into two general subsystems: verbal and nominal (including articles, pronouns, adjectives, and nouns). Nominals have four distinct cases: nominative, genitive, dative, and accusative, and a fifth case, the vocative, which is most often identical to the nominative. There are classes of number, singular and plural, and a third, the dual, which is much rarer. For non-nouns, forms for masculine, feminine, and neuter exist although many adjectives only display masculine/feminine and neuter endings. Verbs may have up to seven tense in the indicative mood and five tenses in the subjunctive, opiative, infinitive, imperative, and participial moods. The aorist and future tenses exhibit active, middle, and passive voices, and all other tenses exhibit active and medio-passive voices. Participles are also declined as adjectives. Dialectical variations may be ignored for most authors, with the notable exception of Homer. Most of the overproductivity of any Greek morphological system will be generation of forms not in the appropriate dialect.

[^18]: See Crane's "Generating and Parsing Classical Greek" (1991) for more information on Morpheus. 

[^19]: As an example, Morpheus would, if allowed, generate an infinite number of verbs by adding more and more preverbs to the stem.

[^20]: Morpheus operates by taking the input string, and strips it of all possible prefixes (verbal augment, preverbs, crasis, etc.). It then scans through the string from the end and tries to make the characters seen so far match with its table of endings. If a match is found, the rest of the string is matched against the table of stems while trying all combinations of connecting vowels. Morpheus stops when all possible endings of the string have been examined.

One important weakness of Morpheus remains: it generates analyses of words taken out of context. About 37% of the unique forms in Herodotus can be parsed in more than one way. This ambiguity occurs less between different parts of speech (as in English) as it does between different forms of the same word.[^21] The verb ἦγον, for example, may be the first person singular active imperfect, or the third person plural active imperfect of ἄγω. Verb tenses, however, are not as subject to ambiguity, and we merely have to deal with the rare cases where what is actually a nominal could be parsed as a verb.[^22] In later versions of my scanning program, a great many of these cases were eliminated by the process of article-binding. When, in scanning the text, the program reaches an article, it notes the article's gender, number, and case. The program determines for each of the four successive words if that word could be parsed as a noun or adjective with the same gender, number, and case as the article, and if so, all other parses of that word are ruled out. This simple context-informed feature is one of the most useful additions that I wrote to my program.

[^21]: Steven DeRose, (unpublished dissertation, Brown, 1988). Another interesting result of this dissertation is that although English and Greek lexical ambiguity may differ qualitatively, the rate of ambiguity for a given amount of text in either language is constant.

[^22]: The most exasperatingly common examples of nominals parsed as verbs were ἄλλα, parsed as an apocopic form of ἀναλάω, and ἄνδρα, parsed as a form of ἀναδράω. Later versions of my program did not admit forms where the verbs had suffered apocope (dropping of the final preverb vowel before a consonant).

My scanning program itself exists in two principal versions, a simple one in lex and a more complex one written in C. Most interestingly, the lex program is not significantly inferior in performance to its more sophisticatud descendant. On the other hand, the lex program requires that the text input file receive more elaborate preparation than would be necessary for the C program, but in either case, some preliminary preparations are identical.

First, the text of Herodotus is tokenized into words and sorted, and all duplicate strings are removed. This list of unique strings in Herodotus (with the exception of proper nouns[^23]) is run through Morpheus. Each of the unique strings is also given a numerical key. For the general C program, the text was tagged so that each word was marked with its corresponding key; for example, each occurrence of ἥδε in the text would be marked
```
<W K="11072">h(/de</W>.
```
The number in quotation marks is the unique key for this word. For the lex program, I used a more direct tagging system. All the words that could be parsed as verbs were tagged with tense, mood, and voice information, with a slash separating different possible parses. The verb λέγουσι would be tagged
```
<V P="pres.ind act/pres.part.act*>le/gousi</V>.
```
[^24]
The information in the quotation marks indicates that this word may be parsed as a present active indicative verb or as a present active participle.

[^23]: Thanks to some precautions taken by the Perseus text tagging, proper nouns are easily identifiable. In a normal Greek text, both proper nouns and the first words of paragraphs are capitalized. A list of capitalized words was produced for each text, and a human editor went through this list and deleted all proper nouns. A program then decapitalized all the remaining words. This scheme allows one to confidently search for all occurrences of, say, the river Ἄξιος without finding all occurrences of the common adjective ἄξιος.

[^24]: Both of these tagging processes were handled by a series of awk and lex pregrams. Basically, a list of words in Herodotus was produced such that the appropriate words were tagged (verbs in the one case and all non-proper nouns in the other). A lex program then reassembled the text of Herodotus with the tagged words.

The disadvantages of tagging only verbs are obvious. Without information on the words around a verb, one cannot use contextual evidence to determine which parse of a verb is correct or if the word is, in fact, a verb at all. Nevertheless, verb information is all one really needs to search for historic presents in a text. Later versions of the scanning program that took contextual information into account succeeded less in finding new occurrences of the historic present than in filtering out the noise that comes from Morpheus, which in many cases generates input that is inappropriate for the context. We gain a subtler advantage by using the keyed version of the text instead of the verb-tagged version: we are able to change the queries we make without changing the input. If the text is only tagged for tense, mood, and voice, one r.ust reconstruct the text from the ground up if one wants to ask about the person and number of a verb as well.

The program that scans for historic presents acts essentially like a pattern matcher, which is why lex works so well for the purpose. The pattern that defines a historic present is this: over the set of indicative, third-person verbs, look for a string of past tenses (aorist, imperfect, or pluperfect) followed by a string of presents followed by a past tense. In other words, make sure that you are in a past context by seeing a string of past verbs; also make sure that you switch back to the past after having seen a certain number of present verbs. If the string of present verbs is too long, we may assume that the narrative is no longer historical, but is instead an ethnographical or geographical, or that the authorial voice has given way to direct speech. The two parameters in this definition of the historical present are therefore the number of past tenses that is necessary to establish a historical context and the maximum number of presents that can occur without switching out of a historical context. From some preliminary trials, I determined that a past narrative context could be established by as few as two past verbs, and that any more than four presents in a row were likely to indicate a non-narrative context.

Both the lex and the C scanning programs produce the same output: a list of verbs in the historic present with the reference number at the beginning of the line. There may be more than one word per line if there are two or more historic present verbs in a row. This output can then be processed in a variety of ways. The most common procedure is to search the list for all occurrences of a single verb. This search can be done with simple string matching whereby someone looking for all occurrences of _pémpô_ would search for `pe/mp`, or with more elaborate lemmatized searches. To find all forms of, say, _didômi_, one searches the Morpheus output for that word and then uses the results to searci the historic present output file. Alternatively, one can reverse the procedure for lemmatized searches and produce lists of the number of times a lemma is used, regardless of what form it takes. Thus, if _teleutâi_ occurred in the historic present list 15 times and _teleutôsi_ appeared 5 times, the entry in this lemmatized list would read `teleuta/w: 20`. With complete morphological information, one can calculate the ratio of historic presents to aorists, imperfects, or any combination of tenses and draw conclusions of the relative frequencies of various verbs.

The C scanner can also produce information on clause government. When the scanner comes across a subordinating conjunction, it enters a special "subordinate" state that lasts until it sees a verb. One can use these data on subordinate clauses to gain insight into narrative grounding since backgrounded text tends to be subordinated more often than foregrounded text.[^25] Here again, we can see which verbs are more likely to occur in subordinate clauses.

All of these tools are useful only insofar as they are used for the interpretation of the text. Any results turned up by the programs must be tested for validity within the context of the narrative and quantitative data must be shown to be statistically significant.[^26] What these tools do allow us to do is to ask many questions, to have those questions answered sooner, and to have the time to refine and re-ask the questions. Almost all of the results to follow in the next chapter are derived from the output of the programs described here; but without any idea of how the Greek language works, without any theory of narrative, these data would make little sense. These programs simply allow us to test a theory of language in days where it once would have taken years.

[^25]: Of course, the paratactic style of Herodotus means that backgrounded information is not subordinated much of the time.

[^26]: The test used most is this thesis (and in fact by humanists in general) is the chi-sqared test of independence. This test's most common application is for determining if a correlation between two variables is significant or merely random. If we want, therefore, to \[The rest of this footnote seems to have been suppressed by the word processor due to the chapter break. —ed.]


<!-- ## Chapter Three -->
## The Historic Present and Narrative Grounding

Before we draw any general conclusions about the historic present, let us examine its use in narrative contexts. The Gyges story, one of Herodotus' most famous tales, provides three examples of the historic present.[^27] The first occurs when Gyges the unwilling voyeur is glimpsed by Candaules' wife.

[^27]: The translations of Herodotus and other ancient authors are those of the Loeb edition. For the sake of convenience, I have changed verbs that translated a Greek historic present into an English historic present. Both the Greek and English historic presents are underlined.

>  καὶ μετὰ ταῦτα αὐτίκα παρῆν καὶ ἡ γυνή. ἐσελθοῦσαν δὲ καὶ τιθεῖσαν τὰ εἵματα ἐθηεῖτο ὁ Γύγης. ὡς δὲ κατὰ νώτου ἐγένετο ἰούσης τῆς γυναικός ἐς τὴν κοίτην, ὑπεκδὺς ἐχώρεε ἔξω, καὶ ἡ γυνὴ <ins>ἐπορᾷ</ins> μιν ἐξιόντα.\
> His wife followed presently, and when she had come in and was laying aside her garments, Gyges saw her; when she turned her back upon him to go to bed, he slipped from the room. The woman <ins>glimpses</ins> him as he went out.\
> ([Hdt. 1.10.1–2](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:1.10))

The second historic present occurs when Candaules' wife confronts Gyges with his transgression and gives him the choice of treason or death.

> οὔκων δὴ ἔπειθε, ἀλλ᾽ ὥρα ἀναγκαίην ἀληθέως προκειμένην ἢ τὸν δεσπότεα ἀπολλύναι ἢ αὐτὸν ὑπ᾽ ἄλλων ἀπόλλυσθαι: <ins>αἱρέεται</ins> αὐτὸς περιεῖναι.\
> But when he could not deter her, and saw that dire necessity was truly upon him either to kill his master or himself be killed by others, he <ins>chooses</ins> his own life.\
> ([Hdt. 1.11.4](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:1.11.4))

The final working out of the plan to kill Candaules is capped with a third historic present.

> ὡς δὲ ἤρτυσαν τὴν ἐπιβουλήν, νυκτὸς γενομένης ... εἵπετο ἐς τὸν θάλαμον τῇ γυναικί, καί μιν ἐκείνη, ἐγχειρίδιον δοῦσα, <ins>κατακρύπτει</ins> ὑπὸ τὴν αὐτὴν θύρην.\
> When they had prepared this plot, and night had fallen, Gyges followed the woman into the chamber... She gave him a dagger and <ins>hides</ins> him behind the same door.\
> ([Hdt. 1.12.1](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:1.12.1))

Note that these historic presents do not occur, as some would have it, at the peak of the narrative; rather, they describe events which are decisive in terms of the later turns of the story.[^28] As for the syntactic context of these historic presents, it is enough for now to observe that the verbs immediately preceding them are in the imperfect. This juxtaposition throws the historic present into higher relief than an aorist-present combination would have.

[^28]: De Jong (1991: 41), in her analysis of the historic present, draws a distinction between important or decisive actions and actions marked by the narrator as important or decisive. In the case of Herodotus (as opposed to de Jong's Euripidean messengers), this distinction is not very useful. The very presence of an event in the _Histories_, let alone that event's relative importance or decisiveness, is determined by the will of the narrator.

Nevertheless, Herodotus does not use the historic present solely as a marker for isolated events. The massacre of the Magi by Darius and his fellow conspirators provides many examples of the historic present used, it seems, purely for the sake of vividness. The conspirators enter the palace without opposition, but when they are confronted by the eunuch messengers, they draw their knives and simultaneously start the killing and the historic presents.

ทนUVETO Kai TOUTO LEU

'iaopeveas Tou boBanorNHE STMEYE OUTEDCE TOGUCTiTE

TOUTOUS SE SEDKOEELK O EUEETITTONEL TEN ETTO SUO,

KGIÉTUXÉ KWS TOU MÁYOU. ¿nOKTEÍVaVTES bÈ TOÙS MáYoUS Kai

aoaMoves aUTTE KEAd, TOU HETwariasTผนOบ

MEÍTOVEL Kai dUvaGins ElVEKEV Kai pUraKis ths aponórios...

These, giving each other the word, and drawing their knives, stab the eunuchs who barred their way,...One rushes to take down a bow, the other went for a spear....but the other defended himself with his spear and wounds Aspathines in the thigh and Intaphrenes in the eye...So one of the Magi wounds these; the other flces... Two of the seven rush into the room with him, Darius and Gobryas...So Darius complying stabbed with his knife and somehow stuck the Magus. When they had killed the Magi and cut off their heads, they leave their wounded there because of their infirmity and for the sake of guarding the acropolis...

(Hdt. 3.77.3-79.1)

This passage, aside from demonstrating a vivid use of the historic present, presents two paradoxes. Firstly, why is Darius' killing of the Magus in the inner room in the aorist, while all other killings or woundings are in the historic present? Secondly, why does Herodotus use the historic present when, after the action is over, the conspirators leave their wounded behind? If w a maintain that the historic present must highlight decisive events, we should ex/ ect a historic present (and not an aorist) in the first case and an aorist or imperíect (and not a historic present) in the second.

Although some may argue that Herodotus employs the historic present arbitrarily, and even unconsciously, that seems not to be the case. Fleischman (1990: 76), writing about oral narrative, observes that "a speaker's use of tenses will not be consistent across multiple retellings of the same story." But Herodotus, where he does in fact present us with parallel stories seems to be consistent in his placement of the historic present. When Cambyses has a dream, which he believes to be about Smerdis, he acts thus:

> πρὸς ὦν ταῦτα δείσας περὶ ἑωυτοῦ μή μιν ἀποκτείνας ὁ ἀδελφεὸς ἄρχῃ, <ins>πέμπει</ins> Πρηξάσπεα ἐς Πέρσας, ὃς ἦν οἱ ἀνὴρ Περσέων πιστότατος, ἀποκτενέοντά μιν.\
> Fearing therefore for himself, lest his brother might slay him and so be king, he <ins>sends</ins> Prexaspes, the most trusted of his Persians, to Persia to kill him.\
> ([Hdt. 3.30.3](http://data.perseus.org/citations/urn:cts:greekLit:tlg0016.tlg001.perseus-grc1:3.30.3))

Cambyses later explains this event to his wise men.

Taxirepa noopwtepa iv riyap avepornin oio our n a

És LoûGa ¿noKtEvÉOvra suépoLv.



Then I feared that my brother would take away my sovereignty from me, and I acted with more haste than wisdom; for it is not in the power of human nature to run away from what is to be; but I, blind as I was, send Prexaspes to Susa to kill merdis.

Considering these and other examples,29 I argue that Herodotus was conscious of his modulation between imperfect, aorist indicative, and historic present. The issue of authorial intent, intent, presents too large a problem to be dealt with here.

Can we thus conclude that the historic present is a generalized authorial tool to be pressed into service whenever a passage calls out for sp acial distinction? Fortunately for the student of style, Herodotus restricts his use of the historic present in two respects. These restrictions may be classified under the broad headings of syntax and semantics. Syntactically, the hi toric present may only be substituted for certain past-tense constructions; semantically, the lexemes in the historic present possess a common thread.

The historic present is, of course, the substitution of a presunt verb for a past one. In ancient Greek, however, there are two normal narralive tenses (the imperfect and the aorist indicative) to only one present tense. As Comrie (1976: 74) points out, "the morphological restriction of overt aspect differentiation to the Past Tense means that a priori there can be no aspect distinction in the narrative present."30 Interestingly, though, in the passages cited above, the historic present invariably stands in for an aorist. Consider, for example, the vertal parallelism of peávEl...Etpáeto in the story of the Magiphonia31 and the obvious perfective

29 Finding parallel passages by hand is tedious, and it is not something that can yet be done reliably by machine. Two examples of parallelism using the historic present may be found in Hdt. 7.163.2 and 7.172.1, and in Hdt. 9.20.1 and 9.39.1. There are undoubtedly more examples of parallel passes bureat is talking about French, but it is obviously applicable to the case of ancient Greek. The interesting difference is that French allows both the imparfait and the passé composé to be mapped onto the historic present, which is not, as we shall see, the case with Greek.

31 Some may object that there is also an imperfect/historic present parallel in this same story: nuÚveto... aíEl. This is an example of Herodotus subordinating one thought to another while



The Historic Present and Narrative Grounding

26

aspect of ai péetal aròs nepteîval at the peak of the Gyges story. Note that the perfective nature of the historic present allows it to represent the pluperfect as well.

XOREÚTEPa. TPÍTW MÈV YÀP ÉTEI MPÒ TOÚTWU EKÚDAS ÉKE AÚNEL TAûTA

MÈU ON TPÍTUÉTET PÓTEPOV ÉYEYÓVEE TOV TÓTE MIV KATEXIVEWV.

But not long after this Miltiades son of Cimon had come to the Cherso.ese, greater difficulties than the present afflictions overtook him. He is driven fron. the country three years before this by the Scythians...All this had happened three years Lefore the matters that now engaged him.

(Hdt. 6.40.1-2)

The parallelism of ¿кфєє!..¿YEYÓve€ is made even more strikir.g by the repetition of the temporal phrase "three years before." The historic present, it seems, does not stand in for one past tense so much as for past per jective aspect. In this conclusion, I differ from Smyth (1956: 422), who states that "Lie historical present may represent either the descriptive imperfect or the nar ative aorist" and with McKay (1974: 250) who asserts that "the historic present commonly occurs in circumstances in which the imperfect would be as appropriate as the aorist or more so."

This dedication of the historic present to perfective, aristie events is not surprising in light of the earlier discussion of narrative grounding: Events told in the historic present, whether for the sake of vividness or decisive.ess, are inevitably on the main thread of the narrative. As has been shown, the aorist indicative is the normal tense for relating events on the main thread, while the imperfect provides the background. Therefore, any verb in the narrative foreground would have to have replaced the aorist. 32 That the historic present

placing them in a coordinate structure. We should better translate this sentence by: "While the other was defending himself with he spear, he wounds..."

32 De Jong (1991: 40) observes that the historic presents in the Euripidean messneger speeches are substituted more often for the aorist than the imperfect.



The Historic Present and Narrative Grounding

27

should be perfective is, of course, contrary to the nature of the present as expounded by most grammarians. Rijksbaron (1984: 1) states that "the present stem signifies that the verbal action continues through a point in time given in context or situation and is, therefore, not-completed (imperfective value)." I would contend that, syntactically and semantically, the historic present is not a present tense at all.33

One of the most striking syntactic properties of the historic present is its aversion to subordinate clauses. Out of the 117 historic presents that de Jong (1991: 185-6) finds in the Euripidean messenger speeches, only two are in subordinate clauses. Wolfson (1982: 41-3) finds no examples in her data of a historic present in a subordinate clause. In Herodotus, 1650 of the historic presents showed up in main clauses and the other 200 in subordinate clauses.

That is to say, 10.8% of the historic present verbs were in subordinate clauses. Of all the remaining third-person present indicatives in Herodotus, 1993 out of 13,773, or 12.64%, were in subordinate clauses. The proportion of of historic presents in subordinate clauses is thus significantly lower than the overall proportion of indicative verbs in subordinate clauses, 34 It is not, of course, as low as the proportions that Wolfson and de Jong report. Since the scanning program is overgenerative, and since most "historic presents" that the program locates in subordinate clauses are, upon examination, spurious, we can say confidently that the proportion of historic presents can only decrease.

If the historic present possesses, syntactically, a perfective aspect, then it also has a semantic propensity for representing telic situations. As noted in the first chapter, main narrative actions tend to be telic since the narrator tells a story

   The classic example of the non-present status of the historic present in Greek and Latin is its treatment as a secondary tense in the Sequence of Moods or Tenses, respectively.
   The chi-squared statistic for these numbers is 5.089, which indicates that the correlation between the historic present and main clauses has at least a 97.5% chance of being significant.




The Historic Present and Narrative Grounding

in order to reach a certain point. As the historic present tends to replace an aorist, we may use the frequency with which an author chooses the historic present over the aorist as a measure of the affinity of a particular verb for the historic present. The verbs that have the greatest (statistically sig.ificant)

proportion of historic presents to historic presents and aorist indicatives are all highly telic verbs: amefbô (answer), teleutáô (die), píptô (fall), pheúg (flee), dídômi

(give), and pémpô (send). The following table lists the raw data, thie ratio of historic presents to historic presents and aorist indicatives, and the chi-squared test statistic. Note that all of the chi-squared statistics are greater than 10.83, the number required for 99.9% certainty of significant correlation.

historic

1hM1

all indicatives

双gu6rstnamm

m152013176251B

ratio of HP to

HP and aor.

0.60

0.59

0.46

0.41

0.39

0.33

0.19

chi-squared statistic

26.81

0m0kmxm

I contend that the common semantic feature of these verbs is telicity. In the case of píptô or teleutáo, we might reason that Herodotus is trying to emphasize a sudden violent action, but then we cannot account for the 48 instances of pémpo in the historic present. This verb expresses an action which is neither sudden, nor violent, nor necessarily "appealing] to the senses" (de Jong, 1991: 39),35



35 One objection that could be advanced to this argument runs as follows. The verb pémpô is in fact inherently imperfective, for it has more in common with the English "to escort" or "to organize a procession" than "to send". I concede that if Herodotus did use pénipô in this fashion, I



The Historic Present and Narrative Grounding

29

Similarly, didômi does not represent a particularly striking action - though it might represent an important one, such as the betrayal of a city. Nevertheless, it is highly telic, for the action of giving culminates in the transferrence of the gift to the receiver.36 We could also, of course, adduce a "special case" explanation for

amebô since there is a widespread opinion that narrators have a tundency to put verbs of speaking in the historic present. 37 Note, however, that no other verbs of speaking — not even légô, the most common — are on this list. Tie explanation, I believe, is that ametbô represents particularly directed, telic speech. The answer to a question is an entity that may or may not be imparted38 and whose delivery moves the rhetoric of the narrative forward. It seems reasonable io assert that verbs with a special affinity for the historic present are telic in nature.

One verb, however, seems to present great difficulties for the theory of the

historic present as a perfective, telic entity. This verb — mêkhanác mai — has one of the most rigid syntagmatic positions of all the historic presents in Herodotus.

It always occurs at the beginning of a narrative (obviously a narrative of plotting) and is always followed by the forward-looking pronoun toiáde. Sume examples will demonstrate the pattern. 39

'AR UÁTTNS MÉA ROL MOLNGELV, UNXaVTOL TOLÁSE•

would have a hard time making the case for a perfective, telic interpretation for this verb. But I have examined all 51 examples of this verb in the historic present. What all instances of pémpô in the historic present show is that some authority — who stays behind — sends a messenger who reaches his destination. There cannot be anything more punctual and goal-directed than that.

   The number of historic presents accorded to dídômi may also be related to the importance of gift-exchange in archaic Greek culture. In that case, we would have to view giving as a timeless cultural moment on a par with birth, marriage, and death (see below).
   Kiparsky (1968: 32): "A curiously pervasive fact is that verbs of saying are especially frequently
But sing the histol prose ity, a my lay do was san lang to the king but was

interrupted" as against "He was answering the king but was interrupted." With regard to the former case, it is fair to say "He managed to speak to the king," but we may not say of the latter case "He managed to answer the king."

39 The other occurrences of mêkhanáomai in the historic present are: Hdt. 1.60.3 (twice), 3.11.2, and

6.62.1. This verb is not used in the present outside of the historic present.



The Historic Present and Narrative Grounding

30

But Thrasybulus, forewarned of the whole matter, and knowing what Alyattes meant to do, plots the following things:

(Hdt. 1.21.1)

SUANEEaE E OTaENTAS KOiTAOYATEN TEDAKPIN TOOTOS

un xavâtas toládE.

He collected partisans and pretended to champion the uplanders, and plans the following.

(Hdt. 1.59.3)

BOPKATOUS CUS KATA MÈU TÒ lO XUPÒY OỦK aLPETOI ElEV, CÓAC SÈ aiDETOÍ,

DOLÉEL TOLÁGE•

Amasis the general of the foot soldiers devises these things. Knowing that Barce could not be taken by force but might be taken by guile, he acts thus:

(Hdt. 4.102.1)

4อ x ตามกินส สาห์บริงขอบ ขล้อ กิบ นกิ cupeein 6 62

He, however, feared detection and had no other way of informing them than plotting the following:

(Hdt. 7.239.3)

In all of these passages, the historic present verb sums up what is to follow

and has much in common with Rijksbaron's introductory imperfect, but whenever Herodotus uses mêkhanáomai, the plot is carried out im.nediately. The second example makes this unanimity of plan and action explit. We may argue, therefore, that mêkhanáomai has a telic - and even an perfective - character that the introductory imperfect lacks. Since a plot is never laid withot.t being executed, we may say that the working out of a plot is itself part of the same

event.

We have seen anecdotal evidence that the historic present is used for highlighting certain parts of a narrative. We have also seen that Herodotus tends to use the historic present with a perfective aspect and in telic situations and that he tends to avoid the historic present in subordinate clauses. The theories of grounding presented in the first chapter cited these features as characteristics of



The Historic Present and Narrative Grounding

31

narrative foreground, and indeed, it is this functional framework that seems best to explain the uses of the historic present.

Narrative background, as Rijksbaron has demonstrated, is represemted by the imperfect tense. Although parenthesization is editorial, it can still give us a good idea of the kinds of verbs that represent backgrounded everts. Of the 104 passages in parentheses in Herodotus, there are 17 aorist indicatives, 43 imperfects, 49 present indicatives, seven future indicatives, four perfect indicatives, and six pluperfects. Compare this to the 8200 aorist indicatives and 17,243 imperfects in Herodotus as a whole. Thus 25.75% of the aorists and imperfects in the parenthesized passages are aorists whereas this proportion is 32.23% for all of Herodotus. More importantly for this study, all of the present indicative verbs in parentheses refer to the time of the narrative, not the time narrated. If we say that passages in parentheses are by definition backgrounded, it is significant that no historic presents appear in these passages.

Before I proceed, however, I must deal with a general obje tion to the theory of the historic present as narrative foreground. As I mentioned in my discussion of the story of the killing of the Magi, Herodotus does not always employ the historic present for the peak of a narrative even when he uses it extensively elsewhere in that same narrative. How is it that the historic present, which is normally used for marked, foreground events, is not use i for the most important event of the story? Fleischman (1990: 77) explains that the high points of narratives "constitute a marked discourse context in which the markedness relationships normally operative in a text predictably reverse." De Jong (1991:

41) theorizes that the alternation between historic present and aorist, even at the high points of a narrative, is a case of simple variatio. These explanations ignore the possibility that there could be less correlation between the narrative foreground and narrative peak than has been postulated. Nothing prohibits an



The Historic Present and Narrative Grounding

32

author from placing the formal "climax" of a story more in the background than other events. Herodotus wants us to be impressed when the fornerly passive Gyges decides to kill Candaules and not so much when he actually carries out the deed. He wants the bloodbath of the Magiphonia to be more meriorable than how it actually ends.

As we have seen above, a tension exists in the use of the historic present

between the inherent character of the verb and the narrative func.ion it serves.

Some verbs, however, possess denotations that are particularly u. eful for delimiting and clarifying narrative structure. One most importart class of these verbs relates to rites of passage, "significant moments in a person's life such as birth, wedding, and death" (Rijksbaron 1984: 24). Although von Tritz (1949: 191) asserts that in these situations "no dramatic effect can possibly be intended," it is

difficult to dismiss so lightly the weight of the matters recounted by such verbs as tíktô (to give birth), gaméô (to marry), and teleutáô (to die, when applied to a person). Having examined all of the occurrences of these three verbs in Herodotus, I believe that this use of the historical present has in certain cases become so institutionalized as to lose its particular emotional effet and is employed instead for structural reasons.

The birth of a royal child is, of course, a momentous event in a monarchy, especially when the succession is contested. To describe how Cle menes came to the Spartan throne, Herodotus describes his birth.

AvaEavpiEns EV O AEOVTOS OUKEEL TEPLEV EBaOiAEVE

GANO ETETENEUTHKEE, KAEOMEUNS GE d AVaEavEpiGEN ETXE Tทุบ

BaoiAninv, ou kar' avSpayaBiny oxwv anAd kard yEvos…xpovou 6E ov

HOLLOU BLEABOVTOS H EOUOTEDON EMEABOUEC YUUn TiKTEL TOV 6ท

KREONÉVEA TOÚTOV.

At Sparta, Anaxandrides the son of Leon, who had been king, was now no longer alive but was dead, and Cleomenes son of Anaxandrides held the royal power. This he had won not by manly merit but by right of birth...[A description follows of the barrenness of



The Historic Present and Narrative Grounding

33

Anaxandrides' first wife and his coercion by the ephors into marrying a second wife.] ...After no long time the second wife gives birth to Cleomenes.

(Hdt. 5.39.1-41.1)40

Equally momentous are the circumstances, told in an aside, of Pe. icles' birth.

ทีuvoKnoaTE EaveinTe TApiopovos kai yuos oioa E0062

6v TnvA.

ESOKEE 6E NEOVTA TEKEV, Kai LEr' bAiyas กuipas LitE

Перскла Eaveinnw.

She [Agariste] was married to Xanthippus son of Ariphron, and when she was pregnant she saw in her sleep a vision in which she thought she gave birth to a lion. In a few days she bears Xanthippus a son, Pericles.

(Hdt. 6.132.2)

When Cleomenes slanders Demaratus on account of the circumstances of his birth, Herodotus inserts a long digression on the birth of Demartus that ends

thus:

อบTH LEบท InuTpiEnu EonyayEroyuvaira dApiotav, tav BeurEpnu

In this way Ariston married his third wife, after divorcing the second une. But his new wife gives birth to Demaratus too soon, before ten lunar months had y assed.

(Hdt. 6.63.1)

I shall examine the narrative context of these examples in more d. tail below. For now, let it be noted that all of these births are in fact presented as turning-points.



40 Right after this passage, in 5.41.3, when the first wife finally does give birth, there is an example of what could be conjunction reduction if, in fact, there were a conjunction present. The historic present verbs govern the verb in the aorist.

RSE WEETEKE AWpLEa iBEws IOXEL AEWVinv, Kai uerd Toutor iaews

'OXEL KREÓMBPOTOV OI SE KaI GOÚMOUS REYOUOL KREÓMBPOTOV Kai

NEWVIONY YEVÉO8aL.

She gave birth first to Dorieus, then straightway to Leonidas, and right after him to Cleombrotus. Some, however, say that Cleombrotus and Leonidas were twins.

Note, however, that the use of verbs in the present tense does not destroy the temporal sequence of events. If this were true, there would not be a contradiction to say that the sacond and third children (whose births are in the present tense) were born at the same time.



The Historic Present and Narrative Grounding

34

In a like manner, Herodotus recounts important dynastic Larriages in the

historic present. Pisistratus union with the daughter of Megacles is crucial for his rise to power.

dmonap 5Etnv tupavvia tpone ri cipnueve o netoiocaros kard thy

bucAoyinv nv mpos MeYaKAEa YEvOuEn YOuEEL TOU ME/AKAEOG THU

evyatépa.

Having got back his sovereignty in the manner which I have describec, Pisistratus marries Megacles' daughter according to his agreement with Megacles.

(Hdt. 1.61.1)

Amasis, too, cements his alliance with Cyrene by marrying the d& ughter of a leading Cyrenan.

เที่ ouvoanu naikn

Amasis made friends and allies of the people of Cyrene. And he decid d to marry from there...in any case, he marries a certain Ladice, said by some to be the aughter of Battus, of Arcesilaus by others, and by others again of Critobulus, an esteeme citizen of the place.

(Hdt. 2.181.1)

In the account of Miltiades' marriage to the daughter of King Olo us, Herodotus equates the consolidation of power and the marriage by casting both in the historic present.

MATIONS TE En IOxEL TnV KEpGOUnOV, TEVTaKODIOUS BOCKWU

Enikopous, kai youte 'opou Toบ opnixwy Bacieos tiy Buyarepa

So Miltiades makes himself master of the Chersonese; there he maintained a guard of five hundred men, and marries Hegesipyle the daughter of Olorus, king of Thrace.

(Hdt. 6.39.2)

We may also cite again the story of Demaratus' birth (Hdt. 6.61.1-62.1). The marriage and remarriage of his mother, which contribute to his doubtful paternity, are both told in the historic present.



The Historic Present and Narrative Grounding

35

Of all the verbs in the historical present, teleutáô exhibits th. highest proportion of historic presents to other narrative tenses, with 16 listoric presents and 15 aorists and imperfects. This means that 52% of all the uses of this verb in narrative are in the historic present. Most interestingly, Herodotts' use of teleutáô echoes an annalistic style, for when the death of a king or general is recorded with this verb, the length of the reign and the name of tie successor follow. These examples demonstrate the pattern.

'AR UÁTTIS BÈ Ó NUÒC TÒY TPÒS MINNGÍOUS TÓMEMOV GIEVE KAS METÉTELTA

IEREUTA, BAGIREÚGAS ÉTEa ENTà KAi MEVENKOVTa. TEMEUTaUTOS SÈ

'AAVATTEW CEESEEaTO InU BaLAninu Kpoiros o'AAVTTEW, ETEWV EQU

Alyattes the Lydian, his war with the Milesians finished, dies after a r ign of fifty-seven years... After the death of Alyattes, his son Croesus, then thirty-five ye irs of age, came to the throne.

(Hdt. 1.25.1-26.1)

META SE TOUTA KUALAPAS MEV, BATIMEUTAS TEMOEPaKOVTa LTEa OUV TOîOI

Baơi nínv.

Afterwards, Cyaxares dies after a reign of forty years (among which I ount the years of the Scythian domination) and his son Astyages inherits the sovereignt.

(Hdt. 1.107.1)

CUTÓS TE YMAINS GIPÉWV TAUTO Tà ÉAVEa VOUCW IETEUTA IV TÂ TRWá.

OUTOS MEU ST OUEW ETEAEUNGE, APTOODEUnS GE o Eapoic Vapxos Kai

'orauns o rpiros otparnyos eraxendav enitnv'wvinv kcitnv mpocexea

While he was conquering these nations, however, Hymaees himself di as of a sickness in the Troad. Even thus he died, and Artaphrenes, viceroy of Sardis, and Otanes, the third general, were appointed to lead the army against lonia and the Aeolian territory on its borders.

(Hdt. 5.122.2-123.1)

NEUTUXÍONS 6È Ó MENÁDEOS ANMaPÁTOU KATaTaUGDÉUTOS fLEDÉEaTO TNV

BaciAninv, Kai oi yiveraL mais zeufionuosoutos o zEvionuos ouk

'APXÍENHOV. DEUTUXIONS SÈ OTEROEiS LEVELENHOU YOUÉEL SEUTÉPnU

Yuvaika EupubanvEK Ins oi EpEv HEV YiVETCL OUBEV, BUYEnp 6E



The Historic Present and Narrative Grounding

36

Leutychides son of Menares succeeded to the kingship after Demaratt j was deposed. A son is born to him, Zeuxidemus... This Zeuxidemus never became king of Sparta, for he dies before Leutychides, leaving his son Archidemus. After the loss of Zeuxidemus, Leutychides marries a second wife, Eurydame...By her he has no mak offspring, but a daughter, Lampito, to whom Archidemus son of Zeuxidemus is marri d by Leutychides.

(Hdt. 6.71.1-2)

The first two examples are straightforward dynastic notices, listir g the name of the sovereign, the length of his reign, and the name of his success or. The record of the death of Hymaees, in the third example, also includes the rames of his successors. Of course, as the length of the general's commission is ommitted as it is not as crucial for dating purposes as the length of a reign. The third example splendidly displays the narrative structure that Herodotus builds around these death notices. As in all four examples, Herodotus links the death to the previous narrative event ("While he was conquering these peoples..."), but, even more strikingly, he also links the statement of Hymaees' death to the st bsequent events ("Even thus he died, and Artaphernes..."). In addition, Hurodotus strengthens the contrast by using teleutáô first in the present and Uhen in the aorist. The record of the general's death is thus carefully insulate 1 from the surrounding narrative, and it passes from the realm of past histor y into present record. The fourth example is also tied to the previous narrative ("...after Demaratus was deposed."), but it contains a string of historic pre_ents describing birth (twice), marriage (twice), and death. The convolutions of the Spartan royal succession are set down in an orderly manner without any elaboration. 41

Thucydides provides evidence that this use of teleutáô is stylisticaly reconizable.

Although Thucydides customarily uses apothnêisko to express death in the historic present, he does have one instance of the historic present of teleutáô. In Thuc. 1.138.4, Themistocles dies (in the historic present) at the Persian court. As

41 The other usages of teleutáo —all of which recount the deaths of important f.gures — are at:

Hdt. 1.161.1, 1.214.1, 1.214.3, 2.159.3, 4.78.2, 5.27.2, 5.56.2, 6.1.1, 6.38.1, 6.136.3, and 9.102.4 (twice).



The Historic Present and Narrative Grounding

37

the Themistocles narrative is an echo of Herodotus, it is not incor.ceivable that the use of teleutâi might be a similar echo.

Inscriptional evidence confirms that when Herodotus uses the historic present to describe successions, he affects a highly annalistic tone. The Parian chronicle, also known as the Parian Marble, is inscribed with events in Greek (mostly Athenian) history. It notes exactly how many years before the present each event took place and proceeds at a plodding pace from 1581 B.C. to the date of the stela's erection in 263 B.C. As there is no variation in the tone of the

chronicle, it is not surprising that this inscription invariably uses he aorist indicative — even for the deaths of such illustrious figures as Aes shylus, Sophocles, and Euripides and for deaths as dramatic as Socrates'. But for a king's death, and even more frequently for his heir's accession, the chro.cle switches into the present.42 The stela reads, for the year 489/88,

Kdi ApEios TEAEVIEL EEDEnE O EE ViOS BaGIAEVEL.

...also Darius dies, and his son Xerxes reigns...

(IG XII:5', 107)

It is interesting to note that tyrants are explicitly denied this treat.nent; for the year 368/7, we read:

'AP' DU ALOVENIOS EURERINTS ÉTEREÚTNOEV, Ó SÈ VIOS AIOLÚOIOS

ETUPRUVEUEEV, Kai ANEEavopos TEAEUTEL MEpSiRkas 6E 6 ALVTOU

MaKEDOVWY BaGIAEVEL, EEn HILLI, pXOVTOS 'ABUnG NarSiYEVOUS.

One hundred four years before the present, Dionysius the Sicilian died, and his son Dionysius assumed his tyranny. Also, Alexander dies, and Perdiccas the son of Amyntus reigns over the Macedonians, this while Nausigenes is archon at Athens.

(IG XII:5', 108)



42 Occurrences of the historic present not quoted below are in the years: 420/19, 380/79, 336/35, 313/12, 310/09. All of these verbs are forms of teleutáô or basileúo.



The Historic Present and Narrative Grounding

38

Dionysius, the tyrant of the powerful city of Syracuse, is distingu: shed from the kings of the then minor kingdom of Macedonia. In In a gesture even more dismissive of tyrants (so to speak), the chronicle records the deatl s of two poets

— Philoxenus and Sosiphanes — in the present. The exact reason for this special dispensation is unclear; neither poet hailed from Paros, and neither had lived particularly recently.

Since the temporal structure of the Parian chronicle is quite clear, it provides some of the best evidence againsts the conjunction redu tion and related theories of the historic present. 4 Conjuction reduction is incapable of producing such sentences as the entry for 360/59:

'AD' OU PIALTTOS AMUVTOU MAKESOVEU BOCIAEVEL KOIADTOEEDEnS

ETENEÚTnEV...

Philip the son of Amyntus reigns over the Macedonians and Artaxerx s died...

(IG XII:5', 109)

The conjunction reduction theory would, in fact, expect the tenses in the above example to be reversed. These data also cannot support the asser ion that the historic present records an event simultaneous with the event previous in the narrative. Since basileúei in this passage occurs first in this entry, here is a gap of several years between it and the last event in the previous entry. Finally, one might say that since basileúo is inherently a stative verb, we shoul l expect it in the present. Teleutáô (properly, "to come to an end") is an undeniably punctual



43 In one case, the historic present is not confined to the succession of a realm, but of a piece of territory. For 311/10: 'A' OU NIKOKPÉWV ÉTEREÚTNGEV KAI MTOREMaTOS KUDLEÑEL TS

vnaou..., "Before this time, Nicocreon died and Ptolemy has sovereignty over the island."

44 Especially if, as McKay says (1974: 247), "the 'annalistic' present, being less colorful, would, one might expect, lend itself to conjunction reduction." This argument need not be adduced, for even if we consider conjunction reduction a better explanation than vividness, we need not exclude all vivid events from the conjunction-reduced present.



The Historic Present and Narrative Grounding

39

verb, but in annalistic contexts, basileúei is also punctual and inceptive, for in these sentences it clearly means "to take the kingship."45

These so-called annalistic presents form the weakest link in existing theories of the historic present. Smyth (1956: 422) merely says that "closely connected with the historical present is the annalistic present, which is used to register historical facts or to note incidents." Rijksbaron (1984: 24) places himself in a slightly more defensible position by saying that "the 'eyewiti.ess' and

'turning-point' effects mentioned above play no role in cases were a series of historic presents occurs, without contrasting with imperfects and aorist indicatives...These actions cannot possibly be viewed as turning- Joints, since the following does not consist of a story demonstrating their significance." Rijksaborn's statement, however, can only be true for lists of isola ied events such as the Parian chronicle. In historical narrative, especially narrative as tightly knit as those of Herodotus, aorists and imperfects always occur, and contrast is never lacking. Rijksbaron also fails to notice that the historic present m.y not only introduce a narrative, but also cap one off. (This latter is function is obviously appropriate when the historic present tells of someone's death.) The chief fault of these definitions is that the annalistic present is placed side by side with the historic present without any demonstration of their interrelations.up.

When we view the annalistic present in the light of narrati /e grounding, we see that these colorless notices of royal births and deaths are rendered into the historic present in order to delineate the structure of the narrative rather than to



45 This inceptive force is explicit in the examples from Herodotus above, where we find

EKDEKETQL Tnv BaciAninv, "he takes hold of the kingship". See Stork's ar ticle, "Aspectual

Variant Readings in Herodotus" (1988), for a brief discussion of the aspectual features of basileúo.

He notes (p. 287) that passages that include "a matter-of-fact listing of successive reigns without any further details and with adjuncts of time specifying the exact perdiod during which the reigns lasted" normally take the aorist. But since the Aktionart of basileúo is normally durative, some texts use the imperfect.



The Historic Present and Narrative Grounding

40

emphasize any inherent interest in the events. When he recounts the birth of Cleomenes, Herodotus must first tell of the barrenness of Anaxardrides' first wifeand of his remarriage. When he reaches Cleomenes' birth, he places the event in the historic present to signal the end of his digression. Likewise, in the narrative of Demaratus birth (Hdt. 6.61-3: part of which is quoted above), by the time Herodotus actually gets to the birth, he has already embedded himself in a double digression, first about his father marrying a third wife and then about this third wife's mysterious beautification as a child. By putting the actual birth in the historic present, Herodotus reminds the reader what the who'e point of his story was.

Herodotus also sets up markers at the juncture of two narratives, the most

obvious examples of which are the "king dies, successor rules" combinations.

The death of Aristagoras of Miletus (Hdt. 5.126.1-6.1.1) is particul irly striking since it occurs over a book boundary and is accompanied by a shit in scene from Greeks to Persians. Herodotus employs historic presents on either side of the book division to mark the transition. Returning to an earlier exariple, we may observe that pémpô almost always marks a narrative transition by changing the scene from the place of the sender to the place of the receiver. This transitional function might be the best explanation for the large number of hi. toric presents of this verb. We may characterize transitional passages as particularly foregrounded since they advance not only their own narrative but they start the development of a new one. In fact, Rijksbaron's observation that historic presents "introduce a new series of actions" is special case of this transitional function.



## Conclusion

We have seen how foregrounded passages advance the flow of the narrative whereas backgrounded passages merely comment on it; we have seen how the historic present possesses many of the features associated with the narrative foreground, such as perfectivity, telicity, and a preference for main clauses. If history is primarily the record of _erga megála te kai thômastá_, of "deeds great and wondrous," then we should expect the historian to focus his most striking narrative devices on just those events that advance his ta.a of marvelous deeds. When he employs the "annalistic present," Herodotus is i cording the raw data of history, the births, marriages, and deaths of great and powerful leaders. These events may not be inherently interesting to us, but they are history, the most objective data that inquiry can produce. Likewise, when Herodotus reports that Gyges chooses to kill Candaules or that Cambyses sends Prexaspes to kill Smerdis, he is recounting an objective, verifiable event. As Hopper and Thompson observe, unrealized or potential events rarely invade the narrative foreground. I argue, therefore, that Herodotus structurs his history, naturally enough, around those events that are the most unequivocally historical and that he reports a great number of these events in the historic present.

The greatest weakness of my analysis springs from its greatest strength. My computer programs have been so successful at documenting the historic present that I have had precious little time to examine the overall structure of the _Histories_. As observed by Longacre and Levinsohn and by Rijksbaron, syntactic features can be used to structure both sentences and entire narratives. What my analysis gains by documenting the historic present's discourse function at the micro-level, it loses by slighting the macro-level. Any further treatment of this topic must take into account the large-scale compositional issues in Herodotus.

I could greatly enlarge knowledge of the historic present by applying the methodologies I have used for Herodotus to other historians. Thucydides and Xenophon are certainly rich in historic presents. Even Diodorus Siculus, late as he is, offers some tantalizing clues. In an experimental pass, I found under fifty historic presents in Diodorus; three of these were forms of _pémpô_. In any event, the tools that I have written for Herodotus need almost no adaptation to work for any other Greek prose author.

It is precisely the power of these tools that I wish to stress. Using morphological information and some simple ambiguity-breaking and pattern-matching routines, I have produced some very interesting data on an intriguing construction. While some may disagree with my interpretations, I hope that everyone interested in textual research may appreciate the aid electronic tools can give us in the art of reading.


## Bibliography

Comrie, Bernard. _Aspect_. Cambridge: Cambridge University Press, 1976.

Comrie, Bernard. _Tense_. Cambridge: Cambridge University Press, 1985.

Crane, Gregory. "Generating and Parsing Classical Greek". _Literary and Linguistic Computing_ 6 (1991) 243–45.

Denniston, J. D. _Greek Prose Style_. Oxford: Oxford University Press, 1952.

Fleischman, Suzanne. _Tense and Narrativity_. Austin: University of Texas Press, 1990.

Fritz, Kurt von. "The So-Called Historical Present in Early Greek". _Word_ 5 (1949) 186–201.

Godley, A. D, trans. _Herodotus: With an English Translation by A. D. Godley in Four Volumes_. London: William Heinemann, 1926.

Goldfarb, Charles F. _The SGML Handbook_. Oxford: Oxford University Press, 1990.

Herwijnen, Eric van. _Practical SGML_. Dordrecht: Kluwer Acaderic Publishers, 1990.

Hopper, Paul J. "Aspect and Foregrounding in Discourse". _Syntax and Semantics_ 12 (1979) 213-241.

Hopper, P. J. and S. A. Thompson. "Transitivity in Grammar aná Discourse". _Language_ 56 (1980) 251-300.

Hude, Charles, ed. _Herodoti Historiae_. Oxford: Oxford University Press, 1908.

Jong, Irene J. F. de. _Narrative in Drama: The Art of the Euripidean Nessenger-Speech_. Leiden: E. J. Brill, 1991.

Kiparsky, Paul. "Tense and Mood in Indo-European Syntax". _Foundations of Language_ 4 (1968) 30-57.

Levin, Saul. "Remarks on the 'Historical' Present and Comparable Phenomena of Syntax". _Foundations of Language_ 5 (1969) 386-90.

Longacre, R. and S. Levinsohn. "Field Analysis of Discourse". ed. W. U. Dressler, _Current Trends in Textlinguistics_. Berlin, New York: De Gruyter (1977) 103-22.

McKay, K. L. "Further Remarks on the 'Historical' Present and Other Phenomena". _Foundations of Language_ 11 (1974) 247-51.

Rijksbaron, Albert. _The Syntax and Semantics of the Verb in Classical Greek_. Amsterdam: J. C. Gieben, 1984.

Rijksbaron, A., H. A. Mulder, and G. C. Wakker, eds. _In the Footsteps of Raphael Kühner: Proceedings of the International Colloquium in Commemoration of the 150th Anniversary of the Publication of Raphael Kühner's Ausführliche Grammatik der Griechischen Sprache, II. Theil: Syntaxe_. Amsterdam: J. C Gieben, 1988.

Rijksbaron, Albert. "The Discourse Function of the Imperfect". In: Rijksbaron, Mulder, and Wakker (eds.) (1988) 237-54.

Smyth, Herbert Weir. _Greek Grammar_. Cambridge, Massachusetts: Harvard University Press, 1956.

Sperberg-McQueen, C. M. and Lou Burnard. _Guidelines for the Encoding and Interchange of Machine-Readable Texts_. Draft version 1.0.

Stork, P. "Aspectual Variant Readings in Herodotus". In: Rijksbaron, Mulder, and Wakker (eds.) (1988) 265-89.

Wolfson, Nessa. _CHP: The Conversational Historic Present in American English Narrative_. Dordrecht, Netherlands: Foris Publications, 1982.


## Index Locorum

Hdt. 1.10.1-2

Hdt. 1.107.1

Hdt. 1.11.4

Hdt. 1.12.1

Hdt. 1.21.1

Hdt. 1.25.1-26.1

Hdt. 1.59.3

Hdt. 1.61.1

Hdt. 2.181.1

Hdt. 3.30.3

Hdt. 3.65.3

Hdt. 3.77.3-79.1

Hdt. 4.102.1

Hdt. 5.122.2-123.1

Hdt. 5.39.1-41.1

Hdt. 6.115.1

Hdt. 6.132.2

Hdt. 6.39.2

Hdt. 6.40.1-2

Hdt. 6.62.1

Hdt. 6.63.1

Hdt. 6.71.1-2

Hdt. 7.239.3

Hdt. 9.64.2

Xen. Anab. 1.1.1



22

35

22

23

30

35

30

34

34

24

25

24

30

35

33

7

33

34

26

7

33

36

30

7

7
