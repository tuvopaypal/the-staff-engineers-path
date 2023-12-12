# The Staff Engineer's Path

## Introduction

**Big-picture thinking**

Big-picture thinking means being able to step back and take a broader view. It means seeing beyond the immediate details and understanding the context that you're working in. It also means thinking beyond the current time, whether that means initiating yearlong projects, building software that will be easy to decommission, or predicting what your company will need in three years.

**Execution**

At the staff level, the projects you take on will become messier and more ambiguous. They'll involve more people and need more political capital, influence, or culture change to succeed.

**Leveling up**

Every increase in seniority comes with more responsibility for raising the standards and skills of the engineers within your orbit, whether that's your local team, colleagues in your organization, or engineers across your whole company or industry. This responsibility will include intentional influence through teaching and mentoring, as well as the accidental influence that comes from being a role model.

You're going to need "humaning" skills, like:

-   Communication and leadership
-   Navigating complexity
-   Putting your work in perspective
-   Mentorship, sponsorship, and delegation
-   Framing a problem so that other people care about it
-   Acting like a leader whether you feel like one or not

## Part I. The Big Picture

### Chapter 1. What Would You Say You Do Here?

Three reasons titles are necessary: "Helping people understand that they are progressing, vesting authority in those people who might not automatically receive it, and communicating an expected competency level to the outside world."

Good decisions need context. Experienced engineers know that the answer to most technology choices is "it depends." Knowing the pros and cons of a particular technology isn't enough—you need to know the local details too. What are you trying to do? How much time, money, and patience do you have? What's your risk tolerance? What does the business need? That's the context of the decision.

To avoid local maxima, teams need decision makers (or at least decision influencers) who can take an outsider view—who can consider the goals of multiple teams at once and choose a path that's best for the whole organization or the whole business.

Just as important as seeing the big picture of the situation now is being able to anticipate how your decisions will play out in future. A year from now, what will you regret? In three years, what will you wish you'd started doing now?

TPMs are responsible for delivery, not design, and not engineering quality. TPMs make sure the project gets done on time, but staff engineers make sure it's done with high engineering standards.

Staff engineers are role models. Managers may be responsible for setting culture on their teams, enforcing good behavior, and ensuring standards are met. But engineering norms are set by the behavior of the most respected engineers on the project. No matter what the standards say, if the most senior engineers don't write tests, you'll never convince everyone else to do it. These norms go beyond technical influence: they're cultural, too. When senior people vocally celebrate other people's work, treat each other with respect, and ask clarifying questions, it's easier for everyone else to do that too.

Like it or not, humans pay attention to status and hierarchies—and reporting chains. You're likely to have much less influence if you're reporting to a line manager. The information you get is also prone to be more filtered and centered on the problems of that specific team. If your manager doesn't have access to some piece of information, you almost certainly won't either.

Be prepared to ignore your scope when there's a crisis: there is no such thing as "not my job" during an outage, for example.

If your scope is too broad (or undefined), there are a few possible failure modes:

-   **Lack of impact**. If anything can be your problem, then it's easy for everything to become your problem, particularly if you're in an organization with fewer senior people than it needs. There will always be another side quest: in fact, it's all too easy to create a role that's entirely side quests, with no real goal at all.9 Beware of spreading yourself too thin. You can end up without a narrative to your work that makes you (and whoever hired you) feel like you achieved something.
-   **Becoming a bottleneck**. When there's a senior person who is seen to do everything, the convention can become that they need to be in the room for every decision. Rather than speeding up your organization, you end up slowing them down because they can't manage without you.
-   **Decision fatigue**. If you escape the trap of trying to do everything, you'll have the constant cost of deciding which things to do. I'll talk in Chapter 4 about choosing your work.
-   **Missing relationships**. If you're working with a very broad set of teams, it's harder to have enough regular contact to build the sorts of friendly relationships that make it easier to get things done (and that make work enjoyable!). Other engineers also lose out: they don't get the sort of mentorship and support that comes from having a "local" staff engineer involved in their work.

But watch out for the risks of a scope that's too narrow:

-   **Lack of impact.** It's possible to spend all of your time on something that doesn't need the expertise and focus of a staff engineer. If you choose to go really deep on a single team or technology, it should be a core component, a mission-critical team, or something else that's very important to the company.
-   **Opportunity cost.** Staff engineers' skills are usually in high demand. If you're assigned to a single team, you may not be top of mind for solving a problem elsewhere in the org, or your manager may be unwilling to let you go.
-   **Overshadowing other engineers**. A narrow scope can mean that there's not enough work to keep you busy, and that you may overshadow less experienced people and take learning opportunities away from them. If you always have time to answer all of the questions and take on all of the tricky problems, nobody else gets experience in doing that.
-   **Overengineering**. An engineer who's not busy can be inclined to make work for themselves. When you see a vastly overengineered solution to a straightforward problem, that's often the work of a staff engineer who should have been assigned to a harder problem.

