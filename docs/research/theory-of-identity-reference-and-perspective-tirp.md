---
layout: page
title: "Theory of Identity, Reference and Perspective (TIRP)"
permalink: "/research/theory-of-identity-reference-and-perspective-tirp/"
---
The **Theory of Identity, Reference and Perspective (TIRP)** combines basic semantic, pragmatic and cognitive principles into a single model that relates forms and expressions used in language to their possible meanings and referents in a world and in a specific context, showing observed ambiguity and variation as opposed to the potential ambiguity given a large vocabulary, the complete world and massive text corpora.

**Basic assumptions:**

- We identify what we refer to, we refer to what we identity and we make reference to things in different ways on the basis of our perspective
- We therefore need an integrated model for relating form and meaning (sense and reference) to the shared context in data distributions that combines basic semantic, pragmatic and cognitive principles to explain ambiguity and variation in context:
  - Frege’s Sinn und Bedeutung (1960): make reference to the same thing in different ways
  - Gricean maxims of quantity and quality (Grice et al. 1975): provide minimally ***sufficient*** and ***necessary*** reference for the purpose of communicating (semantics and perspective)
  - Roschean Basic Level of categorisation (Rosch et al. 1976): adhere to the most natural levels of cutting up the world in categories, which maximises generality (apply to most instances) and informedness (predict most properties)
  - White’s appraisal theory (2015): framing and stance taking expresses appraisal and perspective
  - Molinsky (2007): we choose the most appropriate coding scheme within socio-cultural settings

- ***Ambiguity*** and ***Variation*** are abundant in language as a system and in large data volumes across contextual boundaries
- ***Ambiguity*** and ***Variation*** resolve with specific contexts defined by time, place, situations and social relationships
- ***Perspective*** reflects personal emotion, stance, judgments, relevance with respect to situations in context
- Ambiguity and variation are extremes on continuums:
  - each form can mean anything (max. ambiguity)
  - all forms mean the same (max variation)
- Socio-cultural settings and relationships with temporal, spatial and situational contexts define an optimal balance in the continuums for effective (least confusion) and efficient (least effort) communication

TIRP measures ambiguity and variation of language in relation to the complexity of the surrounding world and the richness of the lexicon. Through TIRP, we can measure the degree to which language use is optimised for communication between communicative partners, given their shared experience, information and background and given the goals and tasks at hand. For this we use the following measures (see Ilievski et al. 2016 for the details):

- MOA: mean observed ambiguity
- MOV: mean observed variation
- RORA: relation between observed & resource ambiguity
- RORV: relation between observed and resource variance

We have shown that in selective sample of language ambiguity and variation is almost absent, as shown by the MOA and MOV values that approximate “1” meaning one form one meaning  and one meaning one form. This is extremely low compared to the ambiguity and variation in existing resources, e.g. all variants of concepts and meanings of words in WordNet, in SemCor (a balanced corpus).

Formally:

- Define all contexts as the set of tuples {W, S, T, L, P, E}, such as that:
  - W = set of worlds,
  - S = set of of socio-cultural contexts
  - T = set of periods in time
  - L = set of regions
  - P = set of inter-Personal contexts
  - E = set of situations
- A context ***c*** is then defined as <*w,s,t,l,e*> such that w ∈ W, s ∈ S, t ∈  T, l ∈  L, p ∈  P, and e ∈  E
- Resources such as wordnet and large corpora are proxies for comprehensive language systems and language use
- Within each ***c*** we predict variation and ambiguity to approximate 1

Given sufficient data in which the parameters for the context *c*are defined, the optimal and real balance between complete ambiguity and complete variation can be learned.

The robot model [Leolani]({{ site.baseurl }}/) uses these measures to optimise the communication with people, given the shared experience, information and background and given the goals and tasks at hand (Vossen et al. 2019). Building a social relationship thus creates the context for effective communication through a so-called ‘personalized language’ (through our relationship we know what we mean). In fact, our robot implementation uses the measures of TIRP to select the most effective interpretations and most appropriate expressions  (following Gricean maxims of quantity and quality), but also the most natural expressions and interpretations (following basic level categorisation principles, Rosch et al. 1976) within a basic Fregean framework of sense and reference (Frege 1960). In addition, TIRP tries to explain remaining variation in making reference as a function of the perspective of the communication partners, e.g. expressing emotions, judgements and bias, interest, etc.
Our goal is to set up experiments in which communication between people and robots is modelled in combination with an explicit model of the shared knowledge and information. Through these experiments, we hope to demonstrate that communication partners adapt their communication over time to optimise its effect within these parameters.

**References:**

Gottlob Frege, “On Sense and Reference,” in Translations from the Philosophical Writings of Gottlob Frege, edited by Peter Geach and Max Black (Oxford: Basil Blackwell, 1960): 58-70.

Grice, H. Paul, Peter Cole, and Jerry Morgan. “Logic and conversation.” 1975 (1975): 41-58.

Rosch, Eleanor, Carolyn B. Mervis, Wayne D. Gray, David M. Johnson, and Penny Boyes-Braem. “Basic objects in natural categories.” Cognitive psychology 8, no. 3 (1976): 382-439.

Molinsky, Andrew. “Cross-cultural code-switching: The psychological challenges of adapting behavior in foreign cultural interactions.” *Academy of Management Review* 32, no. 2 (2007): 622-640.

White, Peter RR. “Appraisal theory.” The international encyclopedia of language and social interaction (2015): 1-7.

P. Vossen, M. Postma, and F. Ilievski, (2018) “Referencenet: a semantic-pragmatic network for capturing reference relations,” in Global wordnet conference 2018, singapore, 2018.

F. Ilievski, M. Postma, and P. Vossen, “Semantic overfitting: what `world’ do we consider when evaluating disambiguation of text?,” in Coling,  pp. 1180-1191. 2016.

M. Postma, F. Ilievski, P. Vossen, and M. van Erp, “Moving away from semantic overfitting in disambiguation datasets,” in Proceedings of the emnlp workshop on uphill battles in language processing, 2016. pp. 17-21. 2016.
