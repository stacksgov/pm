# Stacks Governance - Standard Operating Procedures

This document contains recommended best practices for managing various aspects of the Stacks governance initiative.

TODO: INSERT TOC

## Get Involved!

From [Stacks Governance Update #1 - 4 March, 2020](https://github.com/stacksgov/updates/blob/master/updates/20200304-update-001.md):

> Stacks governance is a community-run initiative! As such, it cannot work without your help, and without the input of as many community members as possible. You do not need anyone’s permission to get involved and contribute to the initiative. The #governance working group channel on [Blockstack Discord](https://discordapp.com/invite/ny6wGkx) is a great place to begin getting involved, as many community members regularly share ideas, updates, and resources there. You can also find a number of topics under the [governance category](https://forum.blockstack.org/c/Working-Groups/governance/) on the Blockstack Community Forum which need your input.

## Additional Outlets

More information about the Stacks Foundation and its mission can be found at the links below:

- Website: https://stacks.org
- Twitter: [@StacksOrg](https://twitter.com/StacksOrg)
- Resources: https://stacksgov.github.io/resources
- Project Management: https://stacksgov.github.io/pm

## Governance Working Group Calls

Governance Working Group calls are held every other week, and follow the basic agenda format listed below:

- A quick standup update from each attendee
- Updates from the Stacks Foundation 
- Review of Action Items 
- Review of Discussion Items 
- Review of Miscellaneous Items

The meeting agendas and various topics discussed can be found on GitHub, under the [issues tab](https://github.com/stacksgov/pm/issues) of the `stacksgov/pm` repository. There are labels for each issue based on the agenda categories, and the issues tab can be filtered by each label for review.

- Meeting Agendas: [mtg-agenda](https://github.com/stacksgov/pm/labels/mtg-agenda)
- Stacks Foundation: [mtg-stacksfoundation](https://github.com/stacksgov/pm/labels/mtg-stacksfoundation)
- Action Items: [mtg-action](https://github.com/stacksgov/pm/labels/mtg-action)
- Discussion Items: [mtg-discuss](https://github.com/stacksgov/pm/labels/mtg-discuss)

> **Note:** When using GitHub, the word "issue" also means "topic", "item", or "idea". Issues are used to track individual discussion items, and labels are used to help categorize and group the issues. More information can be found in the [Mastering Issues](https://guides.github.com/features/issues/) guide from GitHub. 

The notes and resources from previous calls are stored in the `stacksgov/resources` repository, and listed in a table on the [Stacks Governance Resources - Calls Page](https://stacksgov.github.io/resources/#/calls/). 

## Governance Working Group Call Procedures 

Below are the steps for setting up, hosting, and following up on a call.

### Preparing for a Call

1. Create a new agenda by opening an issue based on template 
    - ideally this is done right after the last call, to give people enough time to add agenda items for the next meeting
    - example of the issue template on GitHub:
    ![Agenda Issue Template Example](sop-meeting-agenda-example.png)
1. Update the Date/Time to the future meeting date
1. Create an Event Time Announcer link to help with time zone conversions
    - Access the [Event Time Announcer form](https://www.timeanddate.com/worldclock/fixedform.html) from timeanddate.com
    - Name the event, e.g. `Stacks Governance Working Group Call #26`
    - Set the Event Location to `UTC`
    - Enter the Month, Day, Year, Hour, and Duration values based on `UTC`
    - Add a link to the result following the Date/Time in the issue 
    - e.g. in Markdown format: `[time zone conversion](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Stacks+Governance+Working+Group+Call+%2326&iso=20201022T16&ah=1)`
    - example of the announcement after someone clicks on it:
    ![Event Time Announcer Example](sop-timeanddate-example.png)
1. Update the roles, or list TBA if unknown
1. Close the issue from the previous call (instructions below)
    - open the issue from the previous call 
    - add a comment: "Closing in favor of #X" where #X is the issue number of the new agenda
    - click **Close issue** next to the comment button
1. Share the new issue in the `#governance` channel on Discord

Reminders about the governance call and a link to the agenda should be shared in the `#governance` channel on Discord based on the following schedule:
- After the new agenda is created
- One week before the call
- One day before the call
- The day of the call

A sample post is included below, but feel free to modify based on current events and/or tag relevant people based on the issues!

> Reminder that our next governance meeting is scheduled for next Thursday - agenda here: https://github.com/stacksgov/pm/issues/105
>
> In the meantime, please update your issues with any progress you've made!

### Hosting a Call

TODO: add content

### Uploading Call Videos 

TODO: add content

### Publishing Call Updates

TODO: add content, to be done on the Stacks Forum

## Access to Services

TODO: add more details

- GitHub repository
- YouTube account / [channel](https://www.youtube.com/channel/UCirhluDUpSPVMZQn210HETg)
- Zoom Pro meeting room

# Licensing

This repository and all contributions herein are licensed under [Creative Commons Zero v1.0 Universal](https://github.com/stacksgov/pm/blob/master/LICENSE). Please note that, by contributing to this repository, whether via commit, pull request, issue, comment, or in any other fashion, **you are explicitly agreeing that all of your contributions will fall under the same permissive license.**

<!-- notes and previous data

TODO: figure out how to approach in a decentralized fashion ? blocker: calendar invite, zoom link, youtube account

TODO: add second template for "other issues" (blank issue link hard to find?)
    - could do one for action item, discussion item, foundation item, or other ?

IDEA: move updates to the forum, easier for anyone to write based on the call, and can be linked from the call table. good community challenge and could be done by someone watching the recording after.

IDEA: if we had a set default for how calendar entries are sent out and for meeting location (i.e. stacks zoom account with settings ready to go), that would be really helpful.

Juliet: not sure where we are on the grant, historical intro but recap of the last month or two

-----

1. Set up a Zoom invite for the call. First, check if a recurring Zoom invitation has already been set up—if so, you'll see the link in the regular calendar invitation. If it has already been set up, make sure you've been added as a host. If one has not been set up, you'll need to set up a new meeting. You'll need a Zoom Pro account. Jenny or Lane can do this for you. We recommend the following settings:
    - Registration: Not required
    - Meeting ID: Generate Automatically
    - Meeting Password: Require a password
    - Video: All off (by default)
    - Audio: Telephone and Computer Audio
    - Meeting Options: Do not enable join before host, do not enable waiting room
1. Add the Zoom invite link for the call (which should include the meeting password, to allow one-click join) to the regular calendar invitation, if there is one.
1. Do NOT share the link to join the call publicly. Do NOT post it on social media!

### Hosting a Call

1. 24 hours before the call, remind everyone in the working group channel about the upcoming meeting, using the `@everyone` tag. Include a link to the agenda issue. Here's a sample message:

    > Hey @everyone, reminder that our next governance working group call is in 24 hours! Agenda is here, please review it before the call and feel free to propose topics: https://github.com/stacksgov/pm/issues/19. See you all tomorrow!
1. Repeat the same thing an hour before the call.
1. Review the agenda issue and add proposed topics to the agenda.
1. About ten minutes before the call, fire up Zoom and start the meeting. Make sure that the link joins, and that you have host capabilities. Share the Zoom link in the working group chat. (Again, do NOT post the link anywhere public, including on social media.)
1. Wait until 5-10 minutes past the hour, or at least until there is a reasonable quorum, before starting the call.
1. Quickly scan the names of all of the participants in Zoom. Make sure that all of the names are correct, and in particular, that no one's phone number is displayed publicly. As moderator ("host" on Zoom), you can rename a participant if necessary.
1. Notify everyone that you're about to hit record, and remind them that the rest of the call will be public and on the record.
1. Hit Record (you generally want to record to the cloud), and start the meeting!
1. Introduce yourself and explain that you'll be moderating the call. Ask if anyone else would like to introduce themselves to the group.
1. Ask if anyone would like to share a weekly update: what they've been working on, what they'll work on next, and if they have any blockers. Feel free to offer your update first to kick things off. Don't pressure anyone to share an update if they don't opt to on their own.

Some helpful tips for hosting a call:

- Keep an eye on the time. Don't spend more than 5-10 minutes max. on any given topic. If the discussion of a particular topic goes over this amount of time, offer to reserve some time to continue discussing the topic at the end of the call, politely remind everyone that there are other items on the agenda to discuss, and introduce the next topic.
- Let people speak freely, but feel free to cut someone off if they speak for more than a few minutes. Do so politely, and remind them that it's important that we give everyone a chance to share their thoughts. Suggest that, if they have more to say on this topic, they could write up their thoughts and post them to the forum and/or share them in the chat channel.
- Try to keep the conversation focused on the present topic. Slight diversions are of course fine, but if the topic diverges too far from the current agenda item, bring it back on track by gently reminding the group of the question at hand - and offering to return to the new topic later, time-allowing.

### After a Call

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
1. Open a new pull request against `stacksgov/resources` and add the info for the call: notes, link to YouTube recording, and a link to any other resources (e.g., a presentation) shared on the call. Here's a [sample PR](https://github.com/stacksgov/resources/pull/25). You should let another working group member review and approve the PR before merging it. The PR should include:
    - A new notes file in https://github.com/stacksgov/resources/tree/master/calls/notes named `YYYY-MM-DD-Meeting-XXXX.md`
    - An update to the table in https://github.com/stacksgov/resources/blob/master/calls/README.md, adding the new call, with links to the agenda, video recording, and notes

## Regular Updates

The governance working group collaboratively publishes a regular update, approximately once a week, for the broader Blockstack community. You can find previous updates in the [`stacksgov/updates`](https://github.com/stacksgov/updates) repository. Here's how to write such an update.

1. Using the previous update as a template, write the update in markdown format. It should be called `YYYYMMDD-update-XXX.md` and live in https://github.com/stacksgov/updates/tree/master/updates. Make sure the update includes a link to the agenda and notes for the most recent call, as well as a brief update on each of the main initiatives the working group is working on.
1. Save the update into a new branch and open a PR to merge it into the master branch.
1. As part of the same PR, update https://github.com/stacksgov/updates/blob/master/README.md to add a link to the new file.
1. Share the URL for this new PR in the chat channel to give others in the working group a chance to review it, suggest additions/corrections, etc.
1. After giving other members of the working group a few days to review and approve the update, feel free to merge the PR.
1. Announce the new update to the working group.

-->