The four disciplines that are needed in any job in the world:

-   **Core technical skills.** Coding, litigation, producing content, cooking—whatever a typical practitioner of the role works on
-   **Product management.** Figuring out what needs to be done and why, and maintaining a narrative about that work
-   **Project management.** The practicalities of achieving the goal, removing chaos, tracking the tasks, noticing what's blocked, and making sure it gets unblocked
-   **People management.** Turning a group of people into a team, building their skills and careers, mentoring, and dealing with their problems

### Chapter 2. Three Maps

When you join a new company, most of the big picture is completely unknown to you. A big part of starting a new job is building context, learning how your new organization works, and uncovering everyone's goals. Think of it like the fog of war in a video game.

For example:

-   Your locator map can help you make sure the teams you work with really understand their purpose in the organization, who their customers are, and how their work affects other people.
-   Your topographical map can help highlight the friction and gaps between teams and open up the paths of communication.
-   Your treasure map can help you make sure everyone knows exactly what they're trying to achieve and why.

Four risks:

-   **Prioritizing badly.** When everyone around you cares about the same set of things, it's easy to magnify the importance of those things. The problems that exist outside your group can start to appear simple or unimportant by comparison. That's why you see teams making those local maximum decisions I talked about in Chapter 1: the local maximum starts to feel really important. The more time you spend staring at your own group's problems, the more they seem special and unique and worthy of special, unique solutions. And sometimes they are! But it's unusual to find a problem that is genuinely brand new. If you check for prior art and preexisting solutions, you'll spend less time reinventing wheels.
-   **Losing empathy.** It's easy to overfocus and forget that the rest of the world exists, or start thinking of other technology areas as trivial compared to your rich, nuanced domain. It's like you start looking at the world through a fish-eye lens that makes the thing right in front of you huge and squeezes everything else into the periphery. You can lose empathy for the work other teams are doing: "That problem they're solving is easy. I could solve it in a weekend." The words you use, the things you choose to explain versus those you leave implicit, and the motivations you ascribe to other people will all be influenced by your perspective. That's why it can be so difficult for engineers to communicate with nonengineers. Loss of empathy shows up in incidents, too, where teams can get absorbed in the interesting technical details of the problem and forget there are users waiting for the system to be back online.
-   **Tuning out the background noise.** If one failure mode is your team's concerns seeming more important than everyone else's, another is the exact opposite: you stop noticing problems at all! If you've been working around the same mucky configuration file or broken deploy process for months, you might get so used to it that you stop thinking of it as something you need to fix. Similarly, you might not notice that something that started out as just slightly annoying has slowly become worse. Maybe a problem is close to becoming a crisis, but you don't even notice it anymore, so you can't be objective about how quickly you need to react.1
-   **Forgetting what the work is for.** Being in your silo can mean that you lose your connection to what's going on elsewhere in the company. If your group originally took on some project to solve a larger goal, the project might still be ongoing even though the goal no longer matters or has already been solved in some other way. If you're working only on your own little part of a project, it's easy to stop thinking about what the project is for. You can slip into a world where everyone does their own little part and nobody feels like they're responsible for the end result. You can lose sight of the ethics of what you're doing, too, and find yourself working on something that you wouldn't really be OK with if you stepped back and thought about the whole picture.

When the new person on your team looks at an architectural tangle or a pile of technical debt, they have no historical context. As my colleague, Dan Na, says, a new person can always see the problems. They haven't been around for the gradual change and the boiling frogs: they're just seeing the raw situation as it is. Without preconceptions, they're free to look around and ask, "What's really happening here? Is any of this working?"

Go beyond engineering: build relationships with product folks, customer support, administrative staff, and more. If your work affects them or their work affects you, go be friendly and understand their point of view. It will give you a whole new way of thinking about what's important to your department or your business.

Charity Majors, CTO of Honeycomb, often hands out stickers that say: "Nines don't matter when users aren't happy."

You need to measure success from your users' point of view. (If your customers are other teams inside your company, this still applies!) If you don't understand your customer, you don't have real perspective on what's important.

Let's explore some of the difficulties you'll face if you set out on a mission without a detailed map of the terrain:

-   **Your good ideas don't get traction.** Being right about a need for change is less than half the battle. You'll have to convince other people that you're right and, even more difficult, convince them to care that you're right. That means knowing how to build momentum within your organization: figuring out who can sponsor your idea or help it spread, and how you can get it over the finish line and make it "real."
-   **You don't find out about the difficult parts until you get there.** Many obvious-seeming journeys have some crucial point that nobody has figured out how to get past. You may be attempting to scale a cliff that's defeated many other people before. Staff engineers can often navigate past obstacles that less experienced engineers can't, and it's possible that you'll be able to succeed where others have failed. But if you know where people got stymied in the past, you can take a different path or solve the hardest part of the problem first, so other people will be convinced the project is worth their effort.
-   **Everything takes longer.** Unless you know how your organization works, decisions that should be straightforward will take months or quarters. The mechanics of your organization's planning cycles will affect you too. There are times of year when it'll be easier to make the case for staffing a new project or to rally everyone behind some goal. If you announce an initiative immediately after the quarterly engineering OKRs have been set, you'll have a hard fight and you may have to wait a quarter before you'll see any progress toward your goal.

