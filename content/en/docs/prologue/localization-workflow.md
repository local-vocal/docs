---
title: "Localization Workflow"
description: "There are different approaches to a localization workflow. However these five steps are common."
lead: "There are different approaches to a localization workflow. However these five steps are common."
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 110
toc: true
---

1. Uploading the main language file

2. Translating

3. Reviewing (sometimes not needed)

4. Downloading all languages files

5. Publishing to end-users

### A localization process usually involves 4 types of collaborators:

1. Software developers
2. Product managers, product owners, project managers, localization managers
3. Translators, copywriters, marketers
4. Reviewers, quality assurance (QA) members

The process usually starts with developers, as they add string keys to the code while programming the screens shown to end-users. Each text on the screens is identified by its key, which helps developers to select the proper text.

Localization files contain the keys & translated text pairs. So depending on the localization file format used, it usually ends up with one file per language for end-user.

There are many localization file formats: Apple Strings or Stringsdict for iOS, XML for Android, JSON/YAML for Web, etc. Since these files are structured and intended to be used by machine/software it is hard to understand their structure for a non-technical person.

# Localization workflow

### 1. Uploading the main language file

It starts with the main language content provided to a team of translators.

In most cases, there are already some localization files (in just the main language or in multiple languages that are partially or fully translated). It’s a good idea to do the initial project set up using Vernacle web app, and when you get familiar you will be able to automate the upload process via Vernacle REST API, CLI tool , or via GitHub integration.

Once you create a project, simply upload your file(s) via the Upload page for your project.

### 2. Versioning

With turned on branching for a project (via Project Settings page), you can handle localization content for different versions of your software. For example, if you released version 1.2 of your app, and you actively work on version 2.0, you would like to use 2 branches in Vernacle for them. In case you need to make minor localization changes for 1.2 but you don’t want that change for 2.0. You will be able to see exactly what is changed between branches.

### 3. Translating

You can invite your in-house translators, invite a third party translation agency or order professional translations.

Besides helping with the automation of localization process, Vernacle has a collaborative editor that is easy to use, and reminds of Excel files that teams initially tend to use for persisting translations.

### 4. Collaboration via comments

Besides the contextual information like descriptions and screenshots that project admins may provide for keys, Vernacle has a built-in chat with Slack-like @mentions so translators and admins can discuss the potential translation change or exchange ideas.

### 5. Reviewing

After translation work is done by translators, often you want to review if everything is ok and if it is ready for integration back into your app. There is a reviewed flag for each translation.

### 6. Downloading all language files

Once the translation tasks are complete you need to download the content and publish it to end-users.
Besides simply downloading the files using the web UI you can use REST API to automate it via custom scripts, CLI tool, or use GitHub integration.

### 7. Publishing to end-users

After all localization content is up to date in your source code repository, you can build a new app version and publish it to your end-users.
