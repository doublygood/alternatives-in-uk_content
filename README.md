# Welcome!

This is the content repository for the website [alternatives-in.uk](https://alternatives-in.uk) 

If you want to make a contribution, but are not familiar with how Github works, you can always add your company via [our online form](https://docs.google.com/forms/d/e/1FAIpQLSeu6SXEzV9Fz8pcUsI5lsdkgSsRiI4nlXTH81tIRPS2hhkwGw/viewform?usp=dialog).

* Submit a service provider
* Adding logos

## Useful information

All of the files for the written content on the website are markdown format. This is a plain text file, written in a certain way that generates HTML for the site. We've deliberately chosen markdown, as it's quite commonly used and can be edited with almost any basic text editor. You can even create and edit a markdown file directly in the GitHub site.

Don't worry too much about formatting, we'll double-check all the formatting and content before it goes live on the site.

## Submit a provider

**Create a file**

The filename should be a simplified name of the provider or service. For instance, the file for Google Cloud Storage is `google_cloud_storage.md`. Use underscores `_` for spaces, and `-` for dots. Wordpress.com is stored in `wordpress-com.md`

The `.md` extension is our preferred extension for markdown files.

**Write your content**

At the top of each file is a bit of text that _describes_ what the page is about, it looks something like this:

```
---
title: Company name
description: A description of what the services does. 
date: 2025-02-24T12:00:00
features:
 - email
 - calendar
---
```

We call this 'frontmatter'. You can look at any of the existing files to see how they're formatted. 

The 'features' list is how we compare services, a bit like hashtags. Put each feature on a new line. You can see a list of the existing features on the website. Of course you can add new features, but we ask you to try to use existing ones where possible. Don't use more than 5, and put the _most_ relevant or important feature at the top.

---

Next up is the content itself, you can write what you like in here, but we prefer to keep things brief where possible. Here's our listing for Mojeek:

```
## Description

"The alternative search engine that does what’s right, that values and respects your privacy, whilst providing results that we have crawled and indexed with tech built in-house."

https://www.mojeek.com/about/"

## Details

* Mastodon: [@mojeek](https://mastodon.social/@Mojeek)

```

Our required items are:

* A single, short Paragraph about the company or service.
* A link to the provider website
* Any useful contact details such as phone numbers or social media profiles to follow.

After this, you can add a little more detail about the services offered. However, we _will_ strip out any links, especially anything with redirects, trackers or UTM strings. We will also tone down or remove any excessive marketing copy or hyperbole. Ultimately, all the content is published at our discretion and we will attempt to validate everything before it is published. 

If you want to be kept informed of changes, or simply when the listing goes live, you should leave a contact email address or mastodon account handle and we will let you know when the page goes live.
