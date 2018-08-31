---
name: Freesound
x-slug: freesound
description: Freesound aims to create a huge collaborative database of audio snippets,
  samples, recordings, bleeps, ... released under Creative Commons licenses that allow
  their reuse. Freesound provides new and interesting ways of accessing these samples,
  allowing users to browse the sounds in new ways using keywords, a sounds-like type
  of browsing and more--upload and download sounds to and from the database, under
  the same creative commons license, and interact with fellow sound-artists!
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Freesound_project_website_logo.png
x-kinRank: "8"
x-alexaRank: "6485"
tags: Freesound
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/freesound/master/_listings/freesound/apis.md
specificationVersion: "0.14"
apis:
- name: Freesound - Search sounds
  x-api-slug: searchtext-get
  description: This resource allows searching sounds in Freesound by matching their
    tags and other kinds of metadata.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Freesound_project_website_logo.png
  humanURL: https://freesound.org
  baseURL: https://www.freesound.org//apiv2
  tags: Technology, internet, Audio, Sounds, Music, API Provider, Profiles, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/freesound/master/_listings/freesound/searchtext-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/freesound/master/_listings/freesound/searchtext-get-openapi.md
- name: Freesound - Details of a sound
  x-api-slug: soundssoundid-get
  description: This resource allows the retrieval of detailed information about a
    sound.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Freesound_project_website_logo.png
  humanURL: https://freesound.org
  baseURL: https://www.freesound.org//apiv2
  tags: Technology, internet, Audio, Sounds, Music, API Provider, Profiles, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/freesound/master/_listings/freesound/soundssoundid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/freesound/master/_listings/freesound/soundssoundid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://fraudlabs.pro.api.gallery.streamdata.io
- type: x-api-stack
  url: http://freesound.stack.network
- type: x-blog
  url: https://blog.freesound.org/
- type: x-crunchbase
  url: https://crunchbase.com/organization/freesound
- type: x-developer
  url: https://freesound.org/help/developers/
- type: x-documentation
  url: https://freesound.org/docs/api/
- type: x-forum
  url: https://freesound.org/forum/
- type: x-login
  url: https://freesound.org/home/login/?next=/apiv2/apply/
- type: x-terms-of-service
  url: https://freesound.org/help/tos_web/
- type: x-twitter
  url: https://twitter.com/freesounddev?lang=en
- type: x-website
  url: https://freesound.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---