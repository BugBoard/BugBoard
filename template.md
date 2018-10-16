# [ProjectName #001: Short Description of Bug](http://link-to-external-tracker.example.com/001)
#### Analyzed by List, Of, Authors, Here, Casey Doran
#### Date Bug Reported
##### Provided under the [Creative Commons 4.0 Attribution Share-Alike license.](https://creativecommons.org/licenses/by-sa/4.0/)

# Background
Provide relevant information about the open source project here. Describe what it does and what kind of person typically uses it. If the bug at hand is a result of a project-wide initiative, like a major rewrite, a port to a new platform, a core library replacement, or a much-needed update, make sure to provide information about the initiative as well.

If there are other relevant open source projects, describe how those projects relate to the one the bug is filed against. In addition, if the tracker the bug is filed in is not the main tracker for the software in which the bug appears, please explain why this is the case- for instance, a bug might be filed against a Linux distribution's tracker because of an interaction between libraries only present in that distribution, or because of a patch only normally distributed with that distribution.

# Description
Briefly and scientifically describe the bug from a behavioral perspective. What do you need to do to trigger it? What seems to happen? Are there any non-obvious side effects? Is the bug a minor annoyance or a critical blocker? Is there a workaround without fixing the root technical cause?

Provide screenshots of GUI applications when helpful, or code or console snippets for APIs/libraries and terminal applications. Specify which versions of the project were affected and on which platforms. Don't delve into the technical root cause, that comes later.

# Discovery and Report
Brief narrative of the report itself- is the reporter a nontechnical user, a developer, a customer? Is their use case common or rare (and is the bug likely to affect many users or only a small subset)? How did they find it and were there likely others who filed reports before they did? Was there a long delay for others to reproduce or verify the bug? Did the reporter need to provide some additional information to get to a breakthrough? Was there argument over the "correct" behavior or the best way to solve the problem?

You're merely a reporter here. Don't mischaracterize views or statements of others, comment on behavior or developer capability, or otherwise try to opine in here- you're merely recounting what happened from when the reporter started typing to when the report was closed.

# Technical Cause
If the problem was discovered at all, this is where the description of it will go. If it's a mistake in code, configuration, or a data file, provide a snippet (even a cleaned or "simplified" version) and describe what's happening in it.

If a more complex interaction occurs, do your best to describe it in a way that a developer with limited programming skill- maybe a few hello worlds- could understand. Use graphs or diagrams or whatever aides you need to relate the core problem that was occurring in the software system.

Do your best in either case to describe when and how the offending behavior was actually introduced to the system- was it a typo in a new feature? Introduced by a hasty bugfix? Who caused it to appear and what did they think they were doing?

# Systemic Cause
Here's your chance to have a professional opinion! With the technical problem identified and well-understood by the reader, tell us what the project was doing wrong beyond just the technical stuff.

# Bug Resolution and Legacy
Finish up the story. Tell the reader what ended up happening with the report and when, and who implemented the fix in what way. If this bug resulted in a lasting change to the project, outline how the project is different today than when it was filed.

# Ways to Defend Against This Type of Bug
And some more room to have professional opinions. This time you're writing the "moral of the story", what enterprising young software engineers can do to make sure they don't have these problems happen in their own project. Most of the time it'll be things like "have a lot of tests" and "there's nothing you can reasonably do to defend against this type of thing", but you're the professor here- tell us what we're supposed to learn!

# Appendix: Dissent About This Analysis
Professionals love to argue! If you think parts of this analysis are incorrect, sound off here! Be courteous and reasonable, but what you have to say is important in helping young engineers to grasp how many ways there are to solve the problem!