Secret or open? How much does everyone know? In secret organizations, information is currency and nobody gives it away easily. Everyone's calendars are private. Slack channels are invite-only. Often you can get access to something if you ask for it, but you have to know it exists! When all information is need-to-know, it's harder to come up with creative solutions or really understand why something's not working.

One team I worked in had a cowboy hat that would end up on the desk of whichever team member had last done something a little too "Wild West." It was affectionate, but it was a good reminder too.

Where do initiatives come from? A completely bottom-up culture is one where employees and teams feel empowered to make their own decisions and champion the initiatives they think are important. However, when those initiatives need broader support, they slow down. If teams disagree about direction or priority, the lack of a central "decider" can lead to deadlock.

On the other hand, people in a fully top-down company will find it much easier to choose initiatives and take decisive action. Those decisions won't be the best ones, though, because they're missing local context. The engineers likely feel controlled and won't be empowered to react to changes as they arise.

Fortresses are teams or individuals who seem determined to stop anyone from getting projects done. Maybe you need their approval but can't get time with them. Or maybe they're gatekeepers and seem to decide your idea is bad before they even know what you're asking. Although some fortresses are petty tyrants, the majority are well-intentioned. They gatekeep because they care. They're trying to keep the quality of the code or architecture high and keep everyone safe.

