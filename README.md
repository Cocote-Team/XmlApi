XML API
=======

Here, you will find specification of *offers* and *shops* XML feeds.

This work is in progress and may evolve.


## Offers feed

To come ...


## Shops feed

This feed describes shops feed. It's relevant only for _"agent"_ account.
This kind of account allows to manage several _"shop"_ accounts.

The point of this feed for the agent is to automate the creation and the update of managed accounts.

### Access to shops feed

As this feed contains some sensitive data, we need this feed is available via an authentication method (oauth2).

In your Cocote account, you will be asked for following information:
* url of shop feeds
* id for oauth authentication
* secret for oauth authentication