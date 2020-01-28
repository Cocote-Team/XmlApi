![Cocote](https://avatars2.githubusercontent.com/u/45873841?s=200&v=4)

[Cocote Marketplace](https://fr.cocote.com)

XML API
=======

Here, you will find specification of *offers* and *shops* XML feeds.


## Offers feed

This feed describes offers. It's relevant for both _shop_ and _agent_ account.

Feeds are described with XSD files.

You will find an example of offers feed in _examples/_ folder.


## Shops feed

This feed describes shops feed. It's relevant only for _"agent"_ account.
This kind of account allows to manage several _"shop"_ accounts.

The point of this feed for the agent is to automate the creation and the update of managed accounts.

### Access to shops feed

This feed should be accessible via an URL containing a hash to avoid anyone can find it.

You will be asked for this URL in your Cocote agent account.