To pass through the fortress gates, you might need to bring a token of sponsorship from someone the gatekeeper respects, or know the password to lower the drawbridge. (Common passwords include proving that you've mitigated all of the risks of your proposed change, completing lengthy checklists or capacity estimates, or replying to huge numbers of document comments with acceptable answers.)

Unfortunately, not all roads are well paved. We've all tried to solve a problem the official way for a long time before someone told us the secret path to success: the undocumented search feature, the admin who can set up an account for you, or the one person in IT who responds to DMs.

Remember that cartography is inherently political: what you choose to include says something about you as well. Pay attention to what you put at the center of the map and where you're inclined to take sides.

If you don't understand how decisions are made in your organization or company, you'll find yourself unable to anticipate or influence them.

If you've watched the musical Hamilton, you'll remember Aaron Burr's craving to be "in the room where it happens." As Burr tells us, people who aren't in the room "don't get a say in what they trade away".

Figure out where decisions are happening.

Adding someone to a group is rarely free for the people who are already there. Every extra person in any meeting slows it down, extends discussions, and reduces attendees' willingness to be vulnerable or brutally honest. If the group is used to working together, every new person resets the dynamic; to some extent, attendees have to learn to work together again.

Will Larson's article "Getting in the Room" emphasizes that as well as adding value to the room, you need to reduce the cost of including you: show up prepared, speak concisely, and be a collaborative, low-friction contributor. If you make the room less effective at making decisions or sharing information quickly, you won't be invited back.

The "shadow org chart": the unwritten structures through which power and influence flow. The shadow org chart helps you understand who the influencers of the group are, and it's probably not the same as the actual org chart. These influencers are the people you need to convince before a change can happen.

The authors identify "connectors" who know people all across the org, and "old-timers" who, regardless of rank or title, wield influence just from being around a long time. These folks are likely to have a good pulse on what can and can't work, and the people who do have rank and title will likely trust them and rely on their good judgment when making decisions.

I asked on Rands Leadership Slack about how everyone approaches knowing things, and a common thread was paying attention to information that isn't secret exactly, but isn't necessarily for you. This included reading senior people's calendars, skimming agendas or notes for meetings you're not in, and—something that had never occurred to me—looking at the full list of Slack channels sorted by most recently created so you can see what new projects are happening.

The problems that slow down tech organizations are most often human ones: teams that don't know how to talk to each other, decisions that nobody feels empowered to make, and power struggles.

### Chapter 3. Creating the Big Picture

A technical vision describes the future as you'd like it to be once the objectives have been achieved and the biggest problems are solved. Describing how everything will be after the work is done makes it easier for everyone to imagine that world without getting hung up on the details of getting there.

A technical vision is sometimes called a "north star" or "shining city on the hill." It doesn't set out to make all of the decisions, but it should remove sources of conflict or ambiguity and empower everyone to choose their own path while being confident that they'll end up at the right place.

A strategy is a plan of action. It's how you intend to achieve your goals, navigating past the obstacles you'll meet along the way. That means understanding where you want to go (this could be the vision we just discussed!) as well as the challenges in your path. When I use the word strategy in this chapter, I always mean a specific document, not just being a strategic sort of thinker.

Take a tactic from the Internet Engineering Task Force (IETF), whose principles of decision making famously reject "kings, presidents, and voting" in favor of what they call "rough consensus," positing that "lack of disagreement is more important than agreement." In other words, take the sense of the group, but don't insist that everyone must perfectly agree. Rather than asking, "Is everyone OK with choice A?" ask, "Can anyone not live with choice A?"

Not deciding is a decision (just usually not a good one). When you're choosing between Option A and Option B, there's an implicit third option, C: don't decide. People often default to Option C, because it lets them stay on the fence and not upset anyone. This is the worst thing you can do. Decisions constrain possibilities and make it possible to make progress. Not deciding is in itself a decision to maintain the status quo, as well as the uncertainty that surrounds it.

If you're stuck, timebox it. Instead of saying, "We'll choose the best storage system on the planet," try, "Let's research storage systems for the next two weeks and choose by the end of that time."

Making someone unhappy is, unfortunately, inevitable when you're creating a strategy or vision. If everyone gets their wish, it's unlikely that you made any real decisions.

## Part II. Execution

### Chapter 4. Finite Time

There's infinite work. There's exactly one of you. Everything you commit to has an opportunity cost. By choosing to do one thing, you're implicitly choosing not to do another.

Executive coach Fabianna Tassini of Confidantist gave me the best advice for managing my workload: put nonmeetings in the calendar too.

There's a barrier to entry: you must have this much energy to be able to start this task.

Understand what kinds of work are expensive for you, and what kinds will leave you with some smartbrain at the end of the day.

When I asked on Twitter what causes a loss of credibility, one of the big themes was absolutism: if you're a fan of some technology and advocate for it in every single situation, people will stop believing you know what you're talking about.

Credibility extends to your skills as a leader, too. If you're polite (even to annoying people), communicate clearly, and stay calm in stressful situations, other people will trust you to be the adult in the room. If you are rude or highly dramatic, send emails that are unreadable walls of jargon, or make all-hands meetings wait while you ask a rambling question that only applies to you, it will have the opposite effect.7 You will build credibility as a professional every time you take on a chaotic situation and make it easier for everyone else to understand. You'll lose credibility when you're seen as contributing to the chaos, or when a project goes badly and you don't do a good job of navigating the failure.

Whether we talk about it or not, everyone has a bank account of capital with each of the people they know. If someone has built up credit with you, you're more likely to do them a favor or give them the benefit of the doubt. Social capital is a mix of trust, friendship, and that feeling of owing someone a favor, or of believing they'll remember that they owe you one.

Social capital builds up over time, and you'll need more of it with some people than others. In general, you'll want to stay on good terms with the people in your reporting chain and build a track record of helping them achieve their goals. If there's a business-critical problem and you refuse to help, or you take on an important project and don't complete it, you'll burn goodwill. And if you always ask for favors but never repay them, you'll start to find it difficult to get people to help you.

As Alexandre Dumas said, nothing succeeds like success.

The skills resource behaves a little differently from the others, because it's always slowly decreasing. That doesn't mean you're forgetting what you know (though you will lose fluency with technologies or techniques that you don't use for a long time); it means that any technical skill set slowly becomes less relevant and eventually gets out of date. Our industry moves fast. If you take on projects that teach you nothing (or at least nothing that's relevant to the projects or roles you want), you won't keep up with the rate of decrease.

As you work through your career, you'll increase your skills bar in three main ways.

-   The first is by deliberately setting out to learn something: you take a class, buy a book, or hack on a toy project. While this kind of structured learning can often happen at work, you may struggle to find time for it, and find it spilling into your free time.
-   The second way is by working closely with someone who is really skilled. Being the least skilled person on a team of superstars will teach you more than being the best person on an otherwise mediocre team. When you work with great people, it's almost impossible to avoid becoming greater yourself.
-   The third way—and the most common, I think—is learning by doing. You get better at what you spend time on. If there's a skill you want to hone, the easiest way to practice it will be to take on projects that need that skill.

Pairing with someone very skilled for an afternoon can sometimes teach you more than you'd pick up in a week of learning on your own.

If you're expecting some huge life event, this is probably not the time to start a project that will need a ton of your energy and attention.

In general, work that matters to the people in your reporting chain is work that builds social capital. I suspect we all know the kinds of people who only optimize for looking good to leadership, and those aren't people we tend to respect. But do keep an eye on your current standing with the people who influence your calibration, compensation, access to good projects, and future promotions. Managing up includes understanding your boss's priorities, giving them the information they need, and solving the problems that are in their way—in other words, helping them be successful. Their success gives them social capital that they can spend to help you.

Your project can build—or lose—social capital with your peers depending on how it aligns with their values. I've seen many disapproving backchannel conversations along the lines of "I'm really surprised to see x person work for x distasteful project or company."

Notice when you're in danger of wasting your social capital. And be deliberate when you spend it to help other people, such as asking your company to interview a friend who has a résumé they would normally pass up. This form of support, sometimes called sponsorship, costs you something: if the person ends up failing, being a jerk, or otherwise being a regrettable choice, it will reflect on your judgment.

Some people make you better at your job without setting out to teach you anything: they're so competent that you build skills just by bathing in their aura. OK, the reality is that you learn by watching the skill being executed well, but I've definitely had colleagues who seemed to have a magical effect on their team.

ively delegate." He says that there's guaranteed to be work that shows up on your plate on which you can "get an A" every single time, and if you give it to someone else, they're probably going to get a B. But, he argues, a B is a pretty great outcome for their first time doing this kind of work: "You're demonstrating trust by giving them work that's scary to them and that you know—and they know—is beyond their means. ‘I know you can do this. I'm going to help you with this.' That's amazing." The other person gets to learn. And maybe you can coach them from a B to an A.

Being the responsible person during a major incident also tends to increase credibility and social capital—assuming you do it well.

You won't succeed unless you can defend your time. The number of demands on it will increase and the number of available hours will stay the same, so be deliberate about what you prioritize. And, when you choose a project, make sure you have enough of the resources you'll need to do a good job.

You are responsible for managing your energy.

### Chapter 5. Leading Big Projects

What makes a great project lead? It's rarely genius: it's perseverance, courage, and a willingness to talk to other people. Sure, there might be times when you need to come up with a brilliant and inspired solution. But, usually, the reason a project is difficult isn't that you're pushing the boundaries of technology, it's that you're dealing with ambiguity: unclear direction; messy, complicated humans; or legacy systems whose behavior you can't predict.

The number one tool for success: writing things down.

George Mauer, director of engineering at findhelp.org, told me that he used to feel imposter syndrome, until he realized "99% of people don't know better than I what to do."

The difficulty is the point. I find that I can handle ambiguity when I internalize that this is the nature of the work. If it wasn't messy and difficult, they wouldn't need you. So, yes, you're doing something hard here and you might make mistakes, but someone has to. The job here is to be the person brave enough to make—and own—the mistakes. You wouldn't have gotten to this point in your career without credibility and social capital. A mistake will not destroy you. Ten mistakes will not destroy you. In fact, mistakes are how we learn. This is going to be OK.

Create an anchor for yourself. Here's how I start, no matter the size of the project: I create a document, just for me, that's going to act as an external part of my brain for the duration of the project. It's going to be full of uncertainty and rumors, leads to follow, reminders, bullet points, to-dos, and lists. When I'm not sure what to do next, I'll return to that document and look at what Past Me thought was important. Putting absolutely everything in one place at least removes the "Where did I write that down?" problem.

Think about who you're going to talk with when the project is difficult and you're feeling out of your depth. Your junior engineers are not the right people! While you can and should be open with them about some of the difficulties ahead, they're looking to you for safety and stability.

In some ways, the start of the project is when it's easiest to not know things. You can preface any statement with "I'm new to this, so tell me if I have this wrong, but here's what I think we're doing" and learn a lot. Later on, it becomes a little more cognitively expensive or may even feel a little embarrassing not to know things.

If you don't understand what your customers need, you're not going to build the right thing. And if you don't have a product manager, you're probably on the hook for figuring out what those needs are. That means talking to your customers and listening to what they say in response.

Product management is a huge and difficult discipline, and it's not easy to understand what your users actually want—as opposed to what they're telling you.

Try not to use jargon, because people can get intimidated and not want to tell you that they didn't understand.

Remember that tenet of Amazon's principal engineer community I mentioned in Chapter 2: "Respect what came before."

If you want to make all of this more sophisticated, a popular tool is RACI, also known as a responsibility assignment matrix. Its name comes from the four key responsibilities most typically used:

-   Responsible: The person actually doing the work.
-   Accountable: The person ultimately delivering the work and responsible for signing off that it's done. There's supposed to be only one accountable person per task, and it will often be the same person as whoever is "Responsible."
-   Consulted: People who are asked for their opinion.
-   Informed: People who will be kept up to date on progress.

Project managers sometimes use a model called the project management triangle, which balances a project's time, budget, and scope. You'll sometimes also hear this framed as "Fast, cheap, good: Pick two."

Probably you're not going to deliver the whole project in one chunk. If you have multiple use cases or features, you'll want to deliver incremental value along the way. So decide what you're doing first, set a milestone, and put a date beside it. Describe what that milestone looks like: what features are included? What can a user do?

If the project is big enough, you might split the work into workstreams, chunks of functionality that can be created in parallel (perhaps with different subteams), each with its own set of milestones.

"Driving doesn't mean you put your foot on the gas and you just go straight." Driving, in other words, can't be passive: it's an active, deliberate, mindful role. It means choosing your route, making decisions, and reacting to hazards on the road ahead. If you're the project lead, you're in the driver's seat. You're responsible for getting everyone safely to the destination.

If you really want to reduce complexity, use pictures. There's no easier way to help people visualize what you're talking about.

Be aware of existing associations: don't use a cylinder on your diagram unless you're OK with many readers thinking of it as a datastore. If you use colors, some of your audience will try to interpret their meaning, for example assuming that green components are intended to be encouraged and red ones should be stopped.

A common approach to sharing information in this way is a design document, often called a request for comment document (or RFC).

Depending on what you're trying to do, the design section could include:

-   APIs
-   Pseudocode or code snippets
-   Architectural diagrams
-   Data models
-   Wireframes or screenshots
-   Steps in a process
-   Mental models of how components fit together
-   Organizational charta
-   Vendor costs
-   Dependencies on other systems

Here are two tips to make your design more precise:

-   Be clear about who or what is doing the action for every single verb. If you find yourself writing in the passive voice, like "The data will be encrypted in transit" or "The JSON payload will be unpacked," then you're obscuring information and making the reader guess. Instead, write with active verbs that have a subject who does the action: "The client will encrypt the data before it is transmitted" or "The Parse component will unpack the JSON payload."
-   Instead of saying "this" or "that," you should add a noun to spell out exactly what you're referring to, even if you've just mentioned it.
    -   Example: We only have two boxes left. To solve this, we should order more.
    -   Revision: We only have two boxes left. To solve this shortage, we should order more.

The "alternatives considered" section is where you demonstrate (to yourself and others!) that you're here to solve the problem and you aren't just excited about the solution. If you find yourself omitting this section because you didn't consider any alternatives, that's a signal that you may not have thought the problem through.

I have a policy that if a plausible-seeming option already exists inside the company and we're not going to use it, the RFC author has to send the new design to the people who own that system and give them an opportunity to respond.

If you're the most senior person on the team and you're sloppy, you're going to have a sloppy team.

Be clear on what success on the project will look like and how you'll measure it.

Write things down. Be clear and opinionated. Wrong gets corrected, vague sticks around.

### Chapter 6. Why Have We Stopped?

Escalating doesn't mean raising a ruckus or complaining about the other team. It means holding a polite conversation with someone who has the power to help, and trying to solve a problem together. Keep it constructive.

Our team motto became "lack of planning on your part is not an emergency on mine."

"A good Three Bullets and a Call to Action email contains (at most) three bullet points detailing the issue at hand, and one—and only one—call to action. That's it, nothing more—you need to write an email that can be easily forwarded along. If you ramble or put four completely different things in the email, you can be certain that they'll pick only one thing to respond to, and it will be the item that you care least about. Or worse, the mental overhead is high enough that your mail will get dropped entirely."

Denise Yu, a manager at GitHub, describes "the art of the rollup": summarizing all of the information in one place to "create clarity and reduce chaos." It's a versatile technique, useful in any situation where there's a ton of backstory and several different narrative threads and where some people might not have kept track of what's going on.

Aggregating the facts that go into the rollup is a great way to build your knowledge and make sure you understand what's going on. But writing it all down also might mean you synthesize new information that nobody had articulated before.

If you're someone who hates asking for help, remember that by learning from other people's experiences, you're amortizing the time they had to spend learning the same thing: it's inefficient to have you both figure out solutions from first principles.

Heidi Waterhouse, a developer advocate for LaunchDarkly, once blew my mind with the observation that "nobody wants to use software. They want to catch a Pokémon." A user who wants to play a video game doesn't care what language the code is in or which interesting algorithmic challenges you've solved. Either they can catch a Pokémon or they can't. If they can't, the software may as well not exist.

Before you start the work, agree on what the end state will look like. The Agile Alliance proposes setting a definition of done, the criteria that must be true before any user story or feature can be declared finished.

Is it possible for you to regularly use what you're building? Of course, this isn't always going to apply, but if there's a way for you to share your customers' experience, take the time to do that. This is sometimes called eating your own dog food or "dogfooding."

Celebrate shipping things to users, rather than milestones that are only visible to internal teams. You don't get to celebrate until users are happily using your system. If you're doing a migration, celebrate that the old thing got turned off, not that the new thing got launched.

Michael R. Bernstein has a great analogy for creating solutions and then not marketing them at all. He says it's like a farmer planting seeds, watering, weeding, and growing a crop, and then just leaving it in the field. You need to harvest what you grew, take it to people, and show them why they want it. The best software in the world doesn't matter if users don't know it exists or aren't convinced it's worth their time. You need to do the marketing.

I used to work in a data center, a long time ago, and one thing I learned there is that there's no such thing as a temporary solution. If someone ran a cable from one rack to another without neatly cabling and labeling it, it would stay there until the server was decommissioned. The same is true for every temporary hack: if you don't have it in good shape by the end of the project, it's going to take extraordinary effort to clean it up later.

## Part III. Leveling Up

### Chapter 7. You're a Role Model Now (Sorry)

This is the blessing and the curse of a staff engineer title: people will assume you know what you're talking about—so you'd better know what you're talking about! Your work will be a little less checked and your ideas considered more credible. Rather than guiding you, people will look to you for guidance.

There will be times when you'll think "This is a problem and someone should say something"…and realize with a sinking feeling that that someone is you.

The clearest indicator of what the company values is what gets people promoted.

If your engineering principles describe a culture of thorough code reviews, but senior engineers approve PRs without reading them, everyone else will rubber-stamp code reviews too. The work that you do is implicitly the type and standard of work that others will see as correct and emulate.

Staff engineers typically have at least 10 and principal engineers have at least 15 years of experience.

Never, ever accept a managerial role until you are already solidly senior as an engineer. To me this means at least seven years or more writing and shipping code; definitely, absolutely no less than five. It may feel like a compliment when someone offers you the job of manager—hell, take the compliment upside-down face emoji—but they are not doing you any favors when it comes to your career or your ability to be effective.

Being a senior engineer means having a growth mindset and a drive to improve. It's embarrassing for everyone when a technical leader insists on a "best practice" that has been debunked for a decade or a technology that everyone else has moved on from. Stay engaged with what's happening in your part of the industry.

Admitting ignorance is one of the most important things we can do as tech leads, senior engineers, mentors, managers, and other influencers of team culture. I love asking for an "ELI5," a term that comes from Reddit and means "Explain it like I'm five years old." It's a helpful shortcut to mean "Look, rather than guessing my level of understanding, just spell it out for me. I promise not to be offended if you tell me things I already know." (The social contract here is that you can't get offended if they start with the very basics of the topic.)

