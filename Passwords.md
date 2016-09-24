
# On passwords

Most people do passwords wrong. This is mostly because very few people are taught to know any better, but even in light of all the recent, very high-profile cases of breached servers and various kinds of data theft (IRS information, photos), it doesn't seem like the masses are worried about their passwords.

There are all sorts of debates we could have about what passwords should and should not be, but one thing experts agree on is that length matters, a lot. Ideally, you should max out the password length on every site you use. Another thing experts agree on is that you **must not** reuse passwords. You cannot sufficiently trust any one company to protect your password enough that you would trust that one company with the keys to multiple accounts. I cannot overstate how important this is.

Long passwords are more secure, but hard to remember. What to do??

### Password managers

[Good passwords are not necessarily hard to remember](https://www.xkcd.com/936/), but a large quantity of good passwords is certainly more difficult to remember than **One Good Password**. This is why password managers were created.

Browsers and operating systems often have autofill features built in that will ask to store your passwords. These features are usually pretty rudimentary, and have been known to have security issues. In some cases, if an attacker got access to your computer (maybe you downloaded an email attachment that you shouldn't have), that attacker would have instant access to your passwords if they were stored using those built in features. No good!

In any case, if you're going to entrust something with your passwords (they're like the keys to your house!), wouldn't you want it to be something that was built solely for securely storing passwords? 

Both of the following options use **One Good Password** to protect and access all your other passwords. They both offer:
 - browser extenstions that provide autofilling capabilities in web browsers, so that you don't have to type your very long passwords, or usernames.
 - vaults, which are available offline, and in which you can view and edit your logins and other securely stored information (you can store notes, credit card info, etc, and all of that is encrypted as well).
 - mobile apps for iOS and Android
 - graceful handling of multiple accounts for the same website
 - advice for choosing better passwords

Conveniently, 1Password supports importing data from LastPass, so if you feel you might try both, start with LastPass and if you don't like it, you don't have to start over from scratch to try 1Password.

## [Lastpass](https://lastpass.com) (freemium option)

Lastpass gives you a basic but solid set of features for free, centered around browser extensions. Once installed, their browser extension will offer to save new account information in your vault, try to detect when you change your password and ask to save that change for you, and autofill usernames and passwords for websites that have matching info in your vault.

In cases where you need to use passwords outside of a browser (like logging into desktop apps for Evernote, Spotify, whatever), you can copy a password from the browser extension and paste it wherever you need it, though that feature is hidden behind some point-and-click navigation through the browser extension's menus.

Lastpass also has a nifty feature where it can automate the process of changing your password on certain sites. It isn't super fast, but it is kind of cool (if a bit eery) to watch your computer navigate to a web page, login, click buttons, and otherwise act on your behalf.

### Setup

Start at [their website](https://lastpass.com/misc_download2.php), where you'll be able to install the browser extension for whichever browsers you use. You'll need to create an account, and use a good strong password to protect it. 

Once the install is complete, you'll see the icon for their browser extension show up. When you're logged out, it's grey, and when you're logged in, it's red. It only works when you're logged in. If you're not sure, click the icon, and it will either show you your account name and some menu options, or it will show you a login form.

From there, sign into a website you use frequently (email is a good starting point), and LastPass will offer to save your username and password. (If that doesn't happen, either the install didn't go well, or you aren't signed in in the browser extension.) Let it do so, and you should be able to use the browser extension to view your vault, and find your email (or other) account login details in there.

If that goes well, you should be able to log out of your email (or other) account, and then log back in using LastPass. I believe LastPass autofills usernames and passwords when you only have one account on a given site, and when you have multiple, it makes you choose. If you have multiple accounts on a site, you choose one by clicking on the little gray LastPass icons that show up in the boxes where you ordinarily type your info. Those icons will display a list of accounts, if there are any.

Make sure to confirm that the URL that LastPass thinks you're signing into is the correct one for the website. Sometimes funny things happen where a login forms redirect you to an intermediary page, or "Sign In" buttons redirect you to a sign-in page with a URL different from the main one, or other things like that.

## [1Password](https://1password.com) (paid option)

1Password does pretty much everything that LastPass does, with the addition of a few features as well as native desktop apps for Mac and Windows.

For me, 1Password stands out because the interface is more polished and easy to navigate, and (more importantly) because the keyboard shortcuts are better. Since there is also a desktop app, the keyboard shortcuts, which are great, are available to me _all the time_, so I have not just passwords, but notes and any other information I would like to store securely, available via a relatively quick few keystrokes - very quick when compared to pointing and clicking around in a menu. Given that I'm likely unlocking 1Password dozens of times every day, I consider the keyboard interface to be very valuable, but not everyone is obsessed with good keyboard shortcuts like I am!

You can try it free for a month, and you can upgrade from an individual acount to a family account to lower your costs later on.

### Setup

Start at their website, and click the Sign Up button. You'll be prompted to start making an account. Follow that process. Just like with LastPass, use the best password you can think of as your Master Password. Remember, it is the only password you need to remember once all your passwords are stored away in your vault.

You'll be given an account key. You can write it down when they tell you to if you want, but it's not required. You'll have the option to use a QR code to sign into your account instead of typing the very long account key.

They will tell you about your Emergency Kit. This is a document you really should print and store somewhere. It has a space for you to write your master password which you should or should not fill in, based on whether or not you have a safe place to put that piece of paper (use your judgment). 

You can keep the Emergency Kit PDF on your computer temporarily (it has your QR code on it, which you can use to sign into the desktop app later on), but remove it from your computer eventually.

Eventually, you'll be prompted to install browser extensions, and apps for your other devices. Install away, and make sure to sign in.

From this point on, 1Password works more or less the same as LastPass. When you sign into a new site (new from the perspective of 1Password), it asks to store the info. To autofill in web browsers, use the keyboard shortcut that it shows in the app's preferences; to access passwords outside of a browser, you activate what they call 1Password mini, which is a small helper app that's always open, which has its own keyboard shortcut and through which you can navigate using the arrow keys as well as the mouse.

Like with LastPass, make sure to confirm that 1Password is storing the correct information for each site. Autofill will obviously not work if the information is not correct, but if you don't check what 1Password automatically stores, you'll occasionally get unexpected results.

### Other

Where LastPass has a business-level plan (for teams), and an individual paid plan, 1Password has a business plan, a recently unveiled individual plan, and a family plan. The family plan is $5/month for 5 users, so if you can find 5 people who want to use it, it's $1/month, and you get a larger feature set than LastPass premium for the same price.


## [KeePass](http://keepass.info/)

One more which is spoken highly of, but which I haven't ever used, is KeePass. It's open source, free, and provides desktop apps for major operating systems. There are "unofficial" mobile apps listed on the website which I know nothing about.


## Caveats

As always, use your best judgment when providing sensitive information to websites. Hopefully, that website you like to use will encrypt your data in some way that involves your password providing sole access, but there's no compentence or security test to run a website, so maybe they don't. Sites you like might not always be sites you can trust. 

