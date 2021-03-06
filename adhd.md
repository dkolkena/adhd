footer: © Daniel Kolkena
slidenumbers: true
autoscale: true
build-lists: true

## Attention++: Professional Success with Adult ADHD in Tech

#### OpenWest
#### April 10, 2019

---

![left 50%](danprofile.jpg)

# About the Presenter

Daniel Kolkena is a Senior DevOps Engineer with 10 years of industry experience in system administration, software development, and application support. This, despite dropping out of college–twice! He’s passionate about tooling, process optimization, self-improvement, and music from the 1980s.

^ Discuss personal story! "Gifted" child, underachiver in adolescence, chronic underperformer in college and early in career.

---

# Intro

Attention Deficit/Hyperactivity Disorder is a neurodevelopmental disorder that affects up to 5% of adults. It’s an often misunderstood condition that can significantly affect one’s personal and professional life. I’m excited to share insights from a career full of highs and lows managing Adult ADHD and some tools for anyone, ADHD or not, interested in improving their productivity.

^ It's estimated that 5% of adults are affected by ADHD

^ This is an important topic for me because it's affected my professional life so profoundly. I'm happy to share some of the resources I've found along the way.

---

# Disclaimers

![right 50%](scottyandbones.jpg)

**I’m an engineer, dammit, not a doctor!** This talk is _not_ intended to be a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

I have received _no_ compensation for any recommendations I make of treatments, techniques, or products. The information and advice contained herein is solely the result of my own research and experience.

^ I can't diagnose you, and I highly recommend against diagnosing yourself. If you feel like you identify enough with these challenges for a formal diagnosis, talk to your doctor!

^ Any recommendations I make are based on my own experience. I have not been paid for anything I speak about today. Which kind of sucks now that I think about it.

---
[.build-lists: false]
# What will this talk cover?

1. What is ADHD
1. What can I do about it?

^ Take an informal poll: How many people here know they have ADHD? How many suspect they might? You are among friends here.

^ This talk is aimed at people who know or suspect that they have ADHD and want help to succeed in the workplace. I'll talk about what it is, as well as available treatments and techniques to overcome those challenges.

^ Reassure audience that they should feel free to take notes, but there will be links to the slidedeck shared at the end, including citation and external link info.

---
[.hide-footer]

# What is ADHD?

![](erik-mclean-1431586-unsplash.jpg)

---
[.build-lists: false]
## What is ADHD?

>_“A lifelong, persistent pattern of inattention and/or hyperactivity-impulsivity that interferes with functioning or development across time and settings.”_

* Was described as “ADD” in DSM-III in 1980
* Formally defined as “ADHD” in DSM-IV in 1994
* Current definition has 3 subtypes: **Predominantly Inattentive**, **Predominantly Hyperactive-Impulsive**, and **Combined Presentation**
* The condition onsets in childhood. Up to 5% of children may meet the diagnostic criteria. 1/3 to 2/3 of children diagnosed will continue to exhibit symptoms through adulthood.

---
[.build-lists: false]

# [fit] DSM diagnostic criteria for **Inattention**

* Often fails to give close attention to details or makes careless mistakes in schoolwork, at work, or with other activities.
* Often has trouble holding attention on tasks or play activities.
* Often does not seem to listen when spoken to directly.
* Often does not follow through on instructions and fails to finish schoolwork, chores, or duties in the workplace (e.g., loses focus, side-tracked).
* Often has trouble organizing tasks and activities.
* Often avoids, dislikes, or is reluctant to do tasks that require mental effort over a long period of time (such as schoolwork or homework).
* Often loses things necessary for tasks and activities (e.g. school materials, pencils, books, tools, wallets, keys, paperwork, eyeglasses, mobile telephones).
* Is often easily distracted
* Is often forgetful in daily activities.

^ The Inattention subtype deals with being easily distracted or forgetful. Symptoms include things like daydreaming, struggling to stay on task, and a general lack of organization.

^ For adults, at least 5 symptoms from this list are required.

---
[.build-lists: false]

# [fit] DSM diagnostic criteria for **Hyperactivity and Impulsivity**

* Often fidgets with or taps hands or feet, or squirms in seat.
* Often leaves seat in situations when remaining seated is expected.
* Often runs about or climbs in situations where it is not appropriate (adolescents or adults may be limited to feeling restless).
* Often unable to play or take part in leisure activities quietly.
* Is often “on the go” acting as if “driven by a motor”.
* Often talks excessively.
* Often blurts out an answer before a question has been completed.
* Often has trouble waiting his/her turn.
* Often interrupts or intrudes on others (e.g., butts into conversations or games)

^ The Hyperactive subtype deals with feeling restless and fidgety. This is the "classic" stereotype of ADD.

^ For adults, at least 5 symptoms from this list are required.

---
[.build-lists: false]

# Further diagnostic criteria

In addition to the previous criteria, you must have

