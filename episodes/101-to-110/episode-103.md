# Episode 103

**FCG103 - Proxy Problems?  (feat. Ron Dawson)**

The Proxy workflow in FCPX is pretty amazing. If you don’t use it, you may want to look into it. If you do use the Proxy workflow I promise you’ll learn something about it in this episode that you didn’t realize. Ron Dawson of daydreamermag.com and an alum of this show (FCG011) comes back to explain a very interesting problem that he came across in the Proxy workflow that is a part of FCPX and offers up a bit of a work around that he came across. daredreamermag.com - the art and business of filmmaking within the library >transcoded media>proxie media> symlinks to original media

---

## Download

- [MP3](https://cdn.fcp.cafe/grill/FCG103-Ron-Dawson.mp3)

---

## Featuring

- [Chris Fenwick](http://chrisfenwick.com)
- Ron Dawson - @daredreamermag
- Guest Name - @twitter

---

## Transcription

**`00:00.080:`** **Speaker 1**: Hey, good morning and welcome to another episode of Final Cut Grill, episode 103 with Ron Dawson.

**`00:05.440:`** **Speaker 1**: Now Ron Dawson was on episode 11, way back in the stone ages of this uh of this little podcast.

**`00:11.820:`** **Speaker 1**: And back then, what did we talk about?

**`00:13.500:`** **Speaker 1**: We talked about oh, the episode title was Affordable, Desirable, and Admirable.

**`00:19.100:`** **Speaker 1**: Anyway, that was very much in the early part of the show.

**`00:22.880:`** **Speaker 1**: Ron, who's a good friend, he called me up earlier this week and he's like, oh, dude, I can't find my proxy files.

**`00:29.920:`** **Speaker 1**: And we spent, I don't know, maybe a half hour on the phone and we could not

**`00:34.120:`** **Speaker 1**: Find the proxy file.

**`00:35.640:`** **Speaker 1**: So we're going to dig deep into the proxy workflow and not so much the proxy workflow because the proxy workflow in Final Cloud 10 is actually quite simple when it works.

**`00:47.640:`** **Speaker 1**: But what Ron had a very specific problem when he was moving his project from drive A to drive B and all of his proxy media, although he could see it in the finder

**`00:59.640:`** **Speaker 1**: He could not make Final Cut 10 recognize that it was there.

**`01:04.120:`** **Speaker 1**: And so we went through in this episode, we're going to go through the many steps of troubleshooting that he went through.

**`01:11.580:`** **Speaker 1**: and finally get to the solution in the end.

**`01:15.740:`** **Speaker 1**: But I think that the troubleshooting is part of the learning process

**`01:20.780:`** **Speaker 1**: So I could just say, I mean, this could be a two-minute blog post, you know, like this is how you solve it.

**`01:26.940:`** **Speaker 1**: But I think that this discussion

**`01:30.240:`** **Speaker 1**: It's important at many levels, so bear with it.

**`01:33.360:`** **Speaker 1**: And if you're never ever going to use the proxy workflow,

**`01:36.840:`** **Speaker 1**: I promise you, you're still going to learn some particulars about the way Final Cut deals with media management.

**`01:43.880:`** **Speaker 1**: So I'm going to highly recommend that you listen to this anyway.

**`01:47.360:`** **Speaker 1**: And you know, frankly, I wouldn't make the show if I didn't think it was worth listening to.

**`01:50.560:`** **Speaker 1**: So there you go.

**`01:51.840:`** **Speaker 1**: Before we get going, I want to thank the people at PremiumBeat.

**`01:54.719:`** **Speaker 1**: com for

**`01:56.320:`** **Speaker 1**: They're great music.

**`01:58.480:`** **Speaker 1**: You know, I have people talking to me all the time, and they're like, Oh, yeah, you're right.

**`02:03.200:`** **Speaker 1**: I've been using it.

**`02:04.000:`** **Speaker 1**: It's great.

**`02:04.860:`** **Speaker 1**: That's very encouraging to hear, mainly because I think it's nice when I realize that a decision that I personally have made is actually a good one that other people agree with.

**`02:16.120:`** **Speaker 1**: So if you haven't, if you're one of those people that haven't looked at PremiumBeat.

**`02:20.440:`** **Speaker 1**: com, go check them out.

**`02:24.500:`** **Speaker 1**: Premiumbeat.

**`02:25.460:`** **Speaker 1**: com.

**`02:26.260:`** **Speaker 1**: And you know, the other thing I just want to say once again thanks to Dan Phillipson, who is my current favorite composer.

**`02:34.000:`** **Speaker 1**: And it's been it was really cool.

**`02:36.400:`** **Speaker 1**: I was going through Twitter the other night.

**`02:37.600:`** **Speaker 1**: It's like, oh, look, Dan Phillipson retweeted something from me.

**`02:40.720:`** **Speaker 1**: So yeah, I love his music.

**`02:43.280:`** **Speaker 1**: And I'm currently cutting a project, which I'll be working on for a few weeks now.

**`02:48.020:`** **Speaker 1**: to one of his cuts, and it's great.

**`02:50.900:`** **Speaker 1**: So check out Premium Beat.

**`02:53.060:`** **Speaker 1**: So this episode is a little long, not super long.

**`02:56.040:`** **Speaker 1**: But go um uh enjoy this with Ron Dawson, who is not in San Jose anymore, and he's not in Atlanta anymore.

**`03:04.680:`** **Speaker 1**: He's now living up in Seattle.

**`03:06.600:`** **Speaker 1**: Uh but um let's let's hear about his proxy problems.

**`03:12.240:`** **Speaker 1**: Hello, hello.

**`03:13.440:`** **Speaker 1**: There we go.

**`03:14.720:`** **Speaker 1**: Hello.

**`03:15.920:`** **Speaker 1**: Hey, good morning, Rod Dawson.

**`03:18.000:`** **Speaker 1**: It's early.

**`03:19.680:`** **Speaker 1**: You outearlied me with this request.

**`03:22.720:`** **Speaker 1**: How are you?

**`03:23.680:`** **Speaker 1**: Good.

**`03:25.300:`** **Speaker 2**: Don't you love that feeling when you stay up late into the evening working and calibrating on a project and you send it to export because you have to send it in the morning?

**`03:38.099:`** **Speaker 2**: And you expect in the morning when you get up and you're going to look at the project and the expirated video is going to be perfect and ready to go and you find out that

**`03:47.299:`** **Speaker 2**: A credit is coming in over a person's face.

**`03:54.659:`** **Speaker 2**: And then five minutes before a podcast, you have to try to fix it because you know you

**`03:58.160:`** **Speaker 2**: It's going to take a heck of a long time for it to export again.

**`04:01.040:`** **Speaker 2**: How long is your piece?

**`04:02.160:`** **Speaker 2**: How long is it taking to export?

**`04:04.400:`** **Speaker 2**: Oh, it's well, it's three and a half minutes, but most of the footage is

**`04:09.240:`** **Speaker 2**: 4K downscale to ten eighty P.

**`04:12.280:`** **Speaker 2**: So it takes a while to X it should be finished before this podcast is over, but I have to say like after a call.

**`04:20.120:`** **Speaker 2**: But

**`04:22.000:`** **Speaker 2**: That's why I'm a little bit that's why I'm five minutes late, because I was fixing and even now I don't even know because I don't render before I export, so it could still be

**`04:31.539:`** **Speaker 2**: broken by the time this is all said and done.

**`04:33.620:`** **Speaker 1**: Actually, that's a very interesting thing.

**`04:35.220:`** **Speaker 1**: You know, I I have quite often recently been turning off the render thing just for

**`04:43.120:`** **Speaker 1**: fluidity as I'm working on stuff.

**`04:46.560:`** **Speaker 1**: But I find that what I usually do is at when I'm done with sort of you know, every edit has different phases, okay?

**`04:54.319:`** **Speaker 1**: First you have your organizational phase, you're bringing in stuff and

**`04:57.760:`** **Speaker 1**: you know, client keeps handing you things and you're, you know, putting it into your keywords, et cetera, et cetera.

**`05:02.880:`** **Speaker 1**: Then you have your editorial phase where you s where you're actually s seeking and finding and whatever.

**`05:09.320:`** **Speaker 1**: And then you're going through like color, audio, maybe you know, maybe it's a heavy graphics piece.

**`05:17.240:`** **Speaker 1**: There's going to be a whole graphics phase.

**`05:19.240:`** **Speaker 1**: But at some point

**`05:21.220:`** **Speaker 1**: I do turn on the go-ahead and render in background thing.

**`05:26.020:`** **Speaker 1**: And I do it maybe, you know, 70%, 80% through the piece.

**`05:31.199:`** **Speaker 1**: And it does and at that point, w if you're just coloring, you know, it it doesn't affect you as much because you're spending more time like staring at A-frame.

**`05:40.300:`** **Speaker 1**: Instead of shuttling through thousands and thousands of frames.

**`05:45.979:`** **Speaker 1**: Anyway, that's an interesting discussion to have someday.

**`05:48.940:`** **Speaker 1**: Maybe we'll do that at another time.

**`05:50.780:`** **Speaker 1**: Today,

**`05:52.260:`** **Speaker 1**: You called me a few days ago, and you're like, What the hell's going on with Proxy?

**`05:57.700:`** **Speaker 2**: Well, I know.

**`05:58.820:`** **Speaker 2**: And because this project that actually was for a different project, I think, but

**`06:06.360:`** **Speaker 2**: I was um I had needed to move the project I was working on from one hard drive to another, and I had already started on hard drive A.

**`06:17.620:`** **Speaker 2**: And so I moved everything.

**`06:19.139:`** **Speaker 2**: And you would think, you know, just a click I mean, a simple click and drag, because I keep everything in the job folder.

**`06:25.220:`** **Speaker 2**: And I kind of set up my

**`06:29.980:`** **Speaker 2**: Media similar to a Eudycaris, where I store, I have the what do you call it, the slim library

**`06:37.260:`** **Speaker 1**: Yeah, I started calling it the the slim library and then uh and then somebody el or trim library and then somebody else said lean library and I go, Oh, that's better.

**`06:45.420:`** **Speaker 2**: I'm going to use that.

**`06:46.860:`** **Speaker 2**: Yeah, so I've been I use the lean library and then I save everything

**`06:51.360:`** **Speaker 2**: I set as my storage locations for library settings a folder called FCP Expedia.

**`06:58.560:`** **Speaker 2**: But everything's in one job folder, so you know you would think I'll just click and drag that job folder from drive A to drive B, boom, bah, you're good to go.

**`07:08.820:`** **Speaker 2**: Bada bing, bada boom.

**`07:10.740:`** **Speaker 2**: No, it's not that easy.

**`07:12.420:`** **Speaker 2**: So I did that.

**`07:13.380:`** **Speaker 1**: I love it when a black man from Atlanta tries to come across like an Italian mobster from New York.

**`07:18.900:`** **Speaker 1**: Go ahead.

**`07:21.660:`** **Speaker 2**: First, I know I'm not from Atlanta.

**`07:23.260:`** **Speaker 2**: I know, I know.

**`07:23.820:`** **Speaker 2**: I'm sorry.

**`07:24.780:`** **Speaker 2**: And actually, I don't even live in Atlanta anymore.

**`07:26.540:`** **Speaker 2**: We live in Seattle.

**`07:27.500:`** **Speaker 2**: I know, I know.

**`07:28.460:`** **Speaker 2**: Yeah, anyway.

**`07:30.220:`** **Speaker 2**: So it didn't work.

**`07:32.300:`** **Speaker 2**: Well.

**`07:33.120:`** **Speaker 2**: I thought it was working, so I go back into the project, the one that's now in drive B.

**`07:38.080:`** **Speaker 2**: I opened it up, and I naturally expected things to be

**`07:42.820:`** **Speaker 2**: off, because whenever you move anything in Final Cut, even if you move a whole job folder, since they are absolute references, as you've pointed out.

**`07:53.419:`** **Speaker 2**: even though everything is relative to one another the way they were before, since you've moved it from drive A to drive B, you need to reconnect it.

**`08:01.419:`** **Speaker 2**: Right.

**`08:01.979:`** **Speaker 2**: So one of the things I love about the new final cut is

**`08:05.540:`** **Speaker 2**: when you go to relink a file, you can pretty much just select the top level drive or the top level location, and it'll find everything, right?

**`08:14.600:`** **Speaker 1**: Let me ask you about that.

**`08:15.480:`** **Speaker 1**: Do you uh and actually, b before we go too much deeper, I want to back up and talk about uh uh some of the background about what you're doing and and kind of clarify a few things.

**`08:25.800:`** **Speaker 1**: So, um

**`08:27.500:`** **Speaker 1**: I think that in any software development, there is a lot of testing and planning that happens in sort of the ideal scenario.

**`08:39.880:`** **Speaker 1**: And then there is hopefully, there is robust beta testing.

**`08:46.120:`** **Speaker 1**: And that's where end users are doing things that the engineers didn't think of doing.

**`08:53.700:`** **Speaker 1**: Okay.

**`08:55.140:`** **Speaker 1**: And then s somewhere along the way, there's the final release, and then there's the period of time.

**`09:04.780:`** **Speaker 1**: Where the actual users are doing things that the beta testers didn't think anybody would do.

**`09:09.820:`** **Speaker 1**: And I think that and I'm not going to point any fingers and I'm not going to speculate as to the

**`09:18.380:`** **Speaker 1**: the vastness or the robustness of the Apple's beta testing or alpha testing or whatever phase.

**`09:27.819:`** **Speaker 1**: But clearly, we are coming across

**`09:32.019:`** **Speaker 1**: issues that are they're interesting because they're quite possibly issues that would not have come up in a ten point zero era.

**`09:43.520:`** **Speaker 1**: before we had the ability to make the lean library.

**`09:46.640:`** **Speaker 1**: Now we really wanted the lean library potential.

**`09:50.000:`** **Speaker 1**: Apple gave it to us.

**`09:51.839:`** **Speaker 1**: And I think that almost like a teenager, once, you know, we want it, we want it, we want it, and then we realize, oh, this is really hard, you know?

**`10:01.459:`** **Speaker 1**: And I think we might be experiencing a little bit of that with this issue that you have come across.

**`10:08.339:`** **Speaker 1**: And again, we're going to get deeper into that.

**`10:11.120:`** **Speaker 1**: Oh, by the way, I'm calling this episode Proxy Problems.

**`10:15.600:`** **Speaker 1**: So one thing that happens quite often in a in a real life production environment, not a test environment,

**`10:24.720:`** **Speaker 1**: Is for whatever reason, we're moving a project from one drive to another.

**`10:30.880:`** **Speaker 1**: So we might have started the project on a drive on a portable drive when we were in the field.

**`10:37.339:`** **Speaker 1**: And then we get back to the studio and we're like, oh, I want to put this on my raid, so you pick up, you know, the whole the whole thing, the whole pro you know, you and I work with a project folder where we have all of the um associated assets in that folder.

**`10:53.260:`** **Speaker 1**: I think that, you know, in an ideal and I refer to this as the soccer dad mode.

**`11:01.520:`** **Speaker 1**: That you could actually almost, and I do know people that work this way, where everything they need for their video edit.

**`11:09.840:`** **Speaker 1**: Now, granted, it's a bit simpler than what you're doing or what I'm doing.

**`11:14.240:`** **Speaker 1**: everything they need for that video edit can live within the library file.

**`11:19.600:`** **Speaker 1**: And so in their world, it's much easier to move something from A to B, from drive A to drive B.

**`11:25.339:`** **Speaker 1**: But what you and I are running into is the problem of now we have more flexibility that we have requested as the petulant teenagers from Apple.

**`11:35.140:`** **Speaker 1**: We have that more flexibility and because of that flexibility, we're also running into problems.

**`11:40.020:`** **Speaker 1**: So I've been dealing this with this a lot, and I I think I've referenced this on one show, but we had a problem with one of our Pegasus raids.

**`11:47.380:`** **Speaker 1**: I don't know if I've told if I've talked about this, but

**`11:50.020:`** **Speaker 1**: It's probably a whole episode to have, you know.

**`11:54.740:`** **Speaker 1**: Maybe I'll get Topher Martini, my hard drive expert.

**`11:57.920:`** **Speaker 1**: To come and discuss what happened, what I did, what I should have done, how I should have prepared, whatever.

**`12:04.399:`** **Speaker 2**: Yeah, I like to interview with him about that.

**`12:06.560:`** **Speaker 1**: Yeah, Topher's a great guy.

**`12:09.040:`** **Speaker 1**: And so.

**`12:10.600:`** **Speaker 1**: When you move a project from drive A to drive B, working the way you and I do, now your library storage location, you're calling it FCPX

**`12:22.020:`** **Speaker 1**: Media, I call mine FCPX Created because I still keep a lot of media outside of that folder.

**`12:30.180:`** **Speaker 1**: So

**`12:31.400:`** **Speaker 1**: So when you move a job, there's two things you're going to have to do.

**`12:34.760:`** **Speaker 1**: A job folder.

**`12:35.880:`** **Speaker 1**: First thing you're going to have to do is you're going to open it up and it's going to go, uh, I can't find the FCPX media folder.

**`12:42.320:`** **Speaker 1**: So, you're going to have to reaim that before you do anything.

**`12:46.480:`** **Speaker 1**: And it's good, you know.

**`12:48.240:`** **Speaker 1**: I will say this: I don't know if you've noticed this, Final Cut makes you do that before you can do anything.

**`12:55.320:`** **Speaker 1**: Now in an older Funnel Cut 7 world, you could continue to work with your scratch disk pointed to the wrong place.

**`13:03.640:`** **Speaker 2**: And then remember that?

**`13:05.080:`** **Speaker 2**: Everything being saved in a row.

**`13:06.680:`** **Speaker 1**: And then you'd capture another tape, or you'd, you know, it's like, uh, and then you have this stuff splattered across various job folders, which was a pain.

**`13:14.120:`** **Speaker 1**: So I do like the fact that you're forced.

**`13:16.900:`** **Speaker 1**: To retarget your storage location, which could be which very much is like the old scratch disk.

**`13:24.660:`** **Speaker 1**: You're forced to retarget your storage location for your media and your cache files.

**`13:30.260:`** **Speaker 1**: Before you do anything else.

**`13:31.540:`** **Speaker 1**: So that's the first thing you have to do.

**`13:33.140:`** **Speaker 1**: And then you're going to have to relink all your media.

**`13:36.660:`** **Speaker 1**: And like you said, it is much better.

**`13:38.740:`** **Speaker 1**: You can do it at the top level.

**`13:40.420:`** **Speaker 1**: And I was going to ask, do you top when you say top level, do you mean

**`13:43.720:`** **Speaker 1**: you just point the relink media command to the drive or to the job folder?

**`13:49.320:`** **Speaker 2**: To the drive.

**`13:50.680:`** **Speaker 2**: Yeah, try to

**`13:52.080:`** **Speaker 2**: Trying one works, I think.

**`13:53.760:`** **Speaker 2**: I usually do it to the job folder, but yesterday I tried it to the drive and it worked fine.

**`13:58.400:`** **Speaker 1**: Yeah, if you don't if you don't have a lot of stuff on the drive, it doesn't make that big a difference.

**`14:03.920:`** **Speaker 1**: But what I have found is if you go into the job folder, it's a bit faster.

**`14:10.319:`** **Speaker 1**: And if you're really in a hurry, you might want to

**`14:13.440:`** **Speaker 1**: do individual folders in the job folder.

**`14:15.920:`** **Speaker 1**: And the more you target your relink command, the quicker it will be.

**`14:20.640:`** **Speaker 1**: But yes, going into the job folder works great.

**`14:23.620:`** **Speaker 2**: Yeah, and actually I wanted to address your point about where you say you're forced to repoint your media folder

**`14:32.640:`** **Speaker 2**: destination.

**`14:33.680:`** **Speaker 1**: Let's call that the storage location.

**`14:36.320:`** **Speaker 1**: Yes.

**`14:36.560:`** **Speaker 1**: Because that's what Fonocut's calling it.

**`14:38.320:`** **Speaker 2**: Yes, storage location.

**`14:40.960:`** **Speaker 2**: When you here's the interesting point about that, when you first start a project and there's nothing in there,

**`14:46.660:`** **Speaker 2**: you're not forced to do anything because there's nothing there to force you.

**`14:50.900:`** **Speaker 2**: So I've had to get in the habit of remembering that when I first create a library

**`14:55.940:`** **Speaker 2**: to repoint everything because everything defaults to library location.

**`15:00.900:`** **Speaker 2**: The the yeah, the wherever SPS.

**`15:04.900:`** **Speaker 2**: I call it in library.

**`15:06.720:`** **Speaker 2**: Yeah, in library, exactly.

**`15:08.880:`** **Speaker 2**: Everything defaults to in library.

**`15:10.560:`** **Speaker 2**: So if you do want to use the lean library method, you really have to remember

**`15:14.860:`** **Speaker 2**: That when you first create a library, the first thing you do is repoint.

**`15:19.580:`** **Speaker 2**: Exactly.

**`15:20.140:`** **Speaker 2**: Yep.

**`15:20.780:`** **Speaker 2**: And then on top of that, since I name each folder FCPX Media, and that's just all I name it.

**`15:27.240:`** **Speaker 2**: If I start a new library, I have to remember what Final Cut will do sometimes.

**`15:34.040:`** **Speaker 2**: It'll remember, like if you haven't quit out, it'll remember

**`15:37.900:`** **Speaker 2**: The previous lean location.

**`15:41.980:`** **Speaker 2**: You're right.

**`15:42.380:`** **Speaker 2**: So if I go in, say like I go in to relink it, and I click on the Finder or the Locate folder.

**`15:49.920:`** **Speaker 2**: And oftentimes, you know, in Apple's, you know, in uh in Apple programs where the locate finder will will uh

**`15:59.000:`** **Speaker 2**: Remember the last location that you selected.

**`16:03.800:`** **Speaker 2**: And then so sometimes they'll say, oh, FCPX Media, I remembered it.

**`16:07.240:`** **Speaker 2**: But it's the FCPX media of the last

**`16:10.420:`** **Speaker 2**: Job folder I created.

**`16:12.019:`** **Speaker 1**: Does that make sense?

**`16:12.980:`** **Speaker 1**: Yep, it makes perfect sense.

**`16:14.180:`** **Speaker 1**: And I think that in an ideal world, our software could read our minds and it's not quite that smart yet.

**`16:19.860:`** **Speaker 2**: Right, right.

**`16:20.420:`** **Speaker 2**: Anyway, so I went creating a library, you have to remember to

**`16:24.339:`** **Speaker 2**: One, relink it, and two, make sure that if the locate folder folder that it's selecting is the correct SPX media.

**`16:35.220:`** **Speaker 2**: Anyway, so

**`16:37.360:`** **Speaker 2**: So back to my predicament.

**`16:40.160:`** **Speaker 1**: So now you've moved your project.

**`16:42.959:`** **Speaker 1**: You've retargeted your FCPX media folder, as you call it.

**`16:47.360:`** **Speaker 1**: You've relinked your media.

**`16:49.339:`** **Speaker 1**: But something else is missing.

**`16:51.180:`** **Speaker 2**: Yes.

**`16:51.660:`** **Speaker 2**: So all the original media and the optimized optimized media, but I didn't create any optimized media for this project.

**`16:59.819:`** **Speaker 2**: But all the original media are really fine.

**`17:03.320:`** **Speaker 2**: But the proxy media didn't.

**`17:06.120:`** **Speaker 2**: Although, like if I were to one thing that's interesting with proxy media, if you select on a file

**`17:13.339:`** **Speaker 2**: within Final Cut and go to Reveal and Finder, it takes you to the original meter from which the proxy was created.

**`17:20.620:`** **Speaker 1**: Even if you're in proxy mode?

**`17:22.539:`** **Speaker 2**: Even if you're in proxy mode.

**`17:24.140:`** **Speaker 1**: Hmm, interesting.

**`17:25.820:`** **Speaker 1**: So I'm going to say that prior to the proxy media workflow that has been made available to me,

**`17:39.300:`** **Speaker 1**: In Final Cut 10, that I'm going to make a grotesque admission here.

**`17:45.780:`** **Speaker 1**: I didn't really get what proxy meant.

**`17:49.720:`** **Speaker 1**: And I don't know, maybe I shouldn't be admitting that publicly, quite so publicly, but I just you know, I realized, oh yeah, proxy, it's like a replacement and I don't really get it.

**`18:01.800:`** **Speaker 1**: And I think that

**`18:03.740:`** **Speaker 1**: you know, to be honest, you know, we for quite some time have lived in a world where we didn't really have to worry about

**`18:16.019:`** **Speaker 1**: If we wanted to, if we didn't have a giant project, we really didn't have to worry about just working with the actual media.

**`18:22.899:`** **Speaker 1**: I mean, if we look at like the last 15 years

**`18:25.919:`** **Speaker 1**: uh so much of which was, you know, like standard F D V or um you know uh v you know very light codex

**`18:33.720:`** **Speaker 1**: Yeah, I just work with the real media.

**`18:36.680:`** **Speaker 1**: Now, in the avid world, they were still doing their AVR 77 or AVR whatever.

**`18:44.940:`** **Speaker 1**: A lot of times people would digitize at a low res, do their cut and then redig at a higher resolution.

**`18:54.140:`** **Speaker 1**: Or not resolution necessarily, although maybe, but bit rate.

**`18:58.960:`** **Speaker 1**: So the proxy workflow allows you to take large or small quantities of full quality media.

**`19:08.900:`** **Speaker 1**: You select that media in your library.

**`19:12.580:`** **Speaker 1**: I believe there's a command under the file menu, create proxy media.

**`19:16.340:`** **Speaker 1**: And actually, you can do it automatically when you're importing.

**`19:19.620:`** **Speaker 1**: And basically, you're just making another copy of your media that I believe and correct me if I'm wrong if you know that by default Apple makes

**`19:31.200:`** **Speaker 1**: Final cut makes the proxy media one half the width and height, so quarter the number of pixels.

**`19:39.179:`** **Speaker 1**: And I believe they're making it in I want to say like ProRes LT?

**`19:43.260:`** **Speaker 1**: Prorex no, ProRes Proxy.

**`19:45.740:`** **Speaker 1**: Oh, there's yet another version.

**`19:47.260:`** **Speaker 1**: Great, yeah.

**`19:47.820:`** **Speaker 1**: Oh, yeah, yeah.

**`19:48.700:`** **Speaker 2**: So here's what's interesting about that.

**`19:50.700:`** **Speaker 2**: 'Cause I when I in Final Cut Classic, I would oftentimes, for smaller projects, use ProRes Proxy

**`20:02.580:`** **Speaker 2**: as the codec of choice when editing in my um when editing or creating programs because

**`20:11.940:`** **Speaker 2**: I would do a test and like the the the bit rate of the the compression bit rate of a Proreus proxy file

**`20:19.940:`** **Speaker 2**: was about on par of like the old MIDI DV files in terms of like around twenty four megabits per second or something like that.

**`20:27.940:`** **Speaker 2**: And so

**`20:29.340:`** **Speaker 2**: I actually, for smaller projects, would edit and even finish projects in ProRes Proxy.

**`20:37.400:`** **Speaker 2**: And deliver online.

**`20:38.840:`** **Speaker 2**: Crazy town.

**`20:39.640:`** **Speaker 2**: Are you kidding?

**`20:40.600:`** **Speaker 2**: No, I'm serious.

**`20:41.480:`** **Speaker 2**: Yeah.

**`20:41.800:`** **Speaker 2**: I mean, if if there wasn't a lot of color grading that was needed, and if it wasn't if it was like a small, short project,

**`20:50.860:`** **Speaker 2**: it would it work worked fine for me.

**`20:53.340:`** **Speaker 2**: So when Final Cap um 10 came out and I saw a proxy and I knew that it was

**`20:59.519:`** **Speaker 2**: converting these files to ProS proxy.

**`21:01.840:`** **Speaker 2**: I assumed it was it was ProS Proxy, but I didn't know about it cutting it in half.

**`21:08.159:`** **Speaker 2**: So I had I think I had like exported a project in pro when it was in proxy mode.

**`21:14.559:`** **Speaker 2**: And it was tiny.

**`21:15.840:`** **Speaker 2**: It was like half the size it was supposed to be.

**`21:18.320:`** **Speaker 2**: Right.

**`21:18.760:`** **Speaker 2**: Then I realize, oh, Final Cut is actually also cutting in half.

**`21:23.640:`** **Speaker 2**: Yeah, so hold on.

**`21:24.919:`** **Speaker 1**: Now, let's be clear.

**`21:26.360:`** **Speaker 1**: That was a revelation that you had with Final Cut Classic.

**`21:31.340:`** **Speaker 2**: What revelation are you referring to?

**`21:33.020:`** **Speaker 1**: About it being quarter resolution.

**`21:34.940:`** **Speaker 2**: No, no, no, no, no, no.

**`21:36.140:`** **Speaker 2**: In Flander Kid 10.

**`21:37.660:`** **Speaker 2**: So in Flancade Classic, I would use MPEG stream clip.

**`21:41.500:`** **Speaker 2**: To convert.

**`21:43.340:`** **Speaker 2**: mov files from a DSLR into ProRes proxy to conserve drive space

**`21:49.120:`** **Speaker 1**: Okay, now you're touching on something very interesting.

**`21:52.400:`** **Speaker 1**: So in olden times, you could take your media and you could process it

**`22:02.019:`** **Speaker 1**: two ways.

**`22:02.740:`** **Speaker 1**: You could process a proxy version and you could and i in a DSLR workflow, you could take your H.

**`22:10.100:`** **Speaker 1**: 264s and make it into a ProRes HQ or ProRes422, whatever.

**`22:15.740:`** **Speaker 1**: You could do it two ways.

**`22:17.180:`** **Speaker 1**: And then there was this very laborious or, you know, kind of sketchy workflow where you'd have to reaim, you'd have to tell your

**`22:27.240:`** **Speaker 1**: your software.

**`22:28.520:`** **Speaker 1**: No, no, no.

**`22:29.640:`** **Speaker 1**: When I want you to look for this media, I want you to look over here.

**`22:34.200:`** **Speaker 1**: And then it would go, Oh, yeah, there's all those file names.

**`22:37.160:`** **Speaker 1**: Okay, I got it.

**`22:38.640:`** **Speaker 1**: And then at some point in the workflow, you'd have to say, okay, now let's relink the media over to here

**`22:46.740:`** **Speaker 1**: And Final Cut 10 makes that much easier by in its implementation of the proxy workflow when it works.

**`22:55.620:`** **Speaker 2**: When it works, yeah.

**`22:56.900:`** **Speaker 2**: So in this case.

**`22:59.140:`** **Speaker 2**: When I move the job folder over, the ridge, like I said, the original media connected fine

**`23:06.260:`** **Speaker 2**: but the proxy media didn't even after I went through and I re relinked everything and um confirmed that

**`23:14.640:`** **Speaker 2**: The original files that it was accessing.

**`23:17.440:`** **Speaker 2**: And to do this, you know, after I copied everything in drive B, I dismounted drive A just to make sure that FileKit was not accessing

**`23:27.640:`** **Speaker 2**: any of the original files on Drive A because everything obviously is identical.

**`23:33.080:`** **Speaker 2**: So I thought.

**`23:33.880:`** **Speaker 1**: That's actually a really important point.

**`23:35.640:`** **Speaker 1**: So if you are in the process of moving jobs

**`23:38.880:`** **Speaker 1**: Because Final Cut is using you mentioned it earlier, an absolute file path, and you would launch the library that's on Drive B, if you still have Drive A mounted,

**`23:50.919:`** **Speaker 1**: Even though you've launched the library on Drive B, it is going to link to the files that are on Drive A.

**`24:00.200:`** **Speaker 1**: Right.

**`24:00.600:`** **Speaker 1**: So it's very important to be able to, you know

**`24:03.419:`** **Speaker 1**: Excuse me, toggle drives on and off, or you know, either unmount them or power them down.

**`24:08.059:`** **Speaker 1**: Well, unmount them and power them down.

**`24:10.299:`** **Speaker 1**: I had an interesting problem that happened recently.

**`24:14.500:`** **Speaker 1**: with somebody where they had started their project on their internal drive, and then we had to copy it off to an external drive, and there's no way to unmount the internal drive.

**`24:23.940:`** **Speaker 1**: So that was a bit of a you know, we had to be careful about that.

**`24:27.940:`** **Speaker 2**: Oh, yeah, I guess that you could have, just to be safe, copied it to a second drive and deleted the internal drive and the internal project line, right?

**`24:35.779:`** **Speaker 1**: You know what we ended up doing is, I think what we did is we

**`24:41.260:`** **Speaker 1**: pushed those files to the trash can and then launched the other library, and then we crossed our fingers and then we deleted the original.

**`24:52.500:`** **Speaker 1**: I got it.

**`24:53.059:`** **Speaker 1**: Yeah.

**`24:53.220:`** **Speaker 1**: It's a bit dicey there for a moment.

**`24:55.780:`** **Speaker 2**: Yeah.

**`24:58.100:`** **Speaker 1**: So your proxy media doesn't relink?

**`25:02.880:`** **Speaker 2**: It didn't re-link.

**`25:04.400:`** **Speaker 2**: And so started doing a lot of research on this.

**`25:07.280:`** **Speaker 2**: Try to figure out, okay, how to get this to work.

**`25:09.440:`** **Speaker 2**: So

**`25:10.820:`** **Speaker 2**: I discovered an interesting thing on the way to a solution.

**`25:15.140:`** **Speaker 2**: So when you create proxy media

**`25:19.460:`** **Speaker 2**: Final Cut within the library now, Final Cut will create a folder called Transcoded Media.

**`25:28.660:`** **Speaker 2**: And then within the Transcoded Media folder, it will create

**`25:32.640:`** **Speaker 2**: the a proxy media folder.

**`25:35.120:`** **Speaker 2**: And this is all going to be within the storage location that you've selected.

**`25:39.680:`** **Speaker 2**: So like for me, it's FCPX Media, then Transcoded Media, then Proxy Media.

**`25:44.940:`** **Speaker 2**: Within that proxy media folder will be symlinks.

**`25:48.299:`** **Speaker 2**: In Locker and Drive A there will be symlinks that link to

**`25:53.060:`** **Speaker 2**: the original media.

**`25:56.980:`** **Speaker 2**: And now for those of you who are in the know, SimLinks are wherever you look in the finder and you see

**`26:03.380:`** **Speaker 2**: like a link to something else or like it's and it's not a duplicate, but like a proxy link.

**`26:09.780:`** **Speaker 2**: And there's a little arrow in the bottom left hand corner of the icon.

**`26:13.160:`** **Speaker 2**: That's a simlink.

**`26:14.120:`** **Speaker 2**: That's where you're basically Apple is saying or the Mac OS is saying, this little simulated file, if you will, is pointing to another file

**`26:26.280:`** **Speaker 2**: on some other location.

**`26:27.880:`** **Speaker 2**: Right.

**`26:28.360:`** **Speaker 2**: So like if you were to right click on one of those sim links and go to like go to original location or reveal and find or whatever.

**`26:35.460:`** **Speaker 2**: it would jump you to wherever that media is.

**`26:38.180:`** **Speaker 2**: So FinalKit creates these simlinks within the proxy folder, which is located in my storage location of choice, which is SCPX Media.

**`26:49.420:`** **Speaker 2**: I discovered that when I copied the job folder over, the semlinks from drive A did not copy over.

**`26:58.880:`** **Speaker 2**: So even though I just dragged everything from drive A to drive B, on drive B when I drilled down through FCPX media to transcribe media to proxy media, the symlinks weren't there.

**`27:12.940:`** **Speaker 2**: Interesting.

**`27:13.820:`** **Speaker 2**: So I thought, oh, maybe that's the situation.

**`27:16.860:`** **Speaker 2**: And so, you know, everyone was saying, you know, whenever we do research and this, everyone says, don't

**`27:22.700:`** **Speaker 2**: use the finder to media manage your final code library, use the move or copy command.

**`27:28.300:`** **Speaker 2**: So I said, okay, fine, I'll do that.

**`27:30.060:`** **Speaker 2**: So

**`27:30.820:`** **Speaker 2**: I went in to find her.

**`27:32.340:`** **Speaker 2**: This was the first solution I tried that did not work.

**`27:34.340:`** **Speaker 2**: So, what I'm about to tell you does not work.

**`27:37.540:`** **Speaker 1**: Thank you for the heads up.

**`27:39.380:`** **Speaker 2**: I went into the finder.

**`27:41.060:`** **Speaker 2**: I don't have to find it.

**`27:41.860:`** **Speaker 2**: In Filecut, I went to File, and then I went to, I clicked on the event, because I only had one event in this library, and that's the one I was working on.

**`27:49.340:`** **Speaker 2**: what I did was I created a new library with nothing in it on Drive B and then I did the the copy ev copy event.

**`28:00.000:`** **Speaker 2**: Command copying the event from the library on drive A to the library in drive B.

**`28:05.440:`** **Speaker 2**: Did the same thing, dismounted drive A.

**`28:10.120:`** **Speaker 2**: Relaunch Drive the library and Drive B, still no go.

**`28:15.080:`** **Speaker 2**: Now, in doing it, let me ask you this though.

**`28:17.960:`** **Speaker 1**: Did everything else work?

**`28:20.000:`** **Speaker 2**: Yeah, all the original media, everything else.

**`28:23.120:`** **Speaker 1**: Without needing to relink.

**`28:27.360:`** **Speaker 2**: I don't remember that part.

**`28:29.120:`** **Speaker 1**: I mean, it would make sense.

**`28:30.320:`** **Speaker 1**: If you're doing the copy within.

**`28:34.240:`** **Speaker 1**: Here's an interesting observation that I've been having, and you're right.

**`28:38.080:`** **Speaker 1**: There are I'm just going to launch Final Fit here for a second.

**`28:41.200:`** **Speaker 1**: There's a lot of commands that are contextual.

**`28:45.960:`** **Speaker 1**: Underneath the file menu in Final Cut, that are quite that are quite interesting.

**`28:53.320:`** **Speaker 1**: Let me launch, I'll launch this project.

**`28:56.120:`** **Speaker 1**: That's weird that that came up.

**`28:58.740:`** **Speaker 1**: So like for example, there's the copy to library, move to library, merge events.

**`29:07.940:`** **Speaker 1**: Some of those commands now if I select the library

**`29:15.340:`** **Speaker 1**: Okay, and that.

**`29:18.700:`** **Speaker 1**: Yeah, so those those are like databased

**`29:23.120:`** **Speaker 1**: driven commands because what you're dealing with is you're directly talking to files that the Final Cut database is managing.

**`29:32.320:`** **Speaker 1**: And so it makes sense that if we go rogue and we leave Final Cut and then we start hacking around with our Finder files

**`29:41.519:`** **Speaker 1**: Which ultimately, you know, I think Apple wants us to stop using the Finder in general for everything.

**`29:46.720:`** **Speaker 1**: And you've probably heard me talk about some of these

**`29:49.940:`** **Speaker 1**: observations that I've had where the Mac OS is beginning a very slow, maybe even like a ten year migration away from being folder-based to being something more like the iPad and the iOS.

**`30:03.220:`** **Speaker 1**: But that's a whole nother discussion.

**`30:06.980:`** **Speaker 1**: So when we go rogue and we put on our big brain hats and we go out to the Finder and start pushing files around, that's when things get broken.

**`30:15.220:`** **Speaker 1**: They can very easily get broken down.

**`30:17.060:`** **Speaker 1**: We still have our relink command, so we can fix those things.

**`30:21.460:`** **Speaker 1**: But basically, the relink command is just a big database management tool.

**`30:26.100:`** **Speaker 1**: Hello, I know you have some broken links.

**`30:28.179:`** **Speaker 1**: Let me show you where they are.

**`30:30.340:`** **Speaker 1**: You know?

**`30:31.380:`** **Speaker 2**: Yeah.

**`30:32.019:`** **Speaker 2**: Yeah.

**`30:32.580:`** **Speaker 1**: So so at any rate, you what your attempt was there was to say, okay, I'm going to play by your rules.

**`30:40.440:`** **Speaker 1**: I'm going to copy my event to this other library, which is on another drive, and that event

**`30:49.559:`** **Speaker 1**: Had proxy media in it.

**`30:53.000:`** **Speaker 1**: And you know what I just done to me, Ron?

**`30:56.120:`** **Speaker 2**: What?

**`30:57.240:`** **Speaker 1**: That a ten-point

**`30:59.120:`** **Speaker 1**: 1.

**`30:59.840:`** **Speaker 1**: 5 updates going to come out later this week.

**`31:02.560:`** **Speaker 1**: And this whole and this whole episode's going to have to get just thrown out.

**`31:07.920:`** **Speaker 1**: Because we're basically we're troubleshooting what was what is more than likely a bug.

**`31:13.740:`** **Speaker 2**: Well, I can't necessarily, 'cause lots of people don't take the time to update to the latest version of 'cause I don't.

**`31:21.179:`** **Speaker 2**: I take a while before I update.

**`31:22.539:`** **Speaker 2**: A lot of people don't update to the latest version of Funnikit as soon as it comes out.

**`31:26.500:`** **Speaker 1**: Really?

**`31:27.700:`** **Speaker 2**: Yeah, I never do.

**`31:29.140:`** **Speaker 2**: I always wait.

**`31:30.500:`** **Speaker 2**: I wait to listen to everyone else's horror stories.

**`31:34.620:`** **Speaker 2**: Actually, I think you and I have talked about this before, about my whole philosophy about like not upgrading software as soon as it comes out.

**`31:42.460:`** **Speaker 1**: Yeah, yeah.

**`31:44.460:`** **Speaker 1**: And then there's uh do have you heard um

**`31:47.640:`** **Speaker 1**: Alex Golner's approach to final cut upgrades?

**`31:52.760:`** **Speaker 2**: I think I have a reminder.

**`31:56.600:`** **Speaker 1**: If he starts a project in ten point X, whatever.

**`32:01.419:`** **Speaker 1**: He will never open that project in anything but that version of Final Cut.

**`32:07.660:`** **Speaker 1**: So he has like all these disk images of old versions of the software.

**`32:14.100:`** **Speaker 1**: Stored.

**`32:14.660:`** **Speaker 1**: So he's like, oh, I have to open that old project.

**`32:16.980:`** **Speaker 1**: So he jockeys around in his finder and he reverts back to whatever version of Final Cut that job was opened in.

**`32:24.340:`** **Speaker 1**: And then he opens it up again and does the fixes.

**`32:26.840:`** **Speaker 2**: Wow, that seems incredibly painful.

**`32:32.440:`** **Speaker 1**: Yeah, it sure does, Alex.

**`32:35.440:`** **Speaker 1**: At any rate, he goes, Well, I never have problems.

**`32:37.679:`** **Speaker 1**: I'm like, Okay, good for you.

**`32:40.399:`** **Speaker 1**: So, um, so you did the move library or copy li event to a new library.

**`32:47.620:`** **Speaker 1**: And your proxy media still didn't show up.

**`32:50.820:`** **Speaker 1**: Still didn't show up.

**`32:51.540:`** **Speaker 1**: Did you get ever get to the point where you just said, I'm just going to pick up these symlinks and drag them over?

**`32:57.680:`** **Speaker 2**: Yes, actually I did.

**`32:58.960:`** **Speaker 2**: So that was actually I tried that first, where when I you know drove down and discovered that the symlinks weren't there, I tried that.

**`33:05.680:`** **Speaker 2**: That didn't work.

**`33:06.640:`** **Speaker 2**: Then I did the copy

**`33:08.800:`** **Speaker 2**: event from one library to the from library A to library B and so when I did that you know it generated new symlinks

**`33:18.220:`** **Speaker 2**: or copied the old Simlinks windows, and everything was there.

**`33:23.820:`** **Speaker 2**: And so I thought, okay, cool, this is going to work.

**`33:25.820:`** **Speaker 2**: It still did not work.

**`33:28.480:`** **Speaker 2**: So um so I went to uh our um good buddies over at the Ripple in

**`33:36.300:`** **Speaker 2**: No, at the NSYNC F SPX Final Cut Forum.

**`33:40.060:`** **Speaker 2**: What what do you call it?

**`33:41.020:`** **Speaker 1**: The um the secret final cut ten Illuminati.

**`33:44.460:`** **Speaker 1**: Right.

**`33:46.220:`** **Speaker 2**: Um so I went to the Illuminati uh because uh

**`33:51.220:`** **Speaker 2**: It's a small group, but really smart people.

**`33:54.820:`** **Speaker 2**: Yeah.

**`33:55.540:`** **Speaker 2**: You know, and I think that group is a perfect example of quantity over quality.

**`34:00.180:`** **Speaker 2**: I know.

**`34:00.740:`** **Speaker 2**: I'm sorry.

**`34:04.799:`** **Speaker 1**: Yeah, you know, I mean, quality over quantity.

**`34:07.840:`** **Speaker 1**: I think everybody at one point or another, and I know I'm going to piss off some people here, and I'm sorry, what else is new?

**`34:15.220:`** **Speaker 1**: Everybody has had their creative cow moment where they try and enter into a discussion on the creative cow, and all of a sudden, you know, it's like

**`34:26.740:`** **Speaker 1**: It's like a bunch of people with ADD that can't have a conversation without spinning out of control and talking about something totally different.

**`34:37.899:`** **Speaker 1**: You know, I mean, it's like I would like to talk about this red circle.

**`34:42.620:`** **Speaker 1**: My red circle is not exactly the right color, red that I want.

**`34:46.740:`** **Speaker 1**: And the first response you'll get is, who would want to use a circle?

**`34:49.940:`** **Speaker 1**: Squares are much better.

**`34:51.300:`** **Speaker 1**: And then all of a sudden, somebody else chimes in, I prefer the rectangle.

**`34:54.340:`** **Speaker 1**: The rectangle is more flexible.

**`34:55.500:`** **Speaker 1**: It's like, no, I'm talking about my red circle, and I'm talking about the color of the red circle.

**`34:59.500:`** **Speaker 1**: Nope, triangles are way better.

**`35:00.860:`** **Speaker 1**: It's like, oh, good grief.

**`35:02.380:`** **Speaker 1**: This conversation is completely lost already.

**`35:05.220:`** **Speaker 2**: Well, actually, it's funny you say that because I was actually just going to make the comment that That you got your problem solved on the cow?

**`35:13.619:`** **Speaker 2**: Well, no no, I didn't actually get it solved in sync.

**`35:17.359:`** **Speaker 2**: Creative Cow used to be my go to house.

**`35:21.359:`** **Speaker 2**: Yes.

**`35:21.839:`** **Speaker 2**: For and by house, I'm making I'm referencing the popular T V show House.

**`35:27.680:`** **Speaker 2**: You know the T V show House?

**`35:29.119:`** **Speaker 2**: Yeah.

**`35:29.620:`** **Speaker 2**: Yeah.

**`35:30.020:`** **Speaker 2**: Remember how he was the doctor?

**`35:31.220:`** **Speaker 2**: He could figure out everything.

**`35:32.180:`** **Speaker 2**: He was like, This is the first time.

**`35:32.980:`** **Speaker 1**: Eventually.

**`35:34.340:`** **Speaker 1**: After he tried to at some point in every episode, it was sarcoids or whatever, but eventually he would get to the diagnosis.

**`35:43.140:`** **Speaker 2**: Yeah.

**`35:43.539:`** **Speaker 2**: So house was sort of like my house.

**`35:46.500:`** **Speaker 2**: FCP Editors in Sync was sort of like my go I'm really getting messed up.

**`35:50.740:`** **Speaker 2**: Creative Cow.

**`35:52.020:`** **Speaker 2**: Yeah.

**`35:52.620:`** **Speaker 2**: used to be my go-to.

**`35:53.740:`** **Speaker 2**: Like whenever I had an issue that was like unsolvable, like every forum I would ever go on could not find an answer.

**`36:01.820:`** **Speaker 2**: I'd go to Creative Cow.

**`36:04.020:`** **Speaker 2**: and I'd be able to find one.

**`36:05.940:`** **Speaker 2**: Like here's an example.

**`36:07.220:`** **Speaker 2**: And eventually we will get to the solution of the proxy problem.

**`36:10.260:`** **Speaker 2**: But we need to take another tangent.

**`36:13.220:`** **Speaker 2**: So this is where Creative Cow here's a problem I had in Final Cut Classic that was extremely hard to find, very unique, where

**`36:21.560:`** **Speaker 2**: I was bringing in QuickTime files that I had transcoded in MPEG Streamclip and the audio was becoming unsynced from itself.

**`36:35.640:`** **Speaker 2**: So, like, where let's say I had a QuickTime file, and I'm in, let's say, if it's a long 40-minute clip, as I got to the end of the clip, the audio for that file itself would drift.

**`36:46.620:`** **Speaker 2**: And people thought like I was syncing it wrong and like, you know, because you know, this is back when you were syncing DSLR to audio footage from like a digital recorder.

**`36:55.940:`** **Speaker 2**: And I'm like, no, I'm not talking about the sync media.

**`36:58.420:`** **Speaker 2**: I'm talking about the actual original DSLR audio.

**`37:02.339:`** **Speaker 2**: The data audio is like when you play it in the Finder, it's fine, but in Final Cut, it was messing up.

**`37:10.200:`** **Speaker 2**: No one could figure out.

**`37:11.559:`** **Speaker 2**: I got the answer in the cow.

**`37:13.799:`** **Speaker 2**: Here's what the answer.

**`37:15.160:`** **Speaker 2**: So I shoot everything in 24P, which as you all know is really 23.

**`37:19.480:`** **Speaker 2**: 98.

**`37:20.599:`** **Speaker 2**: which, as we all know, is actually twenty three point nine seven six.

**`37:26.440:`** **Speaker 1**: So and of course we all know those numbers.

**`37:29.480:`** **Speaker 2**: Yes.

**`37:29.960:`** **Speaker 2**: An MPIC stream clip I was selecting exactly 23.

**`37:35.160:`** **Speaker 2**: 98 as my frame rate.

**`37:38.099:`** **Speaker 2**: Within Final Cut Classic, you know, everything is marked as 23.

**`37:41.780:`** **Speaker 2**: 98.

**`37:42.820:`** **Speaker 2**: But Final Cut is really looking at it as 23.

**`37:46.579:`** **Speaker 2**: 976.

**`37:48.360:`** **Speaker 2**: So since I had transcoded it exactly to 23.

**`37:52.200:`** **Speaker 2**: 98, that is what was causing the audio drift.

**`37:55.960:`** **Speaker 1**: So it wasn't that it was drifting, it's just that it was progressively getting more and more out of sync.

**`38:02.099:`** **Speaker 2**: Exactly.

**`38:03.460:`** **Speaker 1**: And the cow solved that problem for you.

**`38:06.579:`** **Speaker 2**: Yeah, I went to Crito Cow, someone, and with only a few posts, someone figured it out.

**`38:12.339:`** **Speaker 2**: and said, just leave the target frame rate blank and it'll default to whatever the file is.

**`38:19.220:`** **Speaker 2**: I did that and that worked.

**`38:20.740:`** **Speaker 2**: So

**`38:22.380:`** **Speaker 2**: So CreatorCal has always been a great resource for me, and every now and then still continues to do so.

**`38:27.900:`** **Speaker 1**: Well, as I said, I would probably be pissing somebody off, and no doubt I have.

**`38:32.240:`** **Speaker 2**: Well, lately, f you know, FCPX Editors in Sync has been has been the solution for me.

**`38:37.840:`** **Speaker 2**: So I ended up going there and I ended up getting the solution I needed.

**`38:41.620:`** **Speaker 2**: Finally, from I want to give a shout out to Ronnie, I think his last name is pronounced Courtins or Curtins.

**`38:48.260:`** **Speaker 2**: Right.

**`38:48.900:`** **Speaker 2**: Yeah, C-O-U-R-T-N-S.

**`38:51.320:`** **Speaker 2**: So the solution ended up being in order to get this thing to work, because you know.

**`38:56.840:`** **Speaker 1**: I feel like we need a drum roll here.

**`38:58.360:`** **Speaker 2**: Yeah, blah, blah, blah.

**`38:59.660:`** **Speaker 2**: Yeah, you can add that a post because you do so much post-production work on your I've been called out.

**`39:08.860:`** **Speaker 2**: So the solution ended up being where

**`39:12.760:`** **Speaker 2**: Since the compy event feature did not work, excuse me, what he suggested to do was to, all right, let me make sure I get this right.

**`39:25.820:`** **Speaker 2**: you create your new job folder, right?

**`39:30.220:`** **Speaker 2**: So I have job folder A, which is on drive A.

**`39:33.940:`** **Speaker 2**: I have job folder B, which is on drive B, which I drive B.

**`39:37.859:`** **Speaker 2**: I don't create a new library.

**`39:39.540:`** **Speaker 2**: Right.

**`39:39.859:`** **Speaker 2**: I don't do that yet.

**`39:41.619:`** **Speaker 2**: What I do then

**`39:43.599:`** **Speaker 2**: I open up the project on drive A and then within the I change the storage location on drive A

**`39:55.080:`** **Speaker 2**: To SCPX media on drive B.

**`39:59.240:`** **Speaker 2**: You got that?

**`39:59.960:`** **Speaker 2**: Yeah, yeah.

**`40:00.760:`** **Speaker 2**: Because you know, before it's pointing to the SCPX media on drive A and now pointing to drive B.

**`40:06.860:`** **Speaker 2**: After I do that, I consolidate the library.

**`40:11.580:`** **Speaker 2**: Clever.

**`40:12.300:`** **Speaker 1**: Again, so now going back to what we were saying earlier is that, excuse me.

**`40:17.940:`** **Speaker 1**: There are ways to solve problems in the Finder, and some of them work quite well.

**`40:22.820:`** **Speaker 1**: You are actually so far solving this project problem rather in Final Cut using the database management tools.

**`40:31.340:`** **Speaker 2**: Exactly.

**`40:32.060:`** **Speaker 1**: Okay, keep going.

**`40:33.500:`** **Speaker 2**: And so now and as people know or they should know, when you consolidate a library, Final Kit will take all their optimized rendered media that's actually used.

**`40:45.640:`** **Speaker 2**: and put it into whatever your storage location is, which could be the library or in my case, it's FCPX Media.

**`40:53.319:`** **Speaker 1**: And you're consolidating to an external

**`40:57.440:`** **Speaker 1**: FCPX Media.

**`40:58.720:`** **Speaker 1**: And again, FCPX Media is the Ron Dawson blessed naming convention that he uses for his

**`41:06.320:`** **Speaker 1**: Library storage location.

**`41:08.000:`** **Speaker 1**: I use the the term FCPX created.

**`41:11.920:`** **Speaker 1**: You can call it anything you want.

**`41:13.360:`** **Speaker 1**: It's essentially, once again,

**`41:16.160:`** **Speaker 1**: Very much very similar to our old scratch disk that we used to have.

**`41:19.920:`** **Speaker 2**: Exactly.

**`41:20.400:`** **Speaker 1**: So consolidate, you've consolidated out of your current job folder

**`41:26.099:`** **Speaker 1**: Structure on drive A, and now you're saying, no, no, no, put all this stuff over on drive B.

**`41:32.260:`** **Speaker 2**: Exactly.

**`41:32.980:`** **Speaker 1**: Okay, keep going.

**`41:34.579:`** **Speaker 2**: So then I'll go through the process of make copying all those files.

**`41:38.180:`** **Speaker 2**: You'll see the little

**`41:40.279:`** **Speaker 2**: You know, the little progress circle and final get going.

**`41:43.720:`** **Speaker 2**: So once that's 100% complete, you quit out of the program.

**`41:48.500:`** **Speaker 2**: And now you can copy in the finder the library from drive A.

**`41:57.060:`** **Speaker 2**: To the job folder on drive B, dismount drive A, relaunch final cut from drive B, you know, the library on drive B, right.

**`42:07.460:`** **Speaker 2**: Bada bing, bada boom, it worked.

**`42:09.700:`** **Speaker 1**: Now

**`42:11.599:`** **Speaker 1**: Excuse me.

**`42:12.880:`** **Speaker 1**: There's something else I won't post out of the show.

**`42:17.119:`** **Speaker 1**: And because

**`42:19.360:`** **Speaker 1**: Final Cuts absolute file linking structure has told itself that everything is on Drive B.

**`42:29.200:`** **Speaker 1**: You don't even need to relink.

**`42:31.120:`** **Speaker 1**: Exactly.

**`42:32.220:`** **Speaker 1**: And the proxy media made the journey.

**`42:35.420:`** **Speaker 2**: Yeah.

**`42:35.900:`** **Speaker 2**: Now, here's the one downside to this solution.

**`42:41.380:`** **Speaker 2**: So the good news, bad news.

**`42:43.700:`** **Speaker 2**: The good news is everything worked.

**`42:46.020:`** **Speaker 2**: The bad news is, since you consolidate it, it also moves the original media into

**`42:53.820:`** **Speaker 2**: Your source location.

**`42:55.260:`** **Speaker 2**: Yes.

**`42:55.900:`** **Speaker 2**: So I already had all the original media on Drive B.

**`43:00.300:`** **Speaker 2**: So now it's duplicated on Drive B, right?

**`43:03.020:`** **Speaker 2**: Right.

**`43:03.660:`** **Speaker 2**: It's in my

**`43:04.559:`** **Speaker 2**: I create a raw footage folder.

**`43:06.000:`** **Speaker 2**: So all my original media is in my raw footage folder in Drive B, and it's also in the storage location in Drive B from the consolidation that I did.

**`43:17.240:`** **Speaker 2**: So from there, you can do one of two things.

**`43:19.240:`** **Speaker 2**: Obviously, you can either just delete the original raw footage that was already there since it's in the source location

**`43:25.540:`** **Speaker 2**: But I want it to maintain the same exact structure from the original one.

**`43:30.500:`** **Speaker 1**: And there's a lot of reasons for that.

**`43:31.860:`** **Speaker 1**: We've talked about those.

**`43:34.420:`** **Speaker 1**: So it does make sense.

**`43:35.700:`** **Speaker 1**: You know, this is the balance.

**`43:38.740:`** **Speaker 1**: There's a very delicate balance between a lean library, leave in place, import into library.

**`43:47.700:`** **Speaker 1**: There's a lot of pros and cons to each of these.

**`43:50.660:`** **Speaker 1**: And again,

**`43:52.120:`** **Speaker 1**: Now that we have been given all of this flexibility, there is additional responsibility that lands on our shoulders to keep track of our stuff.

**`44:01.740:`** **Speaker 2**: Yeah.

**`44:02.460:`** **Speaker 2**: Well, in this case, I still have a lean library because all of the media is in my FCPX media.

**`44:15.160:`** **Speaker 1**: Your job folder is double the size it needs to be because you have two copies of all your raw footage.

**`44:19.240:`** **Speaker 2**: Exactly, exactly.

**`44:19.960:`** **Speaker 2**: So you can either, like I said, either delete the original raw footage, or in my case, I deleted the

**`44:27.620:`** **Speaker 2**: Cop the raw footage that was in the storage location.

**`44:31.780:`** **Speaker 2**: Right.

**`44:32.900:`** **Speaker 2**: But then, of course, you have to relink.

**`44:34.660:`** **Speaker 2**: I had to relink it because this new copy library is pointing to the raw footage that was in the storage location.

**`44:41.140:`** **Speaker 2**: But relinking to original media works, whereas relinking to proxy doesn't.

**`44:45.779:`** **Speaker 2**: So I relinked to the original media and my raw footage folder, and then we were back in business.

**`44:51.580:`** **Speaker 1**: So now the one question that I'd failed to ask you earlier in the week when we discussed this, and I haven't, and we're now 42 minutes into this.

**`45:01.220:`** **Speaker 1**: How much media were you really talking about that you had made proxy media out of?

**`45:07.700:`** **Speaker 1**: How many minutes, hours, whatever of footage did you have?

**`45:11.380:`** **Speaker 2**: Oh, that's a good question.

**`45:15.640:`** **Speaker 2**: Minutes-wise, it wasn't a lot.

**`45:17.560:`** **Speaker 2**: I mean, it was, I would say, like, you know, it's probably, I would guess.

**`45:23.580:`** **Speaker 2**: somewhere in the neighborhood of I think it was less than a hundred gigabytes.

**`45:29.340:`** **Speaker 2**: So I'm going to say I think it was around ninety gigabytes.

**`45:32.300:`** **Speaker 2**: Okay.

**`45:32.760:`** **Speaker 2**: of stuff.

**`45:33.640:`** **Speaker 1**: And how long would it have taken you to just say, you know what, forget it.

**`45:37.000:`** **Speaker 1**: You lost my original proxies.

**`45:39.320:`** **Speaker 1**: Please make me new ones?

**`45:42.000:`** **Speaker 2**: Oh, I don't know.

**`45:43.040:`** **Speaker 2**: I don't 'cause I never timed it.

**`45:44.400:`** **Speaker 2**: I mean, I probably I've never timed it.

**`45:47.119:`** **Speaker 2**: So, however long it takes, finally, and so I was editing this on a MacBook 13 inch MacBook Pro.

**`45:55.360:`** **Speaker 2**: Retina, so however long one of those would take.

**`45:59.760:`** **Speaker 2**: But I knew the thing is, I needed to finish that project then.

**`46:04.240:`** **Speaker 2**: And then so I didn't have time to wait for it to do that.

**`46:08.260:`** **Speaker 2**: Although apparently I did have time to spend all the time.

**`46:13.060:`** **Speaker 1**: Well, that's kind of what I was getting at.

**`46:14.980:`** **Speaker 1**: It's like I know that this troubleshooting took did not take twenty minutes.

**`46:20.900:`** **Speaker 1**: 'Cause I know that you and I spent almost that much on the phone and I didn't have an answer for you.

**`46:25.380:`** **Speaker 1**: And I was just wondering, you know, I mean, 'cause th that was one of the things that you and I discussed on the phone earlier this week is that in every troubleshooting

**`46:35.360:`** **Speaker 1**: Scenario, you the first thing you do is you, what I like to do is take a giant step back and say

**`46:44.700:`** **Speaker 1**: Worst case scenario, do I have a workaround?

**`46:47.900:`** **Speaker 1**: And your workaround would have been to say, you know what, dude, just regenerate your proxies and you'll

**`46:54.040:`** **Speaker 1**: You know, you can, you know, take a nap or, you know, go to bed tonight, and in the morning you'll be able to keep going.

**`47:02.120:`** **Speaker 1**: So w you knew that was a a solution, but I think that the your persistence and Rodney's help helped us find another way to deal with media.

**`47:17.039:`** **Speaker 1**: That is a very clever workaround as using the consolidate event files.

**`47:24.079:`** **Speaker 1**: Now I want to say his name is Ronnie, not Rodney.

**`47:27.279:`** **Speaker 1**: I'm sorry, yes, Ronnie.

**`47:30.200:`** **Speaker 1**: I want to say that I have used Consolidate to in other instances okay

**`47:41.020:`** **Speaker 1**: This is an interesting problem that Consolidate fixed and broke.

**`47:48.460:`** **Speaker 1**: I think I mentioned this a couple of episodes ago, that I was doing a lot of projects

**`47:52.559:`** **Speaker 1**: For whatever reason, it was total coincidence.

**`47:54.480:`** **Speaker 1**: Multiple producers, multiple production companies, but I was doing multiple projects where I was drawing upon our vast library of archived files.

**`48:05.200:`** **Speaker 1**: Okay.

**`48:06.520:`** **Speaker 1**: I think we now are up to I think I just created drive number archive drive number one hundred and forty

**`48:13.940:`** **Speaker 1**: And this is now a four terabyte drive.

**`48:16.339:`** **Speaker 1**: Most of them are many of them are threes.

**`48:18.820:`** **Speaker 1**: Some of the oldest ones are five hundred gigabyte drives.

**`48:22.500:`** **Speaker 1**: So we have many, many terabytes of archived media, and we were drawing upon a bunch of old projects.

**`48:28.820:`** **Speaker 1**: So one really cool trick that you can do in Final Cut is

**`48:36.700:`** **Speaker 1**: First, you have to find the shot that you need.

**`48:38.780:`** **Speaker 1**: And I'm using my disk tracker software to reference old projects and say, oh, yeah, that shot's going to be in

**`48:46.040:`** **Speaker 1**: This project called that, and that's on archive number 79.

**`48:49.720:`** **Speaker 1**: So I go drag out drive 79.

**`48:53.080:`** **Speaker 1**: I open up that project.

**`48:54.980:`** **Speaker 1**: Nice final cut.

**`48:56.100:`** **Speaker 1**: I can have two projects open side by side.

**`48:58.740:`** **Speaker 1**: So I just I'm skimming through the other project.

**`49:01.780:`** **Speaker 1**: I go, yep, yep, there's the shot I need.

**`49:03.940:`** **Speaker 1**: I drag it from

**`49:07.039:`** **Speaker 1**: The library of old project into the timeline of new project

**`49:16.160:`** **Speaker 1**: And Final Cut says, Oh, hey, dude, you're copying that between libraries.

**`49:20.320:`** **Speaker 1**: You know that, right?

**`49:21.599:`** **Speaker 1**: And I say, Yes, I do.

**`49:23.200:`** **Speaker 1**: And then Final Cut says, I'm going to have to copy that over.

**`49:26.000:`** **Speaker 1**: And you're like, Yeah, that's cool.

**`49:28.000:`** **Speaker 1**: Do that.

**`49:31.280:`** **Speaker 1**: But what it doesn't do, and I hope I'm saying this right, because now that I'm saying it out loud, it sounds like I'm saying it wrong.

**`49:39.039:`** **Speaker 1**: Um you're go before you unmount that drive, I believe

**`49:48.680:`** **Speaker 1**: I found that I needed to consolidate that that project.

**`49:54.359:`** **Speaker 2**: So you had copied it from

**`49:56.440:`** **Speaker 1**: the timeline in one no no, I copied it from the library, like in the you know, the the keyword collection, the browser, yes, from old project, but to to force it into the new project I had to drag it into the library.

**`50:11.539:`** **Speaker 1**: Now I'm thinking, you know what?

**`50:13.059:`** **Speaker 1**: I'm going to do a quick experiment here.

**`50:14.500:`** **Speaker 1**: Let me make a new library, and I'm going to call this new library Trash Me.

**`50:20.740:`** **Speaker 1**: It's my little trick that I do.

**`50:23.140:`** **Speaker 1**: And I'm going to make a new project in that library.

**`50:25.940:`** **Speaker 1**: I'm going to call that Trash Me.

**`50:28.660:`** **Speaker 1**: And now I have another project open here.

**`50:31.840:`** **Speaker 1**: So I'm going to go into my media folder and I'm going to drag a clip down like this.

**`50:36.640:`** **Speaker 1**: Hey, Chris, I have a suggestion for your show.

**`50:39.520:`** **Speaker 2**: What's that?

**`50:41.020:`** **Speaker 2**: I know Premium Beats.

**`50:42.220:`** **Speaker 1**: Make it a video show.

**`50:46.060:`** **Speaker 2**: No, I know Premium Beats when you're sponsors.

**`50:48.220:`** **Speaker 2**: You need to pick a

**`50:49.859:`** **Speaker 2**: A bolsa nova sounding soundtrack, like something that sounds like girl from Ibanimba.

**`50:54.420:`** **Speaker 2**: Okay, so when you do all these little things that you normally would edit out, you can play that in the background.

**`50:59.780:`** **Speaker 1**: Yeah, but I'd still have to go do that.

**`51:03.360:`** **Speaker 1**: Okay, so so I wanted I wanted to read the the actual dialogue box that pops up.

**`51:09.760:`** **Speaker 1**: What what font when you drag

**`51:12.299:`** **Speaker 1**: From the library, the old library, into the new

**`51:20.280:`** **Speaker 1**: Timeline, okay, because you can't drag between two keyword collections.

**`51:25.480:`** **Speaker 1**: What Feynman says is this.

**`51:28.120:`** **Speaker 1**: You are editing clips between libraries.

**`51:30.920:`** **Speaker 1**: Stop.

**`51:32.920:`** **Speaker 1**: Clips and media will be copied to the library.

**`51:36.799:`** **Speaker 1**: Clips and media will be copied to the library trash me.

**`51:42.880:`** **Speaker 1**: Media stored in external folders will be left in place.

**`51:47.520:`** **Speaker 1**: That's the key phrase.

**`51:49.040:`** **Speaker 1**: So media stored in external folders.

**`51:51.360:`** **Speaker 1**: Now because we use a lean library and we keep our media leave in place in an external folder, it leaves it in the folder

**`52:03.480:`** **Speaker 1**: The media folder of the old project.

**`52:06.680:`** **Speaker 1**: See what I'm saying?

**`52:09.640:`** **Speaker 1**: So a link to it is created.

**`52:12.599:`** **Speaker 1**: And again, this is the plus and minus of having the ability to leave things in place.

**`52:22.660:`** **Speaker 1**: So Final Cut will not copy it into the new library storage location.

**`52:29.940:`** **Speaker 1**: It's going to leave it on that other drive, okay?

**`52:33.480:`** **Speaker 1**: Now stay with me here because this is it's a little bit confusing where the problem arises.

**`52:39.240:`** **Speaker 1**: So you say, okay, that's fine, and now I have a reference to another job on another drive.

**`52:46.640:`** **Speaker 1**: for one piece of media.

**`52:49.279:`** **Speaker 1**: The problem is the minute I unmount that drive, this piece of media gets the link to this piece of media gets broken.

**`52:56.240:`** **Speaker 1**: So before you unmount that drive, what I got very habitual about doing is just saying, okay, now consolidate it.

**`53:06.920:`** **Speaker 1**: And it will take that piece of media which was in the old project, let's say old library

**`53:14.820:`** **Speaker 1**: and it would copy it would make a copy of it into the storage location of the current library.

**`53:22.100:`** **Speaker 1**: All is good.

**`53:22.980:`** **Speaker 1**: Now I can unmount the other drive and all is good to go.

**`53:27.980:`** **Speaker 1**: Except for one thing.

**`53:30.859:`** **Speaker 1**: As you know, because you've heard me talk about this before, I am an avid, no pun intended, user of

**`53:41.680:`** **Speaker 1**: Some of the production techniques that I've talked about and some of the tutorials I've done where I am referencing, say, an After Effects render.

**`53:53.160:`** **Speaker 1**: That I might want to update.

**`53:56.120:`** **Speaker 1**: And by replacing the current one in the finder, it will automatically update into my timeline.

**`54:05.220:`** **Speaker 1**: Or, for example, there is the generate asset trick that I use in Photoshop, and I'll have links to these in the show notes.

**`54:15.120:`** **Speaker 1**: where I'm referencing a PNG that is in the finder in a specific folder, and Final Cut is referencing that in a leave in place manner because when I change it, it updates in my timeline.

**`54:29.839:`** **Speaker 1**: But once I hit consolidate media, it consolidates all media.

**`54:35.920:`** **Speaker 1**: Right.

**`54:36.400:`** **Speaker 1**: In class.

**`54:38.320:`** **Speaker 1**: It's no longer looking at those finder bits, correct.

**`54:43.420:`** **Speaker 1**: Okay, those things that are in those finder folders, and now it's looking at the massive library storage location that Final Cut is managing.

**`54:52.860:`** **Speaker 1**: And it's actually made copies of all of those files.

**`54:55.740:`** **Speaker 1**: and put them in there.

**`54:58.060:`** **Speaker 1**: Okay?

**`54:59.580:`** **Speaker 1**: And so what I want to do is I want to give you one last and I know that this is

**`55:05.020:`** **Speaker 1**: This is a really deep episode.

**`55:07.340:`** **Speaker 1**: I understand that.

**`55:08.540:`** **Speaker 1**: And it really would be great if this was a video podcast.

**`55:13.260:`** **Speaker 1**: But

**`55:15.180:`** **Speaker 1**: I'm going to make reference to one more very powerful tool that we have available to us in Final Cut.

**`55:22.920:`** **Speaker 1**: And that is in the relink files command, there is a radio button that I think a lot of people probably overlook.

**`55:33.480:`** **Speaker 1**: I know that I overlooked it for

**`55:37.060:`** **Speaker 1**: probably a year and a half.

**`55:40.900:`** **Speaker 1**: It's the radio it's the radio button where it says relink missing

**`55:45.420:`** **Speaker 1**: Or relink all.

**`55:47.020:`** **Speaker 2**: Relink all, right.

**`55:48.700:`** **Speaker 1**: And so it's very important.

**`55:51.260:`** **Speaker 1**: And this actually gives you some of the capability of what that old-timey

**`55:56.740:`** **Speaker 1**: proxy workflow would have had to have been like.

**`56:00.900:`** **Speaker 1**: Because you could, in theory, generate your own proxy files.

**`56:05.620:`** **Speaker 1**: And you could use this relink all command where you would say, I want to relink all of these files and then manually point those.

**`56:16.220:`** **Speaker 1**: using the locate selected file uh button to a different folder.

**`56:22.700:`** **Speaker 1**: And so one of my way of solving the fact that I have now mistakenly made generated media

**`56:31.020:`** **Speaker 1**: some of those After Effects and PNG files that are now buried in my storage location, is I just relink them back out

**`56:41.720:`** **Speaker 1**: To the versions that are outside of the storage location that I am continually updating.

**`56:47.560:`** **Speaker 1**: And that's very deep.

**`56:49.160:`** **Speaker 1**: And I understand that if I was listening to myself say that, I would probably rewind it a couple of times to figure it out.

**`56:59.360:`** **Speaker 1**: The fact of the matter is, the point of this whole episode is that letting the

**`57:06.860:`** **Speaker 1**: Final cut library database do more work and letting and sort of

**`57:16.520:`** **Speaker 1**: realizing that we quite often are breaking things when we're managing files in the Finder.

**`57:23.160:`** **Speaker 1**: It's a really good lesson to be had and to be learned.

**`57:27.240:`** **Speaker 1**: And I think you and

**`57:29.740:`** **Speaker 1**: Ronnie, you know, Ronnie pointed that out quite well.

**`57:33.740:`** **Speaker 2**: Yeah, yeah.

**`57:35.420:`** **Speaker 2**: So very good.

**`57:37.100:`** **Speaker 1**: Yeah, quite a journey, huh?

**`57:39.520:`** **Speaker 2**: Well, I think this is also like just a great lesson on the power of like one of the things I've really been learning lately is

**`57:48.900:`** **Speaker 2**: Choosing your resources for education and problem solving.

**`57:57.300:`** **Speaker 2**: Right.

**`57:57.620:`** **Speaker 2**: Because there's so many videos and forms and

**`58:01.620:`** **Speaker 2**: And I think it's really wise to find the one to three locations that you can go to online that you know

**`58:11.440:`** **Speaker 2**: have the experts that you need to get the questions answered because you could spend time.

**`58:18.900:`** **Speaker 2**: If you're good friends with Chris Fenwick, just shoot him a direct message.

**`58:21.859:`** **Speaker 2**: And actually, that still didn't help me either because you didn't have squat.

**`58:25.059:`** **Speaker 1**: I didn't have squat, did I?

**`58:26.900:`** **Speaker 2**: So forget that, forget asking Chris.

**`58:30.420:`** **Speaker 2**: If you just finding that forum or that really has the experts that can answer the questions you need is so vital.

**`58:38.580:`** **Speaker 2**: Building being part of a community, I guess, is the

**`58:42.440:`** **Speaker 2**: Is the moral of the story.

**`58:43.880:`** **Speaker 2**: Absolutely.

**`58:44.280:`** **Speaker 1**: And what I want to add to what you're saying there, like you said, being part of a community, you know, a community is a two-way street.

**`58:52.280:`** **Speaker 1**: It's not just.

**`58:54.160:`** **Speaker 1**: And you know what?

**`58:54.800:`** **Speaker 1**: It's funny, if you don't participate in various discussion groups or communities, and you're that guy who just gets online and he says

**`59:04.140:`** **Speaker 1**: Urgent.

**`59:04.700:`** **Speaker 1**: I can't find my proxy files.

**`59:06.059:`** **Speaker 1**: I need help now.

**`59:07.260:`** **Speaker 1**: It's like, dude, that's not and and then you look at that person's like like history and you realize he's never once given a single bit of advice to anybody else.

**`59:18.200:`** **Speaker 1**: You know, or the other thing that really annoys me is the people who come on and they'll say, Hey, I can't figure this out.

**`59:28.800:`** **Speaker 1**: And then ten people throw out potential fixes, and there's never a

**`59:36.640:`** **Speaker 1**: Thank you, Ronnie.

**`59:38.160:`** **Speaker 1**: This solved my problem.

**`59:40.240:`** **Speaker 1**: I really appreciate your help.

**`59:42.079:`** **Speaker 1**: Because now the people reading the forum, they don't know which one of these things all they know is you had a problem and then you evaporated off the face of the Internet.

**`59:50.660:`** **Speaker 2**: Right.

**`59:51.220:`** **Speaker 1**: Because you got your itch scratched and then you were done.

**`59:55.860:`** **Speaker 1**: You just disappeared.

**`59:57.220:`** **Speaker 1**: So you need to participate in those things.

**Speaker 1**: And at the very least, just say thank you. *01:00:00.780* **Speaker 2**: Yeah. *01:00:04.780* **Speaker 2**: Yeah, I think it's always important to go back. *01:00:06.380* **Speaker 2**: In fact, *01:00:08.700* **Speaker 2**: when I was referencing that problem I had earlier, the one where the audio was coming out of sync and I found the solution in Creative Cal. *01:00:10.440* **Speaker 2**: I think I actually went back to the other forums where I posted the question and put the solution. *01:00:20.440* **Speaker 2**: Right. *01:00:25.640* **Speaker 2**: Just so that when people came to those forums, you're a good online citizen, Ron. *01:00:25.960* **Speaker 2**: Yes, I try to be. *01:00:30.559* **Speaker 1**: Okay, you had told me earlier you needed to go, so I'm going to let you go. *01:00:32.799* **Speaker 1**: Thank you so much for doing this. *01:00:36.799* **Speaker 1**: I think that this was a *01:00:38.319* **Speaker 1**: Very deep and of this could have been here's how you do it. *01:00:40.339* **Speaker 1**: But I think it was very interesting to look at all the steps that you had gone through, the lousy ones, the lousy steps that I had recommended. *01:00:43.859* **Speaker 1**: It's very interesting to tear apart these little problems once in a while. *01:00:53.040* **Speaker 1**: And I think that I think, honestly, I think we have found a bug. *01:00:56.960* **Speaker 1**: And hopefully, Apple is listening. *01:01:02.160* **Speaker 1**: Hey, guys. *01:01:04.720* **Speaker 1**: and could probably fix this. *01:01:05.620* **Speaker 1**: But also thank you, Ronnie, for the solution. *01:01:08.900* **Speaker 1**: Sure. *01:01:11.140* **Speaker 2**: Hey, I wanted to say one quick thing before I go. *01:01:11.780* **Speaker 2**: It's a plug for *01:01:15.300* **Speaker 2**: A series that I'm doing related to the shoot that I did, and it would probably be good to come to your other show and talk about it, but *01:01:17.460* **Speaker 2**: We did like this nine camera shoot, and I'm gonna obviously edit in Final Cut Pro, so it'll be a good Final Cut Pro editing thing. *01:01:25.520* **Speaker 2**: Nothing like the crazy multi-16, 20-camera shoots that our good friend Scott does. *01:01:33.280* **Speaker 2**: But it was a unique project. *01:01:38.840* **Speaker 2**: It was like an improvised jam session between a rock guitarist *01:01:40.360* **Speaker 2**: and a hip-hop rapper and a jazz trio. *01:01:46.540* **Speaker 1**: Oh, yeah. *01:01:49.500* **Speaker 2**: And we're making like a performance film out of it. *01:01:49.980* **Speaker 2**: And so we're going to be doing like a behind the scenes *01:01:52.060* **Speaker 2**: blog post and behind the scenes show about like how we did it and making it and that thing. *01:01:54.720* **Speaker 2**: So I think it'll be it'll be on my website, DaredreamerMag. *01:01:59.599* **Speaker 2**: com in the upcoming weeks or so. *01:02:03.279* **Speaker 1**: So isn't it Daredreamer. *01:02:05.839* **Speaker 1**: net? *01:02:08.559* **Speaker 2**: Daredreamer. *01:02:09.320* **Speaker 2**: net is the name of my comp is that's my company's website, but my blog where I blog about the art and business of filmmaking and photography is Daredreamer Mag. *01:02:10.440* **Speaker 2**: As in Deja Rim magazine. *01:02:19.640* **Speaker 1**: Yeah, got it. *01:02:21.080* **Speaker 1**: Got it. *01:02:21.720* **Speaker 1**: Hey, open invitation. *01:02:22.760* **Speaker 1**: If you ever want to come on Digital Cinema Cafe and talk about your project, just let me know. *01:02:23.960* **Speaker 1**: When you're ready to do it, let me know, okay? *01:02:28.040* **Speaker 1**: Well, I do appreciate it, man. *01:02:29.880* **Speaker 1**: All right, Ron, thanks for the time. *01:02:31.359* **Speaker 1**: Oh, and how do people follow you, like on Twitter? *01:02:32.560* **Speaker 2**: What are you? *01:02:34.880* **Speaker 2**: Twitter at DaredreamerMag, M-A-G, Daredreamer Mag. *01:02:36.960* **Speaker 2**: Perfect. *01:02:41.640* **Speaker 1**: All right, dude. *01:02:42.200* **Speaker 1**: Take care and have a good day today. *01:02:42.839* **Speaker 1**: All right, you too, Chris. *01:02:44.359* **Speaker 1**: Bye. *01:02:45.079* **Speaker 1**: Later. *01:02:45.480* **Speaker 1**: So there you have it. *01:02:46.760* **Speaker 1**: Quite a little journey that Ron and I had to get to his solution. *01:02:48.200* **Speaker 1**: And as it turns out, it it came from Ronnie Cortens from the FCPX InSync Facebook group. *01:02:53.820* **Speaker 1**: If you want to be a part of that Facebook group, *01:03:01.500* **Speaker 1**: To be honest with you, I don't know how to um how to uh become a member. *01:03:05.940* **Speaker 1**: I I was invited by Ron Priest. *01:03:12.020* **Speaker 1**: And I think if you if you seek out Ron Priest, he's the he he's let me think here. *01:03:15.020* **Speaker 1**: He created the group and he's a self-employed *01:03:22.700* **Speaker 1**: Wedding video editor in, I don't actually, Ron, I don't know where you live. *01:03:28.520* **Speaker 1**: But if you contact him on Facebook, I'm sure he can let you in. *01:03:33.400* **Speaker 1**: And it's it is invitation only. *01:03:37.320* **Speaker 1**: And I will tell you, he even had a a culling of the herd, if you will, a while back where he decided that there was a bunch of people that just weren't participating and they weren't getting involved. *01:03:39.359* **Speaker 1**: And I think he booted a bunch of people out. *01:03:49.200* **Speaker 1**: So anyway, don't you know, make sure you get involved. *01:03:52.040* **Speaker 1**: But it's a great group of really smart people, and I appreciate everything that Ron has done to keep that group going. *01:03:54.600* **Speaker 1**: So once again, that's another episode. *01:04:03.120* **Speaker 1**: Thanks again for listening. *01:04:06.960* **Speaker 1**: Thank you so much for subscribing. *01:04:08.960* **Speaker 1**: Tell your friends. *01:04:10.960* **Speaker 1**: I keep hearing from people. *01:04:12.320* **Speaker 1**: That are just like, oh, yeah, I didn't know you had a podcast. *01:04:14.160* **Speaker 1**: It's like, really? *01:04:17.280* **Speaker 1**: How many episodes do I have to do for people to take notice? *01:04:18.320* **Speaker 1**: But tell your friends about the group, this podcast. *01:04:21.280* **Speaker 1**: I'm doing everything I can to make sure that the content is always relevant and informative. *01:04:26.060* **Speaker 1**: Thanks for listening. *01:04:33.980* **Speaker 1**: Go to iTunes, subscribe, and thank you for supporting our good friends at Premium Beat. *01:04:35.100* **Speaker 1**: We'll be back next week with another episode of The Grill. *01:04:40.860* **Speaker 1**: Later, later. *01:04:43.900*
