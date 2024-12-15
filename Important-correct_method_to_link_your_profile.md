# **IMPORTANT!** Correct method to link to your profile on bluesky!

This is especially true for personal/domain handles, Due to the **Bluesky BUG** where accounts are marked with 'Invalid Handles' your account link might not appear correctly for other users!

But will work with the default bluesky social handles in case you encounter the bug, you don't need to utilise a domain handle.

Instead of linking to a profile with: -
> https://bsky.app/profile/corkiejp.github.io

use in my case as an example:-
> https://bsky.app/profile/did:plc:qxlh6bohvep3taqhmtpipx4b



## Follow instruction below to get your account 'did' String

**Found**: - settings – account – handle – own domain – no dns panel – click copy code.

![Account profile string and where you find it!](/assets/blueskyaccountstring-Capture.PNG)


## Another method to get any user 'did' by using an api request:-

You can make a request to the server at the url below:-

> https://bsky.social/xrpc/com.atproto.identity.resolveHandle?handle=corkiejp.github.io

Using my handle as an example the [results of it](https://bsky.social/xrpc/com.atproto.identity.resolveHandle?handle=corkiejp.github.io)

Just change the account after 'handle='!

^^ [Source where I found that api method](https://www.reddit.com/r/BlueskySocial/comments/15hbu83/comment/jusiaws/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

**Sky Zoo also shows 'did' info**
[Sky Zoo](https://skyzoo.blue/stats) by [JYC](https://bsky.app/profile/jyc.dev)

![Account profile string and where you find it!](/assets/sky_zoo_did.PNG)