When you "request comments," don't secretly resent them; each one is an opportunity to make your solution better, so take them seriously even if you don't use them all. Your solutions are not you and they don't define you. Criticism of your work isn't criticism of you.

Making a mistake just stings. Solving the problem you caused may be the last thing you want to do in that moment. But it's the best thing you can do to retain the goodwill and social capital of your team. If you react well and fix the problem you caused, you could even end up with more esteem from your colleagues. And a leader being open about their mistakes will make it easier for everyone else to do the same: it's a big boost to the team's psychological safety.

Someone needs to be brave enough to say, "I don't know what to do with the information you just gave me!" Take charge and ask. Tech can be fraught with egos and insecurity, and it's sometimes scary (or legitimately risky!) for junior people to admit that they don't know something. It's safer for senior people to ask.

If the meeting doesn't have notes, was it really worth getting together? Meeting notes are a great example of glue work.

As a senior engineer, you have a responsibility to the future as well as the present. You will always be responsible for creating software that stands up under stress. But you're working for a business (or a nonprofit, government agency, or other organization) that has goals. The software is the means to those ends, not an end in itself.

Take Dan McKinley's advice too and be judicious about where you spend your "innovation tokens": that is, your company's "limited capacity to do something creative, or weird, or hard." If you can only invest in a few places, is this the right place?

