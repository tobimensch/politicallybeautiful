DISCLAIMER:
> If you don't agree with the reasons for switching out technical terms that I laid out here,
> I'm not judging your decisions and I would prefer if politics played no role in programming in the first place.
> My point is that in a climate where language has to get preemptively sensitive for whatever reason,
> it'd be better to coin words that have a well rounded sound that befits the English language,
> instead of choosing words merely for their technical and logical soundness.

## Debate in the Linux community (and worldwide)
On July 11th new guidelines for a more inclusive language were merged into Linus Torvald's kernel tree.
https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.8-Inclusive-Terminology

This is a sign of the times, where in the light of the Black Lives Matter movement, more and more organizations
are reviewing their policies around language, that could be perceived as offensive.

There's an ongoing debate, if those changes are really necessary in all cases, but the tide is turning into a
direction where you're getting perceived as insensitive when you insist on continued use of words such as blacklist.

On a personal note, I never used to think about any kind of people when encountering the term whitelist,
nor did I make an association to any kind of people while hearing or reading the term blacklist. The same way a white or
black colored car isn't associated with any kind of people for me. Ironically this has changed recently,
because of the very discussion about those words. Now everytime I'm confronted with them, I'll have to think
about the debate that is surrounding them, and hence I'll indirectly be forced to think about ethnic relations.

## My conclusions
Yet, as I followed the discussion surrounding the possible offense that could be taken by the words whitelist and blacklist,
three things became clear to me:

1) If people are offended by a term, and there's an equally good alternative term, then it will just be a distraction from the quality of my code and projects, when I keep using the term that is considered offensive to some, even if I meant no harm by using it.
2) When I don't take part in the formulation of alternative terms, others will decide them for me.
3) Some of the suggested alternatives up to this point have an unappealing ring to them compared to the words they are replacing.

Number 3) is driving me to create this repository and to make my own suggestions for better replacements for words that have fallen out of favor.

I'm accepting pull requests for more suggestions, this repository isn't just for my personal thoughts on the matter.

To me black is one of the coolest sounding words in the English language, and white is also better sounding than your average word,
and I strongly believe that the beauty of sounds factors strongly into the development of human language, slang and technical terms,
it's not just about making technical sense, it's also about sounding right and in the best case cool or beautiful.

One definitely inoffensive example of this is the expression being blue or having the blues. If someone is blue, that's a synonym for saying they are sad, melancholic or depressed.
But the word blue is clearly much more beautiful than the word sad is. Let's imagine for the sake of argument that the word blue was becoming politically incorrect for some reason,
and that in that context the music genre blues would have to be renamed. It just wouldn't have the same feel to it, no matter which alternative you'd be choosing.
Would you want to call it "the sads"? An alternative would sooner or later definitely emerge, but the point is that the sound and feel of a word isn't as easily replaceable as some would have us believe.

The price of being politically correct shouldn't be to neuter language to the point of creating an Orwellian language, where everything that
was formerly described as horrific henceforth gets described as double plus ungood.

So in this repository I want to collect and rate alternatives for those words that are falling out of favor.

## My proposals

### Starting with the terms whitelist/blacklist:

Some of the first suggestions I came across were allowlist/denylist, perfect examples for words that make technical sense,
yet they're less than beautiful linguistically. Can you imagine a word like allowlist or denylist in musical lyrics?
Or in daily natural conversations?
"We put that on the denylist." That sentence can certainly be understood, but denylist feels like the constructed unnatural word that it is!

Replace whitelist with greenlist. There's the expression to greenlight something/somebody, which means to allow somebody
or something to move forward. So the word greenlist is in line with existing English phrases and green is universally used as a color indicating that things are going well.

It was more difficult to find a good sounding replacement for blacklist, not in the least because black is one of the coolest
sounding words in the English language, so any replacement has to be worse (in the sense that it sounds neutered) almost by definition.

Here's a list of possibly good sounding replacements:
- blocklist
- blockerlist
- dodgelist

Here's a list of replacements I don't like for some reason:
- redlist

