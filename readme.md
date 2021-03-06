# Android: Getting Started Samples

This contains Getting Started sample apps to accompany the Android developer guides on [creativesdk.com](http://creativesdk.com).

Stay tuned for updates as we build out this library of samples!

### Contents

- [How to use](#how-to)
- [More resources for the Creative SDK](#resources)
- [Contributing to this repo](#contributing)
- [Get help](#get-help)

<a name="how-to"></a>
## How to use

### In your browser

1. [Register a new app for the Creative SDK](https://adobe.io/console)
1. Note your **API Key** (Client ID), **Client Secret**, and **Redirect URI**. You will need them soon.

### In your local development environment

1. `git clone` this repo
1. Open a component's `code` directory Android Studio (e.g., `send-to-desktop-api/code`)
1. Add a new Java class called `Keys` with this code:  

	```
    public class Keys {

	    public static final String CSDK_CLIENT_ID       = "<YOUR_ID_HERE>";
	    public static final String CSDK_CLIENT_SECRET   = "<YOUR_SECRET_HERE>";
	    public static final String CSDK_REDIRECT_URI    = "<YOUR_REDIRECT_URI_HERE>";

	}
	```

    1. Add your API Key (Client ID), Client Secret, and Redirect URI to the `Keys` class
    1. This class is gitignored so you can avoid exposing your keys on GitHub
1. Sync your Gradle files
1. Run the app
1. See the component's `guide` directory to learn more about the component (e.g., `send-to-desktop-api/guide`)

<a name="resources"></a>
## More resources for the Creative SDK

### Developer portal

[Visit our Android developer portal](https://creativesdk.adobe.com/docs/android/#/index.html) for component guides, class references, and more.

### Blog

We have all kinds of Android content on our blog that explores deeper aspects of the Creative SDK. Have a look at [our Android category on blog.creativesdk.com](https://blog.creativesdk.com/category/android/).

<a name="contributing"></a>
## Contributing to this repo

Pull requests and GitHub issues are welcome!

If you want to do a pull request, please get in touch with us before you start writing code, so we can avoid duplicated effort or unnecessary work.

<a name="get-help"></a>
## Get help

[Our growing community on Stackoverflow is a great way to get help](https://stackoverflow.com/questions/tagged/adobecreativesdk). Just post your question and tag it with `adobecreativesdk`.

If you have feedback on this repo, submit a GitHub issue.