# ✨ IssueTemplates
This repo serves as a copy-paste solution for the identical issues that the different projects are having. 

It was created mostly for personal use as i've been repeating myself in issues in different projects, so here i could actually set up answers better once and copy-paste with minor editing depending on a project. It's also better if the issues are well documented with the resources to help with implementing the said solution, therefore copy-paste on identical issues. So if anyone has anything to add or improve, please [open an Issue](https://github.com/aha999/IssueTemplates/issues).
- share: `https://github.com/aha999/IssueTemplates/`

## Contributing

- Make a pull request if you happen to formulate the requests in a better way with more resources or for the general Readme look
- Make button requests in [Issues](https://github.com/aha999/IssueTemplates/issues)
- Donations: [Paypal](https://www.paypal.me/Slovantes)

### ⚠️ Landing page / Website request:

It would be useful to have this project's landing site / website, so any future news articles can link to it and the website would make a better visual representation of the project that could attract more users, developers and contributors.

A simple and free option is via [Github Pages](https://pages.github.com/), that a lot of github open source projects are using, which Github hosts for any repo on their website.

> Hosted directly from your GitHub repository. Just edit, push, and your changes are live.
> No databases are needed to be set up and no servers to configure

Repositories that use github pages: [Examples](https://github.com/collections/github-pages-examples)

Interesting article: [Link](https://www.toptal.com/github/unlimited-scale-web-hosting-github-pages-cloudflare)

> Consider [Jekyll](https://jekyllrb.com/). You give it [Liquid](https://jekyllrb.com/docs/liquid/) templates and Markdown content
> Free Jekyll templates: https://jekyllthemes.io/free

### ⚠️ Donation platforms:

**Is your feature request related to a problem? Please describe.**

Currently there's no donating information, if users want to show appreciation that way and help fund your time.

**Describe the solution you'd like**

Add a Donations section to the readme and some buttons below as where to donate to your project.

**Describe alternatives you've considered**

Here are some platforms that can be used for donations:
- [OpenCollective](https://opencollective.com/) -- [example](https://opencollective.com/darkreader#sponsor)
- [LiberaPay](https://liberapay.com/) -- [example](https://liberapay.com/k9mail/donate)
- [Github Sponsors](https://github.com/sponsors)
- [PayPal](https://www.paypal.com/)
- [Ko-fi](https://ko-fi.com/)
- [Patreon](https://www.patreon.com/)
- [Flattr](https://flattr.com/)
- [BountySource](https://www.bountysource.com)

Displaying a sponsor button in your repository: [link](https://help.github.com/en/github/administering-a-repository/displaying-a-sponsor-button-in-your-repository) 
A handy list of [donate buttons](https://github.com/aha999/DonateButtons)

### ⚠️ Publish to F-Droid

F-Droid is an app-store that hosts free and open source android apps for download (like google play but only for FOSS), which builds apps directly from source code, so apps are matching source code and are transparent. If you published your app to F-Droid. i think that the number of users will increase as it's very convenient, findable and easy to update. Most of the FOSS android apps are on F-Droid as far as i know and it's great!

- F-Droid documentation for developers: [instructions](https://f-droid.org/en/docs/#developers)

- If you're fine with publishing it on F-Droid, you could [create a Request for Packaging](https://gitlab.com/fdroid/rfp/-/issues/new?issue%5Bmilestone_id%5D=).

- Requests for packaging: [RFP](https://gitlab.com/fdroid/rfp/-/issues)


### ⚠️ Changelog info text in F-droid

**Is your feature request related to a problem?**

Currently, there is no visible window with the latest changes when you open your app's page in F-Droid.

**Describe the solution you'd like**

Add changelog text into a window above the description when you open the fdroid app repo.

**Some tips:**

> F-Droid looks for metadata in the app’s source repo. The supported formats for this metadata are borrowed from popular projects that automate uploading this metadata to Google Play Store.

>The one in your example corresponds to Fastlane Supply and is documented [here](https://docs.fastlane.tools/actions/supply/#changelogs-whats-new). All formats supported by F-Droid are listed [here](https://f-droid.org/en/docs/All_About_Descriptions_Graphics_and_Screenshots/#in-the-applications-source-repository)

**Additional context**

This would be a great option to quickly see the new changes and many apps use this method.

Example of the changelog structure:

```
└── fastlane
    └── metadata
        └── android
            ├── en-US
            │   └── changelogs
            │       ├── default.txt
            │       ├── 100000.txt
            │       └── 100100.txt
            └── fr-FR
                └── changelogs
                    ├── default.txt
                    └── 100100.txt
```
### ⚠️ Translation platform

It would be great if there was a convenient way for general public to contribute translations.

I can recommend [Weblate](https://weblate.org/), as it's popular, the platform itself is open source (compared to others), can be self hostable, and for open source projects like yours, they host translations for free. Weblate automatically merges translations and if you want you can have different widgets shown in github readme, that displays how much percentage each applied language is translated to in real-time.  It's much more simple for people to translate this way and it's free + less work needed for you.

- [set up your libre project](https://hosted.weblate.org/hosting/) 

screenshot:

![screenshot](https://user-images.githubusercontent.com/50620416/119900111-57ffdf00-bf44-11eb-95e6-892f025a7627.png)

### ⚠️ Option to force language change

Although the app is translated in one's language, many users may prefer to use English language for the app's interface. The reasons may vary, from better terminology understanding in English language, to just a preference.

Please add an option in the settings to change a language in the app from a default (local) one to a selected one, like English or other.

### ⚠️ Issue templates

**Is your feature request related to a problem? Please describe.**
Currently, there is no issue templates in this repository, like the one this issue is using with titles for context, which means that issues are not as organized or convenient to understand.

**Describe the solution you'd like**
Implement Issue templates, like this one for example, so users can insert info in pre-determined questions, so they can make better issues. 

Here is a general idea and documentation on how to implement it: [GitHub docs  - issue templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)

**Describe alternatives you've considered**
This can be done ether as a text-based template, or a sort of a form. I think that the text based version offers more freedom when creating an issue.

**Additional context**
Screenshot example, this is a selection window, that displays after selecting "New Issue" on Github:
![image](https://user-images.githubusercontent.com/50620416/170260260-295bcb14-2dc5-4540-99f7-9054f18cb5c3.png)

### ⚠️ Beta versions on F-Droid

**Is your feature request related to a problem? Please describe.** 

Currently, there is no Beta versions on F-Droid to make it easy to update to experimental versions to report the functionality, any new bugs etc.
 
**Describe the solution you'd like** 

Upload alpha/beta releases, apks to Github/Fdroid. Other app makers are also doing so, and it's really nice because you can get all app versions from one place where you get them anyways.

* [Example](https://github.com/k9mail/k-9/releases) of K-9 mail app on Github (pre-release)

* [Example](https://f-droid.org/en/packages/com.fsck.k9/) of K-9 mail app on Fdroid, where the recommended version is the stable one which by deafult installs when installing an app, but pre-release can be installed manually.

It looks like having F-Droid automatically pick up the latest version will always update the recommended version (`CurrentVersion`), too. See https://f-droid.org/docs/Build_Metadata_Reference/#UpdateCheckMode

For example, K-9 Mail's (beta) releases are manually added to F-Droid by creating a merge request to its [fdroiddata](https://gitlab.com/fdroid/fdroiddata) repository. Example: https://gitlab.com/fdroid/fdroiddata/-/merge_requests/8905

They're doing this manually. But I guess there's no reason why this can't be automated.

However, a nicer solution would probably be to add something like an `UnstableUpdateCheckMode` to F-Droid. That could add a release but not update `CurrentVersion`, making it an "unstable" version. It would enable projects to e.g. use a different tag scheme for test versions.

# Linux

### Flatpak support

Currently there is only a limited amount of linux support in your project, which may cause issues on some popular distributions.

Please introduce a modern [Flatpak](https://flatpak.org/) package and publish it on [FlatHub](https://flathub.org/).

Having this project in a Flatpak package, would enable your project to work on most distributions. Here are some of the [reasons](https://docs.flatpak.org/en/latest/introduction.html#reasons-to-use-flatpak) to use Flatpak.
