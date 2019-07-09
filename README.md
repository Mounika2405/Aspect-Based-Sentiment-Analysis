# Aspect-Based-Sentiment-Analysis

Sentiment analysis of reviews can determine the opinion (positive/negative/neutral) of a user about an organisation/entity (restaurant) on the whole but not the subject/attributes (food, service, ambience etc.) specifically. Determining the aspects related to the user sentiment is way more actionable from the business point of view rather than just overall sentiment as the users might have good things to say about few things and complaints/bad comments about some other things. It will also help customers in deciding better which place/entity to choose for specific needs.
 
Data Set Used:
The dataset has been collected from SEMEVAL 2016 Task 5 Subtask 1(Task description mentioned below).

Task Description:

Subtask 1: Sentence-level ABSA. Given an opinionated document about a target entity (e.g. a laptop, a restaurant or a hotel), the goal is to identify all the opinion tuples with the following types of information:
 
 - Slot 1: Aspect Category Detection. The task is to identify every entity E and attribute A pair towards which an opinion is expressed in the given text. E and A should be chosen from predefined inventories of entity types (e.g. LAPTOP, MOUSE, RESTAURANT, FOOD) and attribute labels (e.g. DESIGN, PRICE, QUALITY). The E, A inventories for each domain are described in the respective annotation guidelines documents.
 
 - Slot 2: Opinion Target Expression (OTE). The task is to extract the OTE, i.e., the linguistic expression used in the given text to refer to the reviewed entity E of each E#A pair. The OTE is defined by its starting and ending offsets. When there is no explicit mention of the entity, the slot takes the value “NULL”. This slot will be required only for particular datasets/domains.
 
 - Slot 3: Sentiment Polarity. Each identified E#A, OTE tuple has to be assigned one of the following polarity labels: positive, negative, or neutral (mildly positive or mildly negative sentiment).

