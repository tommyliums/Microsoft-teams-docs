# Getting started with tabs for Microsoft Teams (preview)

You can build a Microsoft Teams tab from scratch or by adapting your existing web app.

> **Don't have Microsoft Teams? Get a free one-year Office 365 developer subscription or activate it for your existing Office 365 account. [Here's how](setup.md).**

## Overview of building a Microsoft Teams tab

Follow these steps to build a tab:

*  [Design a great tab:](design.md) While it's easy to adapt a web app to become a Microsoft Teams tab, it's worth considering which of your experiences and functionality will work most effectively. 
*  [Create the package:](createpackage.md) This package contains the manifest, which specifies attributes of your tab, as well as its icons within Microsoft Teams.
*  [Create the configuration page:](createconfigpage.md) Microsoft Teams displays this configuration page inside the **Add a Tab** dialog, when the user chooses to add your tab. The configuration page enables your tab to present options and gather information from the user so they can customize the content and experience you present in your tab. This is an HTML page which you host and Microsoft Teams displays within an iframe.
	*  You can also [enable users to update a tab](updateremove.md#updating-an-existing-tab-instance) after they add it. 
*  [Create the content page:](createcontentpage.md) Microsoft Teams displays this content page when the user visits your tab. This is also an HTML page which you host and Microsoft Teams displays within an iframe.
	* You can also provide a page for users to specify [what happens to content when they remove a tab](updateremove.md#removing-a-tab).

>**Note:** We are looking for developers to build great tabs for inclusion in Microsoft Teams app gallery.  Submit your proposal [here](https://aka.ms/microsoftteamsdeveloperpreviewinterestform) and review the [tab publisher agreement](https://aka.ms/microsoftteamstabsdeveloperagreement) that will apply if you are accepted.

## Next step

[Design a great Microsoft Teams tab](design.md)
