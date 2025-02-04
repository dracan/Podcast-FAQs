# Purpose Of This Document

We would like to thank you for agreeing to be interviewed for one of our podcasts. In preparation of your appearance on one of our shows, we would like to share this document with you as it provides answers to some of the frequent questions guests ask about being interviewed for one of the [RJJ](https://rjj-software.co.uk)-produced podcasts. Hopefully, this document will provide answers to any questions that you have and provide a little insight into the process of being interviewed for the show.

If you still have questions, please feel free to contact us and ask directly. We will likely ask for permission to include a version of your questions in the next version of this document.

Our thanks go out to [Love Sudo Nimh](https://twitter.com/joseyhowarth) for helping with the formatting and general language used in this document.

## Generic Questions

### Do I Need Any Specific Equipment?

You will need:

- a microphone
- a pair of headphones, earphones, or a form of audio monitor
- a PC, laptop, or similar
- a web browser

In previous years, we have used [SquadCast software-as-a-service platform](https://squadcast.fm/) to facilitate the recording of our podcasts. Whilst we found this service to be more stable than the majority of VoIP products (Skype, Zoom, Hangouts, etc.) we also found that it wasn't as fit for our purposes as we would like. As such, all of the RJJ-produced podcasts are now recorded via Discord using a bot called [Craig](https://craig.chat).

If you do not have a Discord account, we can still arrange recording using a VoIP-based service, but we will prefer to use Discord and Craig where possible.

The reasons we like to use Discord and Craig are numerous, but the two main reasons are:

- the proliferation of Discord throughout the gaming and software development communities
- the ease of use that Craig provides both to our guests and to our editing staff

Craig records audio using the [Opus audio codec](https://en.wikipedia.org/wiki/Opus_(audio_format)) which is rather high quality for very low bandwidth - meaning that it doesn't get in the way of facilitating the conversation, and uses very little bandwidth - and Craig also records each person's audio as a separate track, which is a necessity for the high-quality of editing that [RJJ provide as part of our podcast mastering](https://rjj-software.co.uk/podcasting-services/).

#### Discord Setup

In order to use Discord as a recording system, you will need to join the relevant Discord server for the show you will be guesting on. These details will be sent to you as part of the email exchange that we will have prior to recording.

You will need to have joined the Discord server ahead of the proposed recording date (or the proposed pre-recording discovery call date), and will be invited to join an audio room for the duration of the call.

![](./img/dotnetcore-interview-room.jpg)

*The location of the recording room for [The .NET Core Podcast](https://dotnetcore.show/)*

Once ready to start recording, you will hear an automated voice stating:

> RECORDING

It is vital that you do not navigate to other rooms until the recording has ended, as this will cause Discord to immediately stop recording.

When the recording session has ended, you will hear an automated voice stating:

> STOPPED RECORDING

At this point, it is safe to leave the recording room should you wish.

### What If I Flub/Bungle/Botch What `I Am Saying?

None of the [RJJ](https://rjj-softwar`e.co.uk) produced podcasts are live in any way, and are all edited offline. This means that, should you require more time to make a point or have any trouble saying something, you only have to request another attempt at making it, and our editing team will handle cutting out the previous attempt.

[Jamie](https://twitter.com/podcasterjay), for instance, often says:

> Let me try that again

when he flubs a sentence or falls over his words. The "better" version of the sentence is used in the final cut of the episode, and the same respect will be offered to you.

### Advice for the Best Sounding Recording

tl;dr -> anything that you can hear will be picked up by the microphone; any seat shuffling, desk banging, eating, or other people (or pets) in the room with you. These things can be removed from the final recording, but it will substantially increase editing time. It would normally take around 90 minutes to edit a 30 minute block of audio, with extra background sounds this will increase three to tend fold - so a 30 minute block of audio could take upwards of 900 minutes to edit.

The simple rule of:

> garbage audio in will equal garbage audio out

is worth remembering.

Whilst we will work to the best of our abilities when editing the recording, we ask that you take a few steps to ensure that the recording is of the highest quality possible:

- Ensure that you are in a quiet area
- Ensure that family members and/or roommates know that you are recording and ask them to not interrupt you
- Ensure that all un-necessary applications on your computer are closed or halted
- Please ensure that mobile/cell phones, tablets, and ancillary devices are set to "do not disturb"
- Please ensure that you are not connected to a VPN
  - If you do use a VPN, then the recording may not complete correctly, rendering the discussion useless
- Please check your internet connectivity beforehand
  - We recommend using [fast.com](https://fast.com) as provided by Netflix
- We may ask you to perform a "double ender":
  - This is where we will ask you to record your own audio at your end and send it over after the fact
  - This can be facilitated by installing [Audacity](https://www.audacityteam.org/) or a similar audio recording application
  - We only require your audio, so the use of [Audio Hijack](https://rogueamoeba.com/audiohijack/) (and similar applications) is not recommended
  - Once completed, we will require you to send us the recorded audio encoded in FLAC format
    - This can be done by Exporting as FLAC from within Audacity
    - Or installing [ffmpeg](https://www.ffmpeg.org/) and running the following command (assuming that you have already exported as a wave file): `ffmpeg -i input_file.wav exported_flac.flac`
- If possible, please connect to your network via ethernet rather than WiFi
  - This can increase your available bandwidth and data transfer speed, potentially increasing the fidelity of the audio recorded

### How Will You Arrange The Interview?

Typically, we will arrange the interview date and time via email.

We tend to favour finding a date and time which is convenient for the person(s) we are interviewing. As such, it may take a few rounds of emailing in order to pick the most convenient time.

Once the date and time have been confirmed, we will arrange a Discord recording session and send a calendar invite to each person who will be interviewed. The calendar invite will be set for the specific date and time of the proposed recording, and will contain:

- a link to any planning documents
- a link to the relevant Discord server
- a link to this document

The podcast planning document will contain a link to the relevant Discord server, a link to this document, and a summary of the questions, topics, and points that we are aiming to cover in the session. Please see the [Podcast Planning Document](#podcast-planning-document) section for more details.

### How Long Will The Interview Last?

We usually ask that guests block out 90-120 minutes of their schedule for the interview, however most interviews will take less than 90 minutes.

The reason that we ask guests to block out that much time is to ensure that we have time for a sound check and a light chat at the beginning of the session, along with a conversation about when we are planning to release the episode at the end of the session.

The entire session should take no longer than around 60 minutes of your time, and the recorded portion of that should be around 40-60 minutes long.

You are free to take as much time as you may need in order to answer a question. Similarly, if you find that you would like to start over with your answer to a question or a topic, you need only ask.

### Will I Receive a Copy Of The Interview Before It Goes Live?

We will contact you once editing is completed and will offer a pre-live version of the episode. This is so that you can go through it and let us know of any further edits you would like our editing to make (i.e. `please remove the long "um" at 39 minutes`). The majority of "um"s (and similar) will be left in the interview, as it can sound unnatural to remove them all.

We ask that you listen back to the topics and points raised and verify that you have not mentioned something that you are not allowed to (i.e. perhaps you have signed an NDA or know of some industry secrets) - we would prefer to remove any non-public knowledge from our recordings, as we don't want anyone to get into trouble for having appeared on one of the [RJJ](https://rjj-software.co.uk) produced podcasts. This may require you sending the pre-live version of the episode over to legal representatives to ensure that nothing needs to be removed.

We will make a point of announcing that you are answering and raising points as yourself _not_ as a representative of any third party at several points throughout the conversation.

As our release schedule is rather agile in its nature, We would need notes back from you as soon as possible. The lead time in releasing to the public RSS feeds is usually a week or so but can be up to two months, as such we will need at least a few days notice for any requested edits.

### Podcast Planning Document

In advance of the recording session, we will send over a document which will outline the episode we wish to record with you. This document will contain:

- A link to the relevant Discord server
- A link to this document
- A collection of questions, topics, and points that we would like to discuss
- A request for a profile (if required)

This document is collaborative in nature and we ask you to feel free to edit the list of questions, topics, and points, along with anything else in the document ahead of recording. We will use this document whilst recording the episode, as an aid to memory.

## Show Specific Questions

For show specific questions, please see the following list:

- [The .NET Core Podcast FAQ](show-specifics\dotnetcore.md)
- [The Waffling Taylors Podcast FAQ](show-specifics\wafflingtaylors.md)
