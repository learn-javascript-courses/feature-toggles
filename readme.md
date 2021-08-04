# Feature Toggles

Feature toggles, or feature flags allow development teams to toggle features on and off in production, or roll features out gradually to users.

For this app, you will create a feature toggle database that will serve active feature toggles to the client.

Build a GraphQL API that allows the front end to query all the active features for an app.

Build a front-end UI that allows app administrators to:

* [ ] Create an app
* [ ] Create features for the app
* [ ] For each feature:
* [ ] - `displayName` - A feature name to display in the UI
* [ ] - `featureName` - An identifier-friendly version of the feature name
* [ ] - `description` - A brief description of the feature
* [ ] - `isActive` - Can be `true` or `false`

Make it easy to pair this service with [React Feature Toggles](https://github.com/paralleldrive/react-feature-toggles) and [Feature Toggles](https://github.com/paralleldrive/feature-toggles).
