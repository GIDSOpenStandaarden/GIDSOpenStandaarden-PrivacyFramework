# GIDSOpenStandaarden-PrivacyFramework 	 	
Privacy documents for organizations that make use of GIDS Open Standaarden open source components.

## Introduction
In GIDS Open Standaarden, substantive choices about privacy go hand in hand with practical implementation. GIDS Open Standaarden aims to make people healthier by giving them as much control as possible and by organising care more flexibly and multidecisionally. Privacy in GIDS Open Standaarden is therefore not only about preventing 'data-ripping' but also about giving users choice, real choice and understandable choice. Giving users the choice, as it were, of whether and how to step into the spotlight of a stage.

In designing GIDS Open Standaarden, we therefore started to look with users at how they actually make choices about sharing data. This showed that the most important thing in such choices is with whom you share data and how you deal with that person. So you can never make choices about sharing data if you don't know with whom and for what purpose. And these choices change, how you deal with people changes, sometimes you show more of yourself and sometimes less. Choices must therefore be made when the data is actually used and choices must always be open to revision.

Technically, this means only making visible what people have actually chosen to show. In many places, for example, your e-mail address is used to log in. But those e-mail addresses can be linked to each other and then, as a user, you no longer have the choice of what you share with whom. We therefore ensure that an organisation can know nothing more about you than what is necessary and what you have chosen to do. Giving choice also means clearly marking when another party is involved and marking when the way of dealing changes: those are the moments when you can make sensible choices. 

An example of this is marking transitions and asking permission using [Health Tools Interoperability (HTI)](https://github.com/GIDSOpenStandaarden/Signpost#hti--production). The moment you actually jump to another party, this is made clear and you are offered choices. GIDS Open Standaarden has its own privacy framework for [design principles]() in Dtuch. 

## This Privacy Framework uses a number of principles:
1. Relationship central
Much of what is happening around health can be understood as a combination of others judging you and building a certain image of yourself. This is a process that takes place again within each relationship and is unique for each relationship within all care processes. The aim of the technical development is to focus on relationships in the same way. Social interactions around health, both professional and informal, are very complex and diverse.

From a legal point of view, it is also important to think in terms of relationships: personal data must always have a clear responsible person and depending on your role, you have different rights and obligations. These rights and obligations conflict between the different roles within and outside healthcare. If it is always clear to which relationship certain data belongs and who is responsible for it, the system can be prevented from becoming legal spaghetti.

2. Building relationships and trust
Every relationship is different and has its own dynamics. This dynamism, trust in the other party and the information exchanged go hand in hand and form a dynamic whole. The choices whether or not to share certain data must therefore follow these dynamics. At the same time, the choices must be understandable and well-arranged: first you choose a relationship, then it follows what you do or do not share. This makes it possible to define a set of 'safe defaults' for each type of relationship, as it were templates that serve as standard choices for a particular type of relationship. Depending on the situation, people can always choose to deviate from this (both ways).

3. Control over data
Certainly in healthcare, control over personal data is complex. In principle, as a citizen you have control over your own data, but there are literally dozens of laws and regulations that make exceptions. In practice, this means that control over the personal data can differ greatly per relationship. It also applies that shared data can no longer be 'dissected'. For the removal you depend on the other party and the rules that they must adhere to. It is therefore important to communicate this clearly so that everyone in a relationship knows what to expect from each other. It follows from the [GDPR](https://ec.europa.eu/info/law/law-topic/data-protection/data-protection-eu_en) that notices about this are legally binding.

4. Content
Personal data can have different statuses. It can be a story that you create about yourself, it can also be a story that someone else creates about you. It may be data that is intended to be passed on to others; or it may be data of which it is important that you can demonstrate that it has been verified by someone else.

5. Search and be found
The core of this theme is that you can have different roles / contexts in which you want to be able to be found or where you want to search, but you do not necessarily want them to be linked to each other. These requirements still need to be further elaborated. The functional requirements on this point, other than privacy, are also not yet clear.

6. User interface and interaction design
Self-direction is only possible if there is a user interface and an associated interaction design that helps people make free choices. It also helps if the different applications that implement the SNS use a similar visual language and workflow, so that users recognize the interaction and do not have to discover it again and again. Where necessary, the SNS must enforce this, and support it where possible.

7. Technical requirements
From various angles you have to deal with privacy-oriented requirements that directly affect the technical choices.


(c) 2020 Winfried Tilanus CC-SA-BY 4.0
