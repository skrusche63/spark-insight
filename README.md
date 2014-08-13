![Dr.Krusche & Partner PartG](https://raw.github.com/skrusche63/spark-elastic/master/images/dr-kruscheundpartner.png)

## Real-time Insights with Apache Spark

### Customer Loyalty 

The customer's engagement with a business is reflected by a wide range of events, such as e-commerce orders (or transactions), service calls, social media comments and more. All these events are indicative of the customer's loyalty to a certain business.

Loyalty is usually defined as the strength of the relationship between a customer and a certain business. A higher degree of loyalty results in more purchase orders at a higher frequency.

Customer loyalty is an important parameter for almost any kind of business, and can e.g. be used to measure the effectiveness of marketing campaigns. Following a campaign, the loyalty curve can be analzed for a certain period of time to see if there is any significant impact on customers loyalty.

Loyalty, however, can not be directly observer and measured. It is an internal customer state, that must be inferred adn predicted from customer engagement events.

> Customer Loyalty is a highly valuable business insight derived from customer engagement data using **Predictive Analytics**.

We suggest to predict a sequence of (hidden) customer loyalty states from a sequence of observed customer engagement data by using a [Hidden Markov Model](http://en.wikipedia.org/wiki/Hidden_Markov_model). Identifying customers with a downward loyalty curve with such analysis can directly trigger proactive actions to resurrect the relationships of these customers.


### Purchase Horizon


### Purchase Rules


### Association Rule (AR) Mining

Scala and Apache Spark based implementation of most recent Top-K Association Rule Algorithms as proposed by [Philippe-Fournier Viger](http://www.philippe-fournier-viger.com/). Top-K Association Rule Mining overcomes one of the major problems in traditional Association Rule approaches, i.e. tuning the *minimum support* parameter.

Top-K Association Rule Mining therefore is an appropriate candidate for applying this technique to real-time data streams. Read [more](http://skrusche63.github.io/spark-arules).

### Context-Aware Recommendations (CARs)

Read [here](http://skrusche63.github.io/spark-fm)

### Frequent Sequence Mining (FSM)

Read [here](http://skrusche63.github.io/spark-fsm)

### Hidden Markov Model (HMM)

Read [here](http://skrusche63.github.io/scala-hmm)

### Natural Language Processing (NLP)

Read [here](http://skrusche63.github.io/akka-nlp)

## Elasticsearch Insights

Read [here](http://skrusche63.github.io/spark-elastic)

