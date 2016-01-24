# Summary

When creating a Web app, you need a foundation on which to build. There are
a lot of disparate technologies out there that can be brought together into
a cohesive whole to make this happen. The trouble is in finding, vetting,
testing, and combining these technologies -- all of which needs to happen
before you can begin to make serious progress on your own project.

Bedrock helps you launch your ideas faster by bundling all the best-of-breed
tooling that's necessary to build a modern, scalable Web app. It creates a
solid foundation on which you can build, letting you focus on your
project-specific needs.

Bedrock uses a modular design to help keep code well-organized and to allow an
ecosystem to grow without unnecessary hindrance. Bedrock keeps its core simple:
it provides a powerful configuration system, an event-based API, Linked
Data-capabilities, and testing infrastructure that makes writing interactive
modules easy. Bedrock is an opinionated, but flexible framework; it tells
developers that there's one recommended way to accomplish a task, but if need
be, a developer can go in another direction. Many of Bedrock's modules attempt
to emulate this approach, creating organizing priniciples and clear guidelines
for developers to follow that help break down problems and reduce cognitive
load.

Bedrock uses node.js and runs on Linux, Mac OS X, and Windows. It can run on a
low-powered laptop all the way up to an enterprise server.

* [Bedrock Features Overview](features.md)
* [Introducing Bedrock](introduction.md)
* [Basic Services]
  * [Event Logging](bedrock-event-log.md)
  * [Scheduling Jobs](bedrock-jobs.md)
  * [Sending Email](bedrock-mail.md)
  * [Permissions](bedrock-permission.md)
* [Databases]  
  * [Integrating with MongoDB](bedrock-mongodb.md)
  * [Integrating with REDIS](bedrock-redis.md)
* [Messaging](bedrock-messages.md)
  * [The Messaging Client](bedrock-messages-client.md)
  * [Messaging via Email](bedrock-messages-email.md)
  * [Push Messages](bedrock-messages-push.md)
* [Serving Web Traffic](bedrock-server.md)
  * [Express](bedrock-express.md)
  * [Serving HTTP Content](bedrock-views.md)
  * [Content Negotiation](bedrock-rest.md)
* [Security]
  * [Authenticating via Passport](bedrock-passport.md)
  * [The Session Management HTTP API](bedrock-session-rest.md)
    * [Session Management via MongoDB](bedrock-session-mongodb.md)
  * [Validating Web Request Input](bedrock-validation.md)
  * [Cryptographic Key Management](bedrock-key.md)
    * [The HTTP Key Management API](bedrock-key-http.md)
  * [Protecting Against Distributed Denial of Service](bedrock-request-limiter.md)
* [Identity](bedrock-identity.md)
  * [The Identity HTTP API](bedrock-identity-rest.md)
  * [The Credentials Vocabularies](bedrock-credential-vocabs.md)
  * [The Credentials HTTP API](bedrock-credentials-rest.md)
  * [Storing Credentials in MongoDB](bedrock-credentials-mongodb.md)
  * [Issuing Credentials](bedrock-issuer.md)
  * [Curating Credentials](bedrock-idp.md)
  * [Consuming Credentials](bedrock-consumer.md)
  * [The Credential Curation UI](bedrock-credential-curator.md)
* [Building a Consistent Product Experience]
  * [Angular](bedrock-angular.md)
  * [Autoloading Bower UI Components](bedrock-requirejs.md)
  * [The Angular UI Toolkit](bedrock-angular-ui.md)
  * [Models](bedrock-angular-model.md)
  * [Alerts](bedrock-angular-alert.md)
  * [Filtering](bedrock-angular-filters.md)
  * [Advanced Form Input](bedrock-angular-form.md)
  * [Identity Composition](bedrock-angular-identity-composer.md)
  * [Identities](bedrock-angular-identity.md)
  * [Key Management](bedrock-angular-key.md)
  * [Lazy Compilation](bedrock-angular-lazy-compile.md)
  * [Resolving Resources](bedrock-angular-resolver.md)
  * [Displaying Messages](bedrock-angular-messages.md)
  * [Handling Modals](bedrock-angular-modal.md)
  * [Navigation Bars](bedrock-angular-navbar.md)
  * [Working with Resources](bedrock-angular-resource.md)
  * [Selectors](bedrock-angular-selector.md)
  * [Session Management](bedrock-angular-session.md)
* [Testing]
  * [Unit Testing with Mocha](bedrock-mocha.md)
  * [Integrating Testing with Protractor and WebDriver](bedrock-protractor.md)
* [Utilities]
  * [Internationalization](bedrock-i18n.md)
  * [Autogenerating HTTP API Documentation](bedrock-docs.md)
  * [Proxying HTTP Requests](bedrock-proxy.md)
* [Contributing to Bedrock](contributing.md)
  * [A Hello World Example](bedrock-hello-world.md)
  * [Bedrock Quickstart Tutorials](bedrock-examples.md)
  * [Developing for Bedrock Core](bedrock-dev.md)
  * [The Development Manager](bedrock-dev-manager.md)

