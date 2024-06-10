---
name: Symphony
description: >-
  Streamline work and automate workflows with bots and apps. Build integrations
  from a simple hello world example to fully fledged financial integrations on
  Symphony.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: >-
  https://raw.githubusercontent.com/apis-json/artisanal/main/apis/factset/apis.yml
created: 2024/03/13
modified: 2024/03/13
specificationVersion: '0.17'
tags: []
apis:
  - name: Symphony Pod API
    description: >-
      The Symphony Pod API is used to build tools in order to manage and
      administer Symphony for your organization. 
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.developers.symphony.com/bots/overview-of-rest-api/pod-api
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.developers.symphony.com/bots/overview-of-rest-api/pod-api
      - type: OpenAPI
        url: properties/pod-openapi-original.yml
    aid: symphony:symphony-pod-api
    overlays:
      - type: APIs.io Search
        url: overlays/pod-openapi-search.yml
  - name: Symphony Agent API
    description: >-
      The Symphony Agent is responsible for encryption and decryption of
      messages and content sent to and from a bot.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api
      - type: OpenAPI
        url: properties/agent-openapi-original.yml
    aid: symphony:symphony-agent-api
    overlays:
      - type: APIs.io Search
        url: overlays/agent-openapi-search.yml
  - name: Symphony Authenticator API
    description: >-
      Tailor your portfolio exposures and risks using our hedging and
      optimization tools. Dynamically manage objectives and constraints while
      controlling for cost and tradability to meet your investment goals.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.developers.symphony.com/bots/authentication
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.developers.symphony.com/bots/authentication
      - type: OpenAPI
        url: properties/authenticator-openapi-original.yml
    aid: symphony:symphony-authenticator-api
    overlays:
      - type: APIs.io Search
        url: overlays/authenticator-openapi-search.yml
  - name: Symphony Community Connect API
    description: >-
      Access the full range of Goldman Sachs indices and basket products, or
      create bespoke solutions to tailor your own investment strategies. Design,
      create, and rebalance fully-customized, ready-to-trade basket solutions to
      express thematic and risk views.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.developers.symphony.com/symphony-rest-api/channel-connect
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.developers.symphony.com/symphony-rest-api/channel-connect
      - type: OpenAPI
        url: properties/community-connect-openapi-original.yml
    aid: symphony:symphony-community-connect-api
    overlays:
      - type: APIs.io Search
        url: overlays/community-connect-openapi-search.yml
  - name: Symphony Login API
    description: >-
      Programmatically manage your portfolio lifecycle from creation and update
      to scheduling reports with full control over visibility and sharing.
      Automate your portfolio workflow using our APIs — leaving you to focus on
      the alpha driving decisions.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://symphony-1.gitbook.io/restapi
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://symphony-1.gitbook.io/restapi
      - type: OpenAPI
        url: properties/login-openapi-original.yml
    aid: symphony:symphony-login-api
    overlays:
      - type: APIs.io Search
        url: overlays/login-openapi-search.yml
  - name: Symphony Profile Manager API
    description: Profile Manager is a microservice to manage users profile and groups.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.symphony.com/restapi
    baseURL: https://example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developers.symphony.com/restapi
      - type: OpenAPI
        url: properties/profile-manager-openapi-original.yml
    aid: symphony:symphony-profile-manager-api
    overlays:
      - type: APIs.io Search
        url: overlays/profile-manager-openapi-search.yml
common:
  - type: Portal
    url: https://developers.symphony.com/
  - type: Documentation
    url: https://docs.developers.symphony.com/
  - type: Getting Started
    url: https://docs.developers.symphony.com/bots/getting-started
  - type: Webhooks
    url: https://docs.developers.symphony.com/embedded-modules/universal-webhook
  - type: Certifications
    url: >-
      https://docs.developers.symphony.com/developer-certification/developer-certification
  - type: Change Log
    url: https://docs.developers.symphony.com/admin-guide/change-log
  - type: Rate Limits
    url: https://docs.developers.symphony.com/admin-guide/global-throttling
  - type: Forum
    url: https://forum.developers.symphony.com/
  - type: Privacy Policies
    url: https://symphony.com/legal/privacy-policy/
  - type: Terms of Service
    url: https://symphony.com/legal/terms-of-service/
  - type: Security
    url: https://symphony.com/legal/security-measures/
  - type: Newsletter
    url: https://goto.symphony.com/developer-newsletter-archive?from=developers
  - type: Blog
    url: https://symphony.com/insights/blog/?type=developers
maintainers:
  - FN: API Evangelist
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
aid: symphony
---