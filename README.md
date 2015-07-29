Password Hasher
===============

You need strong, unique passwords for every site, but it's too hard to remember all of them.
You can use a password vault, but what if your computer crashes (you know you haven't backed it up enough),
or you need it on a different computer?
You can use an *online* password vault, but how sure can you be that they're keeping your information completely secure?
And what if you don't have internet at all (maybe that's why you need a password!)?

Enter [the password hasher](https://tabatkins.github.io/password).  Memorize a single, strong password just for this.  Then just remember some easy "tag" for individual sites, like the domain name.  These don't have to be strong or secret, so make them *easy to remember* instead. Heck, write them down, keep a spreadsheet of them, whatever.  Your strong password and memorable tag are combined together and hashed into an unpredictable, indistinguishable-from-random super-strong password that you can use on the site. No need to memorize this, as it'll always generate the same password as long as you provide the same Site Tag and Master Password; just copy/paste it in.

This page doesn't store *any* information at all.  It's all kept in your head, and all processing is done in-page in Javascript, so there's no risk of your password leaking.  Feel free to save the page onto all your devices - the entire app is in the one file, so you can use it even when you don't have internet.

The dingus comes with two default setups, for generating a "short" 12 character password (the shortest recommended length given current and near-future brute-forcing techniques) and a "long" 26 character password (enough entropy to defeat any brute-force for the forseeable future).  They include numbers and both upper- and lower-case letters, but no symbols, for maximum compatibility with dumb password requirements.  If these defaults don't precisely fit your needs, you can tweak any of them - require/exclude numbers, require/exclude symbols, generate *only* numbers (for PINs), and set any length you want.

Protip: mash on the keyboard for the site-tag and master-password, then click "Short" for a strong, unpredictable Master Password you can memorize for use on the site later.

[Try out the Dingus today!](https://tabatkins.github.io/password)
