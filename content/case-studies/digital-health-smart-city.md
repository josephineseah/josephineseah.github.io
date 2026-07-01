+++
date = '2026-03-14'
draft = true
title = 'Digital Health in the Smart City'
summary = 'What happens when users do not engage with digital health programs as designed, and what can we learn from these moments of friction?' 
+++

# Overview and Research Questions 
This project examined the National Steps Challenge (NSC), a nationwide digital health initiative in Singapore delivered via the Healthy 365 mobile app. The programme incentivizes physical activity through wearables, app-based tracking, and rewards. 

The initiative sits at the intersection of public health, behavioural incentives, and smart city infrastructure. 

Large-scale digital health platforms often assume that users have stable daily routines, continuous device functionality, alignment between health goals and incentive structures, and willing participation in user tracking. Nonetheless, real-world engagement is often messy and contingent. In light of this, this project asked: 

What happens when users do not engage with digital health programs as designed — and what can these moments of friction reveal?

# Methodology and Timeline 
- Given that the goal was to understand lived interaction with the NSC and not measure adoption, I chose a qualitative approach for this project.
- I conducted semi-structured in-depth interviews with 51 Singapore residents who were either previous or active participants in the NSC
    - Interviews were held between October 2022 and June 2023
    - The interviews lasted between 30 and 90 minutes
    - Thematic coding using grounded theory, supplemented by reflexive memo-writing (using Atlas.ti)

# Findings

## 1. Users optimize for the incentive structure rather than health goals. 

When a program rewards step counts, users optimize for step counts. This is an intuitive finding, but it has significant implications for how the NSC functions in practice. The study found that participants engaged in a range of tactical adaptations: strategic gaming of their step counts, device sharing within households, running multiple trackers simultaneously, and coordinating participation to maximize reward payouts. None of these behaviours are irrational. They are, rather, highly rational responses to the NSC’s reward structure. 

Consider, for instance, one participant’s experience of asking her sister to reach her step count for her:

> Last night, I wanted to hit ten thousand steps, but I didn’t manage to do it by the time I was going to sleep. So, I asked my sister to help me because she was going out in the evening. I think I was at about six thousand plus, but I wanted to hit the 10k [to get my points], right? But I also told her “By the way, can you put it back on when I’m sleeping? I want to use it to track my sleep [as well].”

**Implication**: Incentive systems always produce second-order optimization behaviours, where the metric being measured becomes the goal, rather than the underlying outcome the metric was meant to proxy (i.e., Goodhart’s Law). The data generated under these conditions reflect how users engage with a reward system and rather little about their physical health. For teams using behavioural data to make decisions — e.g., health policies — this distinction needs to be taken into account as a structural feature of how incentivized self-tracking works (or doesn’t).  

## 2. "Bad Data" can be a good signal. 
Data quality frameworks may treat device sharing, familial pooling, and irregular tracking patterns as noise to be filtered out. My study suggests a different reading. Rather than interpreting these actions as failures of individual compliance, we can see such practices as speaking to the **social dynamics of shared technologies**. When a single wearable circulates among family members to maximize collective rewards, as the quote below illustrates, rather than to negate such data we can see it as a record of participation at the level of the household, instances of (economic) coordination, and collective negotiation of system rules. 

> “Sometimes, if my mom needs to clock her steps, I’ll just take her tracker and go for a run. That will close it up to her goal for her to get her rewards.”

Separately, another participant told me of how she was responsible for managing her parents NSC accounts (i.e., their Healthy 365 app) and would use the accumulated Healthpoints to collectively offset her household expenses. 

**Implication**: Treating such patterns as errors or negating this data risks ignoring how some platforms actually become embedded in everyday life. The practices above suggest that an **oft-neglected unit of participation lies in the household**: a site of shared devices, pooled rewards, and collective management. This has consequences for how product and data teams should think about user modelling, segmentation, and the design of participation structures. Frameworks that are built on the lone individual-user assumption can misinterpret collective participation as noise. In turn, reframing the unit of analysis from the individual to the household can surface a more accurate picture of how these technologies operate in everyday life.  

## 3. Friction can sustain systems over time. 
Perhaps the most counterintuitive finding of this research is that the NSC remained popular and durable despite it’s well-known hardware and software issues. Participants reported experiencing, over the course of their years of engagement with the challenge, everything from broken straps from issued health trackers to faulty charging mechanisms and unresponsive syncing troubles. All through these frictions, participants would leave *and return* to the challenge, drawn back in by its incentives and by the ease with which they could develop workarounds to resolve these issues. 

As seen above, users did not simply comply with the system as designed. They redirected its incentives towards economic ends, integrated it into family and social routines, and repurposed its reward structures for goals the platform never intended, ultimately making it useful in ways that departed from its stated mission.

**Implication**: This suggests that long-term platform durability may depend on leaving room for user reinterpretation. Rigid systems that penalize deviation and enforce narrow participation models can achieve short-term data quality at the expense of long-term engagement. Systems that are designed to accommodate flexible participation, on the other hand, admittedly at the expense of behavioural legibility, may prove to be more resilient precisely because users can adapt them to their own contexts and needs. For platform designers and policy teams, this reframes the relationship between friction and failure. Rather than a design flaw to be engineered out, friction can sometimes be a mechanism through which users make a system their own. 

# So what? 
The frictions above do not prescribe a single fix. Instead, I suggest that they unsettle assumptions that tend to be widespread in the design and evaluation of behavioural platforms; and that they point to a different set of questions that practitioners could ask instead. 

1. **Audit incentive structures along with your data**. If users are optimizing for rewards rather than a stated mission, rather than asking “how can we clean this data?”, perhaps a more productive question could be, “what is our system actually rewarding?” Product and data teams working with incentive-based platforms should routinely examine the gap between intended and actual optimization behaviour. Where that gap is large, behavioural data may be measuring incentive strategies rather than the outcome it was designed to proxy. Closing that gap begins with honest incentive design. 
2. **Treat data anomalies as diagnostic**. Patterns that fail data quality thresholds — irregular activity, shared device signatures, coordinated participation — share often read as noise. This study suggests that they can be instead read as signals of how a platform is actually embedded in users’ lives. Before filtering them out then, we might ask what the anomaly reveals about structural mismatches between system assumptions and real-world conditions. Building this diagnostic step into data governance workflows can surface insights that clean data along cannot. 
3. **Design for user adaptation**. Platforms that accommodate flexible participation may prove more durable than those that enforce narrow usage. If users are actively reshaping a system to fit their own contexts and returning to it repeatedly, that indicates a form of system resiliency worth understanding and enabling. One implication of this is to resist the reflex to close off workarounds and adaptations and instead ask what they reveal about unmet needs or misaligned assumptions.

# Reflections 

I thoroughly enjoyed doing this project, particularly learning of the different ways that users found to game their step counts.

That being said, I reached data saturation in the mid-thirties (out of 51 interviews) but continued recruiting given the strong response to my call for participants. In retrospect, the additional interviews added nuance at the margins rather than substantively changing my findings. 

The more significant lesson was methodological: because I had not yet begun transcribing or coding when I was still in the field, I only recognized saturation in hindsight. Despite having read widely on fieldwork best practices, this was my first sustained experience of doctoral fieldwork, and I had not yet developed the instinct to run data collection and analysis concurrently. Had I done so, I would have identified saturation earlier and stopped sooner. The practical cost of not doing so was real — the volume of back-to-back interviews was exhausting, and I reached the end of my fieldwork having burned myself out, falling ill towards the end.