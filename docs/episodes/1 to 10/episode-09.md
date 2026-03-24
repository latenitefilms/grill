---
label: Episode 9
---

# Episode 9

**FCG009 - FCPX Workgroup Workflow  (feat. John Davidson)**

Compound Clips as Sequences and Shared Storage in a workgroup environment, that’s what John Davidson from Magic Feather Inc. has been preaching since April of 2013. John’s company has chosen to put their oars into the Final Cut Pro X waters. We also get into Smart Collections and how to wire Macs with 10 Gigabit Ether net

---

## Download

- [MP3](https://cdn.fcp.cafe/grill/FCG009-John-Davidson.mp3)

---

## Featuring

- [Chris Fenwick](http://chrisfenwick.com)
- John Davidson - @MagicFeatherInc

---

## Transcription

`**00:00.001:**` Well, if you've been listening to the show since the beginning, you'll realize I've been on a little bit of a hiatus for the last few days.

`**00:00.001:**` Some people think it's going to be extreme sports references.

`**00:00.080:**` Okay, to do a shootout like this, some people would say, Well, it doesn't matter what the tool is, it's the power of the storytelling.

`**00:00.080:**` Let me think.

`**00:00.080:**` Thunderbolt in the Mac Mini from your Pegasus 6, you're going to get a consistent 110 megabytes per second.

`**00:00.080:**` That's what I was.

`**00:00.080:**` At Chris Fenewick.

`**00:00.160:**` Full Final Cut 10 shop.

`**00:00.160:**` Well, John's going to explain, like, like literally, like, get your pad of paper out and you're going to want to take down some notes.

`**00:00.160:**` Tell me a little bit about Magic Feather.

`**00:00.160:**` In today's day and age, where people grab their TiVo remote and go and start whipping through a C-spot, you know?

`**00:00.160:**` To be on Final Cut 10, that it would upset those guys.

`**00:00.160:**` But the fact of the matter is, if you have to work in a big environment and a big work group and you have to have functionality and interoperability, well, yes, actually the tool does matter.

`**00:00.160:**` And their branded entertainment division.

`**00:00.160:**` It's terrible.

`**00:00.160:**` like i call it the we're the canary of the mine um because we we didn't just we didn't just test test it we just said screw it and we jumped all the way in in terms of using compound clips

`**00:00.160:**` Right.

`**00:00.160:**` I could be wrong.

`**00:00.160:**` A new number like After Effects does, but you know, it has to do copy because it's the Apple way.

`**00:00.160:**` I got to say, you have not been in South Georgia very long because you throw the dudes out like a true Californian.

`**00:00.160:**` And now you're doing 10 gigabits.

`**00:00.160:**` 4K raw audio using uh USB two and a chicken wire.

`**00:00.160:**` hard drive array.

`**00:00.160:**` Heel team viewer into your Mac and set it up for you.

`**00:00.160:**` That's awesome.

`**00:00.160:**` And Fresno's in California, so maybe you're right.

`**00:00.160:**` to explain this to me because I hire him to do this for me, so I don't have to think about it.

`**00:00.160:**` Connecting because we used to do what you did too.

`**00:00.160:**` friendly and quite a few free plugins available in the Final Hit 10 world, that that's a whole show in and of itself.

`**00:00.160:**` To just, you know, finesse a mask or things like that.

`**00:00.160:**` I owned an avenue, had it for three months, sold it at a enormous uh financial loss and moved f uh from there to a media one hundred, used that for a couple of years before I

`**00:00.160:**` Andrew Maggio.

`**00:00.160:**` Blew my mind.

`**00:00.160:**` And we're done.

`**00:00.160:**` That's great.

`**00:00.160:**` is changing so dramatically.

`**00:00.160:**` It's probably not a good note, a good thing to say about them.

`**00:00.160:**` Cool.

`**00:00.160:**` Yeah.

`**00:00.160:**` Final Cut 10 editing facility.

`**00:00.240:**` FCPX Grill, the Grill, whatever you want to call it.

`**00:00.240:**` And so at any rate, my account basically, it works fine if I'm going to do one show a week, but it does not work well if I want to do two shows a week or two a day.

`**00:00.240:**` I think what he called it was, it's been a while since I made the recording.

`**00:00.240:**` Once one show rolls off the thirty day conveyor belt, you can put on a new show.

`**00:00.240:**` Is that he's using it in a multi-user environment, which is one of the things that all the detractors say you can't do.

`**00:00.240:**` Chris, as I live and breathe.

`**00:00.240:**` We're speaking now with John Davidson from Magic Feather.

`**00:00.240:**` That is correct.

`**00:00.240:**` The first day it did pay for itself.

`**00:00.240:**` I can get a brand new Mac with a RAID and all this cool stuff for 10 grand.

`**00:00.240:**` having it nothing really ever came of that, but these were the kind of projects that we would we would work with it on just so that we weren't completely flat-footed if a big change came like what came with I think 10.

`**00:00.240:**` public with it.

`**00:00.240:**` That is it.

`**00:00.240:**` And Final Cut 10 people.

`**00:00.240:**` And then, as I said, once you know we get a couple of things worked out, we're going to switch.

`**00:00.240:**` So a year and a half ago.

`**00:00.240:**` I think probably by fix, what they mean is what's about to come out.

`**00:00.240:**` But to stage a shootout is difficult because the shootout is only tells you it doesn't tell you how powerful the tool is, it tells you how powerful the dude is.

`**00:00.240:**` So anyway, that as as soon as that client said that, we we were um one of one of the first networks we were working with when we m we made the decision to switch was A and E.

`**00:00.240:**` While I wasn't working with them directly, they kept in contact with me because we were that vendor that switched.

`**00:00.240:**` And they would digitize it and then they would do, you know, strip silence.

`**00:00.240:**` John, just for people who aren't aware of this workflow theory, why don't you explain it?

`**00:00.240:**` And they were doing so many things at once, it just blew its mind.

`**00:00.240:**` towards the goal of putting a compound clip in a project and then breaking it apart.

`**00:00.240:**` Right.

`**00:00.240:**` You can create a preset that just shows comps.

`**00:00.240:**` Yeah, so that's he created that.

`**00:00.240:**` So I make a smart collection that is designed to seek out all compound clips.

`**00:00.240:**` You know, it's the same reason why you've created your podcast is why I made that.

`**00:00.240:**` So all current ones, the compound clips have an asterisk in the name.

`**00:00.240:**` People that say, oh, you can't work in a multi-user environment and you can't do this and you can't share, and all of that is just wiped, you know, all it's just wiped away.

`**00:00.240:**` Well, we don't have a SAN.

`**00:00.240:**` And then a NAS is just basically like a hard drive managed by a Mac on a server.

`**00:00.240:**` three months ago.

`**00:00.240:**` Bob Zellin, Z-E-L-I-N.

`**00:00.240:**` And so Bob was telling me that he had gotten this amazing workflow with 10 gigabit Ethernet and Thunderlinks to Thunderbolt ports.

`**00:00.240:**` Thunderbolt from your iMac into the Thunderlink.

`**00:00.240:**` The networking card then connects as well to the Netgear, which then sends out 10 different 10 gigabit Ethernet wires to all the different suites.

`**00:00.240:**` 10 that converts it down to 10 gigabit.

`**00:00.240:**` That's something that's going to be interesting to see how that competes when the new Mac Pros come out.

`**00:00.240:**` and the way Mavericks connects to network shares that sped things up.

`**00:00.240:**` My guess is they might go wine country next on something.

`**00:00.240:**` For the jobs or no?

`**00:00.240:**` And I'm not so certain it is.

`**00:00.240:**` The server Mac is doing a lot more than just hosting the drive.

`**00:00.240:**` We don't really hit those limitations.

`**00:00.240:**` back so that's that's why you I mean you could even get a Mac mini yeah and plug and since you're running uh

`**00:00.240:**` So I could pop and say, hey, Mark, drop Walmart.

`**00:00.240:**` I mean, we bounce around so much that it's pretty wild.

`**00:00.240:**` for much of my career I have avoided plug the plug-in world because when you move a job or a project

`**00:00.240:**` Between machines.

`**00:00.240:**` It's, you know, Core SliceX is an awesome, awesome plugin, and it gives you the Animat capabilities that is pretty much the only thing I missed from Avid.

`**00:00.240:**` got onto Final Cut at about version two.

`**00:00.240:**` At all.

`**00:00.240:**` Correct.

`**00:00.240:**` Yep, I write the spots, we edit the spots, we do the graphics for them.

`**00:00.240:**` Mr.

`**00:00.240:**` And when it leaves up you know, we were talking briefly about picture lock, and I told him I said, Picture lock.

`**00:00.240:**` Hit play in a ballroom or in an auditorium filled with people.

`**00:00.240:**` And then they had an incredibly well built and well-oiled machine to finish these out because they do dozens and dozens of spots a day.

`**00:00.240:**` Now when we work with Discovery, we do all the finishing.

`**00:00.240:**` The advertiser and the network.

`**00:00.240:**` And so they do their graphics in-house, and then we implement them as needed through our spots.

`**00:00.240:**` For one network.

`**00:00.240:**` and then we're we're fully digital.

`**00:00.240:**` It's a workflow they developed 12 years ago, and they haven't really evolved from that.

`**00:00.240:**` Internet video killed the TV network.

`**00:00.240:**` Well, this network won't let you do anything less than DVC Pro HD.

`**00:00.240:**` It's very much, you know, as things get better and more advanced, people are going to either get with the times and catch up or they're just going to get retired.

`**00:00.240:**` The next big thing, great.

`**00:00.240:**` It's like, hmm.

`**00:00.240:**` No, I think maybe probably 10.

`**00:00.240:**` any software, you know, you the point zero release is always a little uh good luck with that.

`**00:00.240:**` Clearly, we are living in exciting times.

`**00:00.240:**` But how would you like to join me and I know there's a few other guests that have been on the show that might join us to do a Google Hangout when 10.

`**00:00.240:**` Well, we can have a few key people have screen sharing capabilities and other people can view in and watch us live as we sort of crack it open and figure it out.

`**00:00.240:**` Sure, I have not done a Google Hangout, so that would be kind of fun.

`**00:00.240:**` Sure.

`**00:00.240:**` Really almost even though it's still relevant, it's past tense.

`**00:00.240:**` Yeah, I would love to talk some more.

`**00:00.240:**` And they're on the internet.

`**00:00.240:**` to answer all your questions, to do all the testing, to forge out ahead and show you the best way to build your Final Cut editing facility.

`**00:00.240:**` And of course, you know, Ben's Consoli, and there's always going to be a Mike Carroll posting there.

`**00:00.240:**` Put the show higher in the rankings so more people hear about it.

`**00:00.240:**` And I got to tell you, I'm really interested in taking another look at this software.

`**00:00.240:**` So that's why we do this.

`**00:00.320:**` So the way this works in the podcast airing world is you get this account, and the account has a finite amount of space

`**00:00.320:**` Is really digging Final Cut 10 and he chooses to use that as I do.

`**00:00.320:**` So I say all of this by way of the fact that you know what, I would love to do more shows.

`**00:00.320:**` Today, we have a great guest.

`**00:00.320:**` and it's sort of enhanced advertising, where the viewer perhaps won't change the channel or skip thirty seconds ahead.

`**00:00.320:**` Right, right.

`**00:00.320:**` as everything moves closer and closer to just being a full online experience and not so much cable and broadcasting.

`**00:00.320:**` Now take a four-minute bathroom break.

`**00:00.320:**` And so we kind of are a vendor that handles a lot of that, but we also do regular on-air promotions as well.

`**00:00.320:**` flat gray background with tiny text and it just it was old.

`**00:00.320:**` Everyone went through it.

`**00:00.320:**` that was representing their pro apps versus Final Cut 7 and its previous iterations, which really they were kind of like that satellite

`**00:00.320:**` Symphony standard definition on a system that maybe you shouldn't connect to the internet with, or

`**00:00.320:**` Yeah, and what I would do is I would put assistant PAs, things like that, on tasks with Final Cut 10 that were what I considered personal projects like

`**00:00.320:**` Somewhere on the beach in California.

`**00:00.320:**` One of our clients had a big meeting in LA about and I can't obviously disclose which one because they're not ready to go.

`**00:00.320:**` Continue to be yeah, that was a sh sinking ship, definitely.

`**00:00.320:**` Which is when we started getting broadcast output from Thunderbolt.

`**00:00.320:**` You know, they were just like, oh, oh, just visibly reacting negatively.

`**00:00.320:**` So we started from that point on.

`**00:00.320:**` Pretty ballsy move by the network.

`**00:00.320:**` That was when I was like, okay, well, you know, we just need someone to take a lead here.

`**00:00.320:**` Came out at the end of the shootout and said that they're probably gonna go to switch to this.

`**00:00.320:**` Three of us.

`**00:00.320:**` And, you know, a lot of people are like, oh my God, that's so terrible.

`**00:00.320:**` Back then, if you recall, we didn't have any ability to export AAFs.

`**00:00.320:**` I have been crediting Ron Dawson with turning me on to that.

`**00:00.320:**` In terms of using Final Cut.

`**00:00.320:**` Or maybe he was, maybe it was right when it first came out.

`**00:00.320:**` Instead of using and this this was what we he the client suggested we try compound clips as versions.

`**00:00.320:**` And then add a second parameter as the rule for your preset keyword.

`**00:00.320:**` And then what I'll do is I will I take my current highest number compound clip and I keyword it current.

`**00:00.320:**` And so when I click on the current keyword collection, I know that that's the most recent timeline.

`**00:00.320:**` a compound clip.

`**00:00.320:**` You're using a center a centralized n uh uh server, correct?

`**00:00.320:**` He and I kind of got to be pals on Creative Cow over the over the years.

`**00:00.320:**` Uh the the R680 is the card needed to manage the data in the RAID created with uh the Pro Aveo.

`**00:00.320:**` And so you're taking Thunderbolt off the back of the iMac through a thing called a Thunderlink, okay?

`**00:00.320:**` Connects to the Addo card, which is mounted in a 2008 Mac Pro.

`**00:00.320:**` Yeah, and the Pro Aveo is connected through the R680.

`**00:00.320:**` And now if you were just editing off of that Mac Pro, you'd have 60 gigs just to edit off the Mac Pro, and it would be crazy fast.

`**00:00.320:**` to it's complicated.

`**00:00.320:**` Yes, and then the 10 gigabit card can be used.

`**00:00.320:**` And we recently upgraded all the rooms to have Pegasus R sixes on Thunder Tube.

`**00:00.320:**` No, that sits in a server room and that its only job is to disseminate video to the all the different suites.

`**00:00.320:**` If you use sparse disks, it's a trick that makes the Mac think that it's a mounted hard drive.

`**00:00.320:**` Evenly distributing video to all the different rooms.

`**00:00.320:**` We hit go connect to server and then we punch in AFP colon backslash backslash and then whatever IP address 192.

`**00:00.320:**` Right.

`**00:00.320:**` move this footage over to a new Mac or just something, just we can open it.

`**00:00.320:**` So at any rate, yeah, no, that was another thing that you mentioned in your studio walkthrough, that you guys create a lot of your own plug-ins.

`**00:00.320:**` Perfect for you.

`**00:00.320:**` You know, I found back then it was just a click monster.

`**00:00.320:**` Keys, you know, he says, Oh, they don't have to look good.

`**00:00.320:**` And then tag, I'm out.

`**00:00.320:**` We'll call that picture lock now.

`**00:00.320:**` and mixing.

`**00:00.320:**` And and it's never going to be good.

`**00:00.320:**` somewhere between Africa and Hawaii.

`**00:00.320:**` And unfortunately, a lot of these guys that didn't think that there was going to be a need to learn Avid were laid off.

`**00:00.320:**` I mean, I can understand why they feel that way.

`**00:00.320:**` So, I mean, you know, you've got people on MacBook Pro Retinas.

`**00:00.320:**` with Final Cut 10 and and hope to even keep it working correctly.

`**00:00.320:**` is that missing networking link.

`**00:00.320:**` You know, share back and forth.

`**00:00.320:**` But you can also choose to choose one of your screens or even one of your windows to be the camera feed, if you will.

`**00:00.320:**` I mean, there's, you know, I think probably a lot of the keyword tagging and metadata is going to stick.

`**00:00.320:**` All right.

`**00:00.320:**` On the 25th of January, Sam Mestman, remember him?

`**00:00.320:**` And they're invite you know, they have like AJA is going to be there.

`**00:00.320:**` To all the good listeners.

`**00:00.320:**` um commented on the iTunes.

`**00:00.320:**` So, thank you so much.

`**00:00.320:**` And even, I've even found, I had one comment with somebody, I think it was an email that I got, where a guy, I had been apologizing that the RSS feed thing wasn't working right.

`**00:00.320:**` Your RSS debacle meant that I accidentally downloaded an FCPX Grill from the Digital Cinema Cafe feed.

`**00:00.400:**` per month.

`**00:00.400:**` And then I can maybe up the account and do a better job.

`**00:00.400:**` Let's go to this interview.

`**00:00.400:**` Like I was watching the episode.

`**00:00.400:**` And so that I went online.

`**00:00.400:**` I'm glad we went with it.

`**00:00.400:**` I had one of our PAs like just cut together scenes and just learn how to work with one long stretch of video of the beach that I took in

`**00:00.400:**` Ah.

`**00:00.400:**` From old Final Cut VII.

`**00:00.400:**` which normally would be used to hold multiple clips and groups and things like that in an old project style edit.

`**00:00.400:**` And your events and projects just get enormous because you're duplicating render files and all that crap.

`**00:00.400:**` And I can see all the previous iterations.

`**00:00.400:**` Remind me where this multiple-part tutorial about your workflow that I saw, was that on FCP Co.

`**00:00.400:**` To say that, dude, you guys can do all of this stuff that you do on Avid or are trying to do on Premiere.

`**00:00.400:**` And then that goes into the 10 gigabit Ethernet switch by Netgear, which then

`**00:00.400:**` SAN command in to get at this data?

`**00:00.400:**` Okay, that's your problem.

`**00:00.400:**` And I love that we can have 60 terabytes that we can all access instantly.

`**00:00.400:**` Oh, Sapphire.

`**00:00.400:**` Right.

`**00:00.400:**` of my peers that I know still work with it.

`**00:00.400:**` Sent it via the interweb off to some server backstage, and they go, Yep, we got the new version, we're going to roll it right now.

`**00:00.400:**` So it really is every network has its own odd little rules.

`**00:00.400:**` Right.

`**00:00.400:**` Yeah.

`**00:00.400:**` Right.

`**00:00.400:**` I think you're right.

`**00:00.400:**` And so you can switch and it's pretty easy to switch between your screen and and your camera.

`**00:00.400:**` uh sorry magic feather if there are uh magic magic featherinc.

`**00:00.480:**` At any rate, John is going to go literally like piece by piece of all the stuff, and he's also going to give some great recommendations of some consultants that he dealt with when he built his network that he has all of his edit suites on.

`**00:00.480:**` We have a name for Avid.

`**00:00.480:**` So we were doing a lot of that stuff.

`**00:00.480:**` Every girl comes up to me and she's like, You know Kim Kardashian?

`**00:00.480:**` And then I'll remove the keyword collection from the previous version.

`**00:00.480:**` at kind of sort of I'm going to say sort of crack you know, peeling the onion back of the OS and the

`**00:00.480:**` So we've actually, I'll give you the scoop, we've changed our office since that video was made.

`**00:00.480:**` Um which is insanely fast for uh network storage.

`**00:00.480:**` Yeah.

`**00:00.480:**` This is how you can do what you need to do to stay relevant in the world.

`**00:00.480:**` That will make you lose clients later because you didn't keep developing.

`**00:00.560:**` A company called Magic Feather Inc.

`**00:00.560:**` And I want to say it was like in the middle of like a cop show or something, and coming out of the previous commercial, like the first two shots, I felt

`**00:00.560:**` And it was like, you know, boy, I'm really hungry.

`**00:00.560:**` both promotions and advertising, and a lot of different networks are creating their own advertising agencies to deal with it.

`**00:00.560:**` because they're big and they have a lot of editors and a lot of vendors.

`**00:00.560:**` We have only had in the history of 18 months, you know, we've probably cut a thousand different I mean, God, I can't even imagine how many compound clips we've created edits of.

`**00:00.560:**` I mean at least it was yeah, at least it was a database versus a you have to hit control or command S because every time I'd make the change the change would stick.

`**00:00.560:**` Correct.

`**00:00.560:**` Yeah, no, I mean, I agree.

`**00:00.560:**` we're getting about 1900 reads, between 1600 and 1900 read-write.

`**00:00.560:**` that that connects to it's it's weird like think of the server as a Mac Pro and then you have the add-O card going to the RAID

`**00:00.560:**` I think you can even go 600 feet with Cat6, actually.

`**00:00.560:**` Yeah, I've it's who knows.

`**00:00.560:**` That has to be done through a mounted network.

`**00:00.560:**` You're increasing the amount of flow that it's going to go through because what's happening is when you mount over Finder just from one room to the next, you're not really getting and Bob Zellen would be better

`**00:00.560:**` before they'd switched to Final Cut six or seven years ago.

`**00:00.560:**` X.

`**00:00.560:**` This is a component of, you know, the song Video Kill the Radio Star?

`**00:00.560:**` All right.

`**00:00.560:**` Yeah, I've actually held off on doing certain tutorials that I want to do because I think, yeah, I think that's going to die.

`**00:00.560:**` Okay, that was John Davidson.

`**00:00.640:**` Tied in with their show Gold Rush.

`**00:00.640:**` We tie in a lot of different products in this sort of co-branded entertainment world, which is where an advertiser blends their brand with a network's brand in a kind of unique and creative way.

`**00:00.640:**` people are going to get really spoiled by Netflix.

`**00:00.640:**` But for editing, Final Cut all the way.

`**00:00.640:**` You know, using compound clips versus projects.

`**00:00.640:**` Fine at the time for what we were using it for, but now we needed more connection to more suites.

`**00:00.640:**` They are not stable.

`**00:00.640:**` It just at the time, and you know what?

`**00:00.720:**` I really love the idea of HD podcasts that are just images and scenes that run for about 30 minutes, like a beach scene and things like that.

`**00:00.720:**` But it only had one issue, and that was on a project that had about 10 layers of custom Final Cut Pro generators that we'd made in motion.

`**00:00.720:**` database correction tool.

`**00:00.720:**` Well, there are a lot of people that work on these things.

`**00:00.720:**` Right.

`**00:00.800:**` Walkthrough of how Magic Feather rooms are wired together.

`**00:00.800:**` That's been really great.

`**00:00.800:**` So when you're done with it, you're making either a file or laying it off to tape, and it is a done deal.

`**00:00.800:**` as the transition to Avid occurred around 2000, some were able to make the transition and some were not.

`**00:00.800:**` Wouldn't it be great if I had better details?

`**00:00.880:**` What that means is on-air promotions being promos, movie like trailers, movie tie-ins with networks like, for example, we just did one for the Hobbit and Discovery Channel.

`**00:00.880:**` So how what is your experience wh when did you first start playing with Final Cut X?

`**00:00.880:**` set of programs from Apple that really didn't feel like Apple.

`**00:00.880:**` I timed my click before the crash to copy and paste into a new project, and that's how I got it out.

`**00:00.880:**` SAN is a storage area network, I think, and it requires special software to connect to it.

`**00:00.880:**` And Sam, people will tell me, like, oh my gosh, you got to get that.

`**00:00.880:**` So anyway, he he told me before this in the tutorial I was using a small tree what I call PEG 6, but it's really PEG126 something.

`**00:00.880:**` So I said, hey, screw it, let's do it.

`**00:00.880:**` Yeah.

`**00:00.880:**` I got the new Bakersfield OS.

`**00:00.880:**` And what's I don't know this one.

`**00:00.880:**` And that was amazing because you could just focus on the creative.

`**00:00.880:**` I should let you go.

`**00:00.880:**` Well, thanks for sharing.

`**00:00.880:**` The comments are really encouraging, and it helps me get up the energy to do this every day or get up and do the interviews and whatnot.

`**00:00.960:**` So at any rate, we're basically and I've now adopted this.

`**00:00.960:**` You know, the networking capability.

`**00:00.960:**` If you are working by yourself, if you kind of have like, let's say you're a wedding shooter editor, that's.

`**00:00.960:**` And the work they do with it is excellent.

`**00:00.960:**` Mr.

`**00:00.960:**` It's like, wow, I would love to have that opportunity to be able to concentrate like that.

`**00:00.960:**` You know, my boss, his I don't know how old the oldest is, but you know, his daughters, when they want to listen to music, they don't go to iTunes, they go to YouTube.

`**00:00.960:**` And you know what?

`**00:01.040:**` Yeah, I mean clearly Final Cut was based on 90s code.

`**00:01.040:**` It's the worst thing ever.

`**00:01.040:**` Are you patient zero here?

`**00:01.040:**` And that was it.

`**00:01.040:**` And when you're not doing that, you save a lot of disk space.

`**00:01.040:**` ZZ all, and I do ZZ so it's at the bottom of the list.

`**00:01.040:**` we hear this a lot, and it's a phrase that I've heard many times talking with people in the last month while doing interviews for this show.

`**00:01.120:**` And imagine like, you know, the the bond bond you know, Lucy Lucille Ball's bond bonds running off the end of the conveyor belt.

`**00:01.120:**` So anyway, they had a shootout between they were going to schedule a summer test between teams of avid people, Final Cut 7 people, and I'm sorry, avid people, premier people.

`**00:01.120:**` It's war on America.

`**00:01.120:**` And it has been awesome because the concept of duplicating a project means you have to duplicate the render files.

`**00:01.120:**` And also one of the issues that you run into is when you have a lot of projects, even if you use folders, it gets super cluttered.

`**00:01.120:**` I can't believe how many graphics we used to work on in Avid back in the day, and we would use this in Symphony to.

`**00:01.120:**` That doesn't surprise me in the slightest.

`**00:01.120:**` You know, and so it is a completely different world, and it's, you know, like it or not, it's the world that we're living in.

`**00:01.120:**` Well, the world only started to exist when I started working.

`**00:01.120:**` They're going to get retired.

`**00:01.200:**` Now, when I open it up, it's just like the saddest thing ever.

`**00:01.200:**` Your cut or whatever you're editing in, you just hit option G in the event and you create a compound clip

`**00:01.200:**` I really do think that our business is probably six months to a year away from this type of a solution.

`**00:01.200:**` Ars disks, you cannot mount a location on a NAS.

`**00:01.200:**` And he's a he's a he's cuts commercial spots all the time, but he doesn't finish them.

`**00:01.200:**` I think you should probably know that by now.

`**00:01.280:**` I don't know how I remember that from reading through your website really quick.

`**00:01.280:**` Actually, you know, come now that you mentioned this, it seems to me I've seen a few.

`**00:01.280:**` Now, was this summer 12 or summer 13?

`**00:01.280:**` Okay, so hold on.

`**00:01.280:**` You know, if we want to use this as a transition to why we don't use a lot of, you know, fun glows and stuff like that, it's because I want to be able to, if I need to.

`**00:01.280:**` If you don't have, I mean, there's nothing worse than having a motion graphics guy say, Oh, yeah, I'll send you my file.

`**00:01.280:**` X at Network X testing funnel cut X.

`**00:01.280:**` And I just hate all these internet names.

`**00:01.360:**` The Thunderlinks will get about 400 megabyte read, right?

`**00:01.360:**` But to be honest, there are so many very affordable, very.

`**00:01.360:**` If you're in Nebraska and you are the local guy that makes commercials for your town, you are set.

`**00:01.360:**` So we're entering this phase where the traditional workflow, the guys that consistently say, oh, I need to send OMFs

`**00:01.440:**` At that time, were you cutting in Final Cut or Avon?

`**00:01.440:**` So I think this is going to have some significant updates, especially in terms of working with shared storage.

`**00:01.440:**` Where do you think Apple is going with the OS names?

`**00:01.440:**` I was just talking to a fr of a guy who was here at the office, one of our clients the other day, and he was saying that his twelve-year-old son, he says, he doesn't watch TV.

`**00:01.520:**` But yeah, so we we are Final Cut 7 and we work also with After Effects Heavily and Creative Suite.

`**00:01.520:**` So then well, they wouldn't be my clan afterwards.

`**00:01.520:**` In this shootout?

`**00:01.520:**` We would just basically crank out creative cuts, send them our project and final cut and an OMF.

`**00:01.520:**` Would you answer that?

`**00:01.520:**` And I remember when HTV first came out, everybody crapped on it.

`**00:01.520:**` Every, every I mean, we would even five years ago, we were still getting footage shot H T V for a reality network, and then you'd have people come up and say, Oh

`**00:01.520:**` If you want to go and give us stars, I prefer the five-star ratings.

`**00:01.520:**` That's why we get together and chat.

`**00:01.600:**` Before it came out, I was very excited about it.

`**00:01.600:**` It's not, you can't do OMS exports.

`**00:01.600:**` Um, but they had a thing and they were gonna do a shootout between Premiere Avid and Final Cut ten because they wanted to stay um forward focused.

`**00:01.600:**` Now his.

`**00:01.600:**` And then we also at the same time or relatively around the same time we upgraded 10 gigabit Ethernet.

`**00:01.600:**` This has gone a little too long, but I look forward to talking to you more.

`**00:01.600:**` Speaking of which, it is now going to be like, what, the 20th of December when you're listening to this, if you listen to it the first day.

`**00:01.680:**` It's called Shitty Clicks.

`**00:01.680:**` Right.

`**00:01.680:**` If you think about it like that, suddenly it's awesome and you jump in.

`**00:01.680:**` Really?

`**00:01.680:**` I think a lot of the complaints that people had are going to be eliminated in this one.

`**00:01.680:**` If you want to do a post-launch chat, I would be down with that.

`**00:01.760:**` He's not a fan of the Avid.

`**00:01.760:**` And they didn't really, there was a fundamental difference in how compound clips worked before from five to six.

`**00:01.760:**` And I think he's got some other new stuff now that actually does a little bit of what you're talking about, unless you search through the event and I think the metadata without having Final Cut open.

`**00:01.760:**` So, thanks again.

`**00:01.840:**` We have one rule is a clip is a compound and then a second rule within that smart preset which is text has an asterisk in it.

`**00:01.840:**` So what kind of hardware are you using with the 10 gigabit Ethernet?

`**00:01.840:**` R680, which is the Netgear switch plugs into a card inside of the Mac Pro.

`**00:01.840:**` He moves on to the next city while somebody else comes in and does all the finish work.

`**00:01.920:**` Good.

`**00:01.920:**` Like I said, we're hitting 650 megabytes per second.

`**00:01.920:**` You can look that up.

`**00:02.000:**` I was so excited to find John Davidson.

`**00:02.000:**` Sunsets and scenes like the Golden Gate Bridge and just random cool scenes.

`**00:02.000:**` Damn you.

`**00:02.000:**` You can't do any grading on it.

`**00:02.000:**` 1.

`**00:02.000:**` And by the way, just so you know, you've been grilled.

`**00:02.080:**` Hope you enjoy it.

`**00:02.080:**` Oh, go ahead.

`**00:02.160:**` How are you, man?

`**00:02.160:**` So a year after Final Cut 10 comes out, what was the thing that made you now?

`**00:02.160:**` We work with a NAS.

`**00:02.160:**` Somebody else said locations in California because Apple always says designed by Apple in California.

`**00:02.160:**` Now, granted, everything else about the Avid system sucked for me.

`**00:02.160:**` It's going to be more complicated to implement something like Final Cut 10.

`**00:02.240:**` We did a little joke video for one of our clients at 20th Century Fox.

`**00:02.240:**` And again, we found that we were getting laggy video playback.

`**00:02.240:**` If it's premiere, great.

`**00:02.320:**` And I was very inspired by the system that you have.

`**00:02.320:**` That gives us about sixty terabytes.

`**00:02.320:**` I'm going to slow you down here.

`**00:02.320:**` So you so essentially that stance says it doesn't do it doesn't work my way, so it's out.

`**00:02.400:**` And so they did the shootout and they tested it and they made mock-up spots using all three systems.

`**00:02.400:**` And as soon as we heard the mock-up, they even hinted that they kind of liked Final Cut 10 more.

`**00:02.480:**` Exactly.

`**00:02.480:**` And so we started working on storage wars and shipping wars and all these shows.

`**00:02.480:**` Are you the first guy to come up with this theory?

`**00:02.480:**` No, I got it now.

`**00:02.480:**` Can I ask who that network is?

`**00:02.480:**` No, I would not.

`**00:02.480:**` 2 is going to be where a couple of little bugs get worked out.

`**00:02.560:**` I was like, okay, I did pay for it today.

`**00:02.560:**` I'm looking forward to this release.

`**00:02.560:**` So that's coming up on the 25th of January.

`**00:02.640:**` What do you guys do?

`**00:02.640:**` No, in the shootout, they had teams from their own staff.

`**00:02.640:**` And so working with this guy, I want to say that it was before 1006 came out that he suggested it.

`**00:02.640:**` What is Animat?

`**00:02.640:**` Hey, look what I just found.

`**00:02.640:**` Very exhilarating.

`**00:02.640:**` Also, I want to say, let me just click a couple things here.

`**00:02.720:**` I mean, that was I had used I had worked with Avid before up until the foundation founding of my company, and then I realized like, whoa, I can get an $80,000 Avid

`**00:02.720:**` So Magic Feather was chosen to be the representative of the Final Cut 10 users, correct?

`**00:02.720:**` The as of yet unnamed network.

`**00:02.720:**` Right.

`**00:02.720:**` How else can you do it?

`**00:02.720:**` Well, you know, it's weird.

`**00:02.800:**` You might want to edit that out, but you just click, click, click, click, and keep clicking until the spot's made.

`**00:02.800:**` Right, it is.

`**00:02.800:**` I mean, they did cats for over a decade, so surf spots seems pretty logical compared to that.

`**00:02.800:**` I hope you enjoyed that.

`**00:02.800:**` At any rate, I'm pretty sure it's a physical event.

`**00:02.880:**` And to compete with that, networks are going to have to provide something that enhances the experience as opposed to just

`**00:02.880:**` I I've had the avid people approach me multiple times in the last year to try and say, Hey, you know, Chris, we could give you a test license, we'd really love you know, blah, blah, blah.

`**00:02.880:**` That's all going to get done by the compositors.

`**00:02.880:**` And for a larger network of, say, a hundred suites.

`**00:02.880:**` I think it's fcpworks.

`**00:02.960:**` I don't care, just listen.

`**00:02.960:**` and they're in Valencia, California, down in Southern California.

`**00:02.960:**` We should go to McDonald's or something.

`**00:02.960:**` Well, we'll do 150 in this in this discussion.

`**00:02.960:**` Yeah, I mean, well, here's a great example.

`**00:02.960:**` That's why I haven't done any new updates is because with it so close I wanted to see

`**00:02.960:**` Um Cincy FitGuy, uh Klein BC Scott from Jackson Spalding.

`**00:03.040:**` So, John, thanks for doing this.

`**00:03.040:**` Yeah.

`**00:03.040:**` And, but, you know, and at the time, like, I, I was, especially when we got broadcast playback at NAB 2012, NAB, whatever.

`**00:03.040:**` At some point, you should be able to open up the event library and just look at it in a text editor.

`**00:03.040:**` But then when I want a version up, we call it, I duplicate the current one, I change the number.

`**00:03.040:**` Yeah.

`**00:03.120:**` No, I don't know.

`**00:03.120:**` And if you know anybody that I should be talking to, by all means, send me a little Twitter message.

`**00:03.200:**` So anyway, so back to working on AE stuff.

`**00:03.200:**` The Gladiators.

`**00:03.200:**` He's got a good reputation for just skewering people online because they'll come on there and like, Hey, I want to be able to connect 10 computers and edit

`**00:03.200:**` So we upgraded our hard drives to a Pro Avio 16 drive array.

`**00:03.200:**` And look, there are really great people that work at Avid.

`**00:03.200:**` And that's great.

`**00:03.280:**` Me and my editor came back and we were just like, that's it.

`**00:03.280:**` Okay.

`**00:03.280:**` That goes cat six up to 150 foot run into the

`**00:03.280:**` Can you tell I'm making a shopping list here, John?

`**00:03.280:**` So let me tell you my story.

`**00:03.280:**` Like anything you wanted to do took about five times as many clicks as it did on the Media 100.

`**00:03.280:**` Yeah.

`**00:03.280:**` I think Apple, I think Apple is actually going to have an official presence at this.

`**00:03.360:**` No.

`**00:03.360:**` If you don't do that, I think you're connecting with SMB or something like that when you just do it through Finder.

`**00:03.360:**` And then every reality show started getting shot with it.

`**00:03.440:**` Okay.

`**00:03.440:**` So I won't advertise who it was.

`**00:03.440:**` Oh, it's kind of cool, actually.

`**00:03.520:**` And the number of commercials in a commercial break these days, it's just getting ridiculous.

`**00:03.520:**` Right.

`**00:03.520:**` It's horrible.

`**00:03.520:**` Animat was a basically a quick way to make a dirty animated mask frame by frame in Avid.

`**00:03.520:**` I feel pretty confident that my sparse disk, well, not mine, but the sparse disk image solution is going to not be needed.

`**00:03.600:**` We're basically an on-air promotions department for any network that needs it.

`**00:03.600:**` Right.

`**00:03.600:**` And then the Thunderlink connects using Cat6 cable on a 150-foot run to the server room.

`**00:03.600:**` Right.

`**00:03.600:**` So that's your hardware.

`**00:03.600:**` And I appreciate all the listeners.

`**00:03.680:**` We only use it to black tapes.

`**00:03.680:**` The Kaladashians.

`**00:03.680:**` You know, it's really interesting.

`**00:03.680:**` And it's a really easy, quick way to see what we're current our current edits on.

`**00:03.680:**` So it seems to me I saw you guys using IMAX in your video.

`**00:03.680:**` Okay, so I guess these things didn't happen back when you were familiar with Avid.

`**00:03.680:**` We get their graphics packages and we build that and we customize it as we need to to satisfy

`**00:03.680:**` Oh, David Dixon, I can pronounce that one.

`**00:03.760:**` Avid backward spells Diva.

`**00:03.760:**` I got it now.

`**00:03.760:**` It's, you know, tools versus the other thing to keep in mind, and this is interesting because you're actually finishing your jobs in-house, correct?

`**00:03.760:**` I wanted to say that if there's something to really think about, the people that are bigger naysayers about Final Cut 10

`**00:03.760:**` And that's kind of, well, not necessarily a TV network, but the TV.

`**00:03.840:**` You know, the I don't know if Final Cut FCPX next is what I'm thinking it's called.

`**00:03.840:**` Like Andreas Keel has several products.

`**00:03.840:**` And that was to dispel a bunch of myths and rumors.

`**00:03.840:**` Interesting.

`**00:03.920:**` So, at any rate, that's a little backstory about what's been going on for the last week and a half or so.

`**00:03.920:**` Right.

`**00:03.920:**` And clearly, it works.

`**00:03.920:**` So help me out here because I'm about I'm just behind you in terms of this understanding.

`**00:03.920:**` It's great.

`**00:03.920:**` We're working on that.

`**00:03.920:**` Well, I would say it's split half Final Cut 7, half Avid.

`**00:03.920:**` Every client has different needs.

`**00:03.920:**` Well, there you go.

`**00:03.920:**` If it's avid, great.

`**00:04.000:**` We just did some stuff for Mob City for T and T, and then we did a Thor spot for Discovery.

`**00:04.000:**` And I don't know if that's the Thunderbolts problem or the OS.

`**00:04.000:**` It's actually you're enabling jumbo frames.

`**00:04.000:**` Trap code.

`**00:04.000:**` We enjoy that.

`**00:04.160:**` I understood.

`**00:04.160:**` Well, not really.

`**00:04.160:**` I think we're going to see like Rincon and the Pipeline and stuff like that.

`**00:04.160:**` No, um, we don't do that.

`**00:04.240:**` I mean, I don't know what it was, but it seemed like there was a very subtle tie-in, very clever.

`**00:04.240:**` I think it's going to be amazing worldwide surf spots.

`**00:04.240:**` That's as far as we'll go identifying it.

`**00:04.320:**` At any rate, let me explain why the pause between episode 7 and now Episode 8.

`**00:04.320:**` And you guys are based in beautiful Valencia.

`**00:04.320:**` But in fact, all of a sudden it cuts to the close-up and it's like, you're not the CSI chick.

`**00:04.320:**` Dear Jesus, what happened?

`**00:04.320:**` It's you know what?

`**00:04.320:**` And I think that would have probably happened in a project, but actually the way I salvaged it was I would click on it and it would crash, and I would click and it would crash.

`**00:04.320:**` How does this work?

`**00:04.320:**` But of course, the easiest way for people to hear about it is just call your friends.

`**00:04.400:**` And then the Netgear is going into another 10 gigabit bot like card from, I think, Addo as well.

`**00:04.400:**` I hope not.

`**00:04.400:**` I mean, I had this discussion with a few people off the air and

`**00:04.400:**` That's why we have a central room that's a server.

`**00:04.400:**` And and going back to Avid, he said, I started getting my carfal tunnel back.

`**00:04.400:**` Right.

`**00:04.480:**` Thanks for taking the time to do this.

`**00:04.480:**` Final Cut.

`**00:04.480:**` Steve Jobs would have never allowed that.

`**00:04.480:**` John, how do people find out more about you and

`**00:04.480:**` com.

`**00:04.560:**` They call it like alternative marketing.

`**00:04.560:**` So, well, because I'm kind of an asshole.

`**00:04.560:**` Summer 12.

`**00:04.560:**` You mentioned it really is a database.

`**00:04.560:**` Yeah.

`**00:04.560:**` That's a good outlook.

`**00:04.640:**` I just I don't know, the map and Valencia just seems like a punchline to a joke every once in a while.

`**00:04.640:**` No, I totally understand that.

`**00:04.640:**` Or, like, you say, like, maybe you just have a compound clip

`**00:04.640:**` Okay.

`**00:04.640:**` It's a great solution.

`**00:04.640:**` With Thunderbolt 2.

`**00:04.640:**` Okay, I'm going to ask you a trivia qu or a I'm going to ask you to divine some some future here.

`**00:04.640:**` And that plays into why I kind of avoid third-party plugins.

`**00:04.640:**` You can.

`**00:04.640:**` You can ask.

`**00:04.640:**` And it's got to be this.

`**00:04.640:**` Oh, absolutely.

`**00:04.640:**` com or uh magicfeather dot tv points to it as well oh very cool

`**00:04.640:**` I did.

`**00:04.720:**` Well, I was so excited when we started the show, I started just pumping out shows like every couple of days, and one day I even mistakenly put up two

`**00:04.720:**` So there's that.

`**00:04.720:**` And so then I sat here, and back then I think there were just.

`**00:04.720:**` It's a whole different war.

`**00:04.720:**` Okay, I'm not going to take credit for it.

`**00:04.720:**` And then Mark unmounts it and then we mount it on my system.

`**00:04.800:**` John owns a company called, or I don't know if he owns it, but certainly he's a principal.

`**00:04.800:**` So, um, yes, a lot of people are still paddling around in it.

`**00:04.800:**` You ever work on the Kardashians?

`**00:04.800:**` Because, you know, before, compound clips were just kind of groups.

`**00:04.800:**` But then I make another keyword collection called current.

`**00:04.800:**` And then they pay all this money every month.

`**00:04.800:**` Okay.

`**00:04.800:**` 12 years ago.

`**00:04.800:**` He was on like episode two or three or something like that.

`**00:04.880:**` And as long as you made sure it was exactly 30 seconds or however long it needed to be, that was your focus.

`**00:04.880:**` With TNT, they do their own graphics.

`**00:04.880:**` But I worked at a place and they had in Atlanta.

`**00:04.960:**` So that's that's kind of that made this the decision for us.

`**00:04.960:**` And it was this client.

`**00:04.960:**` Oh, my mind is racing reading through your resume here.

`**00:04.960:**` Right, right, right.

`**00:04.960:**` But I delete, you know, hit, I hit the enter key and the backspace six times and change the number.

`**00:04.960:**` And you really got to watch it because so many

`**00:04.960:**` You can only mount a location on a sand.

`**00:04.960:**` So we've been doing this bars disk for about a year, something like that.

`**00:04.960:**` When I was at, I used to work at a specific network.

`**00:04.960:**` And so, you know, if Final Cut becomes, you know, the next

`**00:04.960:**` I don't care.

`**00:05.040:**` They didn't look like Apple.

`**00:05.040:**` So it was great for me to see that.

`**00:05.040:**` Right.

`**00:05.040:**` No, it's wi whenever you're whenever you're describing a thing like this, you always have to kind of do it step by step.

`**00:05.040:**` And I wanted to ask you, this is not official.

`**00:05.040:**` So you can even tell people that think they don't care about Funal Cut 10, and they may be pleasantly surprised.

`**00:05.120:**` We don't do Avon.

`**00:05.120:**` When I go, I'm from South Georgia, when I go home on a tangent.

`**00:05.120:**` You know, and it's not until then.

`**00:05.120:**` Yep.

`**00:05.120:**` It might be work.

`**00:05.200:**` But this is the kind of reason why you'd want a NAS server versus

`**00:05.200:**` If you're doing this with Gig E, you're not going to get faster than probably 110 megs a second on a good day downhill with a window.

`**00:05.200:**` So this is a very this is a common problem and frankly

`**00:05.200:**` And so he's just roughing stuff in, picking the frames, picking the pacing, picking the takes.

`**00:05.280:**` They hope to get a couple of things fixed, which

`**00:05.280:**` That makes versioning and versioning up for another crack at something go much faster, correct?

`**00:05.280:**` And then so the Mac Pro that has the big RAID attached to it, you're not actually working on that.

`**00:05.360:**` I was like, this is going to be awesome.

`**00:05.360:**` Okay.

`**00:05.360:**` Right.

`**00:05.360:**` What the next phase for Final Cut is going to bring, I believe

`**00:05.440:**` Great.

`**00:05.440:**` Right.

`**00:05.440:**` Yeah, I want to talk about that for a second.

`**00:05.440:**` And all of a sudden, boop, it disappears out of the current hole.

`**00:05.440:**` Right.

`**00:05.440:**` Oh, it's log GOP or whatever it is.

`**00:05.520:**` And then we pretty much let it just sit there for the next year.

`**00:05.520:**` They created three different teams internally.

`**00:05.520:**` Right.

`**00:05.520:**` And then and we g with the ATTO R680

`**00:05.520:**` But if you have a Mac Pro with a PCI card, that's getting up to 650 megabyte reads.

`**00:05.520:**` But yeah, so I mean, it's, you know, as soon as that network, I think they're going to switch to uploads at some point as well.

`**00:05.520:**` As long as people learn something and stick to it and stay with it.

`**00:05.600:**` Yeah.

`**00:05.600:**` I got it from you through Ron Dawson.

`**00:05.600:**` A Netgear 10 gigabit switch.

`**00:05.600:**` So, you know, when we want to, when we boot up all our Macs.

`**00:05.600:**` That was the first music video to play on MTV back in 1981.

`**00:05.600:**` It's a constant, never-ending workflow development process.

`**00:05.680:**` At any rate, the thing that's unique about John and

`**00:05.680:**` I remember watching something recently.

`**00:05.680:**` So, really, it was April when they announced it, 2012.

`**00:05.680:**` I'm okay, that'll be fun.

`**00:05.680:**` But I think a lot of other stuff is going to change.

`**00:05.680:**` John is a great guy.

`**00:05.760:**` I really, really appreciate it.

`**00:05.760:**` And that kind of reaction, yeah, that made me want

`**00:05.760:**` I mean, it was exactly the same as how we used to work with Digibeta.

`**00:05.760:**` But when you do it within the event browser,

`**00:05.760:**` I can't even imagine the world of having to step into a graphic.

`**00:05.760:**` I was doing OMFs a lot longer than that.

`**00:05.760:**` It might be a web event.

`**00:05.760:**` I want to say, I'm overwhelmed.

`**00:05.840:**` And he says, Oh, no, no, no, you got to talk to John Davidson.

`**00:05.840:**` Can I do it?

`**00:05.840:**` Uh and that that's um

`**00:05.840:**` So we recently had a guest on Digital Cinema Cafe.

`**00:05.840:**` And thanks again.

`**00:05.840:**` I don't need to do that anymore.

`**00:05.920:**` And I do think that at some point we're going to seek out some sponsorship, a little money to help pay for all this.

`**00:05.920:**` He's not a fan of the Avid.

`**00:05.920:**` I'll try and put them in the show notes.

`**00:05.920:**` This is John.

`**00:05.920:**` And yeah, no, I get it.

`**00:05.920:**` Then we go into the Netgear switch, and the Netgear switch plugs into the Addo.

`**00:05.920:**` Exactly.

`**00:05.920:**` Would you answer if I asked?

`**00:05.920:**` It's really, in its current iteration.

`**00:06.000:**` And then 04 came, and after 04, 10.

`**00:06.000:**` If I may, I want to ask about the compound clip workflow.

`**00:06.000:**` Now I can go back into the ZZAL.

`**00:06.080:**` How did this miss the boat?

`**00:06.080:**` Mr.

`**00:06.080:**` That's an Addo Thunderlink, and that's about $1,000.

`**00:06.080:**` What have they done here?

`**00:06.080:**` I think it's works.

`**00:06.160:**` He kind of Bob Went.

`**00:06.160:**` Moz.

`**00:06.240:**` Oh, you couldn't possibly use Final Fed 10 across the network.

`**00:06.240:**` So we were working with just exporting roles as individual audio tracks.

`**00:06.240:**` Very cool.

`**00:06.240:**` And that, frankly, that kind of like

`**00:06.240:**` Yeah.

`**00:06.320:**` Or uh actually, I think it's been more than a week.

`**00:06.320:**` Well, let's talk about the hardware you're using.

`**00:06.320:**` You know, I mean, you use use iPhoto in 2010 and it was vastly different than Final Cut 7.

`**00:06.320:**` And so it was nice to just see something fresh and new because I get bored looking at the same

`**00:06.320:**` And if I can, I'd love to kind of break down some of that.

`**00:06.400:**` At any rate, they have an.

`**00:06.400:**` But that speed comes from Mavericks.

`**00:06.400:**` The next one is going to be Fresno.

`**00:06.400:**` So we'll be back probably in a few days.

`**00:06.480:**` And so when they and we've always said, wherever this client goes, that's where we go.

`**00:06.480:**` In the new format, the way we're using it, the compound clips are essentially a new sequence.

`**00:06.480:**` We expanded about

`**00:06.480:**` You've got IMAX, you've got these smaller, like, I think our solution is about as big as you can get.

`**00:06.480:**` When you start a Google Hangout, you can you know it starts with your eyesight camera.

`**00:06.560:**` Exactly.

`**00:06.560:**` X.

`**00:06.560:**` And a lot of people are negative about it.

`**00:06.560:**` I'm wondering if somebody like Philip Hodges is going to come up with a

`**00:06.560:**` Or then that is the server.

`**00:06.560:**` And I've literally done multiple re-edits the morning of an event.

`**00:06.640:**` What do you call it?

`**00:06.640:**` Okay.

`**00:06.640:**` Yeah, well, you know what?

`**00:06.640:**` Meanwhile, that exact same network that people were saying this stuff about on all the forums was sending me HDV footage.

`**00:06.720:**` But then y you know, and I'm

`**00:06.720:**` And that's what your SAN is attached to?

`**00:06.720:**` I'm going with surf spots myself, but that's off.

`**00:06.720:**` We mount sparse disk images so much.

`**00:06.720:**` And then you go to open it, you realize you need $2,500 worth of plugins just to make his AE project open.

`**00:06.720:**` Okay, trap code you should get.

`**00:06.720:**` It's still an excellent system.

`**00:06.720:**` Picture lock.

`**00:06.720:**` So that was kind of part of what I was trying to show people: this is the future, whether you like it or not.

`**00:06.800:**` Is that correct?

`**00:06.800:**` Right.

`**00:06.800:**` And perfect for small businesses like ours.

`**00:06.800:**` It wasn't working right.

`**00:06.800:**` This only I think Z1.

`**00:06.800:**` Totally.

`**00:06.880:**` Hey, John, it's Chris Fenwick.

`**00:06.880:**` I got burned by Bill and Ted when I was in sixth grade and it never left.

`**00:06.880:**` That's going to be there'll be some bad business insider articles about Apple if they do that.

`**00:06.880:**` And we have found that when we open the sparse disks across the network

`**00:06.880:**` You know, for ABC, they did all the off or they did all the onlining, finishing, and graphics.

`**00:06.960:**` The whole concept of magnetism intrigued me, and mostly I was just glad that we had an Apple app.

`**00:06.960:**` No.

`**00:06.960:**` We're going to do this.

`**00:06.960:**` And my budget's fifty dollars.

`**00:06.960:**` We in fact, we never use that.

`**00:07.040:**` It does.

`**00:07.040:**` What this neckgear guy does is it's

`**00:07.040:**` They have amazing art directors, and the head of art is one of my favorite creatives ever.

`**00:07.040:**` But that's always the case with really any

`**00:07.040:**` Thanks a lot, Chris.

`**00:07.040:**` And/or comment, I think it really helps.

`**00:07.120:**` You can also do it in Final Cut 10.

`**00:07.120:**` That is what is going to hit air.

`**00:07.120:**` They they said that they had had carpal tunnel back when they worked with Avid.

`**00:07.120:**` Now let's do it.

`**00:07.120:**` I appreciate it.

`**00:07.120:**` I'm looking forward to meeting him someday, you know, do a little face-to-face.

`**00:07.120:**` Apparently, Moz used to have a Final Fat 10 podcast.

`**00:07.200:**` And he does a lot of

`**00:07.200:**` Had you been looking at it for that year and watching the slow incremental upgrades?

`**00:07.200:**` ?

`**00:07.200:**` I think they're going to do like a webcasty type thing also.

`**00:07.280:**` He chose not to go the Premier route.

`**00:07.280:**` Yeah, I I feel like this is going to be the future of advertising for television networks because

`**00:07.280:**` So, I said, let's do this.

`**00:07.280:**` And so I name that

`**00:07.280:**` Well, yeah, we're a really small business and I prefer options that I can control and create myself.

`**00:07.280:**` Now what's the Addo device doing?

`**00:07.280:**` A separate card runs the hard drives.

`**00:07.360:**` Yeah, yeah.

`**00:07.360:**` We do that over Gigabit in the office.

`**00:07.360:**` But we still do the finishing and the mixing.

`**00:07.360:**` And some want you to upload, some want you to deliver to tape.

`**00:07.360:**` Check the show notes.

`**00:07.360:**` Go check out FCPXworks.

`**00:07.440:**` The theory came from the head of production at the network that was testing it.

`**00:07.440:**` It seems like it's working very well for you.

`**00:07.440:**` So may I ask you that?

`**00:07.440:**` Right.

`**00:07.440:**` Tell them to download it, tell them to listen to it.

`**00:07.520:**` I acknowledge I'm very bad at that, which, by the way, we would love to have a volunteer to help do that.

`**00:07.520:**` Mr.

`**00:07.520:**` Smart collections?

`**00:07.520:**` We're a very small house, probably a fraction of what you're doing.

`**00:07.520:**` No, I wouldn't want to out there as being a little bit behind the times.

`**00:07.520:**` I think it would be a fun thing.

`**00:07.520:**` And essentially what FCP works is, is it is a company designed

`**00:07.600:**` And that gives us on iMac.

`**00:07.600:**` But

`**00:07.600:**` And this was the Final Cut 7 that we were doing it.

`**00:07.600:**` I don't.

`**00:07.600:**` Because a lot of what we talk about, I feel like we're talking about it in

`**00:07.600:**` Well, Sam is involved in a group called FCP Works.

`**00:07.680:**` Like we were that crazy

`**00:07.680:**` All you got to do is call Bob Zellen.

`**00:07.680:**` He's just cutting the content.

`**00:07.760:**` And so what that means is instead of using a project to edit your

`**00:07.760:**` He has the Create Disk Image, which is what we use to make our sparse disk images.

`**00:07.760:**` You know when I get picture locks?

`**00:07.840:**` The day it came out.

`**00:07.840:**` I loved the idea of not really editing it and just

`**00:07.840:**` That was on FCP Co.

`**00:07.840:**` But anyway, they had a lot of in-house editors that were tape-based, CMX-based.

`**00:07.840:**` I'm literally overwhelmed by the really great comments.

`**00:07.920:**` It's fun.

`**00:07.920:**` It's like, no, get me out of here.

`**00:07.920:**` There was a big change.

`**00:07.920:**` We stopped using projects about probably only about eight or nine months ago.

`**00:07.920:**` And uh

`**00:07.920:**` And plus, there's so much we didn't even talk about.

`**00:08.000:**` X and I had been kind of going back and forth because I was.

`**00:08.000:**` So you're mounting just through Finder?

`**00:08.000:**` So, you know, this world that was created, it's changed.

`**00:08.080:**` And they actually said at the end in August, they announced, we really like Final Cut 10.

`**00:08.080:**` It wasn't that fast until Mavericks came out.

`**00:08.080:**` That's the best one, in my opinion.

`**00:08.080:**` Thanks, John.

`**00:08.160:**` We really, you know, this, we needed this.

`**00:08.160:**` Kind of an easy decision at that point.

`**00:08.160:**` Right.

`**00:08.160:**` Okay.

`**00:08.240:**` You buy every plug-in you can get.

`**00:08.240:**` Yeah.

`**00:08.240:**` I'll probably try and put it there.

`**00:08.320:**` And we were in this room with all these avid guy vendors that

`**00:08.320:**` And they say, oh, there's a risk of corruption and whatnot.

`**00:08.320:**` I wish it would just add a

`**00:08.320:**` Yeah.

`**00:08.320:**` Because it seems to me in that video you were mentioning Gigi.

`**00:08.320:**` But anyway, I just want to thank all you people.

`**00:08.400:**` That was the first big network that we worked with using Final Cut 10.

`**00:08.400:**` A war on taste.

`**00:08.400:**` And it also like I think XSAN wants fiber versus 10 gigabit Ethernet.

`**00:08.400:**` And then Bob will get on there and and have a meltdown on them, and it's and it's pretty hilarious.

`**00:08.400:**` It's definitely something as you expand you want to look into because shared storage is awesome.

`**00:08.400:**` Is 11.

`**00:08.480:**` So anyway, they they

`**00:08.480:**` Yeah, you've done now again

`**00:08.560:**` How are you?

`**00:08.560:**` I would wish you could tell me, but I understand you can't keep going.

`**00:08.560:**` A ski boat can turn a lot faster than a tanker.

`**00:08.640:**` Yeah, so here's a trick I've been doing.

`**00:08.640:**` Well, I think the way we do it is we have

`**00:08.640:**` I got it.

`**00:08.640:**` So you just reach across the network and open up.

`**00:08.640:**` Well, no, I mean, I wasn't ha I wasn't pleased with Avid.

`**00:08.720:**` And then you're using the connect to

`**00:08.800:**` It it yeah.

`**00:08.800:**` Probably like my feelings about

`**00:08.800:**` Don't go too far down that path, but keep going on this idea.

`**00:08.800:**` And that's part of the reason why I sought you out.

`**00:08.880:**` And yes, of course, it is all of that.

`**00:08.880:**` NAS is network attached storage, correct?

`**00:08.960:**` Anyway, my name is Chris Fenwick, and you're listening to Final Cut 10 Grill.

`**00:08.960:**` .

`**00:08.960:**` .

`**00:08.960:**` I'm going to put up another episode.

`**00:09.040:**` I think he's the boss, whatever.

`**00:09.040:**` And working with Sherd.

`**00:09.040:**` Bob Zellen is a guy on Creative Cow, and he's a networking guy, and he's

`**00:09.040:**` Gotcha.

`**00:09.040:**` Finder doesn't have flow control and things like that.

`**00:09.040:**` I haven't don't have this really worked out.

`**00:09.120:**` And I put both of these in a folder called sequences.

`**00:09.120:**` And it's on YouTube if you search for Magic Feather Inc.

`**00:09.120:**` Now,

`**00:09.120:**` Would you be into that?

`**00:09.200:**` So, first of all, John does this great

`**00:09.280:**` He will walk you through exactly what you need to buy, like he did with me.

`**00:09.280:**` Yeah.

`**00:09.280:**` One of the guys that did the shootout for

`**00:09.280:**` I get picture locks when

`**00:09.280:**` I won't say anything.

`**00:09.280:**` And so there was a big layoff.

`**00:09.280:**` Absolutely.

`**00:09.280:**` com.

`**00:09.360:**` So, tell me a little bit about, first of all,

`**00:09.360:**` And that's it.

`**00:09.360:**` And when it would open, I would make one more step.

`**00:09.360:**` It's a broadcast network.

`**00:09.440:**` 0 or is 10.

`**00:09.520:**` And that's what we're using.

`**00:09.520:**` And it's like, okay, is the audience in the room?

`**00:09.600:**` So that's kind of what we're here for on Final Cut Grill.

`**00:09.600:**` Yeah.

`**00:09.600:**` That's off the bank.

`**00:09.680:**` No.

`**00:09.680:**` All the wars.

`**00:09.680:**` But then

`**00:09.760:**` It's so so this is kind of a pioneer area within

`**00:09.760:**` 1 comes out and do

`**00:09.840:**` Right.

`**00:09.840:**` So breakdown, difference between SAN and NAS.

`**00:09.840:**` They're 50 bucks.

`**00:09.840:**` That's the most important thing.

`**00:09.920:**` And so

`**00:09.920:**` So something happened.

`**00:09.920:**` There are people who say, well, we looked at Final Got 10, but it didn't work into our workflow.

`**00:10.000:**` Pretty much.

`**00:10.000:**` You know, before, you know, I remember I'd take a tape in.

`**00:10.000:**` 16 or whatever we've set up and

`**00:10.000:**` It is.

`**00:10.000:**` I mentioned to Sam that I would mention that.

`**00:10.080:**` And and looking five years down the road, obviously Final Cut seven wasn't gonna

`**00:10.080:**` I got it.

`**00:10.080:**` And your Pro Avio is attached to the Mac Pro.

`**00:10.080:**` We're switching between projects so often that we had to install intercoms.

`**00:10.160:**` He's like all of the guests.

`**00:10.160:**` And you plug.

`**00:10.160:**` I'm sorry, go ahead.

`**00:10.160:**` He's doing really rough

`**00:10.240:**` So the solution that we use now.

`**00:10.240:**` Okay.

`**00:10.320:**` Okay.

`**00:10.400:**` Their stuff is amazing.

`**00:10.400:**` At any rate, they're doing this big event in LA.

`**00:10.480:**` Right.

`**00:10.480:**` Okay.

`**00:10.480:**` He watches YouTube.

`**00:10.560:**` We find that it's not quite as robust as a local drive.

`**00:10.640:**` Now are you using sparse disks?

`**00:10.640:**` But if you're in the area, I think it is a, you know

`**00:10.640:**` And he actually said, Hey.

`**00:10.720:**` 04, final cut, 10.

`**00:10.720:**` I think we're calling it 10.

`**00:10.720:**` Right.

`**00:10.720:**` You know, because if there's a reality show, it's about war.

`**00:10.720:**` And you've done a really amazing job.

`**00:10.720:**` I mean, when you think about it, like, did you ever work with Avid?

`**00:10.720:**` We'll talk to you later.

`**00:10.800:**` So and that's the R680 that runs the hard drives?

`**00:10.880:**` Yeah.

`**00:10.880:**` And so we keep an HD cam deck around just

`**00:10.960:**` So I had

`**00:10.960:**` Well I mean, that was a pretty

`**00:10.960:**` And, you know.

`**00:10.960:**` You don't want to get stuck in old workflows.

`**00:10.960:**` I wish that I could email all the people that have.

`**00:11.040:**` It's stupid cheap.

`**00:11.040:**` 1.

`**00:11.120:**` I don't know what that means.

`**00:11.280:**` We just did.

`**00:11.280:**` Oh, I'm so sorry.

`**00:11.360:**` Um.

`**00:11.360:**` Right.

`**00:11.360:**` Correct.

`**00:11.360:**` .

`**00:11.360:**` Yep.

`**00:11.360:**` It was somewhere.

`**00:11.520:**` .

`**00:11.600:**` I remember you showed that in the tutorial that you did.

`**00:11.600:**` Right.

`**00:11.600:**` 0 going to be perfect?

`**00:11.680:**` So

`**00:11.680:**` That's great.

`**00:11.760:**` And I was using a Smalltree 6 port card, and that worked.

`**00:11.760:**` So we go from the iMac to the Thunderlink.

`**00:11.840:**` 1.

`**00:11.920:**` And so.

`**00:11.920:**` This might be what you're talking about.

`**00:11.920:**` , I think.

`**00:11.920:**` It's just acting as a server.

`**00:11.920:**` Yep.

`**00:12.000:**` It'll be 10.

`**00:12.160:**` That's funny.

`**00:12.240:**` Todd LaFord.

`**00:12.320:**` Okay.

`**00:12.400:**` Yeah.

`**00:12.480:**` Everything

`**00:12.640:**` We, when I say we.

`**00:12.720:**` 04.

`**00:12.800:**` And then.

`**00:12.800:**` 1.

`**00:12.880:**` So, I mean, it's.

`**00:13.200:**` And then.

`**00:13.280:**` I mean,

`**00:13.360:**` And.

`**00:13.440:**` Now what we've

`**00:13.520:**` But um

`**00:13.600:**` 03.

`**00:13.840:**` Now I.

`**00:13.840:**` That was.

`**00:14.000:**` Um
