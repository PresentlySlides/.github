# Contributing

First off, thanks for your interest in contributing to this project! When contributing, please keep
in mind these guidelines, as they are here to prevent duplicates and security vulnerabilities.

---

![Contributing Flow Chart](https://github.com/user-attachments/assets/13f8a326-bcf2-481c-9b8a-cd322106f79c)

## General Guidelines

 - **Avoid duplicate posts:**
   Before posting something, it is your responsibility to search in all appropriate places to make
   sure you don't post a duplicate. For example, searching issues/discussions in the correct
   repository.

 - **Use the correct repository:**
   Please ensure that you are using the correct repository for soemthing. This makes it easier for us
   to find and keep track of it.

## Feature Requests

When posting a feature request, please create an issue using the feature request template. If
you're not sure of what repository to use, you can use the
[organization-wide discussions tab](https://github.com/orgs/PresentlySlides/discussions).

## Bug Reports

> [!CAUTION]
> **DO NOT POST SECURITY VULNERABILITIES PUBLICLY.** Doing this will result in other people
> being able to see the vulnerability you're reporting. Instead, please check our
> [SECURITY.md](https://github.com/PresentlySlides/.github/blob/main/SECURITY.md)
> file and follow those steps.

If you aren't reporting a security vulnerability, please create an issue using the bug report
template. Fill out as much information as you can with as much detail as possible. Knowing
the specifics helps us track down the issue.

## Pull Requests

**We keep no obligation to merge your pull requests.** Please keep this in mind when you're
making one. Don't spend any more time than you're able to.

Pull requests have some extra guidelines:

 - **Do not fix any security vulnerabilities.** If you've found a fix to one, email us
   (email found in [SECURITY.md](https://github.com/PresentlySlides/.github/blob/main/SECURITY.md)).
 - **Do not expect an immediate response.** We first need to review the pull request, solve
   any merge conflicts, and then merge it. We won't be able to immediately merge it.
 - **Expect changes being requested.** We might not have the same vision as you, and may ask
   you to make some changes before we merge it.

### Commit Messages

Please keep your commit messages short. If you need to explain something, use the description.
Use correct capitalization and no punctuation, and descriptive commit messages. Please
also keep one complete change per commit. Look at past commit messages if you're stuck.

## Documentation Updates

If you're updating the docs or submitting an issue, please follow the issue/pull request
guidelines.

Some things to keep in mind:

 - If you're adding or removing a page, you need to update the sidebar.
 - Please keep your page similar to other pages—don't enable/disable features like
   the edit link or last updated for no reason.
 - Please follow markdown conventions, installing an extension like
   [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
   can help with this.
   - Don't include a title frontmatter, instead use an h1.
 - Our docs are built with [VitePress](https://vitepress.dev/). GitHub Actions will build
   it when a commit is pushed, there's no need to manually build it.