Your organization, codebase, and production environment probably existed before you joined them. They'll probably exist after you move on. Don't optimize for now at the cost of future velocity or engineering ability. It's OK to plant some seeds that you won't personally see grow.

Anticipate What You'll Wish You'd Done.

Every time someone leaves your company, you lose institutional knowledge.

Software is created once, but it will need to be maintained for years.

Someday your system will be turned off. How hard is that going to be for the people working on it then? Will they have to dig deep into the logic of other systems, unwinding tendrils that touch business logic and tracing through code to understand what data they're accessing? Or will there be a clean interface and a simple cutover?

Your junior engineers are future senior engineers. Give them the space to learn, and opportunities to do hands-on work and solve increasingly difficult problems.

The degree to which other people want to work with you is a direct indication of how successful you'll be in your career as an engineer. Be the engineer that everyone wants to work with.

### Chapter 8. Good Influence at Scale

When you work with someone who is missing skills or has lower standards than you, don't get frustrated: take the time to bring them up a level.

Before you offer advice, think about whether it's welcome. Solicited advice is when someone else asks for something: a recommendation, feedback on their work, help deciding what to do. When it's unsolicited, they haven't asked.

There are times when unsolicited advice is valuable. "Your slides were amazing, but you talk to your shoes when you present and it's hard to understand you" is difficult but probably kind unsolicited advice.

