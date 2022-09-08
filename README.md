# :pray: Please, do not embed spyware

:construction: THIS IS WIP :construction:

> :mag: A "?" in a cell means I have been lazy and there is much left to
> explore.

> :trophy: I have awarded a "\*" to solutions that have proven easy to install.

> :man_office_worker: When a slogan starts with "!" read it outloud and with enthusiasm.


## :bar_chart: Google Analytics

> ! Google Ads and Google Analytics: Stronger together.
> [Google Marketing Platform](https://web.archive.org/web/20210413111911/https://marketingplatform.google.com/about/resources/analytics-ads-integration-feature-brief/)

> Google Ads is a powerful tool that helps marketers grow online businesses.
> Google Analytics offers detailed insights into how people engage with
> websites. By linking the two platforms, marketers can increase the power of
> both.

### Alternatives

| Name | Privacy | Source | Lang | DB | API | Docker |
| ---- | :-----: | :----: | ---- | -- | :-: | :----: |
| [Ackee](https://ackee.electerious.com)\* | GDPR / CCPA / PECR (:warning: detailed mode requires scrutiny) | MIT | Node | MongoDB | GraphQL | `Dockerfile`, `docker-compose.yml`, [`electerious/ackee`](https://hub.docker.com/r/electerious/ackee) |
| [Umami](https://umami.is) | GDPR | MIT | Node | PostgreSQL, MySQL | HTTP/JSON? | `Dockerfile`, `docker-compose.yml`, pre-built images available |
| [Plausible](https://plausible.io) | GDPR / CCPA / PECR | AGPL/MIT | Elixir | PostgreSQL | Plain? (:warning: early-access beta) | `Dockerfile`, ?, ? |
| [Matomo](https://matomo.org) | :warning: Requires consent prompt | GPL 3 | PHP | MySQL, MariaDB | ? | :x: |
| [Simple Analytics](https://simpleanalytics.com) | GDPR / CCPA / PECR | :stop_sign: Proprietary | ? | ? | Plain? | :x: |

### :link: Links

  - [A call by Plausible to remove Google Analytics from your website](https://plausible.io/blog/remove-google-analytics)
  (:warning: Plausible obviously has an insentive to bash Google)
  - [Self-hosted Gatsby Statistics with Ackee](https://dev.to/aleccool213/quit-google-analytics-self-hosted-gatsby-statistics-with-ackee-4011)

## :speech_balloon: Disqus

> ! Reach the most engaged users from across the web on over 10,000 sites.
> [Advertise with Disqus](https://web.archive.org/web/20210413112132/https://about.disqus.com/advertise)

> Advertisers and brands interested in advertising on Disqus can run native ads
> through our Sponsored Story unit. The Sponsored Story fills the space between
> a site’s content and our commenting software, putting your native ads
> directly in front of the Internet’s most engaged audiences: dedicated readers
> and active commenters.

### Alternatives

| Name | Privacy | License | Lang | DB | API | Docker | User AUTH |
| ---- | :-----: | :-----: | ---- | -- | --- | :----: | --------- |
| [Talkyard](https://github.com/debiki/talkyard) (:elephant: Much more than just comments?) | ? | AGPL | Scala | PostgreSQL / Redis / ElasticSearch | ? | `Dockerfile`, `docker-compose.yml`, [a multitude of available Docker images](https://hub.docker.com/search?q=debiki%2Ftalkyard&type=image) | ? |
| [coral/talk](https://github.com/coralproject/talk)\* | GDPR | Apache | Node | MongoDB | GraphQL |`Dockerfile`, [`docker-compose.yml`](https://docs.coralproject.net/coral), [`coralproject/talk`](https://hub.docker.com/r/coralproject/tal) | [e-mail, OpenID, SSO, Google, Facebook](https://docs.coralproject.net/talk/v5/integration/auth) |
| [Isso](https://github.com/posativ/isso) | ? | MIT | Python | SQLite | ? | :x: | ? |
| [Schnack](https://github.com/schn4ck/schnack) | ? | Lil | Node | SQLite | ? | `Dockerfile` | Mastodon, GitHub, Twitter, Google, Facebook |
| [e-comments](https://github.com/skx/e-comments) (:warning:  last updated 3 years ago) | ? |? | Ruby | Redis, SQLite | ? | ? | ? |
| [glosa](https://github.com/glosa/glosa-server) | ? | ? | Clojure | JSON | ? | ? | ? |
| [mouthful](https://github.com/vkuznecovas/mouthful) | ? | MIT | Go | SQLite, MySQL, PostgreSQL, DynamoDB | ? | `Dockerfile`, ?, ? | ? |
| [YoYo](https://github.com/metrue/YoYo) | ? | MIT | Node | ? | ? | ? | ? |

## :symbols: Google Fonts

TODO

## :tv: Youtube

TODO
