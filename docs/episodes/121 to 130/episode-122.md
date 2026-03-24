---
label: Episode 122
---

# Episode 122

**FCG122 - Subtleties of User Interface (feat. Maciek Kaliski)**

I offered to answer some questions to brand new FCPX user Maciek Kaliski. We discuss various workflow tips and ideas. Part of the reason Maciek decided to give FCPX a try was that according to him “Rippling” doesn’t really work well in Premiere, I’m not entirely sure about that but I think Collision Detection has something to do with his observation. We discuss the Three subsets of Data in an edit, What You’ve Imported,  What You Like, What You’ve Used, along with Favorites and Range Based Favorites. I also discover the “broken” Toggle Color Board or “Effects” Command in the 10.2 update.

---

## Download

- [MP3](https://cdn.fcp.cafe/grill/FCG122-Maciek-Kaliski.mp3)

---

## Featuring

- Chris Fenwick - chrisfenwick.com - @chrisfenwick
- Maciek Kaliski - @MaciekKaliski

---

## Transcription

**Speaker 1**: Good morning and welcome to another episode of The Grill.
*00:00.880*

**Speaker 1**: Hey, so today we're talking with let me I gotta get his name right because I had to learn it.
*00:04.160*

**Speaker 1**: This is the problem with interacting with people via social media is you can have long conversations and stuff and never hear them say their name.
*00:11.440*

**Speaker 1**: It's Macek Kaliski.
*00:20.720*

**Speaker 1**: And he, I believe he is, I want to say Polish, but he's living in England, and he is very new to Final Cut 10.
*00:23.039*

**Speaker 1**: And I find out exactly how new in the interview, so I won't spoil it.
*00:33.040*

**Speaker 1**: But this is one of those episodes where we do, it's a little bit of getting your feet wet.
*00:37.280*

**Speaker 1**: And there's going to be a little bit of both myself and Alex Golner via
*00:44.440*

**Speaker 1**: Meerkat, sharing some keyboard shortcuts with Machek.
*00:52.239*

**Speaker 1**: So this is a beginner episode, but it's on its way to being intermediate.
*00:56.640*

**Speaker 1**: So I just want to give you that warning.
*01:02.399*

**Speaker 1**: You know, we're not.
*01:04.239*

**Speaker 1**: launching any rockets here.
*01:05.640*

**Speaker 1**: We're not, you know, saving lives here.
*01:07.000*

**Speaker 1**: But this is interesting because it's somebody who's new to Final Cut.
*01:10.200*

**Speaker 1**: And learning the ropes.
*01:15.540*

**Speaker 1**: We also talk a little bit about keywording in the end, and we talk a fair amount about organization and how to sift through all of your data and media.
*01:16.820*

**Speaker 1**: So that's a little tease of what's coming up.
*01:25.940*

**Speaker 1**: I want to encourage you to please go check out PremiumBeat.
*01:29.460*

**Speaker 1**: com.
*01:32.820*

**Speaker 1**: They have been very generous in supporting us in what we're doing here at Digital Cinema Cafe and the Grill.
*01:33.460*

**Speaker 1**: And so and I'll tell you, I wish
*01:39.540*

**Speaker 1**: Frankly, I wish everybody could be sitting at the table the day we sort of penned, if you will, this deal about them sponsoring the podcast.
*01:43.720*

**Speaker 1**: Because
*01:55.080*

**Speaker 1**: I was very adamant that I would never take money from anything that I don't firmly and utterly believe in.
*01:56.120*

**Speaker 1**: So there's that.
*02:01.800*

**Speaker 1**: And the
*02:02.760*

**Speaker 1**: The music is great, and as an editor, I love the fact I love the way it sits in my mix.
*02:04.860*

**Speaker 1**: It doesn't try and be a rock star, it doesn't try and
*02:10.700*

**Speaker 1**: take over.
*02:13.920*

**Speaker 1**: So that's premiumbee.
*02:14.720*

**Speaker 1**: com.
*02:17.040*

**Speaker 1**: Please check that out.
*02:17.280*

**Speaker 1**: Another thing that I want to encourage people to take a close look at and
*02:18.400*

**Speaker 1**: I'm not going to say that these guys are sponsoring the show, but they are definitely friends of the show.
*02:23.860*

**Speaker 1**: Please go check out LumaForge.
*02:30.980*

**Speaker 1**: com.
*02:33.860*

**Speaker 1**: Sam my friend Sam Messman is involved with this comp company, and they have a new product called the Luma Share.
*02:35.160*

**Speaker 1**: Now Sam asked me if I wanted to
*02:42.760*

**Speaker 1**: For lack of a better term, pimp his product, you know, talk about it.
*02:46.080*

**Speaker 1**: And I told him, I said, You know what, dude?
*02:49.200*

**Speaker 1**: I don't do anything that I don't have first-hand experience with.
*02:50.640*

**Speaker 1**: He goes, Okay.
*02:53.200*

**Speaker 1**: Next thing you know, he's driving up from LA with one of the prototype Luma shares.
*02:54.620*

**Speaker 1**: And we spent
*03:01.500*

**Speaker 1**: a couple of hours one night wiring it in at our facility and testing it.
*03:03.000*

**Speaker 1**: And I gotta say, I was thoroughly impressed.
*03:08.200*

**Speaker 1**: For the price point of what LumaCher does, he is one-tenth the cost
*03:12.060*

**Speaker 1**: of a competitor's installation.
*03:19.320*

**Speaker 1**: And I can't go into details about that, but he's one tenth the cost at better performance.
*03:21.880*

**Speaker 1**: So it's an amazing product.
*03:27.640*

**Speaker 1**: And it is drop dead simple in terms of setting it up.
*03:30.020*

**Speaker 1**: Even I could set it up.
*03:33.620*

**Speaker 1**: And I wish I had made a traditional video instead of a Mircast of the entire setup that we did that night because the Mircast is gone.
*03:35.540*

**Speaker 1**: But um it was really impressive.
*03:44.220*

**Speaker 1**: And I think that, frankly, we're probably gonna make a video of I I think we're gonna end up getting one of these at Slice, the Lima Cher.
*03:47.500*

**Speaker 1**: And if we do, we're going to make a video of the entire installation procedure so people can see what it's like, and then we'll road test it and check it out.
*03:57.420*

**Speaker 1**: But, you know, I opened up some of my projects on it and it was awesome.
*04:07.220*

**Speaker 1**: It's so fast.
*04:10.819*

**Speaker 1**: And the fact that like I'm I I was
*04:12.260*

**Speaker 1**: impressed with its speed and its performance at the same time that another machine in another room was doing a 16 camera 4K
*04:15.240*

**Speaker 1**: Edit.
*04:24.480*

**Speaker 1**: Okay, so it's like insane.
*04:25.760*

**Speaker 1**: So go check out, do your homework.
*04:27.680*

**Speaker 1**: Go to lumaforge.
*04:30.560*

**Speaker 1**: com.
*04:32.400*

**Speaker 1**: Scroll down, you want to look at the Luma share.
*04:32.940*

**Speaker 1**: And Sam did a full demo of it at LA C Pug.
*04:36.380*

**Speaker 1**: A couple weeks ago.
*04:41.620*

**Speaker 1**: So go check it out.
*04:42.900*

**Speaker 1**: It's very impressive.
*04:44.020*

**Speaker 1**: And I don't own one yet, but I think there's going to be one in our future here at Slice.
*04:45.699*

**Speaker 1**: So if you're in the market for shared storage, this is definitely something that you want to check out.
*04:52.820*

**Speaker 1**: All right.
*04:58.820*

**Speaker 1**: Enough of the commercials, enough of the ads, enough of the sponsors.
*04:59.620*

**Speaker 1**: Let's go to the interview now with Macek Kaliski.
*05:03.220*

**Speaker 1**: And I believe he is in England this morning.
*05:07.740*

**Speaker 1**: Get it all raw.
*05:10.860*

**Speaker 1**: Here we go.
*05:11.820*

**Speaker 1**: Here we go.
*05:12.220*

**Speaker 1**: Just like that.
*05:14.540*

**Speaker 1**: I'm dialing.
*05:15.260*

**Speaker 1**: Hey, hello, hello.
*05:20.979*

**Speaker 1**: It works perfect.
*05:22.100*

**Speaker 1**: Oh, you can hear me, that's good.
*05:23.540*

**Speaker 1**: Yeah, I can hear you fine.
*05:24.820*

**Speaker 1**: It sounds good.
*05:26.259*

**Speaker 1**: I I liked your mic stand.
*05:27.460*

**Speaker 1**: You sent me the picture yesterday.
*05:29.220*

**Speaker 1**: Oh, yeah, it's just a box.
*05:30.500*

**Speaker 1**: It's just a box.
*05:31.860*

**Speaker 1**: And it's, and I'm, am I pronouncing your name right, Macek?
*05:33.840*

**Speaker 1**: That's correct, yeah.
*05:37.040*

**Speaker 1**: You've got to be.
*05:37.760*

**Speaker 1**: And Kaliski?
*05:38.320*

**Speaker 1**: Kaliski.
*05:39.840*

**Speaker 1**: Kaliski.
*05:40.560*

**Speaker 1**: Okay.
*05:41.520*

**Speaker 1**: That's correct.
*05:41.840*

**Speaker 1**: Very cool.
*05:42.400*

**Speaker 1**: So, welcome to the little show.
*05:43.280*

**Speaker 2**: Thank you.
*05:45.460*

**Speaker 2**: I'm very honored to be here.
*05:45.860*

**Speaker 1**: Well, let's wait till the end and see if you still think so.
*05:48.259*

**Speaker 1**: So we got you on the Meerkat, you know that.
*05:52.580*

**Speaker 1**: And I think that you and I first crossed paths on Meerkat.
*05:56.659*

**Speaker 1**: Is that correct?
*05:59.460*

**Speaker 1**: Well I've been following you uh on Twitter for quite a while, but did I but was I following you?
*06:00.720*

**Speaker 1**: So um yeah, it's interesting.
*06:08.020*

**Speaker 1**: You know, I I'll tell a quick story.
*06:10.740*

**Speaker 1**: I remember back in the eighties when I first got a pager, if you remember those.
*06:12.740*

**Speaker 1**: Like Doctor, you know, the little pee-beep, pee-pee.
*06:17.240*

**Speaker 1**: A flood of them.
*06:19.320*

**Speaker 1**: Thanks.
*06:20.520*

**Speaker 1**: And so I remember I had a pager that had a voicemail attached to it.
*06:21.160*

**Speaker 1**: So when somebody would page me or when somebody would call my phone number, which wasn't a real phone, it was the kind of the first, it was the beginning of sort of, you
know, voicemail phones, right?
*06:28.400*

**Speaker 1**: Oh, tomorrow's Mother's Day.
*06:39.840*

**Speaker 1**: you would get I would get a page.
*06:42.919*

**Speaker 1**: And I was like, oh, somebody left me a message.
*06:44.599*

**Speaker 1**: So I could call in, listen to my message and respond to it really quickly.
*06:46.440*

**Speaker 1**: I remember the first time that I did an entire production
*06:51.240*

**Speaker 1**: And actually, I wasn't producing or anything, but I was one of the crew members where I never spoke to the producer until I arrived on the set.
*06:56.820*

**Speaker 1**: And because it was all voicemail.
*07:07.300*

**Speaker 1**: And like back then, that was a big deal.
*07:09.380*

**Speaker 1**: And now we're doing like whole you know arrangements and stuff via like ridiculous stuff like Twitter and Meerkat.
*07:11.540*

**Speaker 1**: So anyway.
*07:18.419*

**Speaker 1**: I don't know where that's going from.
*07:19.580*

**Speaker 1**: So, Machek, thanks a lot for doing this.
*07:21.100*

**Speaker 1**: Tell me I want to know a little bit about your background and how you got into this business.
*07:23.740*

**Speaker 2**: Well, I'm not I'm only quite new to this.
*07:29.280*

**Speaker 2**: I'm about four years in about, let's say that.
*07:32.160*

**Speaker 2**: twenty eleven was when I started, all right, beginning of twenty eleven.
*07:34.479*

**Speaker 2**: So I started doing kind of short films on the PC side.
*07:38.960*

**Speaker 2**: I was editing the Premiere and I went kind of through the discovery phase.
*07:41.840*

**Speaker 2**: I wanted to be a DP for quite a while.
*07:45.840*

**Speaker 2**: And only in about the last year or so is when I've really decided that I want to go to the editing side of things.
*07:48.460*

**Speaker 2**: And recently I got the chance to switch to a Mac.
*07:55.900*

**Speaker 2**: And that's really where I came to came across Final Cut.
*07:58.680*

**Speaker 2**: But I've been listening to The Grill for since it started.
*08:01.800*

**Speaker 1**: Okay, so when did you first get the Mac then?
*08:04.920*

**Speaker 1**: Uh beginning of February.
*08:08.520*

**Speaker 1**: Oh, wow.
*08:11.300*

**Speaker 1**: Okay, so you're very new to this.
*08:12.259*

**Speaker 1**: Yeah.
*08:14.180*

**Speaker 1**: All right.
*08:15.300*

**Speaker 1**: So this is interesting.
*08:15.780*

**Speaker 1**: If you go to digital, if you're listening and you go to digital cinema cafe.
*08:17.220*

**Speaker 1**: In the lower right hand corner of the screen, I've started to put in tags.
*08:21.639*

**Speaker 1**: I suck at making tags.
*08:26.759*

**Speaker 1**: There's only two tags there.
*08:28.199*

**Speaker 1**: One says beginner.
*08:30.120*

**Speaker 1**: And one says color.
*08:32.020*

**Speaker 1**: And so there's been a couple of episodes where we've talked about color.
*08:33.300*

**Speaker 1**: And I'm talking about both shows.
*08:36.020*

**Speaker 1**: It's interesting because the tags work for both shows: Digital Cinema Cafe and Funnel Cut Grill.
*08:37.300*

**Speaker 1**: So.
*08:42.660*

**Speaker 1**: Okay, it's still a bit loud.
*08:45.200*

**Speaker 1**: Thanks, Alex.
*08:46.880*

**Speaker 1**: I'm going to turn him down a little bit more.
*08:47.440*

**Speaker 1**: I thought it would be too quiet.
*08:50.880*

**Speaker 1**: No, no, no.
*08:52.080*

**Speaker 1**: It's the game stage in my audio mixer.
*08:53.680*

**Speaker 1**: So, um, but if you go there and you click on beginner, it'll take you to about four or five shows now that are designed for beginners.
*08:56.279*

**Speaker 1**: And some of them, like I think the funniest one was Eric Neso recently, who I had been told via Twitter, oh, yeah, Naso's using phone calls.
*09:06.100*

**Speaker 1**: 10, you should have him on the show.
*09:14.660*

**Speaker 1**: I go, I thought that'd be interesting.
*09:15.620*

**Speaker 1**: So I go, Eric, so how long have you been using File Cat 10?
*09:16.820*

**Speaker 1**: He goes, Well, I downloaded it yesterday.
*09:19.140*

**Speaker 1**: So it's like, okay, so that ended up being just basically me giving some consulting.
*09:21.220*

**Speaker 1**: Why don't you tell me so you're very new to Final Cut.
*09:27.520*

**Speaker 1**: What have been some of the things that drew you?
*09:31.200*

**Speaker 1**: To give it a go?
*09:36.120*

**Speaker 2**: Well, it was just curiosity of whether the grass is really green or on the other side of the fence.
*09:37.720*

**Speaker 2**: I've been listening to your show and it's just been really interesting to see how things are done on the final cut side.
*09:43.880*

**Speaker 2**: I thought
*09:49.560*

**Speaker 2**: I've got a Mac, might as well try it.
*09:50.680*

**Speaker 2**: If I don't like it, I can always go back to Premiere.
*09:52.840*

**Speaker 1**: So it's interesting.
*09:55.720*

**Speaker 1**: You were listening to the show, even though you weren't using Final Cut.
*09:57.560*

**Speaker 1**: What brings you to such pain?
*10:01.800*

**Speaker 2**: I just always found interest.
*10:05.140*

**Speaker 2**: I've I've quite a big podcast guy.
*10:07.860*

**Speaker 2**: Okay.
*10:10.020*

**Speaker 2**: Because I've got a lot of free time.
*10:10.580*

**Speaker 2**: So there wasn't a reason why I started
*10:12.180*

**Speaker 2**: I don't know.
*10:16.540*

**Speaker 2**: It's quite a hard question to answer, really.
*10:17.820*

**Speaker 1**: Had you listened to Digital Cinema Cafe before?
*10:19.820*

**Speaker 2**: Yeah, that's how I found out about you and Alex, and then that's when the grill started.
*10:22.060*

**Speaker 1**: All right.
*10:27.040*

**Speaker 1**: And then did you uh I'm done now so I apologize to everybody, I'm just doing market research.
*10:27.600*

**Speaker 1**: Um did you first hear about Digital Cinema Cafe because of uh th the end the the the one time end of
*10:32.560*

**Speaker 1**: Digital Convergence.
*10:41.760*

**Speaker 1**: Were you listening to Carl Olson's show prior?
*10:43.280*

**Speaker 1**: No, that that's too far back for me.
*10:46.160*

**Speaker 2**: Oh, okay.
*10:48.080*

**Speaker 2**: All right.
*10:48.720*

**Speaker 2**: Well, that's interesting.
*10:49.040*

**Speaker 2**: I started
*10:50.880*

**Speaker 2**: Um I think the first episode I listened to DCC was about in the number ten area.
*10:52.940*

**Speaker 1**: Okay.
*11:00.060*

**Speaker 2**: So it's been going for quite a while, even though guys don't apply that often.
*11:01.480*

**Speaker 1**: I apologise for taking up so much of your time.
*11:05.079*

**Speaker 2**: And then, you know, end of twenty thirteen is when Final Cut 10.
*11:10.420*

**Speaker 2**: 1 came out.
*11:14.660*

**Speaker 2**: Right.
*11:15.460*

**Speaker 1**: Yeah, that was the that was really the big deal.
*11:16.020*

**Speaker 1**: And and and that's when I started actually I started the show just prior
*11:18.260*

**Speaker 1**: And you know, I I didn't I really didn't know ten point when ten point one was coming out.
*11:22.720*

**Speaker 1**: I assu I mean, we it was obvious ten point one was coming because we were at ten point zero nine.
*11:29.120*

**Speaker 1**: And I sensed that there was going to be something big, and that's kind of why I started the show.
*11:34.520*

**Speaker 1**: I wanted to be able to say I started it before the big switchover.
*11:38.600*

**Speaker 1**: Yeah, before all the hype.
*11:43.320*

**Speaker 1**: So you just thought you'd give it a go.
*11:46.440*

**Speaker 1**: Now did you have any limitations with Premiere?
*11:48.519*

**Speaker 1**: Is that what you were cutting with prior to moving to TEN?
*11:52.760*

**Speaker 2**: Yes, I've been cutting on Premiere for pretty much all of my, so say, career.
*11:55.160*

**Speaker 2**: Limitations not really.
*12:01.279*

**Speaker 2**: I mean, it was doing what I wanted it to do.
*12:04.319*

**Speaker 2**: Okay.
*12:06.720*

**Speaker 2**: But sometimes I had to work around it.
*12:07.040*

**Speaker 2**: Like I didn't really like the I don't really like still don't like the idea of
*12:08.560*

**Speaker 2**: the timeline and rippling is really hard on in Premiere.
*12:12.240*

**Speaker 2**: It doesn't really work.
*12:14.800*

**Speaker 1**: Really?
*12:16.320*

**Speaker 1**: Yeah.
*12:17.600*

**Speaker 2**: Yeah, it's it's rubbish.
*12:18.080*

**Speaker 1**: It might be just that you're not used to it.
*12:22.180*

**Speaker 1**: I mean, one of the things that I say a lot is that the magnetic timeline is like rippling for dummies.
*12:24.340*

**Speaker 1**: Because you can make a normal time line ripple just like Final Cut 10 does, the magnetic timeline.
*12:34.579*

**Speaker 1**: What you gain
*12:44.819*

**Speaker 1**: In Final Cut 10 is the added benefit of what do they call it?
*12:46.880*

**Speaker 1**: A clip a colli collision
*12:52.720*

**Speaker 1**: Clip collision or collision aversion, or something.
*12:56.880*

**Speaker 1**: I don't know what they call it, where it will, and here I am doing hand gestures for Mir Kat, where when two
*13:00.240*

**Speaker 1**: clips collide, it just says, yeah, I'm going to put this one on top of the other one.
*13:06.520*

**Speaker 1**: I think one of my complaints is that I think a little bit of work could be put into the
*13:11.320*

**Speaker 1**: I'll call it artificial intelligence of how clip collision works and how it chooses which thing to put above which thing.
*13:20.440*

**Speaker 1**: I think that it could do it a little bit more intelligently.
*13:30.020*

**Speaker 1**: But even if it guesses wrong, you can always change it.
*13:32.980*

**Speaker 1**: So in that regard, clip collision
*13:37.140*

**Speaker 1**: Can make rippling not work.
*13:41.960*

**Speaker 1**: And it's just an extra step as an editor that you have to realize is going to happen.
*13:45.800*

**Speaker 1**: And if you're not
*13:51.640*

**Speaker 1**: Accustomed to it, you're going to go, Why doesn't this work?
*13:53.579*

**Speaker 1**: Well, that's because those two audio tracks way down there on track ten are colliding and you can't see it because it's off your screen.
*13:57.259*

**Speaker 1**: So
*14:04.060*

**Speaker 1**: It was just part of editing.
*14:05.520*

**Speaker 1**: You had to know this when you were pulling things together.
*14:06.800*

**Speaker 2**: Yeah, it might be the case that I haven't been taught it properly.
*14:10.000*

**Speaker 1**: Well, it's not so much even that you
*14:13.520*

**Speaker 1**: get taught it.
*14:15.660*

**Speaker 1**: I mean, I've had almost zero training.
*14:16.380*

**Speaker 1**: It's just experience of like hitting your head on the the the console enough where you go, Oh, I get it.
*14:18.780*

**Speaker 1**: Yeah.
*14:25.100*

**Speaker 1**: You know, basically you make every mistake once and then you move on.
*14:25.740*

**Speaker 1**: You know, hopefully.
*14:31.420*

**Speaker 1**: Sometimes twice.
*14:32.860*

**Speaker 1**: Yeah.
*14:34.140*

**Speaker 1**: Yeah.
*14:34.620*

**Speaker 1**: Those are the embarrassing days.
*14:35.580*

**Speaker 1**: So then let's talk about Final Cut 10.
*14:37.680*

**Speaker 1**: What have been some of the things that you've enjoyed in it?
*14:42.320*

**Speaker 2**: Well, I've I'm just cutting one job in it right now, about to start a second one.
*14:47.520*

**Speaker 2**: Okay.
*14:52.320*

**Speaker 2**: And so far, I'm up to version seven of a job.
*14:53.120*

**Speaker 2**: And what I've found so far is that it's incredibly fast to work in.
*14:57.700*

**Speaker 2**: I'm not talking rendering speed or anything, I'm talking just how quickly you can do things.
*15:01.380*

**Speaker 2**: On the first day of that job that I just started, I started from nothing in Final Cut at midday, and at three o'clock, I had a version one
*15:08.700*

**Speaker 2**: That was ninety seconds uploading for the client to see.
*15:20.020*

**Speaker 1**: Let's talk about let's back up a little bit.
*15:24.660*

**Speaker 1**: What kind of piece are you cutting?
*15:26.900*

**Speaker 2**: It's a promo piece, so talking heads and b-roll and a music bed.
*15:29.620*

**Speaker 1**: Okay.
*15:35.620*

**Speaker 1**: Yeah, it's kind of my staple.
*15:36.100*

**Speaker 1**: I do those.
*15:37.620*

**Speaker 1**: I did I did like eight of those this week.
*15:38.260*

**Speaker 2**: And that was just incredibly so much faster than in Premiere.
*15:42.880*

**Speaker 1**: Okay, so let's get the let's do a little bit of kind of workflow analysis.
*15:47.279*

**Speaker 1**: First of all, what kind of footage were you using?
*15:55.140*

**Speaker 2**: Well, this is going to sound quite embarrassing, but it is actually mini DV footage.
*15:58.100*

**Speaker 1**: Oh, awesome.
*16:02.180*

**Speaker 1**: Yeah.
*16:03.220*

**Speaker 1**: To be honest, I don't even know how you get that into Final Cut 10.
*16:04.100*

**Speaker 1**: So, mini DV.
*16:07.780*

**Speaker 1**: Which is standard deaf for those of you who are new to this.
*16:10.420*

**Speaker 1**: What how did you how did you ingest the media?
*16:15.140*

**Speaker 2**: Well, you can do it in Final Cut, but I did it in
*16:19.620*

**Speaker 2**: Premiere because I just knew it worked.
*16:22.360*

**Speaker 1**: Okay.
*16:24.360*

**Speaker 2**: But I have researched you can do it in Final Cut.
*16:24.680*

**Speaker 2**: But I think we'll go in File Import from Camera.
*16:27.080*

**Speaker 1**: Oh, yeah, yeah, yeah.
*16:29.800*

**Speaker 1**: That would work.
*16:30.760*

**Speaker 2**: And then if you've got it plugged in via Thunderbolt or whatever, you can just capture from that.
*16:31.640*

**Speaker 1**: Yeah, we used to have our last experience with mini D V was one of our clients who was doing
*16:36.120*

**Speaker 1**: He was they were doing show records.
*16:45.980*

**Speaker 1**: So big think big giant corporate theater, 2,000 people in the audience, three cameras, big giant screens.
*16:49.900*

**Speaker 1**: and backstage, even though everything was H D, they would dumb stuff down to standard deaf to do, you know, um, recordings of um
*16:57.420*

**Speaker 1**: Everything that went on.
*17:07.940*

**Speaker 1**: And then from those, we would end up making DVDs to pass out to attendees later somehow, I guess.
*17:09.220*

**Speaker 1**: I don't know.
*17:15.700*

**Speaker 1**: But so these would be like two-hour show records.
*17:16.340*

**Speaker 1**: Three-hour show records, because on mini DV, not mini DV, but DV Cam, you could have a three-hour tape load.
*17:20.019*

**Speaker 2**: Yeah, our minimum mini DV is just one hour tapes.
*17:27.919*

**Speaker 1**: That's quite fun.
*17:30.400*

**Speaker 1**: Yeah, yeah.
*17:30.799*

**Speaker 1**: So anyway, so mini DV footage, that's how you're bringing it in.
*17:31.919*

**Speaker 1**: Are you bringing in
*17:36.480*

**Speaker 1**: And you brought it in through Premiere.
*17:39.240*

**Speaker 2**: I did, because well, because I was sick of standard deaths, I thought
*17:41.720*

**Speaker 2**: Let's try an experiment of capturing a Premiere, put it into After Effects, use that detail preserving upscale
*17:47.340*

**Speaker 1**: And try and turn it into 720p.
*17:56.440*

**Speaker 1**: Interesting.
*17:59.480*

**Speaker 1**: And how did that work?
*18:00.520*

**Speaker 2**: Well, the number says 720p, but quality is just as bad.
*18:03.160*

**Speaker 2**: Yeah.
*18:08.760*

**Speaker 1**: Yeah, no, I I will tell you this.
*18:09.800*

**Speaker 1**: Here's a little tip for people.
*18:12.120*

**Speaker 1**: If you really want to make stand if you wanna really want to up res D V to
*18:14.440*

**Speaker 1**: HD, the best way to do it is through a box called a Terranex.
*18:20.300*

**Speaker 1**: And it's actually a piece of hardware.
*18:26.780*

**Speaker 1**: And um my friend Alex, he recently did a um a restore of I think
*18:29.660*

**Speaker 1**: I probably have the you know, I'm going to be vague because I can't remember the exact band name.
*18:38.679*

**Speaker 1**: It was sort of a classic seventies rock and roll band, and it was all standard deaf footage, but they were going to make a Blu-ray
*18:42.279*

**Speaker 1**: and so they took all the footage through, I believe, a Terranex.
*18:49.620*

**Speaker 1**: And it's made by Black well, it's not mi it's sold by Black Magic.
*18:53.460*

**Speaker 2**: Black Magic bought the company a couple of years ago.
*18:57.300*

**Speaker 2**: But I'm looking at it now.
*18:59.760*

**Speaker 1**: Yeah, it is the apparently it is the bitchin' way to make standard deaf into H D.
*19:03.360*

**Speaker 1**: And there's really
*19:10.000*

**Speaker 1**: There's I mean, you can do it in software, but you know, it just doesn't look good.
*19:11.620*

**Speaker 1**: I mean, you know, it's better than nothing, but yeah.
*19:17.860*

**Speaker 1**: Yeah, I recommend it.
*19:20.600*

**Speaker 1**: Yeah, it's kind of sad.
*19:21.639*

**Speaker 1**: As a matter of fact, I just cut a show this week.
*19:23.080*

**Speaker 1**: Was that this week?
*19:27.320*

**Speaker 1**: Yeah, this week that was One Camera Standard Def, One Camera HD.
*19:28.200*

**Speaker 1**: Yes, it was sad.
*19:35.000*

**Speaker 1**: Yeah, and it was standard death through a fiber feed from the East Coast.
*19:36.280*

**Speaker 1**: And I'm on the West Coast.
*19:42.940*

**Speaker 1**: But anyway, okay, so that's neither here nor there.
*19:44.620*

**Speaker 1**: So the media comes in.
*19:46.860*

**Speaker 1**: Are you bringing in then, are you bringing in big long passages of tape or short little sound bites that you've selectively captured?
*19:48.220*

**Speaker 2**: Well, I'm capturing the interviews as they are.
*19:56.280*

**Speaker 1**: And then you're going to only less than five minutes.
*20:00.280*

**Speaker 2**: Each interview is they're more about quicksand bites.
*20:04.760*

**Speaker 2**: Right.
*20:07.900*

**Speaker 2**: So so that the each the longest interview was about four and a half minutes.
*20:08.700*

**Speaker 1**: Okay, so so small clips.
*20:12.060*

**Speaker 1**: Um, it used to be a real issue, uh, because the people I work for, they would always want to capture D V
*20:13.740*

**Speaker 1**: cassettes in one like one hour clip.
*20:22.320*

**Speaker 1**: Even though there might be, you know, a hundred separate shots in it.
*20:27.920*

**Speaker 1**: It's a drag.
*20:31.360*

**Speaker 2**: Yeah, I know people that do that at my college.
*20:32.540*

**Speaker 2**: Um they just capture the whole tape as as goes and then they do it in the source monitor.
*20:35.660*

**Speaker 2**: Yeah.
*20:39.740*

**Speaker 2**: Drag clips.
*20:40.300*

**Speaker 2**: That's that's too slow for me.
*20:40.940*

**Speaker 1**: Yeah.
*20:42.380*

**Speaker 1**: It also affects your dr drive performance 'cause your drive has to access big giant
*20:42.700*

**Speaker 1**: Hey, I'm going to respond to one question that's coming in on the Meerkat.
*20:47.980*

**Speaker 1**: British Virgin Islands, home sales.
*20:51.900*

**Speaker 1**: You say you want to do homes.
*20:54.220*

**Speaker 1**: We actually do a whole bunch of home
*20:56.380*

**Speaker 1**: Videos.
*21:00.280*

**Speaker 1**: The company I work for, we have like a whole division that does nothing but high end real estate.
*21:02.200*

**Speaker 1**: And follow me on Twitter and we can talk about that at another time.
*21:08.000*

**Speaker 1**: So anyway, and I've talked about that many times on the shows.
*21:12.480*

**Speaker 1**: I think this guy, BVI Home Sales, just found us on the Meerkat and he's been I think so.
*21:16.160*

**Speaker 1**: I think he's
*21:20.320*

**Speaker 2**: Enjoying it as well.
*21:21.060*

**Speaker 1**: So, um, so short clips, that's what you're doing.
*21:23.540*

**Speaker 1**: Um, now, are you using the favorites command?
*21:26.660*

**Speaker 1**: In Final Cut 10?
*21:30.800*

**Speaker 1**: Little bit.
*21:32.560*

**Speaker 1**: Yeah.
*21:33.520*

**Speaker 1**: Are you using it in the sound bites or in the B-roll?
*21:34.320*

**Speaker 2**: B roll mostly.
*21:39.559*

**Speaker 2**: Right.
*21:40.919*

**Speaker 2**: Until recently, I realized I didn't realize they could have time ranged favorites.
*21:41.880*

**Speaker 2**: Yeah, that's and that helped me a lot.
*21:46.600*

**Speaker 1**: That's a massive thing.
*21:48.519*

**Speaker 1**: And
*21:49.960*

**Speaker 1**: And when I really sort of wrapped my head around range-based keywords like that, it
*21:50.620*

**Speaker 1**: Kind of blew my mind because it realized I could work totally different.
*21:59.580*

**Speaker 1**: Because the main thing in an editorial standpoint, and any editor who's done this for a while will tell you.
*22:05.179*

**Speaker 1**: The main thing that you're dealing with is, you're dealing with three subsets of information.
*22:11.140*

**Speaker 1**: The master subset, it's actually not a subset, but the master set of information.
*22:19.120*

**Speaker 1**: It's sort of like what do they call it, a Venn diagram.
*22:23.920*

**Speaker 1**: So all data represents all the media that you have access to.
*22:26.800*

**Speaker 1**: So sorry, BVI home sales.
*22:33.480*

**Speaker 1**: You are a lady.
*22:35.720*

**Speaker 1**: I apologize for referring to you in the mail.
*22:36.600*

**Speaker 1**: Blah, blah, blah.
*22:39.240*

**Speaker 1**: So all data is
*22:40.680*

**Speaker 1**: It is every bit of media that you have access to.
*22:44.360*

**Speaker 1**: Now, actually, hold on.
*22:48.840*

**Speaker 1**: First, you have all the data that you have on your hard drive.
*22:52.560*

**Speaker 1**: Then the first subset is what you have actually imported into your project or into your library.
*22:55.360*

**Speaker 1**: And I will say that I have been caught by this many times, where the producer says, I know we have that shot, I know we have that shot, and all I'm doing is looking at what
I've imported.
*23:02.540*

**Speaker 1**: And I've accidentally not imported one of the cards of media.
*23:12.160*

**Speaker 1**: And I go, Oh, so sorry, I have it right here.
*23:15.600*

**Speaker 1**: Okay, so the first subset of all media is what you have imported into the library.
*23:18.320*

**Speaker 1**: The second subset is what you have used, okay?
*23:24.220*

**Speaker 1**: Yeah.
*23:32.300*

**Speaker 1**: And the third subset no, the second subset is what you like.
*23:32.780*

**Speaker 1**: And then the third subset is what you've used.
*23:36.840*

**Speaker 1**: And what you've liked and what you've used can all be managed.
*23:40.440*

**Speaker 1**: With the favorites, what has a little green bar in the bin, and the used clip indicator, the orange bar.
*23:47.560*

**Speaker 1**: And then you can also sift through it by using the little filter command, the little filter dropdown box.
*23:57.460*

**Speaker 1**: You could say, just show me my favorites.
*24:04.260*

**Speaker 1**: Or could you do like a broad smart collection?
*24:07.860*

**Speaker 1**: Could you do a smart collection for favorites?
*24:10.820*

**Speaker 1**: Yes, you can.
*24:12.660*

**Speaker 1**: You can do a smart collection for favorites.
*24:13.220*

**Speaker 1**: You can do a
*24:15.220*

**Speaker 1**: Mark Collection for
*24:15.780*

**Speaker 1**: Unused, that's another thing.
*24:17.419*

**Speaker 1**: So, obviously, if I know what I've used, I also can figure out what I've not used.
*24:19.179*

**Speaker 1**: You know?
*24:23.900*

**Speaker 1**: So, anyway, there's multiple ways to sort all that.
*24:25.040*

**Speaker 1**: And in the olden times, I used to do all of that in a string-out timeline.
*24:28.960*

**Speaker 1**: And if you listen to the first
*24:35.120*

**Speaker 1**: You know, few episodes of the show, I talked about it a lot.
*24:37.620*

**Speaker 1**: Yeah, I still like using string heights.
*24:40.660*

**Speaker 1**: I still like using string outs, blah, blah, blah.
*24:42.260*

**Speaker 2**: And Premiere, I do.
*24:45.820*

**Speaker 2**: I I use String Outs in Premiere.
*24:46.700*

**Speaker 2**: Right.
*24:48.539*

**Speaker 1**: Yeah.
*24:49.340*

**Speaker 1**: And it's and there are many very viable reasons for using String Outs.
*24:49.580*

**Speaker 1**: And I have been a huge
*24:57.179*

**Speaker 1**: You can rename your favorites.
*25:02.520*

**Speaker 1**: Alex 4D is saying in list view, you can rename your favorites.
*25:04.440*

**Speaker 1**: Can I then search those, Alex?
*25:09.320*

**Speaker 2**: Anyway, I'm sure he can.
*25:11.880*

**Speaker 1**: I mean, it's funny.
*25:13.000*

**Speaker 1**: So at any rate, there's many viable reasons for using String Out.
*25:14.760*

**Speaker 1**: However, I will say, when you get comfortable with what favorites and used and unused does for you, it is faster.
*25:22.140*

**Speaker 1**: It is faster.
*25:31.980*

**Speaker 1**: Because when I if I want to if the producer says, well, what else do we have to use?
*25:33.020*

**Speaker 1**: All I got to do is go to that filter, say just show me unused, and now everything in the bin or in the
*25:37.660*

**Speaker 1**: The browser is not in my timeline.
*25:46.480*

**Speaker 2**: It's very clever.
*25:50.480*

**Speaker 2**: I mean, even in Final Cut, it's just not viable to use string outs.
*25:51.680*

**Speaker 2**: It just doesn't
*25:55.520*

**Speaker 2**: lend itself to to work in that way, even from me coming.
*25:56.720*

**Speaker 2**: Why do you say that?
*26:00.480*

**Speaker 2**: It's just
*26:02.480*

**Speaker 2**: Because the browser is such a big part of Final Cut, it seems a much larger part of the user interface than in Premiere, where it just store clips
*26:05.940*

**Speaker 2**: And you do interact with them on the timeline.
*26:15.620*

**Speaker 2**: But in Final Cut, they want you to set those favorites and use those keywords
*26:18.020*

**Speaker 2**: True.
*26:24.620*

**Speaker 1**: It's much harder.
*26:25.580*

**Speaker 1**: That is true.
*26:26.700*

**Speaker 1**: But if you're just talking, see, Machek, you're in a unique position because you don't have.
*26:27.260*

**Speaker 1**: And we talk about this a lot, you don't have all of the history and muscle memory and bad habits maybe of somebody who's been doing this for several years.
*26:34.040*

**Speaker 1**: So, for you, it was really easy to say, oh, yeah, favorites, I got it.
*26:44.440*

**Speaker 1**: Okay, good.
*26:47.799*

**Speaker 1**: But a lot of transitional users find
*26:49.159*

**Speaker 1**: And I get this all the time.
*26:55.820*

**Speaker 1**: That's not the way I do it.
*26:58.940*

**Speaker 1**: This isn't the way I do it.
*27:01.340*

**Speaker 1**: This is wrong.
*27:02.700*

**Speaker 1**: No, it's not wrong.
*27:03.740*

**Speaker 1**: It's just different.
*27:05.100*

**Speaker 1**: Very much like.
*27:06.860*

**Speaker 1**: pushing your foot down on a gas pedal is completely different than whipping a horse to make it go forward.
*27:09.240*

**Speaker 1**: It's not wrong, it's just it's a different user interface.
*27:18.440*

**Speaker 1**: And
*27:21.960*

**Speaker 1**: History has shown us for the last 120 years or so, the car's been pretty good to us.
*27:22.720*

**Speaker 1**: I mean, we might be ruining our environment, but it's a pretty good tool.
*27:28.640*

**Speaker 1**: It's a lot faster than a horse, if nothing else.
*27:31.920*

**Speaker 1**: So that's I think that you're a great example of somebody who doesn't have
*27:35.060*

**Speaker 1**: All of the history, you know?
*27:43.980*

**Speaker 1**: Yeah.
*27:46.140*

**Speaker 1**: So, um, and actually, I think I did an episode recently.
*27:46.940*

**Speaker 1**: Let me see if I can find it easily.
*27:52.620*

**Speaker 1**: Where we it was called something like baggage or something.
*27:56.620*

**Speaker 1**: Oh, here, yeah, I could search for the word baggage.
*28:01.020*

**Speaker 1**: Baggage experience or baggage with Michael Tao.
*28:04.540*

**Speaker 1**: Toe.
*28:10.220*

**Speaker 1**: It's episode 109.
*28:12.380*

**Speaker 1**: It's not that long ago.
*28:13.580*

**Speaker 1**: So, um, at any rate, um
*28:15.340*

**Speaker 1**: That's interesting.
*28:19.540*

**Speaker 1**: So I was just checking out that little workflow thing.
*28:20.420*

**Speaker 1**: So you are using the key the keywords and favorites, obviously.
*28:24.100*

**Speaker 2**: Yes, I don't know whether I'm using them right.
*28:28.419*

**Speaker 2**: I'm trying to use them.
*28:31.460*

**Speaker 2**: The way that makes sense to me.
*28:32.740*

**Speaker 1**: Well, I think a good tool will offer you a certain amount of flexibility in what you and how you decide to use it.
*28:34.660*

**Speaker 1**: You know?
*28:41.600*

**Speaker 1**: Yeah.
*28:42.320*

**Speaker 1**: Okay.
*28:43.120*

**Speaker 1**: So I had asked you to prepare a list of questions.
*28:43.840*

**Speaker 1**: things that you were having issues with.
*28:50.399*

**Speaker 1**: So again, Machek is a relatively new user.
*28:52.159*

**Speaker 1**: You've only been actually, you're a pretty new user.
*28:56.480*

**Speaker 1**: You've only been using it for about three months, three or four months.
*28:59.120*

**Speaker 2**: I've
*29:02.080*

**Speaker 2**: The first time I've properly looked at Final Cut was about two weeks ago.
*29:03.340*

**Speaker 1**: Whoa, I thought you said oh, you just got the Mac in February
*29:08.460*

**Speaker 2**: Yeah, yeah, I haven't really looked at Final Cut.
*29:11.919*

**Speaker 1**: Wow, I really need to do pre-interviews.
*29:14.720*

**Speaker 1**: You did warn me you were fairly new to it, but I didn't know you were two weeks new to it.
*29:19.760*

**Speaker 2**: Yeah, I'm new.
*29:24.000*

**Speaker 2**: You know, I've been.
*29:25.120*

**Speaker 2**: It's it's it's I'm I'm not Eric Naso knew, but well the quick
*29:28.260*

**Speaker 1**: Experience or baggage is the name of the episode.
*29:34.540*

**Speaker 1**: Yes, 109.
*29:36.780*

**Speaker 1**: Um, so that yeah, that's interesting.
*29:38.220*

**Speaker 1**: And frankly, for the record, I don't know that Eric is actually using Final Pet 10.
*29:40.220*

**Speaker 1**: I think he's still struggling.
*29:44.940*

**Speaker 1**: I keep seeing him tweeting about problems he's having with Premiere.
*29:46.299*

**Speaker 1**: Anyway, so that was an hour wasted of my life that I'll never get back.
*29:50.539*

**Speaker 1**: Let's hope this one goes better.
*29:55.100*

**Speaker 1**: So
*29:56.779*

**Speaker 1**: What uh so let's go to your list.
*29:58.560*

**Speaker 1**: You had some questions.
*30:01.600*

**Speaker 1**: Uh yeah.
*30:03.840*

**Speaker 2**: Okay.
*30:06.400*

**Speaker 2**: So okay, this project that I'm cutting, I have interviews which are on my primary storyline.
*30:07.740*

**Speaker 2**: Okay.
*30:14.299*

**Speaker 2**: And then I've created a secondary storyline for my B roll.
*30:15.260*

**Speaker 2**: And oftentimes, I find that I want to add a placeholder gap to add some clearance.
*30:19.960*

**Speaker 2**: Yep.
*30:28.440*

**Speaker 2**: It's alt W on the keyboard.
*30:29.000*

**Speaker 2**: But when I do that
*30:30.920*

**Speaker 2**: without having selected property.
*30:32.919*

**Speaker 1**: All your B rope gets out of whack after that space holder.
*30:34.679*

**Speaker 2**: No, what happens is that it automatically goes to my primary storyline instead of my secondary.
*30:38.200*

**Speaker 2**: So is there any way of selecting the secondary storyline?
*30:43.660*

**Speaker 1**: Yes.
*30:47.179*

**Speaker 1**: So it as far as I know, it has to be done with a mouse.
*30:47.419*

**Speaker 1**: But basically, so a secondary storyline is up above the primary.
*30:51.500*

**Speaker 1**: And it basically, I call it, it has a wrapper.
*30:55.660*

**Speaker 1**: It has that little black wrapper around it.
*30:58.220*

**Speaker 1**: It's sort of a little window that everything sits within.
*31:00.380*

**Speaker 1**: So, what you do is if you select the black wrapper.
*31:03.980*

**Speaker 1**: Everything that you do that is keyboard centric will now aim at the secondary storyline instead of the primary storyline.
*31:09.899*

**Speaker 2**: Right, right.
*31:19.820*

**Speaker 2**: There's no way of doing it automatically or with a keyboard shock or anything.
*31:21.800*

**Speaker 1**: I think you have to click it.
*31:26.760*

**Speaker 1**: I think you have to select that storyline.
*31:28.360*

**Speaker 1**: But but but keep in mind that gives you a lot of power so once you've selected that I can
*31:32.800*

**Speaker 1**: Alt W a space into it.
*31:40.620*

**Speaker 1**: I can select a clip on my browser, hit the letter E, and append it to the end of it.
*31:43.420*

**Speaker 1**: I can
*31:48.460*

**Speaker 1**: Select a clip on my browser, hit the W and insert it, right?
*31:49.960*

**Speaker 1**: I can
*31:55.720*

**Speaker 1**: What's the other one?
*31:58.340*

**Speaker 1**: D.
*31:59.220*

**Speaker 1**: I think it's D as overwrite, right?
*32:00.260*

**Speaker 1**: I think.
*32:02.019*

**Speaker 1**: I don't use overwrite.
*32:02.500*

**Speaker 1**: But anyway, you can overwrite, you can append, you can do everything that you do to the primary storyline.
*32:03.860*

**Speaker 1**: you can do to that secondary storyline once you have it selected.
*32:09.400*

**Speaker 1**: So I do I agree it would be great if there was a way that I could select it with a keyboard shortcut.
*32:13.800*

**Speaker 1**: There might be a way.
*32:20.560*

**Speaker 1**: And actually, Alex 4D is listening, so he might be furiously typing on his iPhone right now.
*32:22.640*

**Speaker 1**: But
*32:29.200*

**Speaker 1**: That's the trick.
*32:32.380*

**Speaker 1**: Once you do that, it gives you a lot of power inside the secondary storyline.
*32:33.660*

**Speaker 1**: Okay.
*32:38.679*

**Speaker 2**: Yeah, I was just wondering that was because I figured out they could click on it, just couldn't find anywhere online where they could just like and to be clear, for
people that are confused.
*32:39.080*

**Speaker 1**: I'm not talking about selecting the clip in the secondary storyline.
*32:51.820*

**Speaker 1**: I'm saying select the wrapper.
*32:57.260*

**Speaker 1**: And so what you'll do is you'll get a yellow highlight around the whole secondary storyline.
*32:59.919*

**Speaker 1**: And now you know that it is selected.
*33:04.639*

**Speaker 1**: And that's different than selecting a clip that is in the secondary storyline.
*33:07.200*

**Speaker 1**: It's one of those little subtleties of user interface that is you have to get accustomed to it.
*33:12.600*

**Speaker 1**: And I'll tell you, there's a worse one.
*33:19.560*

**Speaker 1**: In Final Cut 10.
*33:21.980*

**Speaker 1**: And it's only worse in that it gives you an enormous amount of power.
*33:23.660*

**Speaker 1**: But it was literally just a couple of months ago that I figured out one of the ways that you can interact with
*33:28.060*

**Speaker 1**: a dissolve icon.
*33:34.820*

**Speaker 1**: There are one, two, three, four.
*33:37.700*

**Speaker 1**: There are five places that you can grab a dissolve icon.
*33:43.620*

**Speaker 1**: And there are actually si we'll call it six that give you five different things that you can do to it.
*33:49.320*

**Speaker 1**: So if you just generally click it and you highlight the whole thing in yellow, you can hit the delete key and delete it.
*33:58.480*

**Speaker 1**: If you very carefully click right in the center of it
*34:04.480*

**Speaker 1**: you now have a rolling edit, so you can slide it to the left or right, leaving the clips on either side of it
*34:09.320*

**Speaker 1**: Where they are, but having the point where the dissolve happens either happen sooner or later.
*34:18.399*

**Speaker 1**: That's if you grab right in the middle of it.
*34:24.480*

**Speaker 1**: If you grab the right side of it or the left side of it, you can stretch out the length of the dissolve.
*34:27.020*

**Speaker 1**: And here's the one that I just learned recently.
*34:34.460*

**Speaker 1**: if you grab the left or right side of it in the top third of it, and there's a little tiny kind of drawn user interface, kind of like a stripe there.
*34:37.220*

**Speaker 1**: You can extend if you grab the right hand side of the dissolve icon and pull to the right, you will make the outgoing clip longer.
*34:52.580*

**Speaker 1**: With the dissolve rate, the same duration.
*35:03.820*

**Speaker 1**: You will also be pushing and automatically rippling the rest of the timeline to the right.
*35:07.020*

**Speaker 1**: And vice versa, if you grab the upper third, the little tiny handle there of the dissolve icon on the left
*35:13.039*

**Speaker 1**: You will be mid and dragged to the left or right.
*35:22.820*

**Speaker 1**: You'll be making the incoming clip either longer or shorter.
*35:26.580*

**Speaker 1**: No.
*35:31.119*

**Speaker 1**: Yes, longer or shorter, but also rippling, changing the duration of your whole piece.
*35:32.079*

**Speaker 1**: And I did not know that.
*35:37.920*

**Speaker 1**: And I was it was so frustrating because every time I wanted to change the length of the outgoing clip, I would delete.
*35:39.680*

**Speaker 1**: I would delete the icon, change the length of it, and then put a new dissolve icon on it.
*35:45.820*

**Speaker 2**: Yeah, I'm just looking.
*35:51.900*

**Speaker 2**: I've just opened the final cut and it's actually, it does work.
*35:52.700*

**Speaker 2**: Chris is telling the truth.
*35:57.500*

**Speaker 2**: He's not making it up.
*35:59.260*

**Speaker 1**: And Alex 4D is saying if you double-click any part of a transition, it will open up the precision editor.
*36:00.780*

**Speaker 1**: Did not know that, Alex.
*36:06.799*

**Speaker 1**: Thank you for that.
*36:08.160*

**Speaker 1**: I like having the Mircast team here, especially when it's Alex.
*36:09.680*

**Speaker 1**: Alex is full of smart stuff.
*36:15.039*

**Speaker 2**: I like that it's on Android now, 'cause I can look at it.
*36:17.720*

**Speaker 2**: What's that?
*36:20.440*

**Speaker 2**: I like that Meika is on Android now.
*36:21.240*

**Speaker 1**: Yeah, I should actually oh, so oh, oh, is that why d you don't have an iPhone?
*36:24.200*

**Speaker 1**: You don't have an iOS device?
*36:28.280*

**Speaker 2**: No, Fafko and Android.
*36:29.640*

**Speaker 1**: Okay, so you're new to the Meerkat thing.
*36:31.480*

**Speaker 1**: Very cool.
*36:33.160*

**Speaker 1**: All right.
*36:34.119*

**Speaker 1**: So that was one question.
*36:34.839*

**Speaker 1**: What's your next question?
*36:36.680*

**Speaker 1**: We're going to knock through the list here.
*36:39.740*

**Speaker 2**: Just wondering, is there any kind of top keyboard shortcuts like on
*36:42.700*

**Speaker 2**: you know, I know the basics like A and B for the selector tool and blade, and there's R for the range selection.
*36:47.320*

**Speaker 2**: But is there anything else I should
*36:54.600*

**Speaker 2**: No, no, no, no, no, no.
*36:57.380*

**Speaker 1**: Really?
*37:00.020*

**Speaker 1**: Okay, here we go.
*37:00.420*

**Speaker 1**: Semi-time.
*37:01.299*

**Speaker 1**: And I'll ask Alex to get involved here.
*37:02.339*

**Speaker 1**: There's a million cool things.
*37:05.059*

**Speaker 1**: I'm going to.
*37:08.500*

**Speaker 1**: Here's a problem that happens all the time.
*37:09.880*

**Speaker 1**: You have a clip, you have your B-roll, or let's just say you have a series of shots together.
*37:13.559*

**Speaker 1**: Producer over your shoulder says, I hate that shot.
*37:21.420*

**Speaker 1**: I never want to see it again.
*37:23.900*

**Speaker 1**: Okay.
*37:26.220*

**Speaker 1**: There's a couple of things that you can do because you're going to replace it.
*37:27.340*

**Speaker 1**: But you're not going to do it right now.
*37:30.700*

**Speaker 1**: Okay.
*37:32.780*

**Speaker 1**: So, one of the things that you can do is one, you can just select that clip and hit the letter V, and that just makes it inactive.
*37:33.420*

**Speaker 1**: Okay, so it's still in the timeline, but it's as if it is not.
*37:40.620*

**Speaker 1**: Okay, you can see through it, it doesn't make any noise, everything.
*37:45.900*

**Speaker 1**: So the letter V for Victor is very powerful.
*37:49.100*

**Speaker 1**: But another thing that I do quite often is I will select that clip, and there's multiple reasons why you want to do this, and you hit Command Option and the up arrow.
*37:54.340*

**Speaker 1**: Command option up arrow will lift it out of the primary storyline so that you can delete it, but it leaves a slug in there that was the duration of the preview of the of the
clip so that your stuff doesn't get knocked out of sync.
*38:04.599*

**Speaker 1**: Okay.
*38:19.920*

**Speaker 1**: Very cool.
*38:20.400*

**Speaker 1**: Command option up arrow, I use that.
*38:20.880*

**Speaker 2**: But could you go down back to canter align with the down?
*38:23.680*

**Speaker 1**: Yes, you can.
*38:27.279*

**Speaker 1**: And as a matter of fact,
*38:28.079*

**Speaker 1**: It's not the same as going up a track, down a track, up a track, down a track, because command option down arrow will put.
*38:30.560*

**Speaker 1**: Whatever you have selected into the primary storyline right where it currently is sitting in time.
*38:38.700*

**Speaker 1**: Okay.
*38:46.460*

**Speaker 1**: Okay.
*38:47.340*

**Speaker 1**: Alex is saying, that's what I was typing.
*38:48.200*

**Speaker 1**: So command option down arrow will take will let's say you had five layers of things stacked up, and you want to put
*38:50.760*

**Speaker 1**: the top thing all the way down in the primary storyline.
*39:00.599*

**Speaker 1**: Even though there's three other tracks of stuff in the way, so to speak, command option down arrow will take that top thing and cram it into the primary storyline.
*39:05.160*

**Speaker 2**: Very cool, very cool.
*39:14.340*

**Speaker 1**: Now it's good to know that.
*39:15.620*

**Speaker 1**: There's not many times when you need to do precisely that, but I got to say, I had it crop up the other day
*39:18.260*

**Speaker 1**: And I was so glad I had it.
*39:26.860*

**Speaker 1**: It was like, oh my goodness, that just I mean, it saved me so much time.
*39:29.420*

**Speaker 1**: Again, I can't remember the exact circumstances of why I had that.
*39:34.140*

**Speaker 1**: I'll tell you another one, and we've talked about this on the show, so this is a little bit of a repeat.
*39:39.940*

**Speaker 1**: But there's a keyboard command you should
*39:45.380*

**Speaker 1**: Program that is not a default setting.
*39:48.520*

**Speaker 1**: So it's important to know that
*39:52.200*

**Speaker 1**: There is a very powerful keyboard command editor.
*39:59.040*

**Speaker 1**: It's under the Final Cut Pro menu under Commands.
*40:02.640*

**Speaker 1**: Why it's not keyboard commands or shortcuts or something.
*40:06.880*

**Speaker 1**: But anyway, and you go to Customize.
*40:10.160*

**Speaker 1**: Which is also Command Option K.
*40:12.740*

**Speaker 1**: And extremely powerful tool here.
*40:15.700*

**Speaker 2**: Oh, yeah.
*40:19.140*

**Speaker 1**: Okay.
*40:19.620*

**Speaker 2**: It's easy to learn them as well.
*40:21.220*

**Speaker 1**: Exactly.
*40:23.140*

**Speaker 1**: So
*40:24.260*

**Speaker 1**: One, you can import, export, duplicate, and delete a command set.
*40:25.020*

**Speaker 1**: And there is a default setting that you can do.
*40:30.700*

**Speaker 1**: Our machines use a series a setup called we call it slice office.
*40:36.080*

**Speaker 1**: But one of the things that you want to do, in the upper right-hand corner, search for the word toggle, okay?
*40:42.560*

**Speaker 1**: Yeah.
*40:50.500*

**Speaker 1**: The second selection is going to say toggle effects on off.
*40:52.579*

**Speaker 2**: Yeah.
*40:56.420*

**Speaker 1**: That's your color effects.
*40:57.460*

**Speaker 1**: Now, do you have a a keyboard selection for that yet?
*41:00.560*

**Speaker 1**: There's nothing in there now.
*41:04.080*

**Speaker 1**: Okay.
*41:05.440*

**Speaker 1**: What we do is we use option C.
*41:05.760*

**Speaker 1**: And that allows you, when you're either in the color board or not, you can option C and toggle your color grade on, off, on, off, before, after, before, after.
*41:09.560*

**Speaker 2**: That's very cool.
*41:23.520*

**Speaker 2**: So does that work with all the effects?
*41:24.559*

**Speaker 1**: You know what?
*41:28.880*

**Speaker 1**: It's interesting.
*41:29.440*

**Speaker 1**: I'm just now noticing that it says effects and not color effects.
*41:30.720*

**Speaker 1**: Because I think it used to be, it used to say colour effects.
*41:36.120*

**Speaker 2**: It says in inspector or colour board, selected corrections and effects are toggled on or off.
*41:40.040*

**Speaker 2**: So I think it means both colour and effects.
*41:45.000*

**Speaker 1**: Let's see.
*41:49.960*

**Speaker 1**: Oh, I think I'm actually looking at a piece that has not been color graded.
*41:57.720*

**Speaker 1**: No, it's color graded.
*42:00.839*

**Speaker 1**: This is compelling radio.
*42:05.820*

**Speaker 2**: Yeah, I mean an argument looking at final cut.
*42:09.020*

**Speaker 1**: That's interesting.
*42:12.780*

**Speaker 1**: It is
*42:13.820*

**Speaker 1**: I don't think it works the same.
*42:16.040*

**Speaker 1**: Let me just try and put some effect on that.
*42:19.320*

**Speaker 1**: I'd be really upset.
*42:22.280*

**Speaker 1**: Select one or more clips, command option, up arrow, and promote to secondary storyline.
*42:26.700*

**Speaker 1**: Yes, Alex.
*42:31.580*

**Speaker 1**: So now here's another little workflow tip.
*42:33.580*

**Speaker 1**: That I glazed over in my recent tutorial that I did with Dave Dugdale from NAB.
*42:37.099*

**Speaker 1**: So, we were doing a thing where we were modifying a timeline, and he had a whole bunch of B-roll.
*42:47.600*

**Speaker 1**: That we didn't want to knock out of place, you know, with the secondary storyline connected to all.
*42:54.299*

**Speaker 1**: Yeah, very important.
*43:02.059*

**Speaker 1**: I will get to that, Alex.
*43:03.339*

**Speaker 1**: So what what we were doing is we were taking what I was doing is I would take my secondary storyline, which let's okay, let's paint this verbally since we don't have
pictures on the show.
*43:05.279*

**Speaker 1**: Let's say you have a one-minute interview and you have one minute of secondary storyline.
*43:16.559*

**Speaker 1**: And it's not so much an interview, but it's a bunch of voiceover from an interview.
*43:20.720*

**Speaker 1**: Okay?
*43:26.720*

**Speaker 1**: So then you decide that one sound bite is superfluous.
*43:28.520*

**Speaker 1**: We want to delete it.
*43:32.120*

**Speaker 1**: So you delete that.
*43:32.920*

**Speaker 1**: And let's say that was at 30 seconds in.
*43:34.120*

**Speaker 1**: Okay?
*43:36.440*

**Speaker 1**: So everything from 30 seconds to the end is going to ripple down.
*43:37.000*

**Speaker 1**: And every all your B roll for the tail end of the piece is going to be out of sync.
*43:42.700*

**Speaker 1**: Now there's a couple of ways to rectify this.
*43:47.660*

**Speaker 1**: One, you don't have to delete the sound bite that you don't want.
*43:50.140*

**Speaker 1**: You may just want a breath of air there.
*43:53.980*

**Speaker 1**: So you could use the letter V to mute it or command option up arrow and then delete it, and that will leave the slug that we talked about earlier in the primary storyline.
*43:57.480*

**Speaker 1**: But more than likely, you do want to pull that up.
*44:05.800*

**Speaker 1**: So here's the trick.
*44:08.920*

**Speaker 1**: Take all the B-roll that's in the secondary storyline that is after the soundbite that you're about to delete.
*44:10.599*

**Speaker 1**: Highlight it all, command option up arrow.
*44:19.800*

**Speaker 1**: What it's going to do is it's going to make a second secondary storyline, another secondary storyline above the first one.
*44:23.080*

**Speaker 1**: And it's going to leave a black slug where all of your B roll was in the first secondary storyline.
*44:32.799*

**Speaker 1**: Does that make sense?
*44:40.540*

**Speaker 2**: Yes.
*44:41.660*

**Speaker 1**: Now what you can do is you can take that black slug and delete it, and the second secondary storyline will drop down adjacent to the
*44:42.380*

**Speaker 1**: First secondary storyline, but it is attached to the next clip, the clip directly underneath it.
*44:52.900*

**Speaker 1**: So when I delete the problem sound byte, all the B-roll that's very carefully associated with the footage
*45:01.860*

**Speaker 1**: Past me is still going to be in sync.
*45:12.380*

**Speaker 1**: Now, there will be a clip collision going on there, okay?
*45:15.500*

**Speaker 1**: And you'll have to decide what to do with the B-roll that was covering the soundbite that you've decided to delete.
*45:19.740*

**Speaker 1**: But that's called editing, and you're so you're going to have to do that either way.
*45:25.860*

**Speaker 2**: Interesting.
*45:30.180*

**Speaker 2**: Also read the thing that Alex said.
*45:30.900*

**Speaker 2**: So if you delete a clip on a primary storyline and you shift delete,
*45:33.780*

**Speaker 2**: That leaves a placeholder as well.
*45:39.840*

**Speaker 2**: That's quite interesting.
*45:42.080*

**Speaker 1**: That's actually one step less than what I just said.
*45:43.120*

**Speaker 1**: Command option up arrow and then delete.
*45:46.240*

**Speaker 1**: Yeah.
*45:48.240*

**Speaker 1**: Thank you, Alex, for making look dumb again.
*45:48.880*

**Speaker 2**: Both interesting ways, both other applications.
*45:54.080*

**Speaker 2**: Yeah.
*45:56.599*

**Speaker 2**: Yeah.
*45:57.320*

**Speaker 1**: Okay.
*45:58.119*

**Speaker 1**: So anyway, that trick, I actually do that about three or four times in the piece that I did with Dave Dugdale.
*45:58.839*

**Speaker 1**: And I had somebody recently on Twitter say, Hey, can you describe that a little bit more or do a tutorial?
*46:07.480*

**Speaker 1**: And so there it's been described a little bit more.
*46:14.280*

**Speaker 1**: I probably still should do a tutorial because it's very much a visual thing.
*46:16.920*

**Speaker 1**: But it all kind of falls within the um the the master category of what I call k you know, timeline kung fu.
*46:20.559*

**Speaker 1**: There's certain tricks you just you know, you kind of need to uh
*46:28.000*

**Speaker 1**: to figure out.
*46:32.820*

**Speaker 1**: Here's one that was like one this was the trick that made me first realize first come up with the term timeline kung fu.
*46:34.500*

**Speaker 1**: You have two shots, shot one, shot two.
*46:43.980*

**Speaker 1**: You look at it and you go, okay, everything is in sync.
*46:46.780*

**Speaker 1**: I don't want to change.
*46:49.420*

**Speaker 1**: I don't want to ripple or.
*46:50.540*

**Speaker 1**: Make something get knocked out of sync.
*46:52.620*

**Speaker 1**: But I want shot number one.
*46:55.100*

**Speaker 1**: I've decided I've overcut this piece, and I want shot number one to be the duration of shot number one and two.
*46:56.700*

**Speaker 1**: In olden days, that would be really easy to do.
*47:04.000*

**Speaker 1**: You delete shot two, you take the left-hand side of shot one, and you drag it out to fill the gap that was left behind.
*47:06.880*

**Speaker 1**: Yeah.
*47:13.620*

**Speaker 1**: That works fine in a track-based editor.
*47:13.940*

**Speaker 1**: We don't have tracks, rip, you know, magnetic timeline.
*47:16.340*

**Speaker 1**: What are we going to do?
*47:19.540*

**Speaker 1**: So here's the trick.
*47:21.540*

**Speaker 1**: take shot number one.
*47:22.940*

**Speaker 1**: We use our command option up arrow, boop, boop, pop it up out of the primary storyline.
*47:24.540*

**Speaker 1**: I now take the right hand side of that clip, drag it out with snapping on to match the duration of
*47:29.980*

**Speaker 1**: Clip number two.
*47:37.500*

**Speaker 1**: Okay.
*47:39.180*

**Speaker 2**: Yep.
*47:39.980*

**Speaker 1**: Now I take my keyboard shortcut, command option, down arrow.
*47:40.700*

**Speaker 1**: I slam it right back down where it was.
*47:45.340*

**Speaker 1**: And the only thing you're going to have to clean up, because Final Cut assumes you might still want the audio for clip number two
*47:48.060*

**Speaker 1**: is you're going to have to delete the the leftover audio from clip number two.
*47:55.079*

**Speaker 1**: Very cool.
*48:03.140*

**Speaker 1**: Very simple.
*48:03.940*

**Speaker 1**: And actually, there's an easier way to do it.
*48:04.660*

**Speaker 1**: You could do command option you could select both clips, command option up arrow.
*48:06.580*

**Speaker 1**: then delete the second one, then drag out the first one to snap to the length of the slug that's left behind, and then command option down arrow.
*48:12.720*

**Speaker 1**: And now since the slug has no audio, it won't try and preserve it.
*48:23.599*

**Speaker 2**: So we'll come.
*48:27.059*

**Speaker 2**: Cool.
*48:28.260*

**Speaker 1**: Yeah, that was something that I figured out like a couple of years ago.
*48:28.900*

**Speaker 1**: And I was like, okay.
*48:32.339*

**Speaker 1**: And that was it was kind of like one of these things where I just went
*48:33.619*

**Speaker 1**: That's not bad.
*48:37.120*

**Speaker 1**: I mean, it is a Scott Simmons workaround.
*48:38.400*

**Speaker 1**: You know, Scott always teases me about having workarounds, but
*48:41.040*

**Speaker 1**: It works.
*48:46.320*

**Speaker 2**: It's a workaround that works.
*48:47.280*

**Speaker 1**: Yeah, exactly.
*48:48.880*

**Speaker 1**: I'm a little upset that my toggle effects is not working.
*48:51.360*

**Speaker 1**: I'm kind of upset by that.
*48:56.560*

**Speaker 2**: I've tried it and I think you have to be in the inspector for it to work.
*48:58.720*

**Speaker 1**: Well, that is new.
*49:03.359*

**Speaker 1**: You didn't have to be.
*49:05.039*

**Speaker 1**: In Inspector or colorboard, selected corrections and effects are toggled on or off.
*49:07.359*

**Speaker 1**: They've I think they've added the word in inspector.
*49:13.200*

**Speaker 2**: Yeah, because off
*49:16.240*

**Speaker 2**: If I'm in Inspector, I can toggle them on and off because I've just applied a generic contrast and that works.
*49:18.200*

**Speaker 2**: But if I click out of Inspector, it gives me the annoying frog noise
*49:24.760*

**Speaker 2**: that's not working.
*49:34.099*

**Speaker 2**: So that's at least it works somehow.
*49:35.140*

**Speaker 2**: Oh, so talking of effects, is there any way to select, say, all clips?
*49:38.339*

**Speaker 2**: and get rid of all effects applied to those clips.
*49:43.680*

**Speaker 2**: Because in Premiere, what I could do is select all clips, Command A, and right click and there'd be a little option saying
*49:48.480*

**Speaker 2**: remove effects.
*49:57.280*

**Speaker 2**: Is that a thing in Florida?
*49:58.960*

**Speaker 1**: Are you saying you want to remove effects or add effects?
*50:00.000*

**Speaker 2**: Remove.
*50:02.800*

**Speaker 1**: Right.
*50:03.600*

**Speaker 1**: So this is a great bone of contention that the community has had with Apple.
*50:04.160*

**Speaker 1**: There used to be a remove attributes tool, which was very powerful.
*50:10.299*

**Speaker 1**: You could select all clips and you can go, I want to take off my audio EQ on all of these clips.
*50:14.700*

**Speaker 1**: And even if all the clips didn't have audio EQ, it would still say, okay, well, that one doesn't have any, so I don't care.
*50:20.320*

**Speaker 1**: No, you can't do that.
*50:28.160*

**Speaker 1**: However, there is a bit of a workaround until they actually give us remove attributes.
*50:29.520*

**Speaker 1**: And that is this.
*50:35.020*

**Speaker 1**: Let's say you've put an audio, you know, you were in a bad mood because somebody was parked in your parking space when you got to the office.
*50:37.180*

**Speaker 1**: And you.
*50:44.619*

**Speaker 1**: And you were EQing stuff with vengeance and anger.
*50:47.260*

**Speaker 1**: And then when you were in a better mood, you started listening to what you had done, and you realized that was really crap.
*50:53.339*

**Speaker 1**: So what you can do, and you've so you do want a clip with anger and vengeance, and then you copy and paste that attribute across all your clips.
*51:00.240*

**Speaker 1**: And then you decide I need to be less angry next time I do audio EQ.
*51:09.940*

**Speaker 1**: So, what you can do is if you select all those clips
*51:14.740*

**Speaker 1**: and they all have the audio EQ on them, or any audio EQ on them.
*51:18.620*

**Speaker 1**: In the Inspector, when you go to the Audio tab, it'll say twelve clips selected.
*51:24.780*

**Speaker 1**: And then you see the audio EQ, and you're like, oh, select it, hit delete, and it is as though you were doing a remove attributes of audio.
*51:31.700*

**Speaker 1**: It's not perfect, and it is clearly a workaround, but I keep forgetting that you can do that.
*51:41.140*

**Speaker 1**: You can.
*51:47.060*

**Speaker 1**: Do a bunch of stuff to well, you could certainly delete effects from a bunch of clips as long as they both have it.
*51:49.760*

**Speaker 1**: Now, here's the downside
*51:57.680*

**Speaker 1**: Let's say in that selection of 10, 15 clips, there was one that was EQ'd really, really well.
*51:59.040*

**Speaker 1**: Guess what?
*52:04.720*

**Speaker 1**: You want you that's going to screw up your whole remove EQs.
*52:06.480*

**Speaker 1**: And there's no way of visually just looking at 15 clips and go, oh, that's the one that doesn't have EQ.
*52:11.260*

**Speaker 1**: So there is a downside to that, and that's why I think Apple needs to address this.
*52:16.140*

**Speaker 1**: But it's you know, it's it's a work it is a workaround that I think we forget is there.
*52:22.100*

**Speaker 1**: Make sense?
*52:29.480*

**Speaker 2**: Makes sense.
*52:30.520*

**Speaker 2**: Makes sense.
*52:31.240*

**Speaker 2**: Yeah.
*52:31.800*

**Speaker 1**: Okay, let's let's this is the answer.
*52:32.680*

**Speaker 1**: Share Alex Fordee's comments show.
*52:35.960*

**Speaker 1**: You have a loan clip connected.
*52:38.760*

**Speaker 1**: Oh, wait, wait, wait.
*52:40.920*

**Speaker 1**: This is a two-part thing.
*52:41.880*

**Speaker 1**: If you delete an interview clip with a secondary storyline connected, it will also be deleted.
*52:42.920*

**Speaker 1**: That is true.
*52:47.560*

**Speaker 1**: You got to be careful.
*52:48.360*

**Speaker 1**: And I hear people say that.
*52:49.400*

**Speaker 1**: It's like, ah, I'm losing my stuff.
*52:50.760*

**Speaker 1**: And that's because they don't realize what the user interface means.
*52:54.080*

**Speaker 1**: If a thing is connected to another thing and you delete the second thing, the first thing gets deleted, whatever it is.
*52:57.840*

**Speaker 1**: If you use Shift Delete on the primary storyline, and you have a lone clip connected.
*53:05.320*

**Speaker 1**: Wait, I can't.
*53:12.860*

**Speaker 2**: No, I I think that's that's two different things.
*53:14.300*

**Speaker 1**: Okay.
*53:16.700*

**Speaker 2**: Yeah.
*53:17.420*

**Speaker 1**: It's that's so use it use shift delete and the and it'll still be connected to the um to the uh
*53:17.740*

**Speaker 2**: Secondary storyline.
*53:24.200*

**Speaker 1**: No, the secondary storyline will still be connected to a slug in the primary storyline.
*53:25.560*

**Speaker 1**: Yeah, that's right.
*53:29.400*

**Speaker 1**: Here's one that's really good.
*53:31.320*

**Speaker 1**: So you have.
*53:33.240*

**Speaker 1**: You have, let's say we have a clip of somebody on a hang glider.
*53:35.940*

**Speaker 1**: I'm making up a video here, and he's hang gliding through the frame.
*53:44.900*

**Speaker 1**: And above that clip, you have a title that says, He's on a hang glider.
*53:49.420*

**Speaker 1**: Okay?
*53:56.700*

**Speaker 1**: And then you look at it and you say, actually, I don't want the guy to start out of frame.
*53:58.180*

**Speaker 1**: I want them to start in frame.
*54:05.440*

**Speaker 1**: So you hit the letter T, here's another keyboard shortcut, T for trim.
*54:07.200*

**Speaker 1**: And then you put your mouse over that clip.
*54:11.280*

**Speaker 1**: And now, when you click and drag left and right on that clip, you're doing a roll edit.
*54:13.520*

**Speaker 1**: No, it's not a roll edit.
*54:19.440*

**Speaker 1**: It's a slip edit where it's slipping it inside the boundaries of your in and out point.
*54:21.200*

**Speaker 1**: Okay?
*54:27.920*

**Speaker 1**: Okay.
*54:28.640*

**Speaker 1**: So the whole.
*54:29.040*

**Speaker 1**: If you move it one second to the left, you'll add one second of tail.
*54:31.040*

**Speaker 1**: If you move it one second to the right, you'll add one second of pre-roll.
*54:35.760*

**Speaker 1**: So it's the same duration, but it's just different frames within that clip.
*54:39.360*

**Speaker 1**: Very powerful.
*54:44.440*

**Speaker 1**: The trim tool.
*54:45.560*

**Speaker 1**: You got to know that.
*54:46.680*

**Speaker 1**: But this gets better.
*54:47.640*

**Speaker 1**: So now you have that title that says he's on a hang glider.
*54:49.000*

**Speaker 1**: But if you drag your clip, if you hit the letter T and drag your clip to the left, that title that says He's on a Hang Glider, which is attached to that clip, is going to slide
with it.
*54:53.280*

**Speaker 1**: So the title will begin on the previous clip now because it's sliding with your clip.
*55:05.820*

**Speaker 1**: Does that make sense?
*55:15.420*

**Speaker 1**: Because it's attached to it.
*55:16.300*

**Speaker 1**: It's connected to it.
*55:17.260*

**Speaker 2**: Yeah, it all makes sense.
*55:18.140*

**Speaker 1**: So powerful.
*55:20.140*

**Speaker 1**: No, that's bad.
*55:21.580*

**Speaker 1**: But here's the workaround: the key that is above your tab key on your keyboard.
*55:23.420*

**Speaker 1**: I call it the accent key, but it's called the grave accent key, I believe.
*55:29.680*

**Speaker 1**: If you select that.
*55:34.720*

**Speaker 1**: It will momenta if you ch press and hold it, it will momentarily disable connections.
*55:37.060*

**Speaker 1**: So you can slip that clip underneath the title without sliding the clip left or right while you have the grave accent key.
*55:45.860*

**Speaker 1**: Depressed.
*55:55.500*

**Speaker 2**: I see, yeah, okay.
*55:56.620*

**Speaker 2**: That makes more sense.
*55:57.740*

**Speaker 2**: That makes more sense.
*55:59.420*

**Speaker 1**: And what you get, what you get is you get a little tiny, what's it like
*56:00.540*

**Speaker 1**: Oh, it's a little orange dot that has the connection icon and it's got a black slash through it.
*56:05.940*

**Speaker 2**: Okay.
*56:14.500*

**Speaker 2**: That's something to keep in mind.
*56:15.540*

**Speaker 1**: Very powerful to keep in mind.
*56:16.900*

**Speaker 1**: You don't need it a lot, but when you do, it's awesome to have remembered it.
*56:18.260*

**Speaker 1**: It's just it's if you ever find that the connection bar is bugging you, just hold that and do whatever it is you needed to do, and you're probably going to be okay.
*56:23.300*

**Speaker 2**: I should put a little sticker on there.
*56:36.099*

**Speaker 2**: A little star.
*56:38.180*

**Speaker 1**: No, just learn it, because otherwise you're going to have a keyboard full of stickers and stars.
*56:39.380*

**Speaker 2**: Just remember this one, and every single key is going to have a star.
*56:44.320*

**Speaker 1**: Like, what did that one do?
*56:47.200*

**Speaker 1**: Exactly.
*56:48.480*

**Speaker 1**: Now I don't have any markers on my keyboard but stars.
*56:48.800*

**Speaker 1**: Here's an interesting little trick that I came up with a while ago.
*56:54.720*

**Speaker 1**: One of our clients likes to
*56:59.520*

**Speaker 1**: dissolve to white and then dissolve to a graphic.
*57:04.599*

**Speaker 1**: So the guy's talking and then it's dissolve to white and then dissolve to a graphic.
*57:07.480*

**Speaker 1**: So the way the way we've dec
*57:11.640*

**Speaker 1**: Decided to do this because it's B roll on top of the
*57:13.720*

**Speaker 1**: The um the sound byte.
*57:18.180*

**Speaker 1**: You know, it it yes, there is a fade to color
*57:21.940*

**Speaker 1**: Transition, but I don't want to transition from the primary storyline.
*57:26.760*

**Speaker 1**: I still want to maintain the audio from the primary storyline, so I do want to put it as B-roll.
*57:30.120*

**Speaker 1**: So, what we do is we make a little 40-frame-long white slug.
*57:34.280*

**Speaker 1**: We then put a 20-frame fade-up and fade out at the beginning and end of the white slug.
*57:40.020*

**Speaker 1**: And then we put it on a yet another
*57:45.380*

**Speaker 1**: Storyline, if you will, right above the transition point that would normally be a cut from the person talking to the PCB role or the graphic.
*57:48.020*

**Speaker 1**: Very cool.
*57:58.080*

**Speaker 1**: Okay, that's one way to do it.
*57:58.960*

**Speaker 1**: But sometimes you are doing it between two images.
*58:02.560*

**Speaker 1**: Let me think.
*58:08.280*

**Speaker 1**: How can I this is a slightly different instance of this how do I how do I explain this?
*58:09.000*

**Speaker 1**: Because in that instance I might be better off with a
*58:20.880*

**Speaker 1**: I'm having a hard time coming up with a simple way of verbalizing this, but let me put it this way.
*58:27.480*

**Speaker 1**: You can change by default when you drop a clip on top of another clip.
*58:33.640*

**Speaker 1**: The connection point is the first frame of the clip that you that is above.
*58:39.000*

**Speaker 1**: The connected clip, by default, connects at its first frame.
*58:43.240*

**Speaker 1**: Sometimes you don't want that.
*58:46.839*

**Speaker 1**: There are times when it's really nice to connect at a different place, and you can do that by hitting Command Option
*58:49.180*

**Speaker 1**: and clicking anywhere on the connected clip, and it will move its connection point to the point where you connected.
*58:57.340*

**Speaker 2**: Okay.
*59:05.500*

**Speaker 2**: And just to make sure, connected clips are have little tabs that go down from the clip, is that?
*59:05.980*

**Speaker 1**: Exactly right.
*59:11.980*

**Speaker 2**: Okay.
*59:13.860*

**Speaker 2**: Yeah.
*59:14.340*

**Speaker 2**: Just been noticing them and wondering what they actually do.
*59:14.820*

**Speaker 1**: Yes.
*59:17.380*

**Speaker 1**: So basically, it's saying so in essence, in traditional video editors, everything is time based.
*59:17.780*

**Speaker 1**: Five seconds in, I want this to happen, and a minute in, I want this to happen, and et cetera, et cetera.
*59:26.880*

**Speaker 1**: And on track three, at five seconds in, I want this to happen, or what
*59:32.400*

**Speaker 1**: But in Farakat Ten, everything is relationship-based.
*59:36.840*

**Speaker 1**: So that's why things are all connected.
*59:40.360*

**Speaker 1**: When this thing happens, I also want this other thing to happen.
*59:42.920*

**Speaker 1**: And it's and the visual metaphor for that is the connection bar.
*59:47.460*

**Speaker 1**: The connector tells me what is related to what.
*59:52.100*

**Speaker 1**: So when you move something, it moves its cur its connected pieces.
*59:55.460*

**Speaker 1**: Which is really good.
*01:00:00.720*

**Speaker 1**: So if I have a piece of B-roll and the guy's saying, you know, at my bank, I really like the fact that when I go to the ATM machine, it's inside a little room that it's safe, so
I can do a transaction in the middle of the night.
*01:00:01.520*

**Speaker 1**: Okay, so during that sound bite, I want a wide shot of the bank.
*01:00:14.620*

**Speaker 1**: I want a wide shot of the door going into the little room, and I want a shot of a guy
*01:00:18.460*

**Speaker 1**: you know, doing a transaction in the middle of the night.
*01:00:23.840*

**Speaker 1**: But if I decide to move that soundbite to another place, I want all those B-roll shots to go with it because they're related to that.
*01:00:26.640*

**Speaker 1**: So that's why it's important to understand how the connected clip stuff works.
*01:00:35.720*

**Speaker 1**: Okay.
*01:00:44.860*

**Speaker 1**: I wish they would do it a different way.
*01:00:45.660*

**Speaker 1**: I think it would be nice.
*01:00:48.140*

**Speaker 1**: Well, now I don't mind the connected clip, but I've always wanted this in an editor, and I've never found one that did it.
*01:00:50.140*

**Speaker 1**: I want to select a handful of things and just group them.
*01:00:56.240*

**Speaker 1**: Command G.
*01:01:01.120*

**Speaker 1**: Now Command G in Final Cut 10 creates a s a storyline, and it's kind of like grouping it.
*01:01:02.480*

**Speaker 1**: But I just wanted to group it like a drawing program would.
*01:01:09.300*

**Speaker 1**: So if I click on any one of the things, it all gets grabbed.
*01:01:12.820*

**Speaker 1**: Right?
*01:01:19.060*

**Speaker 2**: And well, you can do that on Premiere, just to
*01:01:19.700*

**Speaker 2**: Throw it in there.
*01:01:23.080*

**Speaker 1**: Select a bunch of stuff and hit Command G or something.
*01:01:24.440*

**Speaker 2**: I don't think it's there's any
*01:01:28.680*

**Speaker 2**: Default command, the shortcut, but you can set it yourself.
*01:01:31.800*

**Speaker 2**: And it's in the contextual menu when you right-click on a clip.
*01:01:34.600*

**Speaker 1**: I will take a look at that.
*01:01:37.560*

**Speaker 1**: I did not know that.
*01:01:39.320*

**Speaker 1**: I think that's.
*01:01:40.440*

**Speaker 1**: I think.
*01:01:41.560*

**Speaker 1**: I'm probably going to be proven wrong.
*01:01:42.920*

**Speaker 1**: That's relatively new.
*01:01:44.840*

**Speaker 2**: Probably since CS6, at least.
*01:01:48.280*

**Speaker 2**: Because that's when I started looking into it.
*01:01:51.080*

**Speaker 2**: So it's probably at least since that.
*01:01:53.000*

**Speaker 1**: CS55.
*01:01:56.340*

**Speaker 1**: That's when I got fed up.
*01:01:59.780*

**Speaker 2**: That's when I'm talking about a couple.
*01:02:02.180*

**Speaker 1**: Anything else on your list?
*01:02:05.060*

**Speaker 1**: Well, I've got quite a kind of a big question about metadata and perfect thing to ask at fifty seven minutes into the interview.
*01:02:07.279*

**Speaker 2**: Oh, yeah.
*01:02:14.559*

**Speaker 2**: Okay, so I'm shooting a short film end of this week.
*01:02:17.380*

**Speaker 1**: Okay.
*01:02:21.140*

**Speaker 2**: And I've already generated quite a large amount of metadata in in terms of a short list.
*01:02:22.260*

**Speaker 2**: So I have things like scene, shot number, shot size, character, type of shot, location and time of day.
*01:02:28.120*

**Speaker 2**: And I'm wondering what is the best way to get that into final cut.
*01:02:36.120*

**Speaker 2**: Obviously, you could say Philip Hodges Slumberjack, but I don't have an iPad or a
*01:02:39.480*

**Speaker 2**: and a few hundred bucks spare to buy a lumberjack.
*01:02:44.820*

**Speaker 2**: Yes.
*01:02:48.260*

**Speaker 2**: So would you do that with keywords or would you do that in the notes field?
*01:02:48.740*

**Speaker 2**: Or some other way.
*01:02:53.360*

**Speaker 1**: Let's uh you started to talk about metadata, and my mind totally wandered to Philip Hodgetts and Lumberjack.
*01:02:54.560*

**Speaker 1**: And then
*01:03:01.760*

**Speaker 1**: I will admit that I didn't hear what you said.
*01:03:02.840*

**Speaker 1**: So can you repeat what the different bits of metadata that you're dealing with are?
*01:03:05.720*

**Speaker 2**: So I have well, it's things that I put into the shot list.
*01:03:10.120*

**Speaker 2**: So I have.
*01:03:13.480*

**Speaker 2**: Scene shot number, which is like 1A1B shot size, so like Y close-up.
*01:03:14.599*

**Speaker 2**: Character name, type of shot, whether it's dialogue or action or detail, location and time of day in the in the scene.
*01:03:23.039*

**Speaker 1**: Huh.
*01:03:36.359*

**Speaker 1**: Yeah, those would be awesome in shot in Lumberjack.
*01:03:37.240*

**Speaker 2**: Yeah.
*01:03:40.920*

**Speaker 2**: Yeah, I was thinking that because I watched Phillips' demo from NAB.
*01:03:41.640*

**Speaker 2**: Right.
*01:03:45.240*

**Speaker 2**: That was actually really fun.
*01:03:45.720*

**Speaker 1**: Now I believe and you're actually using the Shotlister app?
*01:03:47.620*

**Speaker 2**: No, I'm this is a spreadsheet.
*01:03:52.420*

**Speaker 1**: Ah, okay.
*01:03:54.660*

**Speaker 1**: So let's go through them one at a time.
*01:03:58.100*

**Speaker 1**: What was the first one?
*01:04:02.660*

**Speaker 2**: It's scene.
*01:04:04.020*

**Speaker 1**: Scene and take number.
*01:04:05.380*

**Speaker 2**: Yes, scene and shot number and then take number would be in there as well.
*01:04:07.220*

**Speaker 1**: Okay, so let's keep in mind when you go to your info panel, there are
*01:04:12.960*

**Speaker 1**: In the lower left-hand corner of the Inspector, there is a little pop-up menu that probably defaults to basic.
*01:04:24.119*

**Speaker 1**: All right.
*01:04:32.700*

**Speaker 1**: Now there are when you pop that down, there's many other pop-ups.
*01:04:34.460*

**Speaker 1**: There's general, and that has a place for real scene and take.
*01:04:39.180*

**Speaker 2**: Okay.
*01:04:46.839*

**Speaker 1**: Also camera angle.
*01:04:47.720*

**Speaker 1**: So you could camera angle could be close up wide, whatever.
*01:04:50.680*

**Speaker 2**: Yeah.
*01:04:55.079*

**Speaker 1**: So that's one place you could put a lot of this data.
*01:04:55.799*

**Speaker 2**: And then characters, you could do keywords, couldn't you?
*01:05:02.440*

**Speaker 2**: You could do character A.
*01:05:05.080*

**Speaker 1**: I would definitely want to put characters as keywords.
*01:05:08.200*

**Speaker 1**: I would think.
*01:05:11.000*

**Speaker 1**: You know, um you Lumberjack is is amazing.
*01:05:13.200*

**Speaker 1**: I would also recommend, and I don't normally recommend
*01:05:19.119*

**Speaker 1**: You know, people run out and buy stuff.
*01:05:23.340*

**Speaker 1**: But Michael Matzdorf wrote a whole book about how he did focus.
*01:05:25.420*

**Speaker 1**: And that might be worth.
*01:05:31.500*

**Speaker 1**: Getting to take a look at how it's done at the highest level, because I'm sure that you could apply a lot of that to what you're doing on the short film.
*01:05:34.880*

**Speaker 1**: But but let me ask you this.
*01:05:44.760*

**Speaker 1**: Did you know that there were alternate views of the metadata?
*01:05:46.119*

**Speaker 2**: I did not.
*01:05:49.640*

**Speaker 1**: Cool.
*01:05:50.760*

**Speaker 1**: Then I feel good that I could share something with you.
*01:05:51.720*

**Speaker 2**: So hold on, could you tell me how to get to those message data views again?
*01:05:55.160*

**Speaker 1**: Sure, sure.
*01:05:58.920*

**Speaker 1**: So select any clip in your browser or your timeline.
*01:05:59.640*

**Speaker 1**: Click on in the Inspector in the upper right-hand corner, hit the Info tab.
*01:06:05.040*

**Speaker 1**: Yeah.
*01:06:11.040*

**Speaker 1**: And then in the lower left-hand corner of the Info tab, it says Basic.
*01:06:11.920*

**Speaker 1**: Okay.
*01:06:16.480*

**Speaker 1**: Go down to general.
*01:06:16.880*

**Speaker 2**: Oh, that's revealed a lot of that could go.
*01:06:19.220*

**Speaker 1**: There's a ton of stuff there.
*01:06:23.780*

**Speaker 1**: There's extended, there's audio specific stuff.
*01:06:25.380*

**Speaker 1**: There's settings where you can change your you know, like how it handles alpha channels, what role it's on.
*01:06:29.320*

**Speaker 1**: I would also recommend that you get in the habit of using the roles properly.
*01:06:39.040*

**Speaker 1**: Learn a little bit about how to use roles because
*01:06:43.680*

**Speaker 1**: Michael Matsdorf, for one, will tell you that managing your roles properly is really important when it comes to audio post, for sure.
*01:06:47.880*

**Speaker 2**: Yeah.
*01:06:56.200*

**Speaker 1**: Okay.
*01:06:57.640*

**Speaker 1**: Okay, that is my mom calling a second time.
*01:06:58.600*

**Speaker 2**: Okay, we better go then.
*01:07:01.480*

**Speaker 1**: Yep.
*01:07:03.080*

**Speaker 1**: We will um
*01:07:03.960*

**Speaker 1**: Thank you so much for doing this.
*01:07:06.079*

**Speaker 1**: I really appreciate it.
*01:07:07.520*

**Speaker 1**: Yeah, my podcast just got preempted by my mom.
*01:07:08.640*

**Speaker 1**: But tomorrow's Mother's Day, and I'm going to go see her today.
*01:07:11.359*

**Speaker 1**: So, Machek, thanks so much.
*01:07:13.920*

**Speaker 1**: I appreciate it.
*01:07:15.680*

**Speaker 1**: How do if people want to see what you're working on, or you what kind of social media things can people follow you on?
*01:07:16.720*

**Speaker 2**: Definitely Twitter.
*01:07:22.560*

**Speaker 2**: I'm very active on that.
*01:07:23.360*

**Speaker 2**: At Machekiliski.
*01:07:25.960*

**Speaker 2**: So at M A C I E K K A L I S K I or four colour video dot com
*01:07:27.080*

**Speaker 2**: Which is spelt the American way.
*01:07:34.320*

**Speaker 2**: So F U L L C O L O R.
*01:07:35.920*

**Speaker 2**: You mean P O E?
*01:07:38.960*

**Speaker 2**: The shorter way.
*01:07:41.520*

**Speaker 2**: The reason I
*01:07:42.720*

**Speaker 2**: I put it because it's shorter.
*01:07:43.940*

**Speaker 1**: Very cool.
*01:07:45.540*

**Speaker 1**: Well, anyway, thanks so much.
*01:07:46.099*

**Speaker 1**: I got to run.
*01:07:47.780*

**Speaker 1**: I appreciate your time, and it's been great chatting.
*01:07:48.660*

**Speaker 1**: Take care.
*01:07:52.260*

**Speaker 1**: Brilliant.
*01:07:52.740*

**Speaker 1**: Cheers.
*01:07:53.140*

**Speaker 1**: Bye.
*01:07:53.460*

**Speaker 1**: All right, I warned you.
*01:07:55.320*

**Speaker 1**: That interview was a little bit all over the place, but it was kind of beginning-ish intermediate, right?
*01:07:57.080*

**Speaker 1**: I mean, wouldn't you agree?
*01:08:03.240*

**Speaker 1**: So definitely we found out something very interesting.
*01:08:04.920*

**Speaker 1**: I don't think the toggle effects works the way it used to work in 10.
*01:08:08.920*

**Speaker 1**: 1.
*01:08:13.080*

**Speaker 1**: And I got to say, I'm a little upset about that.
*01:08:13.720*

**Speaker 1**: And I'm going to be writing a bug report as soon as we are done, as soon as I'm done recording here.
*01:08:17.380*

**Speaker 1**: Because I used to use that in the timeline all the time.
*01:08:23.540*

**Speaker 1**: And I'm kind of surprised I didn't know it.
*01:08:26.740*

**Speaker 1**: I haven't noticed it in the last couple of weeks.
*01:08:28.259*

**Speaker 1**: So, thanks for listening to this episode of The Grill.
*01:08:30.319*

**Speaker 1**: Hope you enjoyed our conversation with Machek.
*01:08:32.799*

**Speaker 1**: If you know anybody who's doing something really amazing in Final Cut 10, let me know.
*01:08:35.279*

**Speaker 1**: Find me on Twitter.
*01:08:40.240*

**Speaker 1**: I'll be honest with you.
*01:08:41.200*

**Speaker 1**: I'm going to find stuff on Twitter.
*01:08:42.260*

**Speaker 1**: And if I don't respond back right away, just I give you permission to bug me.
*01:08:43.620*

**Speaker 1**: Okay.
*01:08:48.260*

**Speaker 1**: So I'm always looking for great stuff for the show.
*01:08:48.980*

**Speaker 1**: Also,
*01:08:52.260*

**Speaker 1**: You know, I gotta say, I kinda miss not having Alex around me.
*01:08:53.760*

**Speaker 1**: He and I used to go to dinner all the time, and he's now back in, uh, he's back in New York.
*01:08:56.080*

**Speaker 1**: Uh
*01:09:00.480*

**Speaker 1**: I didn't realize this.
*01:09:01.719*

**Speaker 1**: That guy had an apartment in New York the whole time he was living out here.
*01:09:03.159*

**Speaker 1**: Anyway, so he's doing editing, he's doing coloring, and he's enjoying being in a new environment out there.
*01:09:06.759*

**Speaker 1**: So, anyway, I don't know, no.
*01:09:14.440*

**Speaker 1**: Why I even brought that up.
*01:09:16.480*

**Speaker 1**: Thanks for listening.
*01:09:17.520*

**Speaker 1**: We will be back next time with another episode of The Grill.
*01:09:18.239*

**Speaker 1**: Later, later.
*01:09:21.600*
