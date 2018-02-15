## How to Write a Bug Report on Utopian-IO

![HowToWriteBugReports](https://ipfs.io/ipfs/Qmd94531EubrT6MvTZ5GhwmeNHPL2h4N9t52RSd3DjXSTx)

This article is intended to assist those who wish to support Open Source projects by submitting Bug Reports through Utopian-IO which rewards accepted contributions with the Steem cryptocurrency. 

My intention is to help others increase the quality of their submissions, and not necessarily to provide a thorough overview of the rules.  The official rules are updated frequently, and you can always review them **[here](https://utopian.io/rules)**.  Please know and follow them when submitting a Bug Report or you risk having your submission rejected.

This information is based on over 10 years of experience writing, reviewing and prioritizing thousands of bugs as a QA Lead and Producer in the Video Game industry.

## What is a Bug Report?
A Bug Report’s purpose is to inform the Developers of an unintended behavior in their Application.  It should clearly describe the problem that is occurring, provide detailed steps for how to reliably reproduce the issue, and show the bug occurring using Videos, Gifs and/or Images.

## Before Writing a Bug Report
Before you take the time and effort to write a Bug Report, it is recommended that you do a few things first to ensure you are not wasting the Moderator's and your time:

1. **Reproduce the Bug**
   - Verify that you can reliably reproduce the issue.  If the Bug doesn’t always occur, investigate further to see if you can determine the exact steps to follow to reproduce it 100% of the time.  Bugs which a Moderator cannot reproduce at least once using your information will likely be rejected even if you prove it happened with a video or image.
3. **Verify Application Version**
   - Check to see if you’re running the latest version of the Application.  If you aren’t, download the latest version and see if the Bug is still occurring.

4. **Check Project Validity**
	- Determine whether the Project is on GitHub and ensure that the Repository has been updated within a year, is accepting new Issues, contains Code, and has a ReadMe and License.

5. **Search for Duplicates**
   - Search to see if the issue is already logged.  This can be done on GitHub by Searching in the Project’s Issues tab.  To ensure there aren’t any identical issues logged on Utopian-IO which haven’t been accepted and ported to GitHub yet, you can also search there.


## Components of a Bug Report
There are several components which need to be provided for every Bug submitted through Utopian-IO:

### GitHub Project
All accepted Utopian-IO Bugs are copied over to the Application’s GitHub repository where the developers can see it.  In order for this work, it is necessary that you have a GitHub account and that you have Synced it with your Utopian-IO profile.

In order to set the correct Repository for a Bug Report you need to search for and enter the correct Owner and Project in the GitHub Project field.  This is entered in the following format:

    Owner/Project
For Example:
           
![GitHubProject](https://ipfs.io/ipfs/Qmbtt2QXMDnPshqtXmMz5KKtiYb8wRK7DY6MuorWoUZdV5)
      
Often you can search the name of the Application and it will show up when you press ‘Enter’, but sometimes there are multiple projects with the same name or the Project is not named identically to the Application.  If this is the case, you can often find a link to the correct project in the ‘About’ or other similar screen within the Application itself, on the project's website or by searching for it on GitHub.

### Bug Title
The Title of a Bug is one of the most important components for the following reasons:
- It allows developers to quickly know what a Bug is about and to make decisions without having to open and read the whole report.  This can include prioritizing and assigning the issue to a specific person for investigating and fixing.

- It allows other Testers and Moderators to find the issue when searching for Keywords.  We should always strive to avoid entering Bugs which are already documented, and being able to search for Keywords is critical in this endeavor.

In order to support the Developers, Moderators and Testers, it is necessary that a Bug Title is both as short and descriptive as possible.  

Start by asking yourself what words you would search for if you were going to see if the Bug had already been logged.  These are the Keywords which should appear in your Title.  For example, if you experience a Crash in the Settings Menu when you rotate your phone, these would be your Keywords:
- Crash
- Settings
- Rotate

You would then generate a sentence which describes the issue you are reporting as briefly as possible while using all of those Keywords.  Here is one Title possibility for this Bug:
           
![BugTitle](https://ipfs.io/ipfs/QmeVfJWjbBGWwg4k3Bxf938QUEaQFxCQdiLmB3FczbM7ky)

This Title contains all of the Keywords, can be read very quickly and clearly describes the issue that you are reporting.  

You do not need include the name of the Application or use the word 'Bug' in your title because that information is already clarified by the fact that you're posting in the Bug Hunting Category and have entered the Application's GitHub repository. 



### Expected Behavior
The purpose of the Expected Behavior component of a Bug Report is to describe what you believe the intended functionality to be.  Here is an example of what you could write for the Crash Bug we just discussed:

![ExpectedBehavior](https://ipfs.io/ipfs/QmP5WUnCDXjLLceyp6R5aoi7YM5AVov8GB7gvRtemrs7Y5)

Keep this section as brief as possible.  Do not describe the Bug here at all, only the behavior you'd expect if the issue you are reporting was fixed.  

Also, do not refer to yourself in this section by saying things like, "I was trying to rotate the screen and I wanted it to reorient," and do not tell the story of how you found the Bug or why you want it fixed.  Keep it simple and non-personal.

### Actual Behavior

The Actual Behavior component of a Bug Report is where you describe what is happening instead of the Expected Behavior. Here's an example from the Crash Bug:

![ActualBehavior](https://ipfs.io/ipfs/QmdThSqT2zUAZ8w8FJdiAHgcKEFMMJg2cr1bzbV9733b7f)

Just like the Title and Expected Behavior, you want to keep this section as short and descriptive as possible.  Sometimes it is necessary to write more than 1 or 2 sentences, but usually it is not.

### How to Reproduce
The How to Reproduce component of a Bug Report is the most detailed and precise section.  A person who knows nothing about this Application should ideally be able to follow your steps and reproduce the issue 100% of the time.

In order to make this section as readable as possible, it is best to use a Numbered List.  Here is an example using the Crash Bug:

![ReproSteps](https://ipfs.io/ipfs/QmPfYC5i8VmxQGwtCEBGTcPaJ6UKsBdjjKycdPW9e3gmh3)

Note that every single action a User needs to take is listed here.  Most Bugs have between 5 and 10 steps to reproduce, this just happens to be a short example.

### Testing Environment
It is critical that somewhere in your Bug Report you list the Version of the Application and Operating System you are using.  Sometimes bugs are specific to your testing environment, so this information helps others to reproduce and diagnose the problem.

Here is an example of how I like to list this information:

---
    Device: Pixel 2 XL
    OS: Android 8.1.0
    App Version: 1.5.1
---

### Recording of the Bug
This is the section where you provide a Video or GIF showing how to reproduce the Bug.  This shows the Developer the bug occurring without them needing to launch the Application and follow your steps.  Oftentimes this is all they need to diagnose and fix the issue. 

If it's a video, you can upload it to a site like YouTube or DTube and embed or link to it.  If it is a GIF you can upload it by dragging it into the Bug Report window.

Videos and GIFs are important to keep as short as possible to avoid wasting the Moderator's and Developer's time.  Only show your Steps to Reproduce from beginning to end.  Do not provide commentary unrelated to the steps you are following like, "I would like to see this bug fixed," and do not show unnecessary steps.

Here is an example of a GIF I made for the Crash Bug:

![CrashSettingsRotate.gif](https://res.cloudinary.com/hpiynhbhq/image/upload/v1518148964/cnct3ges0dvlthhbnsqc.gif)

### Post Tags
The Tags for your Post are not critical, and you can pretty much add whatever you think is relevant.  I personally like to add the following tags:

- **The Github Owner**
	- This allows the Project Owner to see Bugs and all other Posts related to their Projects if they desire (e.g. *#eskeptor*).
- **The GitHub Project**
  - This allows people to view all Posts related to the GitHub project itself (e.g. *#openpad-for-android*).
- **Utopian-Bugs**
	- I've started using a tag called '*#utopian-bugs*' for all Bug Reports I submit through Utopian.  I see this as a place people can share their Bugs with other testers for feedback or to provide examples of well-written reports that others can learn from.
- **My Steem Account Name**
	- I like to be able to see all Posts I've made through my account using a Tag, so I add '*#thewizardstudio*' to all Bugs I submit.

### Report Submission
When you've filled everything out, Submit your Bug Report and wait for a Moderator to review it.  Check back once and awhile to see if the Moderator has questions or suggestions in the Comment section.

---

### Thank You for Changing the World!
Utopian-IO's goal is to support the creation of Open Source software, and to increase the number of people using these free and open applications around the world.  Maintaining functionality and a smooth user experience is necessary to meet these goals, but issues can't be fixed if the Developer doesn't know about them, which is why Bug Hunters are so important!

For-profit software companies sometimes hire hundreds of people to test one application.  The Open Source world has thousands of projects, with each often containing hundreds of Bugs waiting for you to find. There is so much need and opportunity for you to help and be rewarded for your effort at the same time!

Thank you for joining us in this effort to create a Free and Open World!

**[@cahlen](https://steemit.com/@cahlen)**

![cahlen](https://ipfs.io/ipfs/Qmecmto92DpPHnQ7eKhgfkuGwR1UghLatHkPJ5Hm9C7JEq)

