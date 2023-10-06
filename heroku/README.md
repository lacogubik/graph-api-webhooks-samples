# Graph API Webhooks Heroku Sample

This is a sample client for Meta's [Webhooks](https://developers.facebook.com/docs/graph-api/webhooks/) product, powered by [Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs).

## Setup

### Meta Webhooks

1. Refer to Meta's [Webhooks sample app documentation](https://developers.facebook.com/docs/graph-api/webhooks/sample-apps) to see how to use this app.
1. Deploy the sample app on Heroku with this button:

    [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/lacogubik/graph-api-webhooks-samples)

1. Set up your client's [subscription](https://developers.facebook.com/docs/whatsapp/flows/reference/qualmgmtwebhook using your) `https://<your-subdomain>.herokuapp.com/webhooks` as the callback URL. It is recommended that you set a `TOKEN` [config var](https://devcenter.heroku.com/articles/config-vars) as part of the set up of your Heroku app to secure requests.


