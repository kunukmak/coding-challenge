# Feed Stalker

Feed Stalker allows you to specify a feed of information and a web hook. As soon as the information feed is updated, the webhook is triggered.

## Terminology

- **WebHook**: Webhooks allow you to build or set up Apps which subscribe to certain events on other applications [Read more](https://developer.github.com/webhooks/).

## User Stories

- As a user I want to use the Feed Stalker web application and/or APIs in order to register an Atom feed URL and a web hook so that the web hook is triggered as soon as the feed is updated. Once this is done a secret key is generated and communicated to me through the web application. Only the users that knows this secret can use it so that they can read, update and delete the web hook.
- As a user I want to be able to allow the Feed Stalker web application to prompt for notifications in my browser so that I can get notified as soon as the feed is updated. [Read more](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API/Using_the_Notifications_API) about web notifications.
- As a user I do not want to care about the webhook on Feed Stalker. If the feed is not updated in more that 1 month, then the webhook gets deleted and a DELETE operation is triggered on the webhook URL in order to notify the system subscribed to the feed.
- **[Senior Level]**: As a user I am able to signup and signin to the Feed Stalker web application and/or APIs so that I can safely access my profile information, and I can get a status on the hooks I am managing through this system. It is no longer enough to know the secret to access and perform CRUD operation on the hook, but access instead will have to be related to the user profiles instead.
- **[Senior Level]**: As a user I want to use the Feed Stalker web application and/or APIs in order to register also non-atom feeds ( as for instance rss, json or others ) so that the type of feed is automatically detected by the system and rejected if not supported.
- **[Senior Level]**: As a user I am able to get some samples on how to consume a web hook trigger in 3 or more technologies (as for instance Java, NodeJS and C#) so that the integration task I have is simplified.