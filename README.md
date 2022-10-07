# Amazon_Vine_Analysis
DU Data Analytics Bootcamp: Module 16 - AWS and Spark

## Overview/Purpose of Project
The Amazon Vine program is a paid service available to manufacturers and publishers that incentivises Amazon Vine members with products to provide required reviews. The task of this challenge was to analyze product reviews and investigate if the Vine program actually creates bias, granting businesses that pay for the service better reviews.

## Results Analysis and Challenges

### Vine Program Results
<div>
  <p>Prior to this assignment, I had never heard of the Amazon Vine program. That's probably the first thing you'd notice when reviewing some of the data presented in this analysis. In examination of 1.7 million reviews of tools sold on Amazon, there were approximately thirty thousand reviews that, perhaps didn't go viral, but certainly caught other shopper's attention. Of those 29,517 <i>impactful</i> reviews, only 268 were for products produced or manufactured by a Vine member business. So quite obviously, Vine members are a pretty restricted group. What's the impact of Vine?  Reviews were rated with five stars more often than not: in fact, 55.6% of all Vine product reviews received the top rating.</p>
  <p><img src="https://github.com/cb19weber/Amazon_Vine_Analysis/blob/main/images/analysis_stats.png" align="center"></p>
<div>

### Non-Vine Program Results
<div>
  <p>Non-Vine members received five-star reviews only 46.3% of the time. Or to put that in better perspective, paying for a Vine membership resulted in approximately one additional five-star review, every five reviews. A twenty-percent higher clip for the top-rating is pretty significant. Especially when products are quite similar in function. Perhaps to a tradesman, there is a significant difference by brand of tools. But to the everyday consumer, we can probably make an assumption that the functionality across small tools, like screw-drivers, socket-sets, et cetera is not that large. When product differentiation is small, and the market for a good is closer to a "perfect" market, these ratings could potentially result in a significant uptick in sales for manufacturers.</p>
</div>

## Summary
<p>There certainly seems to be some bias created by the Vine program. But the Amazon product review system is just one of <i>many</i> filters available to shoppers on the platform. Some additional points of analysis would be really interesting to explore. How much of an impact do the reviews really have? In this analysis we looked at five-star reviews. Is there a significant difference in sales between goods with five-stars and, say four-star-reviews? Where is the real drop off? And additionally, are certain markets more effected by reviews than others? Consumer preference can be really difficult to measure, and brand loyalty sometimes difficult to break. As we head into the end of the analytics training course and into machine learning, it would be worth a look at what filters most highly correlate to greater sales numbers.</p>