Blocklist is very close to blacklist, and also has the meaning of to block something in it, so this seems like a good fit, however
I don't quite like it too much, because it doesn't make a very appealing pair with greenlist for an inexplicable reason.
The biggest problem with the term blocklist is though, that it has some ambiquity. Do you mean a list that blocks things, or do you
mean a list of blocks? Blockchain has become a popular term, that refers to blocks, not to blocking. This is way I added blockerlist
to my replacement proposals, as that makes clearly sense to me. Unfortunately the word is longer, which is something I wanted to prevent.

To dodge means to make a movement to avoid something. This is an apt description of what such a list helps to accomplish,
and I think it has a better sound to it than redlist. Rings better to my ears than blocklist as well.
Though both are better than denylist or rejectlist that were floating around as possible replacements.

### Master/slave replacement words:

First, let me rant about the word master for a second. Some advocates against this word are making it appear, as if the word necessarily has to have evil connotations, in every context. Which is very obviously not true, the word is most often used as a title for a person that has gained mastership of a craft or even himself. Even the meaning, where somebody is the master over somebody else, doesn't have to be in connection to slaves or slavery. For example the teacher is the master for and of his students. To master something means to reach a high degree of skill in a difficult endeavor. It's also used as compliment for people that are impressive. So to strike the word master from the English language, means to weaken the ways in which one can express oneself.

It's a different issue, when master and slave are used alongside each other, where the meaning changes to *master of slaves*. Here I can understand, that some people deem it an unfortunate choice of words.

Here are my suggestions for master and slave replacements:
 - master/worker
 - leader/worker
 - director/worker
 - boss/worker
 - head/worker
 - root/worker

Personally, I think that master/worker is a good replacements, as both words make sense in some technological contexts, and they don't sound like neutered language. I think the word worker is actually a more descriptive and better term, than what it is replacing.

If master really needs to be replaced, I think in the workgiver:worktaker context, leader and boss sound nice, but I can also see director, head and root making sense. For example, the root as the origin from where worker threads are started.

There're other contexts where the word master isn't **at all** in relationship to something questionable, ie. in the master/branch context. It was difficult for me to understand, while following the debate, how some people might get offended by a branch being called the master branch. This is what was done in git from the beginning, and now GitHub is going to change the name from master to main. Some claim that main is better than master anyway. But that depends, if you really use the master branch as your main branch or not. Because you don't have to. It simply is the first branch that gets created by the software, and all other branches follow it.

Obviously branches are on trees, and therefore I think it would have made sense for the root branch, to be called root from the beginning.

If I have enough time, I'll maybe change the name master branch to root branch. Because that makes sense as a replacement, but main also sometimes can make sense. You might argue that master is the cooler sounding word, just from the sound of it.

My suggested replacements for master in the branch context:
 - root
 - main
 - leader
 - lead

I'll probably choose root, if I make this change. It sounds relatively cool, and describes the context aptly.

There's one more context of the master/slave terminology, where master stands in relationship to a follower, that usually copies the master.

Here I think these replacements are good:
 - master/follower
 - leader/follower
 - master/clone
 - leader/clone
 - primary/secondary
 - source/clone

Some want to use primary and replica, which I understand, but I think if you use primary you should also go with secondary. Just like B follows A. Secondary things follow primary things, so it seems logical to me, and is a nicer pair of words.

I think source/clone also makes a lot of sense. There are actually quite a few good replacements here.

To those who think that the word master shouldn't be used in any context, and that master/follower from my list is a bad idea, I want to admit **that I might be wrong by defending usecases of the word that I believe to be benign**. I **apologize**, and hope that you understand, that I'm discussing the issue in this document, without claiming to know best or to be right. It's definitely possible that I'm underestimating the power of the word master by itself, and that those who say it should essentially be banned from most or all language, are in the right. It's just hard for me to see, how a master and follower relationship (like the Buddha and his followers, or a carpenter and his students) should offend anyone. So, again, I'm **apologizing**, it's possible that I'm less enlightened than you, or whoever may be offended.