And, again, don't just launch in. Ask "Can I offer some advice?" and get their permission.

If you find yourself holding back on describing an area for growth because you don't want to accidentally torpedo a well-deserved promotion, consider delivering private feedback by email or in person instead.

A review comment like "Don't use shared_ptr, use unique_ptr" only tells the code author what to do right now. They won't know what to do next time. Teaching means sharing understanding, not just facts. While the code author can go read documentation on whatever you just told them about, they might not recognize why it applies. A short explanation or a link to a relevant article or specific Stack Overflow post (rather than a general manual) will be a shortcut to help them learn.

Annotate your advice so it's clear. Some examples:

-   "Use parameterized queries here instead. You're opening yourself up to SQL injection attacks—a malicious user could drop our database!"
-   "The way you're approaching this will work fine, but we prefer to avoid the singleton pattern. Here's a link to the section of our style guide that talks about why."
-   "I'd recommend one bigger microservice here rather than two small ones—I think it'll be easier to maintain. But I don't feel strongly; your call."
-   "This is just a nitpick, but all of the other spellings in this file are in American English, so let's call this one organization instead of organisation.

Putting together a class takes a ton of effort. There's a high up-front cost for the first time you teach it, but you'll amortize that cost every time you teach it again.

Here are some categories of problems you should look for:

