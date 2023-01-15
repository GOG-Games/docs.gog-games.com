# Overview

The GOG Games API allows you to programmacticly interact with the site with HTTPS requests and JSON responses. Access will require authentication with an API key which may be obtained by donating for a Basic or Pro account. 

To learn more about donating and acquiring an account, visit: [https://gog-games.com/donate](https://gog-games.com/donate)

???+ info

    There are currently no plans to allow open API access to everyone. You will have to
    donate to recieve access to the API.

# Authentication

For the API to make a valid response, it requires the request to contain an API key. To generate a key, visit your account page and then click "Create API Key".

???+ warning

    Be sure not to share this key with anyone.


# Rate Limiting

A rate limit is enforced on the API to prevent abuse and discourage the sharing of API keys. Each account tier is allowed one active API key at any given time and each key may make x queries per second.

???+ info

    In the event an API key is exposed, you may generate a new one from your account page. The old key will become invalid.
    
# Endpoints

Todo