* Several inattentive or hyperactive-impulsive symptoms were present prior to age 12 years.
* Several inattentive or hyperactive-impulsive symptoms are present in two or more settings (e.g., at home, school, or work; with friends or relatives; in other activities).
* There is clear evidence that the symptoms interfere with, or reduce the quality of, social, academic, or occupational functioning.
* The symptoms do not occur exclusively during the course of schizophrenia or another psychotic disorder and are not better explained by another mental disorder (e.g., mood disorder, anxiety disorder, dissociative disorder, personality disorder, substance intoxication or withdrawal).

---

# Causes of ADHD

* There’s no scientific consensus on a single cause
* Research points to a heavily genetic component; there’s evidence for environmental factors as well
* Predominant theory: dopamine and norepinephrine neurotransmitters don’t work the same way a neurotypical brain does, so we don’t receive the standard reward feedback for accomplishing tasks

^ Discuss pervasive myths: sugar, caffeine, the teevee, that dang rock music that all the kids listen to

^ Reward feedback loop: our brains don't feel the same sense of reward as neurotypical brains

^ OTOH, for intrinsically motivation activities, it's easy to hyperfocus

---
![right fit](todolists.jpg)

# Areas of Difficulty Managing Daily Activities

* Poor self-management relative to time, planning, and goals
* Poor self-organization, problem solving, and working memory
* Poor self-discipline (inhibition)
* Poor self-motivation
* Poor self-activation, concentration, and alertness

^ The prefrontal cortex is responsible for what we call Executive function: attention control, inhibition, working memory, time management, and problem solving.

^ This is why we might struggle to complete a simple documentation update or bugfix, but spend several hours tinkering with bash dotfiles or tmux settings. Or do all the chores at home we've been putting off instead of

---

![right 150%](ADD_Comorbility.gif)

# Comorbidities

* Depression
* Anxiety
* Oppositional Defiant Disorder (and Conduct Disorder)
* Tic disorders
* Autism spectrum disorders

^ Depression: could be reaction to environmental stressors, or sometimes correlate with bipolar (impulsivity). Imagine the effect of constantly being told you failed just because you didn't try hard enough etc.

^ Anxiety: sense of impending doom (exacerbated by procrastination), mood swings, lack of energy, low self-esteem, imposter syndrome

^ ODD: refusing to comply with rules, frequent periods of anger/resentfulness, potentially issues with unhealthy criminal behavior

^ Tics could include vocal tics, motor tics, nervous habits like nail biting/nose picking/hair pulling/knuckle cracking/jaw clenching, even Tourette's

^ Like ADHD, Spectrum disorders can affect language skills, behavior, social interactions, and the ability to learn. Share "neurodiversity", share some elements with ADHD but are a separate diagnosis.

---
[.build-lists: false]

# Imposter Syndrome

* A feeling that any success or achievement is due to luck and not one's own talent or effort
* A persistent fear of being exposed as a "fraud"
* A feeling that you "don't belong here"

Remember: _actual_ imposters almost never suffer from imposter syndrome.

You can do the hard thing!

^ This is a HUGE thing in tech!

^ A pattern of failure will lead to internalized low self-esteem

^ These feelings of inadequacy can linger despite any evidence to the contrary or external validation

---
![right 125%](squirrel.png)

# How does this affect my life?

* Work
* Relationships
* Finances
* Health

^ Work: Intelligent but underperformed in school, Project an incorrect professional perception, Taking all day to complete a 15 minute task, Procrastinating and poor planning, Inflating progress during standup

^ Relationships: Forgetting important dates and info, giving the perception of ignoring or undervaluing significant other

^ Finance: Forgetting bills, poor money planning due to impulsivity

^ Health: Poor diet due to lack of planning and impulsiveness, failing to follow through long term with plans, putting off or forgetting doctor appts

---

# If you’re not sure: get a professional diagnosis

Your primary care physician can refer you to a licensed clinician, such as a neurologist or psychiatrist

These tests can be long, stressful, and expensive, but is the only way to be officially diagnosed

^ Everyone experiences these symptoms in a limited capacity. It reaches the level of a diagnosable illness if it's chronic, pervasive, and negatively affects your quality of life

---
[.hide-footer]

# Management strategies and mitigation techniques

![](aravind-vijayan-534010-unsplash.jpg)

---

# Professional treatment

* Cognitive Behavioral Therapy (CBT)
* ADHD Coaching
* Medication

^ First step is understanding and accepting the diagnosis. There's no easy cure. Nothing will make this not a challenge.

^ CBT focuses on improving habits and behavior by practicing healthy coping mechanisms

---
![right 200%](medicine.jpg)
# Medication

* Stimulant: Adderall, Ritalin, Concerta, Vyvanse, etc.
* Non-stimulant: Strattera, Clonidine, Guanfacine, etc.
* Everyone reacts differently to different medications
* Work with your doctor to find what works for you

^ Stimulant meds trick the brain into producing chemicals at a rate much closer to that of neurotypical brains. Many of us already self-medicate with caffeine!

^ --Side effects include lack of appetite, restlessness, mild euphoria, small potential for abuse if not used as indicated by doctor