-   **Should this work exist?** What problem does your colleague intend to solve? Are they using a technical solution to solve a problem that should have been solved by talking to someone?
-   **Does this work actually solve the problem?** Will the solution work? Will users be able to do what they need and what they expect? Are there errors or typos? Any bugs or performance issues? Does the design propose using a system in a way that won't work?
-   **How will it handle failure?** How will the solution handle weird edge cases, malformed input, the network randomly disappearing, load spikes, or whatever else can go wrong? Will it fail in a clean way, or will it corrupt data or take a user's money without giving them the service they've paid for? How will you discover problems?
-   **Is it understandable?** Will other people be able to maintain and debug new code or systems? Are the components or variables named intuitively? Is the complexity contained in a well-chosen place?
-   **Does it fit into the bigger picture?** Does the change set a precedent or create a pattern you might not want other people to copy? Does it force other teams to do extra work for future changes? Is this a risky change that's scheduled at the same time as a high-profile launch?
-   **Do the right people know about it?** Is everyone copied on the change who should be? Are there names attached to any actions that need to happen, or is there a lot of passive voice where it isn't clear which team is doing what? Do the people involved know what is expected of them?

Target the level of difficulty to the person you're delegating to—don't throw organizational chaos to a new grad! But when you're looking for someone to delegate to, think beyond the most obvious people. Anyone who can do an A+ perfect job on a project isn't going to learn from it. Instead, try to find someone who will find the work a bit of a stretch but manageable with support.

"We talk about the meritocracy of Silicon Valley, when really it's a mirrortocracy, as people tend to hire people who look like themselves at greater rates than other sectors." Pay attention to who you're recommending or helping, and make sure you're not accidentally only sponsoring people who look like you. It's surprisingly easy to do.

### Chapter 9. What's Next?

Skills are rarely enough to take you where you want to go. You need contacts too. Depending on the business article you read, you'll hear that upward of 70%, maybe as many as 85%, of jobs are not actually published: they're found through networking. When an internal project needs a lead, there'll be a buzz of back-channel conversation among the nearby folks in leadership roles to see who they recommend. When a conference needs a speaker or a project needs a paid consultant, the participants will reach out to people they know. It pays to be known.

Experienced engineering director Cate Huston offers five metrics for evaluating your job health:

-   Whether you're learning
-   Whether you're investing in transferable skills or navigating dysfunction
-   How you feel about recruiting other people to your team
-   How confident you feel
-   How stressed you feel

Here are some other reasons it's good to spend a long time in one place:

-   **Feedback loops** Staying in one place for longer gives you the feedback loop that comes from seeing the consequences of your actions. When engineers move around a lot, everyone's seeing the results of someone else's past decisions instead of the outcomes of their own. You may also get to see the colleagues you leveled up become senior or staff engineers and then become role models themselves.
-   **Depth** The more you know a single domain or a single stack, the deeper and more nuanced your understanding will get. It takes time to intuitively understand something so well that you can build on the knowledge. It's also faster to do things you've done before; you'll be able to make progress more quickly.
-   **Relationships** You've invested time in knowing people all over the organization, and you have people you trust and enjoy working with. You've built up enough mutual goodwill that even the biggest technical disagreements are collegial, not heated. That's an asset that takes time to build up again.
-   **Context** After investing time and effort into learning how to navigate your organization, you have a skill set that might not translate to another one. You've figured out the OKR process, you know the shadow org chart, and you know how to get things done.
-   **Familiarity** You know the work, the schedule, and the people. If you observe particular religious holidays, pick your kid up from school every afternoon, or you always play bocce at lunchtime on Thursdays, you've already set up your schedule to make that happen. It just works, and you're reluctant to change anything.

If you're ready for a change but happy with your current employer, an internal transfer can be a great move. You keep a good amount of your context, relationships, credibility, and social capital, but you get to start fresh on something new. Burin Asavesna, a software architecture lead at Hilti, told me that he thinks of this kind of restart as being like an experienced player of a game making a new low-level character: technically you're starting from scratch, but in reality you already know how the game works and you'll fly up the levels.

"If you're a manager, your job is to get better at management. Don't try to cling to your former glory."

"While you're at a company, learn from as many teams/experts as you can. Frontend, backend, desktop, mobile, design, security, QA, localization, build & release, even (especially!) marketing, growth, and biz dev. When you're an indie, you are responsible for all of these."

You are responsible for your career and choices. There are a lot of options about what to optimize for. Know what's important to you. Be deliberate.

Everything is learnable if it's worth the time investment.

Software has a massive influence on the lives and livelihoods of just about everyone on earth. Take the responsibility seriously.
