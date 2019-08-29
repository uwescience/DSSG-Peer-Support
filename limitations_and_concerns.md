---
layout: page
title: Limitations & Concerns
---
## Limitations
We have many concerns for our research, which are as follows:
### Our indicators of helpfulness:
#### Likes
There are many reasons a poster could like a comment that have nothing to do with it being helpful. Some examples include an existing relationship between the poster and commenter, the comment being funny, the comment sharing an opinion that the poster agrees with, etc.

#### Follows
Likewise, there are many reasons a user could follow a commenter. Additionally, follows were an infrequent outcome compared to our other measurements.

#### Gratitude (non-specific)
Gratitude can be more reflective of social norms than of actual gratitude. Furthermore, it was impossible for us to eliminate sarcastic gratitude from our sample (i.e. where a user says “thanks a lot” in response to something decidedly unhelpful). Lastly, a general expression of gratitude would result in every comment in the thread occurring before that time being marked as showing this outcome; however, this could easily have pulled in comments that were not, in fact, helpful.

#### Gratitude (specific)
If the poster and commenter interacted multiple times before the poster said thank you, we recorded each of those comments as showing this outcome. However, it is possible that this would have included unhelpful comments along the way; we have no way of knowing whether it was the entire conversation that the poster found helpful or just a specific portion. Additionally, because we did not have access to usernames, if the poster mentions a username but doesn’t tag the commenter, this outcome would not catch that mention. Lastly, we cannot determine sarcasm with this outcome.

#### Mood change
While the content posted under a negative mood category seemed to contain similarly negative content, we did not see the same relationship between positive content and the positive mood categories. In other words, a user may post a message with a positive mood (e.g. "calm"), but have the content of the post be far more negative (e.g. "I've decided I'm going to end it"). If the mood of the content itself isn’t changing, then we are not actually seeing a mood change; this outcome, which looked exclusively at the mood category rather than checking for content, would miss this distinction.

Most importantly, we recognize that all of the above indicators are proxies for helpfulness and too problematic to be used as reliable measures of helpfulness. We decided to use these proxies merely because we didn't have access to more robust measures.

### Our features
#### MI Tags
The motivational interviewing algorithm that Mike Tanana used to tag our data was trained on professional counseling interactions, not online peer support. Actually looking at the content behind a comment labeled with an MI (motivational interviewing) tag may not correspond to the construct underlying the tag. For instance, some terms that would be classified as "affirmations" were phrases like “Happy New Year.” Thus, many of the MI tags likely exhibit lower fidelity than they would if they were used on conversation data from a clinical setting. 

### Our analysis
Our analysis took into account features from the text content on the platform and user engagement statistics. We used these variables to predict helpfulness via the use of proxies like likes, follows, and expressions of gratitude. This scope of analysis, however, did not result in very strong model performance as it failed to incorporate several complexities of platform usage that impact our outcome measures.

As we have previously discussed, the external circumstances that a user is facing affect the outcomes we see. As we found from exploring posts of a more critical/serious nature, individuals experiencing those circumstances were overall less likely to use any of our helpfulness proxies. This biases our results as the outcomes we are using are not equal in essence across different users on the platform. Some examples of these circumstances include:
* Existing social relationships: Networks that may exist off the platform or within the sphere of private messaging were completely out of the scope of our analysis but could heavily influence the usage of our helpfulness proxies.
* Social network dynamics: How many people are posting at the same time and what is currently popular and is receiving more attention would affect our outcome measures but were not controlled for in our analysis. 
* Granularity: The granularity of our analysis is performed at the post-question interaction level. Helpful behavior may occur at a coarser granularity.  
* Engagement: The median user on this platform is active for only two days and has only a handful of interactions on the platform. It’s difficult to imagine material changes in mental health outcomes in such a narrow window.

## Concerns
Other concerns not mentioned in the Takeaways section:
* While the platform that we studied specifies that individuals under the age of sixteen should not use it, we frequently observed users writing elsewhere on the platform (such as in a post) that they were under the age of sixteen.
* Ethical concerns over how our research could be misinterpreted and potentially used towards platform changes that would lead to detrimental downstream effects on users’ mental health and wellbeing.
* While the platform we studied does explicitly state that its administrative data is shared with researchers, the platform was more ambiguous about whether or not users were fully aware of experimental interventions that were being performed (not by our team, but by others we learned of). Given that individuals on these platforms represent a vulnerable group, we remain concerned that the platform isn’t adequately prepared for the effect of negative interventions.
* Finally, we remain concerned that these platforms, while well-intentioned, overstate their efficacy.   
