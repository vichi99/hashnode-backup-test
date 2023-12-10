---
title: "How to Create a Good Pull Request Template (and Why You Should Add Gifs)"
datePublished: Fri Apr 14 2023 17:39:14 GMT+0000 (Coordinated Universal Time)
cuid: clghpgn8f07mch0nv3pobck6u
slug: how-to-create-a-good-pull-request-template-and-why-you-should-add-gifs
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1681546653203/e917e705-5422-4bd9-849a-140849c76018.jpeg

---

---
title:  How to Create a Good Pull Request Template (and Why You Should Add Gifs)
published: true
description: Learn how to create a great Pull Request template that improves collaboration between contributors and maintainers. Plus, find out why adding gifs can make the PR experience more fun and engaging.
tags: opensource, webdev, github
cover_image: https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tj0baromkd72zhsfbcf0.png
# Use a ratio of 100:42 for best results.
# published_at: 2023-04-13 17:48 +0000
---
I wasn’t in tech when Pull Requests (PRs) were first introduced by GitHub back in 2008. And when I graduated from bootcamp four years ago, I had probably created only a handful of PRs. I quickly learned how vital PRs were when I started my first job on a team though. And my appreciation for a good Pull Request has only increased as I spend more time as a maintainer.

The great things about Pull Requests are that they allow for collaboration between contributors and maintainers, offer an opportunity to communicate changes that have been made and why they are important, and the ability for maintainers to provide feedback. Because contributors come from different backgrounds, have varying degrees of experience, and speak different languages, sometimes creating good PRs can be tricky. But there are some ways to optimize the experience for everyone–including adding gifs.

## How to Create a Pull Request Template 
Maintainers can help to improve the experience for both reviewing Pull Requests and for contributors submitting them by creating a template. 

I like to think of Pull Request templates as a kind of contributor onboarding. It helps to guide them through the process of writing a good pull request and communicating with the maintainers. Although good templates may vary according to different organizations, their standards, and their needs, there are some basic checklists that you can use to generate your own.

To create a PR template in GitHub, create a `.github` folder in the root of your repository and a file called `PULL_REQUEST_TEMPLATE.md`. 

At OpenSauced, we used [forem’s Pull Request template](https://github.com/forem/forem/blob/main/.github/PULL_REQUEST_TEMPLATE.md) for inspiration for 
[our template](https://github.com/open-sauced/.github/blob/main/.github/PULL_REQUEST_TEMPLATE.md).


![gif of OpenSauced’s PR template](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/42la8o8k1ej48kx9evvf.gif
)

You can use markdown to create your template, and include sections like:

- What type of PR is this?
- Description of the changes
- Related Tickets & Documents
- Mobile & Desktop Screenshots/Recordings
- Tests 
- Documentation
- Post-deployment tasks
- What gif best describes this PR or how it makes you feel?

### Let Them Add Gifs!
That last one might seem out of place to you, but it can actually make the PR experience more fun, engaging, and effective. Here's why:

- Gifs can bridge language gaps and help contributors express themselves more clearly.
- Gifs can showcase contributors' personalities and add a personal touch to the PR.
- Gifs can increase engagement and make the review process more enjoyable for everyone.
 
### How to add Gifs to Your PR
If you’re a contributor, you might be wondering, “What’s the easiest way to add a gif?” I use the [GIFs for GitHub](https://chrome.google.com/webstore/detail/gifs-for-github/dkgjnpbipbdaoaadbdhpiokaemhlphep/related?hl=en) chrome extension. Once it’s installed, you’ve got a quick way to add all your favorite gifs to enhance that PR experience. Just search for the gif you want, and click it. You can even add a caption to describe the gif or explain how it relates to the PR 👏

![adding a gif of leslie knope and april with the caption “How much fun is it working here!?](https://cdn.hashnode.com/res/hashnode/image/upload/v1681546651166/8ea8af35-5cd6-497d-bff3-3432fbe590a1.gif) 

You can read more about PRs with [@Brian Douglas’](https://dev.to/bdougieyo) post on [Tips for getting your Pull Request reviewed on GitHub](https://dev.to/opensauced/tip-for-getting-your-pull-request-reviewed-on-github-2b7c). Or check out the hottest repos and how they handle PRs on [OpenSauced hot repositories](https://hot.opensauced.pizza/). And if you have tips for creating great pull requests, let us know in the comments below. 

<small>header image created using [midjourney](https://www.midjourney.com/app/jobs/53c570b9-3cc2-48c5-9fe0-8d855cfbeb34/).</small>




