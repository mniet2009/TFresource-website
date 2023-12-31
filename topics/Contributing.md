---
title: 'Contributing'
categories:
  - About
---

::: tip Welcome CONTRIBUTORS!
Thanks for reviewing and contributing content!  This site wouldn't exist without volunteers like you.

Remember to refer to the [Style Guide](Style_Guide).

Thank you!!!
:::

::: tip Reminder for committee reviewers:
Be sure to **REMOVE the 'Needs Review'** category line from the top of a page -- after you have verified it and made any necessary updates! :-)
::::

This website serves as a community resource for travel forecasting research and practice. We welcome your participation!

This community is comprised of [volunteers](Community), many of whom are affiliated with the Transportation Research Board's Standing Committee (AEP50) on Transportation Demand Forecasting's Subcommittee for Travel Forecasting Resources.

## Getting started

TF Resource is a collection of pages written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) plain-text format, stored on Github.com. Github uses a "pull request" workflow, which means that **you don't need anyone's permission** to suggest whatever changes you see fit! Rather, you make changes to your own copy of a page, and then you request that those changes be pulled into the site by our team of volunteers.

This removes the need for complicated permissions management or gatekeeping on the site, while still allowing the TFResource editors to prevent spam or incomplete/incorrect changes. After review, TFResource volunteers may then either approve/merge the edits or suggest additional changes.

#### Should I edit directly on the Github website?

Small changes can be made directly on Github using the _Edit this Page_ link at the top of every page.

For larger changes, we recommend following the detailed [setup instructions](Contributing-Dev-Instructions) to create a local copy of the site on your own computer. Then, you can iterate and verify changes locally on that copy before you request that they be published.

This will reduce the number of "round trips" while saving and publishing -- which will save you a lot of time.

## Step 0: Login to GitHub

If you don't have a GitHub account, you'll need to [create one](https://github.com/signup).
Then, [Login to GitHub](https://github.com/login)

## Step 1: Create a GitHub issue for your desired change

1. Navigate to the [tfresource-website Issues](https://github.com/tfresource/tfresource-website/issues) page and click the green **New Issue** button in the upper right.  You will be presented with a few issue templates from which to select; you'll most likely choose "Content Maintenance" or "Topic Request".

2. Please fill out the issue as completely as possible. If discussion with other contributors would be helpful to resolve it, then this is a good place to have that conversation; you can [tag other GitHub users](https://github.blog/2011-03-23-mention-somebody-they-re-notified/) in the issue using **@their_username**.

3. If you intend to resolve the issue yourself, [assign the issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/assigning-issues-and-pull-requests-to-other-github-users) to yourself.

(Side-note: [tfresource-website issue templates](https://github.com/tfresource/tfresource-website/tree/source/.github/ISSUE_TEMPLATE) can be modified, and if none of the existing issue templates are appropriate to your needs, you could still create a blank issue and note that.)

## Step 2a: Editing a page

1. Click the _Edit this Page_ link at the top of any page to create your own copy of the page and start editing.  If this is the first time you are editing, you will be asked to **Fork this repository.** Yes, [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo). That means you are creating your own personal copy of the site, on which you can make whatever changes you wish.

2. You'll be taken to a page with the full text of that page in an editor window. Make changes as you see fit.

   - Page text is in [Markdown format](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), with standard Github-flavored extensions for tables and LaTeX/MathJax equations.

3. You can review your changes in the **Preview Changes** tab, but be warned that some content such as math equations and complex tables may not preview correctly. We wish we knew how to fix this! If you are doing lots of editing, you might want to [build locally](Contributing-Dev-Instructions) instead of using the web editor to get around this limitation.

4. When you are happy with your edits, save the file using the **Propose file change** button. Include a short description of your changes and reference your issue number from *Step 1* by including **#issuenumber** in your commit message.

5. GitHub will take you to a confirmation page which shows a "diff" of the lines you changed. If everything looks good, click **Create Pull Request**.  

   * Make sure your request is into the **source** branch.
   * This will require you to include a message about your pull request as well; you should also reference your issue number from *Step 1* here by including the text **fixes #issuenumber** for your issue.
   * If you notice something amiss with your changes after your pull request has been created, don't worry!  You can commit additional changes to your fork and they'll automatically get added to your pull request.

6. Someone at TFResource will review your changes and either approve, reject, or suggest further edits to your submission.

## Step 2b: Creating a new page

1. To create a new page, you need to fork the content into a local copy on your hard drive as explained [here](Contributing-Dev-Instructions).

   * All pages must be stored in the `topics` subfolder of the site. Pages must be in Markdown format and must include a yaml header with the page title and any categories you want the page to be part of.
   * Please name the file without any spaces or other non-alphanumeric characters.
   *  It is probably easiest to make a copy of an existing page, and start from that, instead of trying to create a blank page with the proper formatting from scratch.
   * Again, please refer to our [Style Guide](Style_Guide) as you develop new content.

2. Commit your changes, referencing your issue number in your commit message by including the text **#issuenumber**.

3. Push your changes to your GitHub fork (e.g. your_username/tfresource-website)

4. Create a Pull Request from your fork into [tfresource/tfresource-website](https://github.com/tfresource/tfresource-website) by navigating to your fork on GitHub, going to **Pull requests** and clicking **New Pull Request**.  

   * Make sure your request is into the **source** branch.
   * This will require you to include a message about your pull request as well; you should also reference your issue number from *Step 1* here by including the text **fixes #issuenumber** for your issue.

## Syle (how to with style)

Please review and refer to our [Style Guide](Style_Guide) in editing and developing new content to ensure your contribution conforms to our common tone and guidelines so that over time the site continues to provide a uniform voice and organization throughout.  That way we can keep the user experience positive and make the site as helpful as possible for the whole community and AVOID *jarring* and **distracting** changes in style.  


## Uploading files and media

- For now, store all images and other attachments in the `.vuepress/public/topics` folder. We're working on finding a better place for these items.
- After you've forked the repository, navigate on [GitHub](https://github.com/) to the `.vuepress/public/topics` folder in your repository, and click the `Upload Files` button to upload images.
- You can then refer to images using the syntax\
  `[Image description](name_of_my_file.jpg "Optional Tooltip Text")`

## Using categories for organization

- Please use categories!
- Please use categories that already exist! We have too many categories already, and don't need any more.
- Be sure to spell and capitalize all categories correctly to ensure that reviewers accept your changes.

## Governance

Dispute resolution will be handled, if necessary, by the TRB AEP50 Subcommittee on Travel Forecasting Resources ("the committee").

The committee has developed and approved the following policies and procedures.  Any necessary additions or updates will be developed and approved by the same committee. The information on the TFResource is divided into topic areas selected by the committee.  Future topics will be considered as content becomes available and contributions are made to the site.  If a topic you really care about is not currently found, please follow the instructions above and in the [Developer Instructions](Contributing-Dev-Instructions) to submit your contribution.

---
