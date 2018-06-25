---
name: Dropbox
x-slug: dropbox
description: Dropbox is a modern workspace designed to reduce busywork-so you can
  focus on the things that matter. Sign in and put your creative energy to work.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/184-dropbox.jpg
x-kinRank: "10"
x-alexaRank: "89"
tags: Latest
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/apis.md
specificationVersion: "0.14"
apis:
- name: Dropbox Core A way to quickly get a cursor for the server's state, for use
    with /delta.
  x-api-slug: dropbox-core
  description: |-
    A way to quickly get a cursor for the server's state, for use with `/delta`.

    Unlike `/delta`, `/delta/latest_cursor` does not return any entries, so your app will not know about any
    existing files or folders in the Dropbox account. For example, if your app processes future delta entries
    and sees that a folder was deleted, your app won't know what files were in that folder. Use this endpoint
    if your app only needs to know about new files and modifications and doesn't need to know about files that
    already exist in Dropbox.

    If you need to build local state to match the server state in Dropbox, you should instead use `/delta`.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/184-dropbox.jpg
  humanURL: http://dropbox.com
  baseURL: https://api.dropbox.com//1//delta/latest_cursor
  tags: Storage,Documents,Delta,Latest_cursor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/deltalatest-cursor-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/deltalatest-cursor-post-openapi.md
- name: Dropbox Core
  x-api-slug: dropbox-core
  description: Dropbox is a modern workspace designed to reduce busywork-so you can
    focus on the things that matter. Sign in and put your creative energy to work.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/184-dropbox.jpg
  humanURL: http://dropbox.com
  baseURL: https://api.dropbox.com//1
  tags: Latest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/openapi.md
- name: Dropbox Datastore API Latest Cursor
  x-api-slug: dropbox-datastore-api
  description: /delta/latest_cursor
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/184-dropbox.jpg
  humanURL: http://dropbox.com
  baseURL: https://api.dropbox.com//1//delta/latest_cursor
  tags: Delta,Latest,Cursor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/deltalatest-cursor-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/deltalatest-cursor-post-openapi.md
- name: Dropbox Datastore API
  x-api-slug: dropbox-datastore-api
  description: Keep your apps structured data in sync with Dropbox
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/184-dropbox.jpg
  humanURL: http://dropbox.com
  baseURL: https://api.dropbox.com//1
  tags: Latest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/dropbox/openapi.md
x-common:
- type: x-application-management
  url: https://www.dropbox.com/developers/apps
- type: x-base
  url: https://api.dropbox.com/
- type: x-blog
  url: https://blog.dropbox.com/
- type: x-blog-rss
  url: https://blog.dropbox.com/feed/
- type: x-branding
  url: https://www.dropbox.com/developers/reference/branding
- type: x-branding
  url: https://www.dropbox.com/branding
- type: x-contact-form
  url: https://www.dropbox.com/developers/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/dropbox
- type: x-crunchbase
  url: https://crunchbase.com/organization/dropbox
- type: x-developer
  url: https://www.dropbox.com/developers
- type: x-email
  url: privacyshield@dropbox.com
- type: x-email
  url: privacy@dropbox.com
- type: x-email
  url: contractnotices@dropbox.com
- type: x-email
  url: copyright@dropbox.com
- type: x-email
  url: dispute-notice@dropbox.com
- type: x-faq
  url: https://www.dropbox.com/developers/support
- type: x-forum
  url: https://www.dropboxforum.com/hc/communities/public/topics/200209245-API-Development
- type: x-github
  url: https://github.com/dropbox
- type: x-pricing
  url: https://www.dropbox.com/plans
- type: x-privacy
  url: https://www.dropbox.com/privacy
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/dropbox-api?sort=votes&pagesize=15
- type: x-support
  url: https://www.dropbox.com/help
- type: x-terms-of-service
  url: https://www.dropbox.com/privacy#terms
- type: x-transparency-report
  url: https://www.dropbox.com/transparency
- type: x-twitter
  url: https://twitter.com/dropbox
- type: x-webhooks
  url: https://www.dropbox.com/developers/webhooks/docs
- type: x-website
  url: http://dropbox.com
- type: x-website
  url: https://www.dropbox.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---