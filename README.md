# Amos

Amos allows you to consume content on terms you dictate. On the internet, your attention is currency and platforms manipulate you to take as much of your attention as they can.

Amos is about disconnecting from being manipulated and giving you the power to choose how you consume.

## Usage

Currently, Amos requires some technical know-how. The cluster of microservices used for pulling data can be hosted on [Vercel](https://vercel.com), while [Deck](https://github.com/takeamos/deck) and any recommenders that you use will need to be ran like a traditional server.

### Data Services

Current (the links are to the repos):
- [Twitter](https://github.com/takeamos/twitter)
- [YouTube](https://github.com/takeamos/youtube)

Upcoming:
- Reddit

Declined:
- Facebook
	- It is technically possible, but requires circumventing protections that Facebook put in place after the 2016 US Election. While this is normally not a concern, they are currently going after someone over messing with your data that Facebook owns: https://www.eff.org/deeplinks/2020/11/once-again-facebook-using-privacy-sword-kill-independent-innovation

### Recommenders

In the spirit of the Amos project, there hasn't been a hard stance of how content is consumed. A few recommenders have been provided as examples, but you should try building your own to see how you want your feed sorted.

### Media downloaders

Coming soon. You shouldn't rely on services' benevolence to keep media accessible.

## Sites that use Amos

- [Tube v2](https://tube.qnzl.co/?version=2)

