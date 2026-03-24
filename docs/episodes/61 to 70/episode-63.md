---
label: Episode 63
---

# Episode 63

**FCG063 - Folder Aliasing Terminal Thing  (feat. John Davidson)**

Big thinkers are my favorite guests. John Davidson is doing amazing things with FCPX and his multi-seat facility in LA servicing broadcasters in a unique way. If you want to learn more about Johns background and his company you may want to checkout FCG009. In this episode we just right into 10.1.2 and how the new Library structure benefits workgroup workflows and John COMPLETELY schools me in a workflow trick that I had not figured out yet. If you share media on a network BE SURE to take notes, this is a “not to miss” episode of The Grill. “Folder Aliasing Terminal Thing” google how to sync to server folder Vimeo Portfolios “a records and c records have to be changed” WMV converters on app store “Theres about 100 wmv converters” Explain how you keep your plug ins in sync between multiple systems Compound Clips as Sequences and Shared Storage in a workgroup environment, that’s what John Davidson from Magic Feather Inc. has been preaching since April of 2013. John’s company has chosen to put their oars into the Final Cut Pro X waters. We also get into Smart Collections and how to wire Macs with 10 Gigabit Ethernet

---

## Download

- [MP3](https://cdn.fcp.cafe/grill/FCG063-John-Davidson.mp3)

---

## Featuring

- [Chris Fenwick](http://chrisfenwick.com)
- John Davidson - @MagicFeatherInc

---

## Transcription

All right, happy Monday morning.
*00:00.160*

Welcome to another episode of The Grill, episode number what do we got here, 63 with John Davidson.
*00:01.520*

Now, John Davidson was on the show
*00:06.880*

few months ago actually actually he was one of the first guests he was on I believe it was like episode nine and his episode came out like two days before
*00:09.000*

10.
*00:17.640*

1 came out.
*00:18.359*

Now back then, John was really one of the big advocates of using the sparse disk method, and that's where I learned it from.
*00:19.560*

And if you don't know what the sparse disk method is, count your blessings.
*00:27.240*

You don't need to know.
*00:30.360*

Literally, it was the biggest stumbling block to getting to a good what what I considered a good workflow with Final Cut 10.
*00:31.859*

0, 10.
*00:39.699*

0 anything, or as Alex Gohner says, 10.
*00:40.820*

0
*00:43.059*

And the most important thing to remember is that with the new library method, and now the new library method, which is part of 10.
*00:44.620*

1.
*00:53.100*

2.
*00:53.580*

Everything is so much better.
*00:54.440*

And I gotta say, I love doing this show.
*00:55.640*

I love doing this show because I learn stuff all the time.
*00:58.120*

And this episode is one of those moments where my mind was blown.
*01:01.880*

So that's John Davidson, and we're going to be talking about 10.
*01:07.780*

1.
*01:12.020*

2 and some workflow issues.
*01:12.500*

Before we get to the interview, I got a quick premium beat story.
*01:14.900*

You know, I'm always talking about premium beats.
*01:18.820*

So
*01:20.580*

Just yesterday, I was training a producer that we work with, and he comes in and he brings us projects to finish for him.
*01:21.840*

And I've been trying to get him to ten point to Final Cut 10.
*01:28.479*

And finally, I got him to come in and I spent a day with him.
*01:32.079*

working on workflow issues and how to get started and things like that.
*01:36.420*

And he's very and he was still using Funnel Cut 6, not even Funnel Cut 7.
*01:40.979*

Anyway.
*01:45.539*

So we get to talking about music and he goes, Well, you know, one of my clients, they have a great you know, they have this, you know, wide open account.
*01:46.500*

With, and I'm not going to say the name, but some other music library company, and it's like a corporate account.
*01:56.060*

They can take anything they want.
*02:01.500*

It's all, you know, paid for, whatever.
*02:02.940*

And he goes, No, I just go to Premium Beat.
*02:05.020*

And I was like, oh, cool.
*02:07.100*

That's the way I feel too.
*02:08.140*

So anyway, if you have not looked at PremiumBeat.
*02:09.640*

com, I'm going to ask you as a favor to me, because they've been very good at supporting our show.
*02:11.799*

Go check it out.
*02:16.680*

Go check out their music.
*02:17.319*

Go check out the prices.
*02:18.280*

Um they have sound effects.
*02:20.620*

It's it's amazing.
*02:22.460*

It's a curated music library.
*02:23.500*

Go check it out.
*02:25.660*

So enough of that.
*02:26.860*

Alright, so now let's get to the interview.
*02:28.060*

This again, this is episode two on that episode.
*02:29.980*

It's it's it's a recap.
*02:32.700*

It's a part of the summer reruns, if you will.
*02:33.980*

And it's not a rerun, it's all new material, please listen.
*02:36.860*

But it is uh John Davidson from Magic Feather Inc in LA.
*02:39.340*

So John, the last time we talked, it was right before 10.
*02:44.019*

1 came out.
*02:47.700*

And you were we had the whole discussion about the sparse disk world, and you were really a big
*02:49.700*

you didn't take credit for it.
*02:57.280*

You tried to give it to somebody else and I refused to accept that.
*02:58.560*

I gave the sparse disk credit workflow to you.
*03:02.000*

sparse disk workflow credit to you.
*03:06.340*

And now libraries are different.
*03:10.020*

What's going on at Magic Feather?
*03:12.819*

**Speaker 2**: Okay, so before we got 10 one, which was, you know, I guess libraries and stuff like that, we were doing it, you know, where you like you're saying, we had the sparse disk
images.
*03:16.220*

**Speaker 2**: And then you would mount your event and your projects would come in through that.
*03:29.220*

**Speaker 2**: And it worked.
*03:33.140*

**Speaker 2**: And because what we have is a central storage location
*03:34.739*

**Speaker 2**: and all of the Macs feed into it.
*03:38.820*

You're saying at um at Magic Feather.
*03:41.300*

**Speaker 2**: Right.
*03:44.020*

**Speaker 2**: But the problem was, uh, unless you're using uh sand
*03:44.580*

**Speaker 2**: storage area network or whatever you call it.
*03:49.299*

**Speaker 2**: And then we we were using a NAS.
*03:51.860*

**Speaker 2**: And Final Cut only wants to mount with the SAN.
*03:54.099*

**Speaker 2**: Right.
*03:57.060*

**Speaker 2**: So the trick around that was to use sparse disks.
*03:57.540*

**Speaker 2**: You double-click on it over the network and it mounts and it tricks your final cut into thinking it's mounted over either locally or a SAM.
*04:01.240*

**Speaker 2**: So it worked and we did it for two years like that.
*04:10.600*

**Speaker 2**: Bless you.
*04:15.080*

**Speaker 2**: Um we did it for two years like that and it was a pretty solid solution.
*04:15.800*

**Speaker 2**: Um was it perfect?
*04:20.360*

**Speaker 2**: No.
*04:22.280*

**Speaker 2**: But what really is in this world?
*04:22.760*

**Speaker 2**: Mostly we're just trying to make our cut look good on tape and who cares how it looks?
*04:25.000*

**Speaker 2**: Getting there.
*04:29.580*

Right.
*04:30.540*

**Speaker 2**: So then 10.
*04:31.260*

**Speaker 2**: 1 happened and we got libraries.
*04:32.540*

**Speaker 2**: And so we did not really change our process.
*04:36.300*

**Speaker 2**: We continue to use sparse disks with libraries because
*04:39.100*

**Speaker 2**: you know, your libraries would store all your render files and cache and all that, and it would just grow and it would be too big to really pass libraries around.
*04:42.820*

**Speaker 2**: The only real difference from where we were before 10.
*04:51.520*

**Speaker 2**: 1 to after 10.
*04:54.960*

**Speaker 2**: 1 was that we just can we just put libraries inside of sparse disks.
*04:56.000*

**Speaker 2**: and kept going as we were going.
*05:00.840*

Now are you keeping all the other media and assets for a particular job in that sparse disk as well?
*05:03.240*

**Speaker 2**: No.
*05:09.480*

**Speaker 2**: We reference media.
*05:10.120*

**Speaker 2**: We would leave it in place and reference it in a third party folder like we have on the server we have a media folder.
*05:11.960*

**Speaker 2**: And then inside of that media folder it breaks down
*05:18.920*

**Speaker 2**: to networks.
*05:22.840*

**Speaker 2**: And then inside of those networks, it would have folders for like digitized QuickTimes of entire episodes with multi-track audio and things like that, of all the
different shows that we work on.
*05:24.520*

**Speaker 2**: But we just got 10.
*05:36.940*

**Speaker 2**: 2.
*05:39.099*

**Speaker 2**: And what a difference.
*05:40.220*

**Speaker 2**: 10.
*05:41.180*

2, right?
*05:41.580*

**Speaker 2**: Yeah, well 10.
*05:42.220*

**Speaker 2**: 1.
*05:43.259*

**Speaker 2**: 2, which actually I think was a bigger update to in terms of our workflow than
*05:43.659*

I'm going to tend to agree with you.
*05:49.259*

I think that there's a lot of stuff that has happened between ten one and ten one two that is pretty outstanding.
*05:50.539*

**Speaker 2**: Oh yeah.
*05:58.280*

**Speaker 2**: So as soon as we upgraded to that, we held off for a couple of days, just wanted to make sure people's computers didn't start blowing up.
*05:59.879*

**Speaker 2**: And they did not.
*06:08.000*

**Speaker 2**: So then we tried it out on one computer.
*06:09.120*

**Speaker 2**: We did tried it on mine because I'm usually the guinea pig because I'm least critical to the editing process these days.
*06:13.759*

**Speaker 2**: So I opened it up on my interesting distinction.
*06:20.199*

**Speaker 2**: Right.
*06:23.479*

**Speaker 2**: I duplicated a sparse disk so that we could test it without, you know, if we screwed up a project, everybody else would be fine.
*06:24.599*

**Speaker 2**: They're covered.
*06:32.759*

**Speaker 2**: So I tested it and I was like, oh, you know, hey, it's snappier and it's got all this good stuff.
*06:33.560*

**Speaker 2**: And then I started going through, you know, what everyone was saying to do.
*06:39.880*

**Speaker 2**: The MacBreak Studio guys, what they were talking about on FCP.
*06:44.140*

**Speaker 2**: co and things like that.
*06:48.220*

**Speaker 2**: And I was like, holy crap.
*06:49.260*

**Speaker 2**: We no longer have to have these large library files.
*06:51.020*

Right.
*06:54.540*

**Speaker 2**: And XML goes as big as you need it to go.
*06:55.880*

And so Yes, so let's back up and break this down a little bit.
*07:00.680*

If you are new to Final Cut 10 and you're working by yourself, Final Cut 10 sort of in its
*07:05.500*

Kind of default infancy mode, if you will, would be that you, when you excuse me, when you import media into your project.
*07:13.920*

It is going to like maybe pull it off of your camera card and put it into your library.
*07:26.440*

And when you drag in photos
*07:32.199*

it will put them into your library.
*07:35.240*

And when you create audio files or whatever, it will put those into your library.
*07:37.080*

And what that does for you is it keeps a very concise
*07:42.040*

Unified place where everything is stored.
*07:46.720*

However, in a more advanced workflow, and I won't say a more pro workflow, but a more complex workflow,
*07:49.440*

quite often you're going to have to have outside people placing assets in your media folder that you will bring into your edit.
*07:57.520*

you might be updating assets in your folders.
*08:08.440*

I know that in one of the workflows that I've preached, if you will, on my website.
*08:11.720*

It's the whole idea of rendering in taking my After Effects renders and putting them in a intermediate place that then when I copy them into my render location
*08:18.260*

Those automatically update in Final Cut.
*08:30.639*

However, if you were using the library in the sort of default mode,
*08:33.200*

those assets don't get updated in the in the library file unless you actually um re-import it.
*08:38.680*

So in some more complex workflows, there's a huge advantage to keeping assets outside of the library.
*08:48.820*

And essentially what we're doing, because the library, I used to describe it as sort of a cross between the old
*08:56.420*

Funnel cut classic project file melded with the old scratch disk.
*09:03.440*

It was kind of a combination of those two things, and that's what the old event/slash project metaphor was in the first iterations of Final Cut 10.
*09:11.240*

However, now we're at a point where the library file is really acting more and more like the old Final Cut project file.
*09:23.839*

However, it still can't be opened across the network.
*09:34.959*

**Speaker 2**: And you know what though, we're fine with that because whereas before your library file would be multiple gigs
*09:38.899*

**Speaker 2**: Sometimes 100 gigs, because you are able to point your cache and all that other stuff into a third-party location
*09:46.800*

**Speaker 2**: Your resulting file size is forty megs-ish, which is way easy to pass around on a network.
*09:55.600*

**Speaker 2**: So now what we do is we just work locally on the library.
*10:03.120*

**Speaker 2**: Build our project, edit with it.
*10:06.339*

**Speaker 2**: It's referencing all the media on the server.
*10:07.779*

**Speaker 2**: But the actual database file, and that's what you should think of the library as, is a database file.
*10:10.420*

**Speaker 2**: It's just pointing to data.
*10:15.139*

**Speaker 2**: It's not holding it, it's not churning it up through your hard drive locally, it's all being pushed off somewhere else so that the actual program is now just focusing on
the library file and it lets all the servers and stuff deal with media.
*10:16.940*

**Speaker 2**: This is great.
*10:31.280*

**Speaker 2**: So now we work locally, and that's how Apple would prefer us to work because when you're working with the database file, all those little bits and bytes going to it can
*10:32.400*

**Speaker 2**: Get messy going over the network, but when they're local, it's happier.
*10:41.820*

**Speaker 2**: It's taking advantage of our SSD and all that stuff.
*10:46.220*

So
*10:48.940*

So, John, what you're saying is you will reach across your network.
*10:49.459*

You see your cache of all of your jobs and projects that you're currently working on.
*10:52.980*

And you see a library file that says this is the Godzilla trailer or whatever, and you're saying you just copy that over to your local drive?
*10:58.080*

Yep.
*11:06.320*

And then you launch it from your local drive, which is the way Final Cut 10 wants to work with library files.
*11:06.960*

And you have all of the pointers.
*11:13.680*

Now let's be clear, there's multiple things.
*11:15.840*

One
*11:18.080*

you want to make sure that you have leave media in place checked in the preferences.
*11:18.940*

Correct.
*11:24.460*

That means when you bring in media, it doesn't say, oh, let's put another copy in the library file, which is kind of ridiculous.
*11:24.860*

But then you can also tell it to put the render files and all the cache files and all of the waveform caches and whatnot.
*11:31.040*

You can leave those on the NAS, correct?
*11:39.519*

That is correct.
*11:44.160*

Okay, this is actually really interesting because, as is the case, John Davidson always takes it one step further.
*11:45.380*

What I was going to talk about today with you was the fact that I have noticed
*11:54.020*

That the new XML output is all inclusive.
*11:59.120*

Whereas in 10.
*12:05.120*

1.
*12:06.000*

1, you would have to do one XML for your event library
*12:06.320*

And then another XML for any project data.
*12:11.460*

You can now, when you do an XML output, correct me if I'm wrong, it gives you everything in one file, correct?
*12:14.980*

**Speaker 2**: Not quite.
*12:21.380*

Okay, correct me.
*12:22.260*

**Speaker 2**: Okay, so that's what we were thinking too.
*12:23.720*

**Speaker 2**: And I was like, holy crap.
*12:25.240*

**Speaker 2**: So when we're done with this, my knee-jerk reaction was, dude, let's just stick with XMLs and keep a local library and only import XMLs.
*12:26.360*

**Speaker 2**: Import and export.
*12:35.420*

**Speaker 2**: Because when you bring in the XML, it creates the events and projects and whatnot.
*12:36.060*

That's kind of what I've been toying with recently, the last few days.
*12:39.100*

**Speaker 2**: And here's where the toy is going to hurt you.
*12:42.700*

**Speaker 2**: The XML does not bring across specific keyframe data.
*12:46.200*

**Speaker 2**: So if you were to animate opacity on a layer in a project and move it and transform it and whatnot.
*12:51.399*

**Speaker 2**: And then you export the XML of that project and you bring that XML into a different system, that data is gone.
*12:59.540*

Wow.
*13:07.220*

**Speaker 2**: And it gets worse.
*13:08.579*

**Speaker 2**: Text information does not necessarily come across correctly either.
*13:10.339*

**Speaker 2**: So if you were to have like an animated text thing that did this whole thing.
*13:14.819*

**Speaker 2**: And then you export the XML, you bring it in, your text is just going to be center basic type right in the middle of the screen.
*13:18.440*

Interesting.
*13:24.040*

Actually, that kind of makes sense.
*13:24.680*

**Speaker 2**: Slates.
*13:26.520*

**Speaker 2**: Your text will be correct, but it will just instead of being broken down into page breaks and things like that, so that you're
*13:28.360*

**Speaker 2**: Slate information is nice and pretty down the middle, it's going to be one gigantic long string.
*13:36.060*

**Speaker 2**: So you're going to have to go through and re-enter it and break it apart.
*13:41.020*

**Speaker 2**: This is not the end of the world for metadata information.
*13:44.779*

Right.
*13:47.980*

**Speaker 2**: If you have keyword tags and ranges and all that stuff, that's all going to come across.
*13:48.620*

**Speaker 2**: That's what you want.
*13:52.620*

**Speaker 2**: For us, that's what we mostly want anyway.
*13:53.560*

**Speaker 2**: Exporting the XML is mostly a way to maintain the metadata from your keyword tagging.
*13:55.640*

**Speaker 2**: Think of it like that, and rebuilding your project, but don't think of it as like a perfect archive.
*14:01.160*

**Speaker 2**: Of your project.
*14:06.420*

It's not the old project file.
*14:08.100*

**Speaker 2**: No.
*14:11.060*

Okay, this is good.
*14:12.420*

I'm really glad we're having this conversation because that's kind of
*14:13.459*

Where my mind was heading to start experimenting this week, and you just saved me a week of time.
*14:16.440*

Thank you.
*14:20.840*

**Speaker 2**: You would be very sad.
*14:21.480*

**Speaker 2**: So, what was the sl so when we realized that, we were like, okay.
*14:23.240*

**Speaker 2**: Let's not do it where we base our old project archives off of XML.
*14:28.520*

**Speaker 2**: And then we were like, wait a minute.
*14:34.040*

**Speaker 2**: The XML file is, I don't know, four megs?
*14:35.640*

**Speaker 2**: The whole library with everything is forty.
*14:39.240*

**Speaker 2**: So let's just copy as a backup, let's just copy our old project libraries.
*14:43.959*

**Speaker 2**: to the server as forty meg file, and who cares?
*14:48.800*

**Speaker 2**: Because Chris, we're running on 10 gigabit Ethernet now.
*14:52.080*

**Speaker 2**: The speed of a forty meg file is an it's literally nothing to transfer back and forth.
*14:55.360*

**Speaker 2**: So that's what we're doing.
*15:00.640*

**Speaker 2**: Will it change for now?
*15:03.500*

**Speaker 2**: Maybe.
*15:04.860*

**Speaker 2**: But it's a great solution.
*15:06.060*

**Speaker 2**: Final Cut's happier with it.
*15:08.380*

**Speaker 2**: It likes you having your library local.
*15:10.300*

**Speaker 2**: So why not just give them what they want?
*15:13.060*

**Speaker 2**: And maybe the benefit for us is things work better.
*15:16.100*

So let's talk a little bit about some of the settings that you do when you start a project.
*15:20.260*

Now
*15:24.660*

There's now a new library's property window, which is very important.
*15:25.339*

And in there, we get to modify the settings of the library, and we get to choose where we put media.
*15:30.540*

where we put cache and where we put backups.
*15:39.120*

That's important.
*15:42.640*

So we have to like let's say if you have a template library that you all start all your projects with
*15:43.839*

I guess you'd still want to set that, which actually is very similar if you think about it.
*15:53.700*

If you were to open up Premiere Pro, the first thing you do is you get that crazy window and you go, Oh, I got to make a bunch of decisions here.
*15:58.980*

**Speaker 2**: Does it?
*16:05.040*

**Speaker 2**: I've never done that.
*16:05.519*

It actually does, yeah.
*16:06.640*

Yeah.
*16:08.399*

I mean, it's a whole bunch of like, I just wanted to edit, you know?
*16:08.880*

**Speaker 2**: Right.
*16:13.600*

And so that's one thing.
*16:14.560*

You have to tell it where to put the media and the cache.
*16:15.920*

**Speaker 2**: Then networks, yeah, we don't we once you've saved that information where you put the media and the cache, it's going to remember that for your next library.
*16:19.720*

Okay, where are you setting that then?
*16:27.880*

**Speaker 2**: On the server, we created an FCPX data folder.
*16:30.320*

Okay.
*16:33.760*

**Speaker 2**: And within the FCPX data folder, we created subfolders of each one of our users, editors.
*16:34.560*

**Speaker 2**: Everybody got a subfolder.
*16:40.899*

**Speaker 2**: If even if you weren't really an editor, if you're an art director, you're still going to use Final Cut.
*16:42.339*

**Speaker 2**: So we just said, screw it.
*16:47.540*

**Speaker 2**: We're going to give each user his own specific folder for cache, renders, and all that other stuff.
*16:49.380*

**Speaker 2**: So we then we made subfolders for each of those three and pointed every user to their own subfolders correctly.
*16:55.020*

**Speaker 2**: And now any time a user makes a new library
*17:01.420*

**Speaker 2**: That new library automatically goes, he still likes it over there.
*17:04.439*

**Speaker 2**: And it points it, and we don't have to think about that anymore.
*17:07.959*

**Speaker 2**: Every new library you created remembers your last choice.
*17:12.679*

Okay.
*17:15.959*

**Speaker 2**: If you bring in a library from another user, you know, when we archive it, say a month down the road, we want to come back to that cake boss project or whatever.
*17:16.519*

**Speaker 2**: Another user brings in that library and opens that library.
*17:24.880*

**Speaker 2**: The library retains the settings and continues to point to the original creator's cache.
*17:27.360*

Right.
*17:33.040*

Now, that's one of the things that I've noticed because I was last week toying a little bit with.
*17:33.520*

creating XMLs, creating a blank library on a local system, importing that XML, that magically it just found all the data.
*17:38.900*

**Speaker 2**: Yeah.
*17:48.300*

It's really spectacular.
*17:49.100*

So it's the same thing when you copy a library off the so so let's say I come in to work in one of your edit suites.
*17:50.300*

And you tell me, you know, you're going to work on you just use cake cake box for a cake cake boss for a sample.
*17:57.620*

So
*18:06.260*

So I'm going to work on some piece there.
*18:06.760*

What I'm going to do is I'm going to log onto the server.
*18:08.840*

I'm going to see the library called CakeBoss.
*18:10.919*

I'm going to drag a copy over.
*18:13.480*

How do I know now that there's two copies of that library?
*18:15.000*

Do you label one as
*18:17.720*

temporary or moved or how do you do that?
*18:20.179*

**Speaker 2**: Nah.
*18:23.460*

**Speaker 2**: And actually, we're still kind of running through the caveats of that, but you would just hoppy it locally.
*18:24.260*

**Speaker 2**: Okay.
*18:29.620*

**Speaker 2**: And unless another user is working on that same library
*18:30.019*

**Speaker 2**: When you're done, you just copy it back.
*18:34.580*

And you'll put it back.
*18:36.740*

**Speaker 2**: And replace it.
*18:37.700*

Copy and replace.
*18:38.500*

Okay.
*18:39.539*

**Speaker 2**: And then obviously, as a redundancy, you want to keep an entirely different server.
*18:42.500*

**Speaker 2**: that backs up that original server, say, once a week.
*18:48.679*

Right.
*18:51.639*

**Speaker 2**: You know, because you don't want to lose all your work.
*18:52.360*

**Speaker 2**: So we have an Aureka
*18:56.279*

**Speaker 2**: 2TB drive.
*18:59.800*

**Speaker 2**: Well, when it's gonna, we're still having some problems with it, but Erika I think is gonna come through for us and replace it.
*19:01.240*

**Speaker 2**: We had some problems with it.
*19:07.560*

**Speaker 2**: I think we got one of the first Thunderbolt 2 8 drive
*19:08.600*

**Speaker 2**: bays that they came off the line with.
*19:12.320*

**Speaker 2**: We've had some wonkiness with one of our Thunderbolt ports.
*19:14.480*

**Speaker 2**: But once that's correct, we're going to have this thirty two terabyte backup of the server.
*19:17.920*

**Speaker 2**: Once we'll just replace everything on it.
*19:22.640*

Gotcha.
*19:24.919*

**Speaker 2**: Go home overnight, come back in the next morning, you know, we can sleep a little soundly, a little more soundly.
*19:25.720*

Now you just doing I've I've often referred to it as a caveman backup, just drag over and say replace, or do you use some software to deal with that?
*19:30.840*

**Speaker 2**: Yeah, we just drag and replace.
*19:38.640*

Yeah.
*19:40.560*

**Speaker 2**: You know, with it, like I said, with its 10 gigabit, we got these awesome, awesome new Sandlink 2 boxes from Smalltree.
*19:41.200*

**Speaker 2**: And what they do is they give your gigabit Ethernet if you have a 10 gigabit capable router like we do, it'll turn your Ethernet cable into a 10 gigabit speed.
*19:50.220*

**Speaker 2**: Connection.
*20:04.200*

**Speaker 2**: So our Mac yeah, our Mac Pros over Ethernet get around 900 to 1,000 read-write speeds when nobody else is using the server.
*20:05.560*

Good night.
*20:16.620*

How does that how does that work?
*20:17.340*

Just magic?
*20:19.820*

**Speaker 2**: It's some sort of magic.
*20:21.420*

**Speaker 2**: I believe elves are involved.
*20:23.100*

**Speaker 2**: I'm not entirely sure.
*20:24.940*

**Speaker 2**: But I here's what I will tell you.
*20:26.780*

**Speaker 2**: If you buy it from Smalltree
*20:28.220*

**Speaker 2**: Steve Monica and those guys are great, and they'll give you these specific little tuning files data that you need to put in to make it really take advantage of
everything.
*20:29.980*

**Speaker 2**: Even with Thunderbolt Bolt One.
*20:38.300*

**Speaker 2**: connections to this Thunderbolt two Sandlink two, we're getting around six hundred readwrite, which is pretty solid.
*20:40.780*

**Speaker 2**: Definitely more than you need for even 4K.
*20:49.000*

Right, right.
*20:52.440*

That's about what I get.
*20:54.280*

That's about what I get off of a local Pegasus One.
*20:55.960*

**Speaker 2**: Yeah.
*21:01.700*

You know, locally.
*21:02.340*

**Speaker 2**: Yeah.
*21:03.940*

**Speaker 2**: It's as fast as the SSD.
*21:04.260*

**Speaker 2**: I mean, there may be a little bit of latency compared to an SSD on a Mac Pro.
*21:05.700*

**Speaker 2**: But now is this the
*21:11.300*

It's called a San Link 2 10 gigabit T switch.
*21:13.940*

It's about or a but little box is about 600 bucks, it says?
*21:17.139*

**Speaker 2**: Yes.
*21:20.899*

And Smalltree not only retails it, but also has some little hacks to make it go Mo Beta.
*21:21.919*

**Speaker 2**: They have some little hacks to make it go better that even Promise doesn't give you if you were to buy it from someone else, which is why I say, hey, call get it from
Smalltree, and if you have a problem, they'll work it out for you.
*21:29.540*

**Speaker 2**: You can get it anywhere, but I like Smalltree.
*21:42.140*

**Speaker 2**: If I can help out a a good value-added vend or retailer, then why not?
*21:44.940*

**Speaker 2**: But they're very smart.
*21:51.660*

**Speaker 2**: So that's that.
*21:54.860*

**Speaker 2**: So every we're we've been upgrading all our stuff to 10 gigabit Ethernet now.
*21:56.140*

**Speaker 2**: Everybody's happier for it.
*21:59.660*

So you put one of these 10 gig
*22:01.100*

uh boxes on the back of each computer, either iMac or iMac Pro.
*22:03.120*

Du it's just Thunderbolt in.
*22:07.520*

Thunderbolt two in.
*22:09.680*

Yeah?
*22:10.880*

**Speaker 2**: Mhm.
*22:11.200*

**Speaker 2**: Thunderbolt is Thunderbolt two and one.
*22:11.940*

**Speaker 2**: The only difference is um if you have a Thunderbolt two connection, it goes faster.
*22:14.100*

Sure.
*22:19.299*

And then um and then from there you take your existing gigabit Ethernet cabling
*22:20.100*

And do you have to I'm assuming you have to change your what like, for example, in our office, we have a gigabit switch.
*22:27.900*

Do you have to put in a special switch then?
*22:35.020*

Yes, we have a lot of different things.
*22:37.620*

**Speaker 2**: We have a 10 gigabit Neck Ear switch.
*22:39.300*

**Speaker 2**: It's about a year old, been working great.
*22:41.300*

**Speaker 2**: And then we, you know, we have we've gone I think we went through this on the last one, so I don't know.
*22:44.820*

**Speaker 2**: Get too deep into it, but yeah, still have a Mac Pro going, feeding to a 16 drive Pro ammio array over Mini SAS.
*22:49.419*

**Speaker 2**: And then the NetGear connects to the Mac Pro and the Mac Pro turns it into
*22:57.419*

**Speaker 2**: Magic.
*23:02.100*

Yeah, I think the thing that's astonishing to me that I don't think we covered last time is the fact that this Sendlink 2 just somehow magically takes your gigabit and
makes it 10 gig.
*23:02.980*

**Speaker 2**: Well, we were using Addo Thunderlink boxes.
*23:13.200*

**Speaker 2**: We had two of them.
*23:16.320*

**Speaker 2**: I didn't want to invest any more because I wanted to get Thunderbolt 2 versions when they came out after NAB.
*23:17.200*

**Speaker 2**: The Addo boxes are great with the caveat that they are loud and heavy.
*23:23.900*

**Speaker 2**: big, big bricks.
*23:33.419*

**Speaker 2**: They look like you know, they look like these G-Ray drives that you get.
*23:34.700*

Yeah.
*23:38.140*

**Speaker 2**: You know what I mean?
*23:38.460*

**Speaker 2**: That they used to you would be your FireWire 800 drives.
*23:39.179*

**Speaker 2**: They're that big.
*23:42.380*

**Speaker 2**: And it sounds like a hairdryer.
*23:43.419*

**Speaker 2**: So the sand link is tiny, it's small.
*23:45.580*

**Speaker 2**: Well, that would be the same thing.
*23:49.500*

**Speaker 2**: And it's quiet.
*23:51.419*

**Speaker 2**: That's the best thing about it.
*23:53.660*

You know, it's really funny.
*23:55.240*

I was talking with a friend of mine, and I'm probably going to either have Jeff or his daughter on the show.
*23:56.600*

He was telling me about how his daughter has been doing all this stuff in Final Pet 10, and she's running it off of a Mac Mini in her bedroom.
*24:02.280*

But yeah, but where it sits on her desk, it gets the afternoon sun through the through the window and it overheats on her.
*24:08.720*

So get this, this is hysterical
*24:16.720*

She keeps putting glasses of water on top of it to kind of water cool it.
*24:19.440*

And he says, Yeah, I'm getting tired of replacing her keyboards because she spills the water into the keyboard.
*24:24.240*

**Speaker 2**: Maybe just put a magazine on top of it?
*24:31.500*

I don't know.
*24:33.899*

I don't know.
*24:34.460*

Paper is an insulator.
*24:35.019*

Who knows?
*24:36.380*

Yeah.
*24:37.580*

**Speaker 2**: Maybe so the thing of gasoline will work, I think.
*24:38.059*

**Speaker 2**: That's what I read.
*24:40.539*

Yeah.
*24:41.540*

Anyway, I thought that was a funny story.
*24:41.940*

She was water cooling a Mac mini with glasses of water, literally.
*24:43.540*

**Speaker 2**: Yikes.
*24:47.060*

Okay, yeah.
*24:48.180*

And so if you're listening and you want to hear more about John's setup, go back to Final Cut Grill 009.
*24:48.820*

And we went literally like cable cable, wire for wire into that.
*24:55.340*

And we talked about how you solicited the help from Bob Zellen on Creative Cow to help you wire and get your stuff.
*24:59.419*

That's all good information.
*25:07.560*

So I'm very pleased to and I'm really again, I love doing the show because I learn something every episode
*25:09.240*

It did not occur to me to literally just copy the library file over to the local machine.
*25:16.519*

**Speaker 2**: Yeah, as long as everything's pointed out of it, you're good to go.
*25:22.200*

Now, I will say that using my what did you say?
*25:24.840*

you know, I would be hurt by my theory.
*25:28.740*

Um I using the um uh the uh XML theory this last week, when I I don't tend to use the text stuff and I don't tend to keyframe too much in the time line.
*25:31.460*

Or maybe, oh, maybe that's what caused that.
*25:45.679*

Anyway, I'm realizing there may have been some problems that I didn't realize I was having.
*25:48.159*

**Speaker 2**: You use it more than you think you did.
*25:53.200*

I I agree, but I don't use the text tools.
*25:54.740*

I really, I really try to stay away from that.
*25:58.260*

Even for slates?
*26:01.460*

No, I'd I'd make a slate in Photoshop.
*26:03.060*

PNG, done.
*26:05.620*

I don't know.
*26:08.159*

It's just my theory is, and the theory has always been, and this is mostly.
*26:08.559*

relative to Final Cut Classic, and frankly, I haven't even tested it with Final Cut 10 yet.
*26:16.840*

Final Cut Classic wouldn't tell you if you had a font missing.
*26:23.800*

It would just go, oh, okay.
*26:28.800*

And it would just say, oh, well, I'll just change it to this.
*26:30.480*

This is fine.
*26:33.280*

And when I first realized it, it was many years ago, and I was opening up a project that a friend of mine had worked on.
*26:34.720*

And I'm looking at the way he had like.
*26:40.400*

Spaced stuff out to the edge of the frame, and I'm like, Really?
*26:42.519*

He wouldn't do that.
*26:46.039*

This guy is a pro.
*26:47.480*

He understands safe titles, safe action.
*26:48.360*

There's no way he would put characters away out there.
*26:50.360*

So I call him.
*26:53.540*

I go, Hey, what font were you using on this project?
*26:54.340*

And he goes, Oh, yeah, that's one of mine.
*26:56.500*

It's blah, blah, blah.
*26:58.660*

And I go, Dude, you got to send it to me because I almost kicked this thing out and called it done.
*27:00.180*

Because it didn't even tell me that it had changed it.
*27:05.220*

So I I tend to always do my text work in something where it is going to be hard stamped into my timeline.
*27:07.780*

That's just me.
*27:15.540*

**Speaker 2**: If you have a local
*27:17.220*

**Speaker 2**: Solution like us, where we never share with anybody.
*27:19.620*

Right.
*27:22.420*

**Speaker 2**: We don't play with other kids.
*27:22.980*

**Speaker 2**: We play only in our own little sandbox, and that's it.
*27:24.260*

**Speaker 2**: We have generators with prebuilt text elements to create slates quickly.
*27:27.620*

**Speaker 2**: Right.
*27:32.900*

**Speaker 2**: Final cut.
*27:33.380*

**Speaker 2**: You just drag the generator
*27:34.340*

**Speaker 2**: Make it two seconds, change the text, you're done.
*27:35.940*

**Speaker 2**: So that's why we do it like that.
*27:38.980*

No, I get it.
*27:40.260*

And there's a lot of advantages to it.
*27:41.299*

And I won't say that we never use it.
*27:43.059*

For example, as you know, it isn't very difficult to make some lower third templates for various clients.
*27:46.179*

And I have done that.
*27:53.059*

So I'm not totally against it, but I tend to stay away from it.
*27:54.340*

**Speaker 2**: And even now, like we create, our art director is now creating all these.
*27:58.060*

**Speaker 2**: He was a stalwart.
*28:02.220*

**Speaker 2**: He was not a big Final Cut 10 person.
*28:03.260*

**Speaker 2**: He really never used it before we hired him, but we wanted him for more graphick-y stuff.
*28:05.580*

**Speaker 2**: However, he knew motion, and so I started explaining to him, like, dude, if you just make these templates, you're going to save yourself all these After Effects renders
*28:10.120*

**Speaker 2**: for M pages and all this stuff, so that you don't have to do this minutiae.
*28:19.860*

**Speaker 2**: All the editors can do it for you.
*28:23.460*

**Speaker 2**: All they got to do is type in the text.
*28:24.740*

**Speaker 2**: So now we have these big network logos come on the screen and they're pre-built graphics that he's rendered out correctly from After Effects with masks and everything.
*28:26.500*

**Speaker 2**: All the editor needs to do if we make a version that says tonight or Friday or next or next Friday or whatever, they just load in the generator.
*28:34.220*

**Speaker 2**: Set the duration and what they want and type the text, and it flies in and it looks like the network graphic.
*28:42.140*

**Speaker 2**: It's exactly like what they would get out of After Effects.
*28:47.580*

**Speaker 2**: But we've just skipped that whole step.
*28:49.900*

**Speaker 2**: I mean, our art director can just play on 3D and fun stuff.
*28:51.900*

Yeah, don't tell the networks that.
*28:56.540*

Now, you're touching on something that I wanted to talk to you about.
*28:59.500*

Last time, you had mentioned that we got into the whole plug-in discussion.
*29:02.380*

And you were like, Yeah, you know, I'm a little leery of getting into plugins because it's hard to keep them, you know, asynchronous across every machine.
*29:07.560*

And you said that by and large, you guys just generate your own plugins.
*29:15.000*

**Speaker 2**: Yes.
*29:18.860*

Okay.
*29:19.580*

So and you had said, and I can't remember what you said, and it didn't really stick last time.
*29:20.300*

What is it that you are doing to make sure that all of the machines have the same plugins across your network?
*29:28.220*

**Speaker 2**: Oh, gosh.
*29:36.840*

**Speaker 2**: We created some sort of folder aliasing terminal thing that syncs your emotion fold.
*29:38.840*

**Speaker 2**: Honestly, man, it's
*29:45.720*

**Speaker 2**: It was seven months ago and it's still been working strong.
*29:47.680*

**Speaker 2**: The basic gist of it is: any user that we have, we go in and we say, sync this motion template folder to the server.
*29:50.320*

**Speaker 2**: So, that whatever's on the server goes here.
*30:00.179*

**Speaker 2**: So, if I go into my room and I create, you know, John's comedy transition pushes.
*30:02.419*

**Speaker 2**: as a theme, and then I make likes left to right, up top to down, you know, easing in and out and things like that and hit save and publish it.
*30:08.460*

**Speaker 2**: Boom, it's on the server.
*30:17.840*

**Speaker 2**: Boom, it's to all the networks, or it's to all the satellite systems.
*30:18.960*

**Speaker 2**: And it's just been working.
*30:22.799*

**Speaker 2**: We've been
*30:24.960*

**Speaker 2**: I mean, we don't even know how it works, really.
*30:26.019*

**Speaker 2**: We just did it, and it works.
*30:27.779*

I think I might call this episode.
*30:32.580*

Folder aliasing terminal thing.
*30:34.060*

**Speaker 2**: Yeah, I mean, you can Google how to sync a folder to a server folder.
*30:36.780*

**Speaker 2**: I mean, that's pretty common out there.
*30:42.780*

**Speaker 2**: There are a lot of
*30:45.580*

**Speaker 2**: Smarter people than me that have created ex explanations for that.
*30:46.800*

**Speaker 2**: But yeah, that's how we do it.
*30:52.480*

**Speaker 2**: And it's, you know, it's reached a point now where I'm so stupid about it.
*30:54.320*

**Speaker 2**: Like.
*30:57.920*

Yeah, you don't have to think about it.
*30:59.740*

It's awesome.
*31:01.100*

**Speaker 2**: I just call the editor in and be like, hey, we got a new Mac.
*31:01.980*

**Speaker 2**: How did you do that thing again?
*31:04.460*

**Speaker 2**: And he types in something and it's good.
*31:05.900*

Oh, so he actually goes into the terminal on the new machine.
*31:08.700*

And said this folder needs to match that folder over there.
*31:13.019*

**Speaker 2**: Basically, and it's I forget.
*31:17.740*

**Speaker 2**: I think even the MacBreak Studio guys made a reference to something like that.
*31:21.260*

So okay, I'm definitely calling this episode folder aliasing terminal thing.
*31:25.440*

**Speaker 2**: Yeah, it's I don't I I wish I could tell you the details of it, but
*31:31.120*

**Speaker 2**: You know, that's not necessarily my specific focus.
*31:35.740*

**Speaker 2**: I'm really good about Googling it and then following the instructions instantly forgetting it.
*31:39.660*

I get it.
*31:44.299*

That's the beauty of Google.
*31:44.780*

We don't have to retain anything.
*31:46.140*

Yep, long-term memory is online.
*31:48.100*

**Speaker 2**: Right.
*31:51.380*

**Speaker 2**: So yeah, and that works great though.
*31:52.980*

**Speaker 2**: I mean
*31:54.899*

**Speaker 2**: it's really awesome.
*31:56.559*

**Speaker 2**: And that fits in with our whole thing of if you buy a plug in, if you update your final cut, it's
*31:58.080*

**Speaker 2**: It's, you know, you got to go back to the original plug-in manufacturer and get the update.
*32:08.060*

**Speaker 2**: Are they even in business anymore?
*32:13.260*

**Speaker 2**: Maybe, maybe not.
*32:14.940*

**Speaker 2**: Or maybe you're using
*32:16.060*

**Speaker 2**: You know, FX factory, which is great.
*32:18.400*

**Speaker 2**: A lot of people love it.
*32:21.120*

**Speaker 2**: But again, um yeah.
*32:22.720*

**Speaker 2**: I've seen people have problems because an applic like a plugin didn't update.
*32:27.700*

**Speaker 2**: And some of the guys at FX Factory busted my butt about this too.
*32:31.700*

**Speaker 2**: They make great stuff.
*32:35.940*

**Speaker 2**: Like I've always said, if you were independent or generally standalone and you don't have a big network
*32:37.540*

**Speaker 2**: You should totally go with them because they have so many awesome things that are really affordable.
*32:43.040*

Well, the beauty of what Nicholas does at FX Factory is he's really built this ecosystem.
*32:47.760*

He is the app store for plugins now.
*32:53.440*

And I'm trying to get him on the show.
*32:57.419*

We've been missing each other, but I love the fact that when you log on.
*32:59.659*

I can see one, everything that's available, two, everything I've purchased, three, everything I have installed.
*33:06.220*

You know, and it's just, it's so handy.
*33:13.500*

And then the other thing is,
*33:15.820*

is I don't have to see everything in my browser.
*33:17.160*

I can say, yeah, I never want to see that thing again.
*33:20.360*

And I hit a little checkbox, and then it doesn't show up in my browser and clutter my browser with a bunch of stuff that I don't need.
*33:22.920*

**Speaker 2**: Right.
*33:29.380*

**Speaker 2**: And that's great.
*33:30.980*

**Speaker 2**: But you're on a network, you got six different computers trying to use the same plugin
*33:32.660*

**Speaker 2**: Oh, did we, you know, is this computer licensed for that?
*33:37.320*

**Speaker 2**: I don't know.
*33:40.600*

**Speaker 2**: We don't even want to deal with it.
*33:41.960*

**Speaker 2**: So we try to keep our final cut as bare bones as possible, unless it's custom-made.
*33:43.400*

**Speaker 2**: And honestly, man, it really works.
*33:48.620*

**Speaker 2**: It works great.
*33:51.900*

**Speaker 2**: I think that's part of why we are able to do all this networking stuff without a whole lot of hassle.
*33:53.100*

Yeah, no, it's clearly working well for you.
*33:59.980*

It's clean.
*34:03.500*

So you had mentioned earlier that when 10.
*34:05.260*

1.
*34:08.700*

2 first came out, you held off for a couple of days, make sure people's machines weren't blown up.
*34:08.940*

What uh as you have upgraded the machines, no problems?
*34:14.420*

**Speaker 2**: Nope, not really.
*34:21.940*

Yeah, I was talking with somebody just the other day and he said, Yeah, I haven't upgraded to it yet.
*34:24.020*

I'm like, what?
*34:28.900*

No, do it.
*34:30.460*

**Speaker 2**: Yeah, it's a solid one.
*34:32.220*

Yeah, it's really solid.
*34:33.819*

And you know, in a discussion I had recently with Alex Golner.
*34:35.260*

He gave me a really interesting little tip.
*34:40.400*

He said, you can tell if Apple perceives a particular upgrade to be a noteworthy one.
*34:42.640*

You know how to do that?
*34:51.040*

How to do that?
*34:52.879*

How do you do that?
*34:53.919*

You go to the help file, you click on Final Cut Pro 10 Help, and the first thing that's going to pop up
*34:54.480*

On the top left side, what's new in Funnel Cut Pro?
*35:03.779*

And when you click on that, it only has the upgrade numbers of the ones that it really saw as, oh, yeah, this is important.
*35:07.619*

So like 10.
*35:16.040*

01 was important, 10.
*35:17.320*

03 was important, 10.
*35:18.840*

06, 10.
*35:20.360*

1, and now 10.
*35:21.720*

1.
*35:22.760*

2.
*35:23.080*

And it's not to say the other ones aren't important.
*35:24.120*

They're obviously fixing little bugs and stuff like that.
*35:25.960*

But the ones that are worth mentioning, they're the ones that are in the little thing.
*35:28.200*

I was like, oh, you clever little guy, you.
*35:33.400*

**Speaker 2**: Yeah, 1.
*35:35.520*

**Speaker 2**: 2, definitely.
*35:36.400*

**Speaker 2**: I would I think somebody tweeted that I said this, but it is definitely the update for shared storage.
*35:37.200*

Oh, absolutely.
*35:43.520*

Absolutely.
*35:44.800*

And more than anything else.
*35:45.599*

I'm really excited to try your system.
*35:47.200*

And I will say that, and I think I started to say this, when I was doing my XML testing.
*35:49.920*

Last week, even over straight gigabit, standard HD footage, you know, H.
*35:56.140*

264 DSLR stuff.
*36:03.180*

I worked all day over it over Gigabit, and it was fine.
*36:07.100*

All the media was stored in another room, Gigabit into the room where I was seated, working on a local library.
*36:12.300*

Worked fine.
*36:19.700*

**Speaker 2**: Well, dude, Gigabit gives you, you know, great, great speeds, and it's honestly good enough for 90% of the people out there.
*36:20.820*

Right.
*36:28.020*

**Speaker 2**: I'm just a little speed freak and I don't know anything new.
*36:28.640*

**Speaker 2**: So, why not go with the 10 gigabit if I can?
*36:32.480*

Absolutely.
*36:36.400*

The link is in my show notes.
*36:37.440*

Definitely.
*36:38.799*

I'm looking at it too.
*36:39.279*

Okay, well that basically covers everything I wanted to talk about.
*36:42.000*

Anything else you want to chat about?
*36:44.480*

Yes, you did mention.
*36:46.480*

Let's talk about that.
*36:49.040*

Introduce the topic.
*36:50.320*

**Speaker 2**: Let me just mention that we are in the process of doing a new set of tutorials for our FCPX on air.
*36:53.140*

**Speaker 2**: Sorry, FCP10 on air.
*37:01.859*

**Speaker 2**: And it's going I want to do it in 4K.
*37:05.480*

**Speaker 2**: I'm getting my GH4 and the mail tomorrow.
*37:08.760*

**Speaker 2**: So I'm totally excited about switching all our cameras to the GH4 and dumping everything else.
*37:12.360*

**Speaker 2**: We're going to shoot, but I want to shoot it in 4K.
*37:18.640*

**Speaker 2**: I mean, why not?
*37:20.640*

**Speaker 2**: I mean, who wouldn't want to see my ugly face in an 8 megapixel per frame?
*37:22.400*

**Speaker 2**: But this GH4 camera, this is the thing I'm so excited about right now.
*37:28.660*

**Speaker 2**: And I think it's supposed to work flawlessly with Final Cut.
*37:32.420*

**Speaker 2**: And I'm very excited to start trying it out.
*37:36.660*

**Speaker 2**: So keep an ear out for us.
*37:39.780*

**Speaker 2**: If you guys follow us at Magic Feather Inc.
*37:42.260*

**Speaker 2**: , I'll post whenever we start releasing some of that stuff.
*37:44.740*

**Speaker 2**: Because I'm going to mention some things like do you use Vimeo, Chris?
*37:48.580*

I do not.
*37:54.480*

I do have a Vimeo account because, you know, I want to be one of the cool kids, but I think I have three videos on it.
*37:55.200*

And it was funny, a couple of weeks ago, I logged on to it.
*38:00.240*

And there was some guy left me a message like three months ago.
*38:07.599*

I was like, oh, I really don't look at this enough to use this as a communication tool.
*38:10.240*

**Speaker 2**: Vimeo is not
*38:16.720*

**Speaker 2**: We're not using it for what you're probably thinking.
*38:19.220*

**Speaker 2**: One of the things that we run into is we post, I don't know, 50 to 100 versions a week on to our
*38:22.420*

**Speaker 2**: websites and stuff like that for clients to review.
*38:29.960*

**Speaker 2**: So having an easy way for clients to review things that takes less effort on our part to actually create the review, that's difficult.
*38:32.840*

**Speaker 2**: That's a challenge for us.
*38:43.839*

**Speaker 2**: We've experimented with back in the day, we used to use it using we used to use iWeb, and we would crank out it at QuickTime and post it in there.
*38:45.440*

**Speaker 2**: Man, we're a lot more busy than we were back then.
*38:54.960*

**Speaker 2**: So now what then we started doing through WordPress, where we would create a website in WordPress, like a post, and then we would upload the Vimeo directly from Final
Cut.
*38:57.520*

**Speaker 2**: And then get the link from Vimeo, paste it on the web page, and we're off to the races.
*39:08.360*

**Speaker 2**: But now we found a trick that I don't think even Vimeo
*39:15.640*

**Speaker 2**: Necessarily wants people to do, but I asked them about it and they said that they didn't have any problems with it.
*39:21.099*

**Speaker 2**: We figured out a way to create, they have these things called portfolios.
*39:27.579*

**Speaker 2**: And any user that has a website address can point their website to a specific portfolio.
*39:33.500*

**Speaker 2**: You would just call it like
*39:40.619*

**Speaker 2**: portfolio.
*39:42.020*

**Speaker 2**: fcpxgrill.
*39:44.180*

**Speaker 2**: com, and then the Vimeo portfolio that you've created goes to that.
*39:45.859*

**Speaker 2**: You have to change some A records and CNAME records in your uh control panel from your web host.
*39:51.060*

**Speaker 2**: But it's a real quick process, and I want to show how to do this.
*39:56.780*

**Speaker 2**: But what some smart guy I saw as a post on Vimeo about this topic, not from a Vimeo forum member, but from like a user.
*40:00.220*

**Speaker 2**: If you instead of creating the portfolio.
*40:10.900*

**Speaker 2**: fcpx.
*40:13.860*

**Speaker 2**: grillcename, if you create an asterisk.
*40:14.980*

**Speaker 2**: fcpxgrill.
*40:19.380*

**Speaker 2**: cname
*40:20.820*

**Speaker 2**: It allows you to create multiple portfolios.
*40:21.920*

**Speaker 2**: The asterisk is interpreted as a wildcard for any web browser.
*40:25.360*

**Speaker 2**: So if you have Vimeo, you can make a hundred different portfolios and you can name it anything you want, like TNT.
*40:31.120*

**Speaker 2**: legacy.
*40:40.960*

**Speaker 2**: dot magicfeather.
*40:43.579*

**Speaker 2**: com or whatever, you know what I mean?
*40:45.260*

**Speaker 2**: And that goes to or you could do V1, then you could do V2 for the second round of stuff.
*40:46.780*

**Speaker 2**: This is not sounding cool when I'm explaining it to you right here.
*40:53.260*

**Speaker 2**: But what's really cool about it is that our clients now get direct access to our spots.
*40:57.320*

**Speaker 2**: They get this custom created web page as a portfolio that you build right inside of the Vimeo.
*41:04.120*

**Speaker 2**: program, and Final Cut uploads it directly to Vimeo.
*41:09.320*

**Speaker 2**: So you're doing all this in Vimeo, and there's no jumping to WordPress or jumping to IPO.
*41:12.920*

**Speaker 2**: And you still get to password protect it.
*41:18.360*

**Speaker 2**: You can, yes.
*41:20.640*

Right.
*41:21.920*

**Speaker 2**: That's really good.
*41:22.640*

**Speaker 2**: So, yeah, that's a trick that we were doing, and that's one thing I want to show off because a lot of people want to figure out how to do that, and it's not been very clear.
*41:23.359*

Now how does this work?
*41:31.640*

Vimeo just recently changed their terms and services within in regards to music.
*41:33.240*

How does this work with Vimeo sniffing files for copywritten music?
*41:38.599*

**Speaker 2**: They haven't come at us for anything.
*41:44.120*

**Speaker 2**: But we keep our account private.
*41:46.200*

**Speaker 2**: We're not a public Vimeo account.
*41:48.040*

**Speaker 2**: We have Vimeo Pro as well.
*41:49.960*

**Speaker 2**: Exactly.
*41:51.640*

**Speaker 2**: So I don't know if that
*41:52.120*

**Speaker 2**: Shields us a little bit more.
*41:53.799*

**Speaker 2**: But yeah, that's what we do.
*41:55.160*

**Speaker 2**: And I mean, I even shared this with Vimeo, like some of our spots, when I was because I wanted to get their feedback, because there were certain things that I wanted to
*41:57.000*

**Speaker 2**: have them make changeable.
*42:07.000*

**Speaker 2**: And so far they're resisting, but if I give them enough heat from it, I think they probably will.
*42:09.080*

**Speaker 2**: So yeah, that's a really cool thing, and because Vimeo ties in so easily with Final Cut.
*42:15.840*

Yeah.
*42:22.740*

**Speaker 2**: That's why this is relevant.
*42:23.300*

I was just training a producer the other day, and he was saying that his preference is to upload straight to YouTube or Vimeo, and he was like totally new to 10.
*42:24.660*

And I said, well.
*42:33.540*

Let me show you what you can do.
*42:34.940*

You know, share to, and he's like, oh, cool.
*42:36.700*

And I said, no, no, I personally wouldn't do that, but that is there if you want to deal with that.
*42:41.260*

**Speaker 2**: Let me tell you, we use the hell out of that.
*42:46.520*

**Speaker 2**: We really do.
*42:49.000*

And you've never had issues where what got exported wasn't what you expected to be?
*42:49.960*

**Speaker 2**: No, no, we we test everything, obviously, before we send a client.
*42:55.080*

**Speaker 2**: Now there are occasions where Vimeo just converts slow as molasses, you know.
*42:59.160*

**Speaker 2**: And that's
*43:05.640*

**Speaker 2**: Fortunately, a very rare experience these days.
*43:07.400*

**Speaker 2**: But yeah, it's good enough to use for movie studios.
*43:10.360*

**Speaker 2**: So we've been happy with it.
*43:14.280*

Yeah, my workflow is to always export a full full res file because from that file I can make
*43:16.400*

And often do any number of export files.
*43:24.400*

**Speaker 2**: Well, here's the thing though, dude.
*43:29.280*

**Speaker 2**: If you do this to Vimeo, Vimeo gives you four download options.
*43:31.040*

**Speaker 2**: An SD version, 720, 1080, and the original.
*43:34.920*

**Speaker 2**: mov file.
*43:41.160*

**Speaker 2**: The smaller versions are all MP4s.
*43:42.920*

**Speaker 2**: But the original MOV file is directly what you output from Final Cut to Vimeo.
*43:45.400*

**Speaker 2**: And it's a little download button right next to the video.
*43:51.160*

**Speaker 2**: My clients love that.
*43:53.400*

**Speaker 2**: So that's.
*43:55.480*

**Speaker 2**: Because then they can have an archive on their computer locally.
*43:57.160*

Yeah, but that's a compressed file.
*44:00.280*

**Speaker 2**: I mean, it's compressed, come out of FileCloud.
*44:03.000*

Right, right, right.
*44:05.080*

**Speaker 2**: Unless you're exporting ProRes, in which case, why would you do that for a rough cut?
*44:06.720*

**Speaker 2**: These are really good quality files.
*44:10.560*

**Speaker 2**: No, no, no, no.
*44:12.960*

I understand that, but what I'm saying is quite often I have to.
*44:14.480*

Do, you know, MP4s, WMVs, sometimes even FLVs, you know, for various.
*44:18.900*

Yeah, no, it's just the world I live in.
*44:25.060*

**Speaker 2**: No, when we have we get the once in a blue moon, you get some somebody's grandma that wants a WMV of a file.
*44:27.520*

Oh, I do a hundred WMVs a week.
*44:33.520*

It's terrible.
*44:37.580*

No, seriously.
*44:38.220*

So you're dealing with broadcast television.
*44:38.860*

I'm dealing with corporate America.
*44:40.620*

And they're all sitting there using their.
*44:42.140*

you know, six-year-old PCs running one of our clients just recently, literally, just recently, like in the last six months, upgraded
*44:44.540*

From Microsoft Office 2003.
*44:54.900*

**Speaker 2**: Wow.
*44:59.860*

Yeah.
*45:00.740*

**Speaker 2**: So here's a question.
*45:01.380*

**Speaker 2**: What do you use to make your WMVs?
*45:02.980*

I think we discussed this last time.
*45:06.400*

We use Flip for Mac in QuickTime 7.
*45:08.480*

**Speaker 2**: You know in the App Store there are about a hundred little apps.
*45:11.840*

**Speaker 2**: You just drag literally, dude, you just drag your exported QuickTime into it.
*45:15.760*

**Speaker 2**: it poops out of WMZ, you go on about your life.
*45:20.440*

**Speaker 2**: 'Cause I used to deal with that any video stuff or flip for Mac stuff too.
*45:24.280*

**Speaker 2**: Again, it's one of those things that's outside the app store.
*45:29.539*

**Speaker 2**: What a pain in the butt.
*45:32.819*

Yeah.
*45:34.099*

**Speaker 2**: And you have to remember your code and all this stuff.
*45:34.420*

Right, right.
*45:36.500*

Forget all about that.
*45:37.059*

Well, let me give you this as a pointer.
*45:37.779*

And I don't know what these apps do, but I will tell you.
*45:39.619*

That if you're taking, say, a 1920 by 1080 and you've been asked to make a 640 by 360, okay?
*45:43.020*

And right now, I'm only talking about the QuickTime seven slash flip for Mac workflow, which I've never seen.
*45:52.600*

**Speaker 2**: We don't even install QuickTime 7 anymore.
*45:59.240*

Understood.
*46:01.240*

I do.
*46:02.120*

I do.
*46:02.840*

But if you're trying to compress from 1920, 1080 down to 640 by 360 and make a W and V at the same time, it's not going to look good.
*46:03.820*

It's not going to look good.
*46:12.820*

And the reason for that that we have found is that the WMV codec doesn't, or at least the QuickTime 7 Flip for Mac workflow, doesn't like scaling
*46:14.740*

and compressing in one pass.
*46:26.420*

**Speaker 2**: Yeah, we don't have any of those issues.
*46:29.780*

**Speaker 2**: I mean, it it just we drag it into the thing, you tell it what size you want, and
*46:32.820*

**Speaker 2**: And it just cranks it out.
*46:36.940*

**Speaker 2**: Let me see if I can tell you exactly.
*46:38.380*

I would love to know the one you're using.
*46:40.780*

**Speaker 2**: Let me.
*46:44.700*

What did you say?
*46:45.339*

There's about a hundred.
*46:45.900*

There's about a hundred of them.
*46:46.940*

**Speaker 2**: Yeah, but I think that it's let's see.
*46:49.740*

**Speaker 2**: Let's go to purchases.
*46:53.980*

**Speaker 2**: It's a pretty useful thing.
*46:57.820*

Oh no, I would love a better way of doing it, especially if it's more modern and takes advantage of more cores, et cetera, et cetera.
*46:59.580*

Because they are a pain to make.
*47:08.460*

And they're slow because it is using QuickTime seven.
*47:10.700*

**Speaker 2**: Standby.
*47:15.900*

**Speaker 2**: Any video converter HD?
*47:16.780*

Any video converter HD from the App Store.
*47:20.240*

Okay, I will look at that one.
*47:27.040*

**Speaker 2**: Yeah, I mean, I think that's
*47:28.480*

**Speaker 2**: Let's see.
*47:30.940*

**Speaker 2**: How much is that that, like five bucks?
*47:31.660*

**Speaker 2**: There's a free version, I believe.
*47:36.619*

**Speaker 2**: Well, now I can't see what the price is because I'm installing it.
*47:41.620*

There's a way to do it in the far right hand.
*47:44.340*

It's six bucks.
*47:47.220*

**Speaker 2**: Yeah.
*47:49.980*

And in the far right-hand corner, even if you've installed it, it has anything.
*47:50.700*

Okay, so any video converter, any video being one word.
*47:58.700*

Yeah, it it is not intuitively obvious to the casual observer that that does WMV as well.
*48:03.520*

**Speaker 2**: It's because you pick, I believe, the computer.
*48:09.599*

**Speaker 2**: Let me open it up.
*48:12.720*

**Speaker 2**: Now that I've installed it.
*48:14.100*

Hey, I'm just buying it.
*48:15.380*

I trust you.
*48:16.900*

**Speaker 2**: I believe it.
*48:19.060*

**Speaker 2**: We've designed we've picked up a bunch of these.
*48:19.700*

**Speaker 2**: So I think if you choose Xbox, the Xbox is WMV.
*48:22.580*

**Speaker 2**: And you can pick you can pick 480p, 720, or 1080p.
*48:27.640*

**Speaker 2**: And then when you just drag your file in and
*48:33.400*

But it's only those sizes, correct?
*48:36.720*

You can't.
*48:39.680*

Is there a custom size?
*48:40.480*

**Speaker 2**: I'm not sure.
*48:43.280*

**Speaker 2**: You know, it's another one of those things, Chris, where I'm sort of.
*48:44.080*

**Speaker 2**: The guys make it work.
*48:48.760*

I don't have time to deal with your little problems.
*48:50.200*

I am the mastermind here.
*48:52.839*

No, and I say that because, again,
*48:54.760*

And this is just a frustrating thing.
*48:59.800*

And I'm sure other people will agree with me.
*49:01.640*

I cannot tell you how many times
*49:05.960*

For corporation X on web page Y, they ask for video file Z and some web designer
*49:07.920*

Has taken an arbitrarily drawn a rectangle and said, I want the video to play in that hole.
*49:18.720*

Right.
*49:24.880*

And they don't bother asking us, you know, well, you know, 64360 is a standard size.
*49:25.520*

128720 or any number of sizes.
*49:30.580*

They just go, No, I want it that size.
*49:33.620*

And I get these numbers and I'm like, What are you kidding me?
*49:35.860*

Oh, no, I want the video to play at that size.
*49:39.220*

Okay.
*49:42.500*

That's what we'll do then.
*49:44.440*

And it's you know, there's there's amazing hoops you pull you'd have to jump through sometimes to get exactly what somebody has asked for.
*49:46.120*

**Speaker 2**: Yeah, man, this creates PAL versions, XVID versions.
*49:54.260*

It looks like you can create your own preset names, too.
*50:00.260*

**Speaker 2**: 640 by 360 for
*50:03.780*

**Speaker 2**: three GP.
*50:06.540*

**Speaker 2**: I mean, what is that, a mobile format?
*50:07.420*

Yes, it is.
*50:09.980*

**Speaker 2**: Yeah, I mean PlayStation versions, iPod versions, Apple T V, like
*50:11.180*

**Speaker 2**: You pick the destination type and just go for it.
*50:15.040*

I don't know what they're giving you as a kickback, but they j you just got my money.
*50:18.640*

I just hit buy.
*50:21.840*

**Speaker 2**: I dude, you know what?
*50:23.220*

**Speaker 2**: That's the worst part about all this.
*50:24.420*

**Speaker 2**: Is I'm not getting kicked back crap
*50:26.900*

**Speaker 2**: I should be getting some some serious payola for all my blabber.
*50:31.040*

Oh, it's fine.
*50:35.440*

You're doing a good thing for the community.
*50:36.640*

So John, let me ask you one last question, then I'm going to let you go.
*50:39.240*

Okay.
*50:43.960*

If you had the ability to sneak into Apple and you found the cubicles where all the programmers were.
*50:45.560*

working on Final Cut X, and you could get them to build you one feature regardless of what marketing or the suits, if you will.
*50:52.000*

Not that anybody wears a suit at Apple.
*51:01.600*

what would the feature you asked them to build be?
*51:04.480*

And I will also throw out the caveat because so many people have said, I want to be able to customize the user interface.
*51:08.960*

We all know that people want that.
*51:14.720*

So that's the one that I'm going to do.
*51:17.260*

**Speaker 2**: Yes, window layouts, obviously, that's if that's already covered in that.
*51:18.859*

**Speaker 2**: I would like to be able to minimize the primary storyline.
*51:23.900*

Yes.
*51:29.420*

Gotcha.
*51:31.660*

**Speaker 2**: For those instances where I just want it to be tiny and everything else can be big.
*51:32.300*

**Speaker 2**: I don't want it to go away.
*51:35.740*

**Speaker 2**: I'm happy with magnetism, but occasionally.
*51:36.940*

**Speaker 2**: It's nice.
*51:39.240*

**Speaker 2**: You know, w when we're playing with loo things loosely, I like to stay out.
*51:40.360*

**Speaker 2**: So if I could just, you know, quickly minimize it, not make it go away, but just make it tinier than the rest.
*51:43.960*

**Speaker 2**: that would be cool.
*51:50.440*

**Speaker 2**: Yeah, and that would be I just think it would be cool to be able to, you know, make that less big, especially if you're working with just gap clips in the bottom or inside of
the primary and then just play around.
*51:51.320*

**Speaker 2**: I mean, that's
*52:01.960*

**Speaker 2**: But dude, that's such a nominal request.
*52:02.760*

**Speaker 2**: It's not even a big deal.
*52:05.080*

**Speaker 2**: Oh, but Chris, did you see that thirty four inch monitor that I posted?
*52:07.240*

**Speaker 2**: I did see.
*52:11.359*

**Speaker 2**: That 4K on a hundred.
*52:11.920*

You like that, don't you?
*52:12.960*

**Speaker 2**: Oh my god, it's beautiful.
*52:14.000*

**Speaker 2**: It is the most beautiful thing I've ever seen.
*52:15.599*

It's the LG, something rather.
*52:17.520*

I think.
*52:20.099*

**Speaker 2**: Yeah, I forget.
*52:20.740*

**Speaker 2**: It's the LG34 UMP.
*52:21.460*

**Speaker 2**: It's a Thunderbolt 2 monitor.
*52:24.180*

**Speaker 2**: It's pretty much.
*52:26.180*

**Speaker 2**: Amazing.
*52:29.940*

**Speaker 2**: I mean, it's 60 hertz, so you're going to get great frame rates on this gigantic thing.
*52:30.740*

**Speaker 2**: The resolution
*52:37.540*

**Speaker 2**: We got two because we have two Mac Pros.
*52:40.880*

**Speaker 2**: It was the only two we could have.
*52:42.640*

**Speaker 2**: Whenever the next Mac MacBook Pro comes out and it's capable of working with this, I'm probably going to switch my system to that because I love this monitor.
*52:44.799*

**Speaker 2**: It is
*52:53.599*

**Speaker 2**: Just, I mean, it should have an Apple logo on it.
*52:55.140*

You know, it's it well, that's a huge statement.
*52:59.300*

And I gotta say that by and large, I look at stuff like that and I go, uh, just gimmick.
*53:02.580*

But then when I saw you saying how great it was, I was like, okay, here's somebody I respect.
*53:07.240*

Okay, maybe I got to take another look at this.
*53:12.520*

But I haven't I haven't seen one in real life.
*53:14.520*

**Speaker 2**: Well, man, you can have Inspector open, Event and Viewer Browser like viewer windows both open.
*53:17.000*

Dude, I'm a huge proponent of screen real estate.
*53:23.800*

**Speaker 2**: the roll list, your your generator tab to the right, like color correction, waveform, like all this stuff can be opened at the same time and it still looks great.
*53:27.580*

Yeah.
*53:37.660*

**Speaker 2**: The guys love it.
*53:38.140*

**Speaker 2**: And
*53:39.340*

**Speaker 2**: Now they can check their Facebook like ten times more efficiently than they could before.
*53:39.920*

**Speaker 2**: Well, that's important.
*53:46.640*

**Speaker 2**: Which was the real goal.
*53:47.520*

**Speaker 2**: Yeah, well, that's important.
*53:48.720*

**Speaker 2**: Netflix looks amazing on it, from I've been told.
*53:50.720*

**Speaker 2**: Cool.
*53:53.440*

**Speaker 2**: But yeah, no, it's that's a great thing.
*53:54.720*

**Speaker 2**: There let's see, what else would I like to share with you before we split?
*53:57.119*

**Speaker 2**: Yeah, anybody that's listening at this point is exhausted, so we should spare them.
*54:03.220*

Yeah.
*54:07.540*

Someday we will talk about I want to I do want to talk and we're out of time here, but someday we really should talk about
*54:08.099*

just the changing landscape of the freelance editor pool when you have so many more people with access to a tool that we use the way we use it.
*54:15.920*

I think that's a big a big a big big head discussion to have someday.
*54:25.420*

**Speaker 2**: Well, I think more than that
*54:31.500*

**Speaker 2**: I think you've got a whole new generation of non-editor or editing non-editors coming up that are kids in high school working with iMovie, and they're going to easily
transition to Final Cut.
*54:34.120*

**Speaker 2**: So, this next generation is going to be like Premiere, uh, Avid.
*54:45.640*

**Speaker 2**: Well, I don't want to do that either.
*54:52.359*

**Speaker 2**: Can I just use this thing that I know?
*54:53.880*

Right.
*54:56.119*

**Speaker 2**: And that's I've always felt like
*54:56.680*

**Speaker 2**: Like Apple should be selling more to people like me and not so much the editors because the editors are going to want to stick with the tools that they know because
they're experts at it.
*54:59.340*

**Speaker 2**: And the people like me are going to be like, but what if we did this and are a little more willing to, you know
*55:11.099*

**Speaker 2**: Turn over the table and spill everything on the floor and pick up the pieces and take a risk on it.
*55:20.160*

**Speaker 2**: And I think that's a good focus for all of us who want to proselytize the
*55:24.720*

**Speaker 2**: The Final Cut 10 experience.
*55:31.520*

Very cool.
*55:33.920*

**Speaker 2**: We can have a bigger conversation about that later.
*55:34.560*

**Speaker 2**: All right.
*55:36.400*

**Speaker 2**: All right, man.
*55:36.800*

Thanks for your time, John.
*55:37.599*

We will be in touch.
*55:39.280*

**Speaker 2**: Thank you.
*55:41.580*

**Speaker 2**: You've been great.
*55:42.220*

**Speaker 2**: All right, man.
*55:42.700*

**Speaker 2**: Take care.
*55:43.100*

**Speaker 2**: Take care.
*55:43.660*

All right, so you know, after the interview with John, the first thing I did is I stood up from the desk I was at.
*55:45.260*

I went downstairs here at Slice where I work.
*55:50.220*

And I had trimmed.
*55:53.960*

I think I talked about it.
*55:56.119*

No, I think I talked about it after the show, but I had taken one of my libraries
*55:57.319*

And I had repointed the media cache to my media folder, and the cache sorry, the media to my media folder, and my cache to a folder inside my media fo
*56:01.620*

Folder than I called cash
*56:14.020*

And after a few minutes of copying stuff over, all of a sudden my twenty one gigabyte file was down to 150 megabytes.
*56:15.520*

I went downstairs, and again, I just have gigabit Ethernet here
*56:22.880*

And so I go downstairs to another edit suite, I copy that 150 megabyte file, which is nothing, just copy to the desktop of the machine I'm at, double-click on it, boom,
finds all my media.
*56:26.660*

Now, I have in the past, either on Twitter or maybe on the show, complained that um the relinking in Final Cut 10 would be better if
*56:37.640*

Everything was a relative position as opposed to an absolute position when it comes to keeping track of where files are.
*56:48.820*

Now, if you don't know what relative and absolute position are, ask one of your web developer friends.
*56:55.540*

But I will say that in this position, in this instance rather, the absolute position of files helps because when I copy that library over, it searches the network for
that drive, and boom, it finds all the files immediately.
*57:01.240*

And then I played through an eight-minute piece and it played great.
*57:15.540*

So, and again, that's just Gigabit Ethernet.
*57:19.460*

That is H.
*57:22.660*

264 Media.
*57:23.380*

It's DSLR footage that we don't transcode because we just don't do that here.
*57:25.300*

So anyway, thank you, John, for that little tidbit of information.
*57:29.520*

I hope that helps you.
*57:34.320*

It certainly is going to help me in my workflow.
*57:35.680*

And again, I love doing this show because of the insanely smart people that I get to talk to.
*57:38.620*

That's it for this episode.
*57:45.100*

We'll be back Friday with another show.
*57:46.220*

Also, this week, we have the return of Digital Cinema Cafe on Wednesday.
*57:48.460*

Make sure you check that episode out.
*57:52.800*

It's awesome.
*57:54.640*

It's with Brett Kulp from Legends of the Night or WeAreBatman.
*57:55.520*

com.
*58:00.400*

So, if you have not listened to Digital Cinema Cafe, go check that episode out.
*58:00.960*

It's going to be Wednesday morning.
*58:04.960*

A great show.
*58:06.960*

So, that's it for this episode.
*58:08.320*

I will see you on this show on Friday.
*58:10.080*

Later, later.
*58:12.800*
