---
title: "Urantiapedia — Administrators help"
description: 
published: true
date: 2021-11-28T14:02:03.086Z
tags: help
editor: markdown
dateCreated: 2021-11-28T14:02:03.086Z
---

<figure class="table chapter-navigator">
  <table>
    <tbody>
      <tr>
        <td><a href="/en/help/roles">Collaborator profiles</a></td>
        <td><a href="/en/help">Index</a></td>
        <td><a href="/en/help/github">Chief Editors help</a></td>
      </tr>
    </tbody>
  </table>
</figure>

## About Urantiapedia

[Urantiapedia](https://urantiapedia.org) is a collaborative website based on [Wiki.js](https://js.wiki/) with the purpose of being a unified center for the dissemination of all knowledge regarding *The Urantia Book*.

## About Blue Fields

[Blue Fields](https://blue-fields.netlify.app/) is a website that has been created to join and organize readers of *The Urantia Book* who wish to collaborate in smart, purposeful and altruistic projects all over the world. It is the website that manages register and collaboration between volunteers of *Urantiapedia*.

## About GitHub

[Urantiapedia](https://github.com/JanHerca/urantiapedia) project on GitHub is a project created to serve as a quick start-up procedure for *Urantiapedia*. It contains files in certain formats and software that help automate the creation of initial content.

## Who is this manual for?

This manual is intended for users called *administrators*, or *admins* for short, users who meet the following requirements:
- registered users with an account in [Blue Fields](https://blue-fields.netlify.app/) and in [GitHub](https://github.com/).
- users who have been authorized as project *admins* by the team that leads the project on [Blue Fields](https://blue-fields.netlify.app/) platform.
- registered users with an account on the [Urantiapedia](https://urantiapedia.org). Only another *admin* user can register a user as a new *admin* user.
- users with a good knowledge on the use of Git and GitHub.
- users with good knowledge of *The Urantia Book* in at least one language in which it is published, and preferably with a good level of the English version.
- users that wish to collaborate in a selfless way in the addition of content related to *The Urantia Book* in the *Urantiapedia*.

*Admin* users are the only ones in charge of bulk-uploading changes to the *Urantiapedia* website during each milestone of the project. More about project milestones in [Milestones of the project](/en/help/phases).

## GitHub workflow

The process will be as follows:
1. "Chief Editor" creates a *fork* (a copy in its own account) of *Urantiapedia* project on GitHub (https://github.com/JanHerca/urantiapedia) and *Urantia-backup* project on GitHub (https://github.com/JanHerca/urantiapedia-backup). The first is a project that contains all the files. The second contains only the files that are synchronized with the *Urantiapedia* website.
2. "Chief Editor" creates a local copy of both projects on PC. The local copy must be of the latest version of *Urantiapedia* content (the master branch). This is done first through a *clone* action and later through *pulls* actions to the project, that downloads any change to the local copy.
3. "Chief Editor" makes changes in the local copy to the files indicated in this manual and in the way explained. "Chief Editor" makes commmits to the local copy.
4. "Chief Editor" sends changes to his GitHub account through a *push* action. 
5. "Chief Editor" performs a *pull request* in GitHub web to the original projects. 
6. The *pull requests* of "Chief Editors" are reviewed by "Administrators", who are in charge of doing a *merge* with the main branch (master) of all those changes that are correct. Any changes that are not correct will be rejected and "Chief Editors" will be notified to fix them.
7. When changes that are OK and "Administrator" has done the merge, any changes to the *Urantiapedia-backup* project are automatically synchronized with the website. Now changes are visible to all, in order to check and validate that they are correct.
8. The process is repeated as many times as needed, returning to point 2.

![](/image/github_workflow_version_2.png)

## Setting up the *Urantiapedia* project

Before any work in *Urantiapedia* using GitHub you must set up all the needed tools. Check [Setting up GitHub project](/en/help/github_setting).

## Content of Urantiapedia project at GitHub

To know the content of the GitHub project and its structure, check [Content of GitHub project](/en/help/github_content).

## Tasks

To know about the milestones of the project check [Milestones of Urantiapedia](/en/help/phases).

Once we have the input in the correct folders, for each language, the steps to take in Milestone I are:
1. Translating *Paramony* from English to the target language. Check [Translation of Paramony](/en/help/github_paramony).
2. Translating and reviewing *Topic Index* from English to the target language. Check [Translation an revision of Topic Index](/en/help/github_topicindex).
3. Obtaining a public-domain translation of *The Bible* in the target language. Check [Obtaining The Bible](/en/help/github_bible).
4. Converting *The Urantia Book* from HTML to JSON without footnotes. Check [Conversion to JSON](/en/help/github_book_json).
5. Adding *Paramony* footnotes to *The Urantia Book* in JSON. Check [Adding Paramony footnotes](/en/help/github_footnotes).
6. Converting *Topic index* from TXT to Wiki.js. Check [Converting Topic Index](/en/help/github_topicindex_to_wiki).
7. Converting *The Urantia Book* from JSON with footnotes to Wiki.js including references to topics. Check [Converting The Urantia Book](/en/help/github_book_to_wiki).
8. Converting *The Bible* from LaTeX to Wiki.js with footnotes. Check [Converting Bible](/en/help/github_bible_to_wiki).
9. Commiting changes to [Urantiapedia-backup](https://github.com/JanHerca/urantiapedia-backup) project. Check [Bulk upload content to Urantiapedia](/en/help/github_upload).

*Chief Editors* and *Assistant Editors* perform tasks 1-3. *Admins* perform tasks 4-9.

![](/image/formats.png)

## External links

- [Urantiapedia Tools - GitHub project](https://github.com/JanHerca/urantiapedia)
- [Urantiapedia-backup - GitHub project](https://github.com/JanHerca/urantiapedia-backup)
- [Urantia Foundation](https://www.urantia.org/)
- [Blue Fields](https://blue-fields.netlify.app/)
- [Wiki.js](https://js.wiki/)

<br>

<figure class="table chapter-navigator">
  <table>
    <tbody>
      <tr>
        <td><a href="/en/help/roles">Collaborator profiles</a></td>
        <td><a href="/en/help">Index</a></td>
        <td><a href="/en/help/github">Chief Editors help</a></td>
      </tr>
    </tbody>
  </table>
</figure>