^ Non-stimulant medications help by boosting norepinephrine, decreasing impulsivity – less risk of abuse, take longer to work

^ There is no single drug that works for everyone! What works for me might be awful for you, and vice versa. Figuring out drug/dosage is a process with your doc

^ It's also possible that no drugs are ideal or worth the side effects. Some people choose not to medicate, and that's okay!

---

# Non-medication treatment

Exercise, sleep, and good nutrition can help but do not represent a comprehensive treatment plan by themselves

^ Meditation and mindfulness exercises are also helpful!

^ Stress management techniques, supportive community, etc.

---

# Optimize your work

* Find roles that leverage your strengths and minimize your weaknesses
* Our brains thrive on novelty, not routine

^ It could be our strengths are more aligned to reactive work instead of proactive work - Ops, Support, etc. Or we may be good at big picture architecture rather than routine bugfixes

---

# Be honest with yourself!

* Don't take on more than you're comfortable with!
* Give yourself buffer time to deliver your commitments.
* Don’t be afraid to ask for help!

^ Taking on too much leads to a cycle of overpromise/underdeliver and instills a sense of hopelessness and failure. Look at your previous successes and failures and your work throughput. Use that to give yourself a baseline of what you can reasonably commit to.

^ 2 story points but you’re not confident in the implementation details yet? Make it 3 or 5. Consistently delivering commitments on time–even if it’s less than you think you might be capable of–will give you confidence and develop your reputation.

---

# Time management strategies

* Pomodoro, timeboxing, pair programming
* Browser extensions/apps to disable or eliminate distractions (email, social media)
* Physical planner

^ We're bad at time management, and any system we use to fix that needs to take that into account

---
[.build-lists: false]
# Organizational tools

* Google Suite, [OneNote](https://products.office.com/en-us/onenote/digital-note-taking-app), [Evernote](https://evernote.com/), [Trello](https://trello.com), [Wunderlist](https://www.wunderlist.com/), [Workflowy](https://workflowy.com), [Airtable](https://airtable.com/), [Todoist](https://todoist.com), [Notion.so](https://www.notion.so/), even CLI tools
* Physical notebook w/ pen

Don't be afraid to evaluate different tools to figure out what works for _you_.

^ Being asked for a status update for a task you've forgotten about is humiliating.

^ Take notes constantly, this can make all the difference. Don't be afraid to invest lots of "overhead" time into writing and reviewing notes. My productivity went through the roof once I committed to capturing as much as possible in meetings.

---

# Workspace changes

* Darker dev environment (Eliminate visual distractions)
* Dark UI, IDE
* Quiet space/headphones
* Work with team to establish optimum communication channels
* Offsetting your working hours

^ Communications in whatever manner works best for your cognition and retention (face to face/conference calls/group chat/email)

---

# Communication with management and team

* ADA legally protects “reasonable accommodation” requests
* Can ask for shorter feedback cycles
* Detailed acceptance criteria
* Ask about mentorships (a great resource for a professional at any stage in their career!)
* **Caveat:** professional risk

^ Being upfront about your needs can be reassuring to your team and supervisor

^ However, some people believe it doesn’t exist/is an excuse for laziness

^ --That could give the impression of laziness or casualness that doesn't describe the real you

---

![fit](twosides.jpg)

^ We have cognitive challenges that affect our lives, but they can also be a source of our unique creative power

^ We're patient, empathetic, and compassionate; able to see big picture ideas, passionate about what drives us

---

> "And now that you don't have to be perfect, you can be good."
-- John Steinbeck, _East of Eden_

^ Self-improvement is a life-long challenge. You're going to fail. But that's okay. We improve by degrees.

^ You can do the hard thing!

---

## Questions?

Feel free to reach out!

Email: daniel.kolkena@gmail.com
Twitter: @dkolkena

This slidedeck is available at:
**http://tinyurl.com/adhd-openwest**
The sourcecode can be found at:
**https://github.com/dkolkena/adhd**

<sub>This presentation was built in Markdown with [Deckset](https://www.deckset.com/).</sub>

---
[.build-lists: false]
### Resources
* *Taking Charge of Adult ADHD* by Russell A Barkley
* The ADHD subreddit [/r/ADHD](https://www.reddit.com/r/ADHD/)
* Dani Donovan ([adhddd.com](https://adhddd.com))
* Jessica McCabe's excellent [How to ADHD](https://howtoadhd.com/) series

### Citations
* https://www.addrc.org/dsm-5-criteria-for-adhd/
* https://www.nimh.nih.gov/health/topics/attention-deficit-hyperactivity-disorder-adhd/index.shtml
* https://en.wikipedia.org/wiki/Adult_attention_deficit_hyperactivity_disorder
* https://add.org/adhd-facts/

---

<!--

# Photo and art credit

* Photo by [Erik Mclean](https://unsplash.com/photos/Tso1j6dz0H8) on [Unsplash](https://unsplash.com)
* Photo by [Aravind Vijayan](https://unsplash.com/photos/Go6jxhtleYs) on [Unsplash](https://unsplash.com)
* Photo from Pixabay
-->
