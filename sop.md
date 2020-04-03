# Stacks Governance Standard Operating Procedures

This document contains recommended best practices for managing various aspects of the Stacks governance initiative.

## Working group

There are a number of working groups in the Blockstack community. Governance is one such group; others include Business Models and Proof of Transfer (PoX). Each working group has a designated sub-category on the [Blockstack Community Forum](https://forum.blockstack.org/): here is the [Working Groups/Governance](https://forum.blockstack.org/c/Working-Groups/governance) category. Each working group also has a designated channel on the [Blockstack Discord server](http://chat.blockstack.org/). Note that, at present, Blockstack PBC is responsible for administering both the Forum and the Discord server.

## Governance calls

Each week, the members of the governance working group meet on a call. These are currently scheduled everyday Wednesday at 10am New York time. The agenda for the next call is posted as a GitHub issue in this repository, and the notes and other resources for previous calls are posted in [the calls subfolder](https://github.com/stacksgov/resources/tree/master/calls) of the `stacksgov/resources` repository.

### How to host a call

Here are the steps you should take to prepare for an upcoming working group call.

### Things you'll need

- Access to the Zoom Pro account used to host the call (or help from the account owner)
- Access to the [Stacks Governance YouTube channel](https://www.youtube.com/channel/UCirhluDUpSPVMZQn210HETg) (or help from someone who has this)

### Preparing for a call

1. Determine who will moderate the call, and who will be responsible for taking notes.
1. Open a [new issue](https://github.com/stacksgov/pm/issues/new) for the call agenda in this repository. This should be done at least a few days before the call to give people the opportunity to propose agenda items. Use the previous call agenda as a template ([full list](https://github.com/stacksgov/pm/issues?q=is%3Aissue+label%3Acall+)), updating the call times in various timezones, assigned call moderator, and agenda items. When updating call times, be especially careful of the times of year—autumn, and spring—when different regions switch timezones at different times, which means that the relative times may change as well. Creating an "Event Time Announcer" on timeanddate.com ([sample](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Stacks+Governance+Working+Group+Call&iso=20200401T10&p1=179&ah=1)) can be very helpful here, as it allows people to easily verify the time in their timezone.
1. Add the "call" label to the issue.
1. Close the issue for the previous call, with the text "Closing in favor of #X" where "X" is the number of the new issue. This will link the two issues and makes navigating among call agendas much easier.
1. Set up a Zoom invite for the call. First, check if a recurring Zoom invitation has already been set up—if so, you'll see the link in the regular calendar invitation. If it has already been set up, make sure you've been added as a host. If one has not been set up, you'll need to set up a new meeting. You'll need a Zoom Pro account. Jenny or Lane can do this for you. We recommend the following settings:
    - Registration: Not required
    - Meeting ID: Generate Automatically
    - Meeting Password: Require a password
    - Video: All off (by default)
    - Audio: Telephone and Computer Audio
    - Meeting Options: Do not enable join before host, do not enable waiting room
1. Add the Zoom invite link for the call (which should include the meeting password, to allow one-click join) to the regular calendar invitation, if there is one.
1. Do NOT share the link to join the call publicly. Do NOT post it on social media!

### Hosting a call

1. 24 hours before the call, remind everyone in the working group channel about the upcoming meeting, using the `@everyone` tag. Include a link to the agenda issue. Here's a sample message:

    > Hey @everyone, reminder that our next governance working group call is in 24 hours! Agenda is here, please review it before the call and feel free to propose topics: https://github.com/stacksgov/pm/issues/19. See you all tomorrow!
1. Repeat the same thing an hour before the call.
1. Review the agenda issue and add proposed topics to the agenda.
1. About ten minutes before the call, fire up Zoom and start the meeting. Make sure that the link joins, and that you have host capabilities. Share the Zoom link in the working group chat. (Again, do NOT post the link anywhere public, including on social media.)
1. Wait until 5-10 minutes past the hour, or at least until there is a reasonable quorum, before starting the call.
1. Notify everyone that you're about to hit record, and remind them that the rest of the call will be public and on the record.
1. Hit Record (you generally want to record to the cloud), and start the meeting!
1. Introduce yourself and explain that you'll be moderating the call. Ask if anyone else would like to introduce themselves to the group.
1. Ask if anyone would like to share a weekly update: what they've been working on, what they'll work on next, and if they have any blockers. Feel free to offer your update first to kick things off. Don't pressure anyone to share an update if they don't opt to on their own.

Some helpful tips for hosting a call:

- Keep an eye on the time. Don't spend more than 5-10 minutes max. on any given topic. If the discussion of a particular topic goes over this amount of time, offer to reserve some time to continue discussing the topic at the end of the call, politely remind everyone that there are other items on the agenda to discuss, and introduce the next topic.
- Let people speak freely, but feel free to cut someone off if they speak for more than a few minutes. Do so politely, and remind them that it's important that we give everyone a chance to share their thoughts. Suggest that, if they have more to say on this topic, they could write up their thoughts and post them to the forum and/or share them in the chat channel.
- Try to keep the conversation focused on the present topic. Slight diversions are of course fine, but if the topic diverges too far from the current agenda item, bring it back on track by gently reminding the group of the question at hand - and offering to return to the new topic later, time-allowing.

### After a call

1. Make a note of issues that you didn't have time to discuss on the call, and make sure they get priority on the agenda for the next call. (You may find it helpful to immediately create the agenda for the next call, as described above.)
1. Log into the Zoom account and download the video recording of the call. This usually takes about an hour to appear, although in rare cases it may take longer. If you don't have access to the Zoom account, ask its owner to send you the video link.
1. Review the video: in particular, the very beginning and end of the video. Make sure that there isn't too much silence or banter in the recording before the actual meeting begins. Trim the video if necessary.
1. Log into the [Stacks Governance YouTube channel](https://www.youtube.com/channel/UCirhluDUpSPVMZQn210HETg) and upload the video of the call. Use this template:
    ```
    Title: Stacks Governance Call #X [YYYY/MM/DD]
    Description:
      Agenda: [link to agenda issue]
      Links shared on call:
        - Link 1
        - Link 2
    ```
1. Grab the YouTube link for the video. Note that you can get the link even before the video has finished processing.
1. Add the YouTube link to the meeting agenda issue description (at the top).
1. Share the YouTube link in the working group.
1. Get the call notes from the note taker.
1. Open a new pull request against `stacksgov/resources` and add the info for the call: notes, link to YouTube recording, and a link to any other resources (e.g., a presentation) shared on the call. Here's a [sample PR](https://github.com/stacksgov/resources/pull/25). You should let another working group member review and approve the PR before merging it.

## Regular updates

The governance working group collaboratively publishes a regular update, approximately once a week, for the broader Blockstack community. You can find previous updates in the [`stacksgov/updates`](https://github.com/stacksgov/updates) repository. Here's how to write such an update.

1. Using the previous update as a template, write the update in markdown format. It should be called `YYYYMMDD-update-XXX.md` and live in https://github.com/stacksgov/updates/tree/master/updates. Make sure the update includes a link to the agenda and notes for the most recent call, as well as a brief update on each of the main initiatives the working group is working on.
1. Save the update into a new branch and open a PR to merge it into the master branch.
1. As part of the same PR, update https://github.com/stacksgov/updates/blob/master/README.md to add a link to the new file.
1. Share the URL for this new PR in the chat channel to give others in the working group a chance to review it, suggest additions/corrections, etc.
1. After giving other members of the working group a few days to review and approve the update, feel free to merge the PR.
1. Announce the new update to the working group.

## GitHub
