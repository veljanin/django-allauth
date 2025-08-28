Discogs (OAuth 1a)
------------------

You will need to register a Discogs app for consumer key and secret.

App registration
****************

To register an app on X you will need a Discogs account.

With an account, you can create a new app at::

    https://www.discogs.com/settings/developers

In the app creation form (optionally) fill in the development callback URL::

    http://127.0.0.1:8000/accounts/twitter/login/callback/

For production use a callback URL such as::

   http://{{yourdomain}}.com/accounts/twitter/login/callback/


Setting up provider:
********************

* 'name', up to you to choose (optional)
* 'client_id', is called "Consumer Key"
* 'secret', is called "Consumer Secret"
