<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/facebook-wall-1.png" width="66%" />
</p>

# The Mastodon Science Collective

<p align="center">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/facebook-wall-2.png" width="66%" />
</p>

Science Collective would be a fork of [the Mastodon project](https://joinmastodon.org/) which I hope to create and maintain to service the maverick science community.  The idea is that each maverick science thought leader would spin up their own [Twitter clone](https://mastodon.social/web/getting-started) dedicated to their particular project.  All of these instances can [federate with one another](https://github.com/tootsuite/documentation/blob/master/Using-Mastodon/User-guide.md#decentralization-and-federation) to form into meta-communities, and the fork would be designed to specifically support collaboration between these independent science communities.

| [![The Pre-Scientific Judgment of New Ideas](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-prescientific-judgment-of-new-ideas.jpg)](https://www.controversiesofscience.com/pre-scientific-judgment/worldview/card) | [![The Decline in Conceptual Revolutions](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-decline-in-conceptual-revolutions.jpg)](https://www.controversiesofscience.com/conceptual-revolutions/worldview/card) |
|:---:|:---:|
| There exists a cultural tendency today to judge complex scientific claims before enough details have been collected to justify those judgments | Is it possible that the rate of innovation in the sciences has been affected by cultural tendencies like this? |

The social network's primary purpose would be to set up a self-supporting ecosystem to support the elaboration of groundbreaking science claims into predictive scientific hypotheses.  To get to that primary objective, science collective breaks the problem down into its constituent components:

1. Creating the infrastructure required to support the aggregation of information about controversial and groundbreaking science claims and questions.

2. Supplementing laypeoples' existing science education with details that are crucial for understanding controversial and groundbreaking science claims.

3. Establishing a process for the aggregation and binning of critique of scientific theories and science journalism, in order to transform from people who are **subject to** science claims, to people who can treat science claims **as objects** (basically helping them to think about science claims at a higher, more critical level). 

| [![The 5 Stages of the Mind](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-5-stages-of-the-mind.jpg)](https://www.controversiesofscience.com/the-5-stages-of-the-mind/worldview/card) | [![Why Critique Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-why-critique-science.jpg)](https://www.controversiesofscience.com/critique-science/worldview/card) |
|:---:|:---:|
| Science education and science journalism both encourage an approach to science which can stunt our cognitive development | One way to address the problem is to seek out the best critiques we can find |

The fork's primary features would include:

*A Discourse Schema Which Brings Order to Process and the Space* - The site would introduce a social network structure for discussion which is intended to distinguish the types of scientific discourse.  This schema is intended to reduce unnecessary conflict between people who are attempting to advance existing models, and people who are attempting to navigate to new arguments and models.  My thesis is that creating a platform where these two types of people are more likely to work together could generate breakthroughs.

*Modeling Integration* - Support into the Mastodon instance for rendering Jupyter notebooks will enable the rendering of complex simulations in service of specific technical arguments.

| [![Why Outsider Mavericks Matter in Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-why-outsider-mavericks-matter-in-science.jpg)](https://www.controversiesofscience.com/outsider-mavericks/worldview/card) |
|:---:|
| Since certain groundbreaking scientific advances require that we reject some pre-existing theory, these problems are more likely to be resolved by maverick thinkers with little investment in the current ideas |

| [![The Stucture of Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-structure-of-science.jpg)](https://www.controversiesofscience.com/structure-of-science/worldview/card) |
|:---:|
| By bringing a newfound sense of organizational order to challenges to mainstream theory, it should be possible to enhance innovation in the sciences |

*Prediction Market Tracking, Integration and Standardization* - Integration of the Auger blockchain for registering and betting on scientific predictions; will probably require the creation of prediction standards to label those predictions which avoid common, predictable mistakes.

*Bounty-Based Moderation Reward Schema* - Karma-like system where ERC20 tokens are used to reward the site's moderation and early adopters.  Roles specifically suited for peer review are built into a checks-and-balances system ecology for reviewing content.  There would be rewards for identifying pertinent content (especially vindications); for proposing novel conjectures or analysis; for creating wikis and controversy cards which users end up actually using for annotations; for participating in the judgment of reviews; for exposing undesired behaviors on the site; for annotating content; etc.

(I do not assume that Ethereum will figure out how to scale, so it may make sense to hold off on implementation of the blockchain aspects of this proposal until then.)

*A Federated System for Annotating Scientific Papers* - All federated sites can activate libraries of annotations according to Mastodon instance.  These are basically tags where keywords are assigned a ranked, context-filtered list of informational bits, for the purpose of automatic tagging of textual content.  Over time, users and moderators would rate the utility of (and contextually bin) these annotations, with the hope that laypeople can eventually use this tool to understand complex scientific papers.  It's sort of like an annotation version of wikipedia, but specifically directed at helping people to read scientific papers that are difficult to understand.

| [![The Crowdsourcing of Scientific Controversies](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-crowdsourcing-of-scientific-controversies.jpg)](https://www.controversiesofscience.com/crowdsourcing/worldview/card) |
|:---:|
| Mastodon can provide the technology needed to crowdsource scientific controversies |

| [![The Annotation of Scientific Papers](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-annotation-of-scientific-papers.jpg)](https://www.controversiesofscience.com/annotations/worldview/card) |
|:---:|
| What if we were to design the system so that one output of this activity is a set of annotations which can subsequently be directed towards helping laypeople to understand complex scientific papers? |

*Controversy Card Annotations* - This is a library, partially constructed, of topics that are necessary to understand in the domain of scientific controversies.  There are currently [182 controversy cards](https://plus.google.com/collection/Yhn4Y).

Compared to wikis, the controversy card format is more story-based, more focused on the passing on of extraordinary critique, more graphical, and also more useful for sharing content to social media.  The site would moderate the creation of controversy cards, but wikis would be open to everybody.  And since the site's schema enables people to create conflicting wikis and controversy cards in different areas, turf battles between maverick against-the-mainstream thinkers and defenders of existing theory could be replaced with discussion of the actual debate.

*Social Media Article Snapshot Tool* - This would be a tool (possibly a chrome plugin?) for snapshotting science journalism quotes with the same color schema for font color and background, but with preferred font size, custom highlighting and framing options.  The tool would identify the original font, then reconstruct the quote (assuming that the font is accessible).  It would also present a variety of formats which would allow placement of either (or both) of an image and title from the article into the social media share.  I could incorporate this into the existing quotes database as metadata, and open the system to participation by others.

*Federated Science Collective Search* - A component which can be placed onto a Mastodon instance which permits searching through all science collectives.

<p align="center">
    <a href="https://www.controversiesofscience.com">
        <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/controversies-of-science-homepage.png" width="50%" />
    </a>
</p>

*A Process for Grooming Questions Into Testable Hypotheses* - This process is meant as a solution to the publish-or-perish problem, where researchers are subjected to a constant pressure to publish results even though original research can require decades to elaborate.

<a href="">
    <img src="https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-pressure-to-publish.jpg" width="100%" />
</a>

Each stage involves feedback.  The process begins with a question.  These questions do not have to necessarily be original; they can simply be questions about existing hypotheses which a person has just recently learned about.  If vindications can be found, they are then aggregated through a collaborative process known as tracking.  All of this tracking and discussion bins under the unique hashtag which is assigned to the original question.  As tracking progresses, any user can submit a request for review, which involves summarizing the claim, question or controversy as length-limited answers to a series of standard questions for a broader audience, who then weigh in on whether or not a controversy card should be created (the next step in this process).  Tracking does not stop once a controversy card is created, and at any point through the process, challenges can be lodged w/ their own hashtags, which then also become a focus for discussion.

[Mastodon's User Guide](https://github.com/tootsuite/documentation/blob/master/Using-Mastodon/User-guide.md)

> When you have a hashtag search open, it will automatically update with new toots. You can pin the column to keep the search open by clicking the settings symbol at the top right of the hashtag search column and clicking "pin".

*An Interface for Users to Track Numerous Controversial Claims* - This is simply a meta-tracking panel which shows metadata for each of the hashtags which a user is following.

| [![The Anti-Pattern of Settled Science](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-anti-pattern-of-settled-science.jpg)](https://www.controversiesofscience.com/settled-science/worldview/card) | [![Controversy-First Science Education](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-controversy-first-science-education.jpg)](https://www.controversiesofscience.com/controversy-first-science-education/worldview/card) |
|:---:|:---:|
| My thesis is that the tracking of scientific controversies over time is the secret missing sauce to evaluating what claims to focus upon | By flipping our approach, the maverick thinker is motivated to learn to think like a scientist through actual practice |

*A System for Assigning Expertise to Users* - As users track controversies, they are encouraged to establish their expertise through a set of activities: 

1.  They convert their learnings into force concept inventory questions for the purpose of helping others to gain fluency in their controversy.

2.  They present vindications in press releases which are then rated by others across a spectrum of criteria.  When other users agree that a vindication has occurred, they receive points to establish their expertise.

3. They create relevant concept maps, wikis or articles which other users agree add clarity to the controversy.

4. They annotate a crucial scientific paper which relates to their expertise in such a manner that laypeople are now able to understand it.

5. They propose experiments or observations which might vindicate the hypothesis.

(etc.)

The way that we will support these activities is to create the infrastructure required to reward particular activities like those listed above -- from providing the UI necessary to bin these activities, to providing the system necessary for other users to judge the contributions, to then providing the token rewards necessary to encourage the large-scale tracking of scientific controversies, to then also aiding in subsequent discovery by and education of other users.

*A System for Measuring a User's Generalization* - This would be a discovery-type tool which measures the breadth of a user's participation, and helps them to identify their own blindspots through exposure to new controversies outside of their preferred specialization.

| [![The Generalist](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-the-generalist.jpg)](https://www.controversiesofscience.com/generalist/worldview/card) | 
|:---:|
| We need a platform which seeks to revive the generalist scientific tradition if we want groundbreaking breakthroughs to become a regular occurrence again |

| [![Innovation's Long Tail](https://github.com/controversies-of-science/science-collective/blob/master/images/controversy-card-innovations-long-tail.jpg)](https://www.controversiesofscience.com/long-tail/worldview/card) |
|:---:|
| Just as Amazon.com created a "long-tail" business by supporting millions of one-off sales, we can also facilitate collaboration by creating a platform which supports one-off informational exchanges |

I don't expect this feature to exist right away, because there needs to be enough social network history for there to be a need to condense the existing feeds into a more targeted service.

*A System for Categorizing Contributions* - The following list is a schema which can act as the basis for categorizing, rewarding and discovering the informational content that is the backbone for tracking scientific controversies.  I don't expect that participants would always bin these properly, so there would need to be a process for correcting binning mistakes.

**THE CLASH OF WORLDVIEWS**

- *An Observational or Experimental Confirmation* - try to be concise if the link between the two is not immediately obvious; emphasis upon documenting the needed context for a typical layperson to understand it (you can assume they have read the controversy card, points deducted if there is some sort of misunderstanding of the controversy or science).

- *Links to the Best Related Critiques* - short-form journalism ("articles"); emphasis upon basic journalism and science standards; do not fall back upon overly-simplistic filters (like ignoring all publications by a particular source), take the time to actually evaluate the claims; emphasis upon the author's selection of details; upon applicability to the controversy; upon level of detail with the sourcing (please add corrections for broken links); emphasis upon empirical science over other forms (thought experiments, purely observational, excessive reliance upon constructs).

- *Press Releases or Scientific Papers that Relate to this Controversy* - not to be confused with PR's that more properly relate to the challenged theory; emphasis upon significance to the controversy; emphasis upon the logic of the claimed fit; points for filtering out unnecessary information or emphasizing the important bits (either bolding or highlighting); particular emphasis upon relevant points from scientific papers which have not shown up in mainstream science aggregators.

- *Noteworthy Online Discussions* - (please include URL to exchange and take high-resolution snapshots of the exchange by pressing command-plus a few times in your browser to embiggen the snapshotted text) emphasis upon identification of misconceptions or misguided "debunking"; upon proper addition of context (could people understand what the point of this was?); upon surprising claims; upon noting patterns discussed in controversy cards; upon character studies of the main players in online debates; upon any related online censorship; upon people who take the time to run claims and report back on their findings with snapshots; upon any discussions for how to deal with online challenges.  Points always deducted for evidence of any petty or trollish behaviors (or any other violation of the site's own principles when members interact with the larger science community since these behaviors can lead to stereotypes).

- *Observational / Experimental Suggestions* - pretend you are a graduate student who actually had access to facilities, equipment and funding, can you devise a test that might resolve the debate?  emphasis upon whether or not sufficient technical detail was provided to fully understand the idea; upon whether or not people think it might work; points for creative problem-solving.  Don't hold ideas back here if you lack all of the quantitative details, assume that somebody else at a later time may be able to help with that.

- *Crucial Resources* - where would somebody go to get a deeper background in this subject? if it's just a chapter of a larger book, please identify (or if helpful) describe the chapters; emphasis upon whether or not the material is accessible to laypeople, but technical materials are of course important here too; if the material is very technical, the reviewer can rank the material higher if they provide their own annotated version of the resource.  Opinions on how to properly approach the subject are encouraged.

**MODEL TALK**

- *The Best Explanations* - selected according to usage of visuals, clarity on assumptions, good presentation of historical context, thorough conceptual explanation of any presented mathematics, written at a level that a layperson non-scientist can understand.  These pieces should not be rated on the basis of age so long as there is no confusion generated from the introduction of that former context.

- *Modeling Practices & Assumptions* - explanation of some particular modeling practice or assumption (preferably focused on just one at a time), with an emphasis upon how the practice/assumption would be conveyed within scientific papers or press releases (such that the reader is now better equiped to identify this pattern in the future).  Points for emphasis upon hidden practices or assumptions whose exposure alters the interpretation of the results.  This would be a good spot to place discussions about statistics.

- *The History and Origin of the Idea* - emphasis upon unexpected context, little-known historical facts/interpretations or popular beliefs, famous or otherwise important quotes.

- *Tracking the Science Journalism and Public Perception* - emphasis upon tracking changes in the journalism; upon initial expressions of surprise or honest admissions which are subsequently rolled into the model (which can help us to identify hindsight biases); upon any omission of context or detail which undermines the offered conclusions; upon materials presented purely for their clickbait attributes; upon dubious logic.  Extra points for those who take the time to dig up some unexpected science journalism gem from the distant past which gives us some insight on how ideas have transformed over time.

- *Press Releases that Relate to the Challenged Theory* - not to be confused with PR's that are more directly relevant to the controversy, and realize there is a category already dedicated to inconsistences and anomalies; try to focus people on the specific part you want them to read, and help us understand why it should matter to us.

- *Things to Know About Wikipedia's Coverage on This* - think supplemental -- the point is not to replicate work already done on Wikipedia (this is analysis, not duplication); emphasis upon ideology posing as facts, questionable selection of evidence, information about wiki wars and activities of those known to abuse the platform.  If the entry (and its history) is unremarkable and uncontroversial, then this bin should be empty.

- *The Inconsistencies and Anomalies* - emphasis upon internal inconsistencies and any attempts to resolve them -- born of either observations or logic; slight emphasis upon those which are more empirically established, but it's okay if some of these turn out to be to incorrect (let's keep a broad dragnet).

**PROPOSITIONS**

- *Dumb Questions* - emphasis upon how common these questions pop up.

- *Poignant Questions* - do not judge these questions on your perception of whether or not they will prove true; the emphasis is upon asking good questions that can in some way be justified; emphasis upon creativity and synthesis (bringing together two ideas whose connection is not immediately obvious).

- *Creative Conjectures* - a general-purpose bin for conjectures; ranking might not be necessary.

- *Confident Claims*

- *Predictions* - emphasis upon the rationale (does this person know something we previously did not?); points after-the-fact if it proves correct.

**CONCEPTS**

- *Concept Maps* - emphasis upon use of concept maps as a pedagogical tool.

- *Explain the Math* - emphasis upon the conceptual explanation or critique of some mathematics.

- *Multiple Representations in Multiple Agents* - emphasis upon some mismatch in definitions, either according to worldview or domain.

**NARRATIVES**

- *Examples* - emphasis upon exposure of unsupported or faddish narratives; upon effective demonstrations, with evidence, that the narratives are off.
