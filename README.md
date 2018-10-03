## List of Continuous Integration services

[![Build Status](https://travis-ci.org/ligurio/awesome-ci.svg?branch=master)](https://travis-ci.org/ligurio/awesome-ci)

**[Subscribe](https://github.com/ligurio/awesome-ci/subscription) to receive notificatons.**


There are a lot of cloud [continuous
integration](http://en.wikipedia.org/wiki/Continuous_integration) services. All
of them have different set of functionality, some of them require payment, some
of them are free.  I have created a list of such
services to make easy comparison of them and choose more suitable for you.

Some of CI services has open source code thus you can setup them in standalone
mode. Pay attention to the column "Features".

There is a
[similar](https://en.wikipedia.org/wiki/Comparison_of_continuous_integration_software)
comparison on Wikipedia.

| Name | Description | Features | Supported repositories | Documentation | Price |
|------|:-------------:|:-----------:|:-------------:|:-----:|:---------:|
|[Abstruse CI](https://github.com/bleenco/abstruse) | Self-Hosted, Open-Source CI Platform. Based on NodeJS and Docker. | Languages: everything that can be installed on Linux | GitHub, GitLab, BitBucket, Gogs | [Documentation](https://github.com/bleenco/abstruse/tree/master/docs) | [Open Source](https://abstruse.bleenco.io)
|[Appcenter](https://appcenter.ms/) | CI Platform. It connects with Hockeyapp where you can store installers and send their by email | Compatible with Android, iOS, Xamarin, Reactive Native, Cordova, MacOS | GitHub, BitBucket, VSTS | [Documentation](https://docs.microsoft.com/en-us/appcenter/) | [Free with limitations](https://appcenter.ms/#pricing) |
|[Appveyor](https://ci.appveyor.com) | AppVeyor automates building, testing and deployment of .NET applications. | Languages: C#, Xamarin, F#, VB.NET, C/C++, Node.js, Ruby, TypeScript, Go, Java, Python, Perl, Erlang  | GitHub, BitBucket | [Documentation](http://www.appveyor.com/docs) | [Free with limitations](http://www.appveyor.com/pricing) |
|[Assertible](https://assertible.com/) | Automated post-deployment testing and web service monitoring | [Example Integrations](https://github.com/assertible/deployments) | GitHub | [Documentation](https://assertible.com/docs) | [Free with limitations](https://assertible.com/plans) |
|[Badwolf](https://github.com/bosondata/badwolf) | Docker based continuous integration and code lint review system for BitBucket | [Source code](https://github.com/bosondata/badwolf) is available | BitBucket | [Documentation](https://badwolf.readthedocs.io/en/latest/) | Free (Open source) |
|[Bitrise](http://bitrise.io/) | Mobile Continuous Integration and Delivery. | [Source code](https://github.com/bitrise-io) is available | GitHub, BitBucket, Gitlab, Custom | [Documentation](http://devcenter.bitrise.io/) | [Free with limitations](https://www.bitrise.io/pricing)|
|[Buildkite](https://buildkite.com/) | A build automation platform which gives you complete control, without the pain of running your own CI system. | Languages: Ruby, Python, Node.js, JavaScript, PHP, Go, Rust, Erlang, Elixir, Java, Clojure, Scala, C/C++, Objective-C, Swift, .NET/C#<br />Source code is available: [Buildkite Agent](https://github.com/buildkite/agent) | GitHub, Bitbucket, GitLab, Custom | [Documentation](https://buildkite.com/docs/guides/getting-started) | [14-day Trial](https://buildkite.com/pricing), [Free for Education, Open Source](https://buildkite.com/pricing) |
|[Chrono CI](https://www.chronoci.com/) | Continuous Integration Security | Languages: Ruby on Rails, Python, Node.js, Solidity C, Java, Go | GitHub | [Documentation](https://www.chronoci.com/docs) | [Free for 100 tests per month](https://www.chronoci.com/pricing) |
|[Circle CI](https://circleci.com/) | Continuous Integration and Deployment | | GitHub, Bitbucket | [Documentation](https://circleci.com/docs) | [Pricing](https://circleci.com/pricing) |
|[Code Climate](https://www.codeclimate.com/) | Hosted platform to continuously measure and monitor code quality | Languages: Ruby, Javascript, PHP | GitHub, Custom | [Documentation](http://docs.codeclimate.com/) | [14-day Trial](https://codeclimate.com/pricing) |
|[CodeFresh](https://codefresh.io/) | Codefresh is a Docker-native CI/CD platform. Instantly build, test and deploy Docker images to Kubernetes | Languages: Ruby, Python, Node.js, JavaScript, PHP, Go, Rust, Java, etc | GitHub, BitBucket, GitLab, Webhooks | [Documentation](https://docs.codefresh.io/) | [Pricing](https://codefresh.io/pricing/) |
|[Codeship](https://www.codeship.io/) | One more cloud based CI service: running tests and deployment | Languages: Dart, Elixir, Go, Java and JVM based languages, PHP, Python, Node.JS, Ruby | GitHub, BitBucket | [Documentation](https://www.codeship.io/documentation) [Free ebook](http://ebooks.codeship.io/efficiency-in-development-workflows-by-codeship/) | [Free for opensource projects or 100 builds per month](https://www.codeship.io/pricing) |
|[Concourse CI](http://concourse.ci/) | Self-hosted CI solution written in Golang |  | GitHub, generic oAuth | [Documentation](https://concourse.ci/introduction.html) | Free (Open source)  |
|[continuousphp](https://continuousphp.com/) | Continuous Integration and deployment for projects writtn in PHP | Languages: PHP | GitHub, BitBucket, GitLab | [Documentation](https://continuousphp.com/documentation/) | [Free for Open source and educational projects](https://continuousphp.com/plans/)  |
|[Coveralls](https://coveralls.io) | Coveralls works with your continuous integration server to give you test coverage history and statistics. | Languages: Ruby, Javascript, Python, PHP, C, Objective-C, Scala, GO | GitHub, BitBucket | [Documentation](https://coveralls.zendesk.com/hc/en-us) | [Free for opensource projects](https://coveralls.io/pricing) |
|[Coverity](http://www.coverity.com) | Code analysis, test analysis | Languages: C/C++, Java, C# | | None | [Free for opensource projects](http://softwareintegrity.coverity.com/free-trial-coverity.html) |
|[Drone](https://drone.io/) | Continuous Integration service | [Source code](https://github.com/drone/drone) is available. | GitHub,BitBucket, Google Code, Custom | [Documentation](http://docs.drone.io/) | [Pricing](https://drone.io/cloud/) |
|[Ebert](https://ebertapp.io/) | Ebert does continuous static analysis of your GitHub repositories and delivers it straight to your Pull Requests, helping your team to focus on what's important and deliver better software. | Languages: Apex, C, Clojure, CoffeeScript, CSS, Elixir, Go, Haskell, Haxe, JavaScript, Markdown, PHP, Python, Ruby, SCSS, Shell, Swift, Vim script. | GitHub | [Documentation](https://ebertapp.io/docs) | [100% free for public repositories on GitHub](https://ebertapp.io/#pricing) |
|[GoCD](https://gocd.io/) | Open source, on-premises continuous delivery tool. | | Git, Perforce, Mercurial,Subversion, TFS, [Custom](https://gocd.io/plugins) | [Documentation](https://docs.gocd.io/) | [Open Source](https://gocd.io/download) |
|[Hound CI](https://houndci.com/) | Review your JavaScript, CoffeeScript, and Ruby code for style guide violations with a trusty hound. | | GitHub | | [Public repositories for free](https://houndci.com/) |
|[Hydra](https://nixos.org/hydra/) | Nix-based continuous build system | | | [Documentation](https://nixos.org/hydra/manual/) | Opensource (GNU GPLv3)
|[Probo.CI](https://probo.ci/) | Continuous Collaboration -  break down the barriers between software developers and the other stakeholders involved in a software development project | Underlying engine is OSS, offers several Ubuntu base images, asset pre-upload helps build speed. | GitHub, BitBucket | [Documentation](https://docs.probo.ci/) | 2 month free trial then starts at $30. [Pricing](https://probo.ci/pricing/) |
|[Rocro INSPECODE](https://rocro.com/) | Review less, move faster. Speed up your software development with Inspecode’s continuous code inspection and automated code correction. | Languages: Java, JavaScript, C, C++, Python, Ruby, PHP, Go, Scala, TypeScript, Clojure and more... | GitHub, BitBucket | [Documentation](https://inspecode.rocro.com/help/) | [Free with limitations](https://rocro.com/inspecode/pricing) |
|[Saucelabs](https://saucelabs.com/) | Automated testing in the cloud for CI | | | [Documentation](https://docs.saucelabs.com/) | [14-day Trial](https://saucelabs.com/pricing) |
|[Scrutinizer](https://scrutinizer-ci.com/) | Build quality software, better | [Sources](https://github.com/scrutinizer-ci) are available | GitHub, BitBucket | [Documentation](https://scrutinizer-ci.com/docs/) | [14-day Trial](https://scrutinizer-ci.com/pricing) |
|[Semaphore](https://semaphoreci.com/) | Hosted continuous integration and delivery solution for open source and private projects. | Ruby, Node.js, JavaScript, Go, Clojure, Elixir, Erlang, Java, PHP, Scala, C/C++  | GitHub, BitBucket | [Documentation](https://semaphoreci.com/docs/) | [Free for Open Source, 100 free builds for private projects](https://semaphoreci.com/pricing) |
|[Shippable](https://www.shippable.com/) | Continuous Delivery | Languages: Ruby, Python, Java, Node.js, Scala, PHP, Go; Databases: MongoDB, MySQL, Redis, Postgres, CouchDB, RethinkDB, Neo4j, and SQLite | GitHub, BitBucket, GitLab | [Documentation](http://docs.shippable.com/) | [Free with limitations](https://www.shippable.com/pricing.html) |
|[Sider](https://sider.review/) | Increase code review efficiency and deliver products with confidence. Sider helps development teams accomplish more, allowing them to deliver more value to their customers. | [Supported Analysis Tools](https://sider.review/en/features/tools) | GitHub | [Documentation](https://help.sider.review/) | [Free 14-day trial for private repositories, and forever free for open source](https://sider.review/pricing) |
|[Solano CI](https://www.solanolabs.com/) | Hosted service that runs your test suite on a distributed infrastructure - fast | Also offers self-hosted, virtual appliance version called Solano Private CI, used by [Airbnb](http://nerds.airbnb.com/testing-at-airbnb/). | GitHub, BitBucket, GitLab, Custom | [Documentation](http://docs.solanolabs.com/) | [14-day Trial](https://ci.solanolabs.com/signups/new) |
|[StyleCI](https://styleci.io/) | The Web Coding Style Service, used by [Cachet](https://cachethq.io/) and [Laravel](https://laravel.com/). | Languages: PHP, JavaScript, TypeScript, Flow, CSS, SCSS, Less, Vue.js, Python | GitHub, BitBucket, GitLab | [Documentation](https://styleci.readme.io/) | [Free for opensource projects](https://styleci.io) |
|[TeamCity](https://www.jetbrains.com/teamcity/) | A Java-based build management and continuous integration server from JetBrains. | Support [wide variety of web browsers and build tools](https://confluence.jetbrains.com/display/TCD10/Supported+Platforms+and+Environments#SupportedPlatformsandEnvironments-BuildRunners) | Git, Subversion, Perforce, Team Foundation Server, Mercurial, CVS, SourceGear Vault 6 and 7, Borland StarTeam 6 and up, IBM Rational ClearCase, Base and UCM modes, Microsoft Visual SourceSafe 6 and 2005 | [Documentation](https://confluence.jetbrains.com/display/TCD10/TeamCity+Documentation) | [Free with limitations](https://www.jetbrains.com/teamcity/buy/#license-type=new-license) |
|[Travis CI](https://travis-ci.org/) | Hosted continuous integration service for open source and private projects. | Languages: C, C++, Clojure, D, Erlang, Go, Groovy, Haskell, Java, Javascript (with Node.js), Objective-C, Perl, PHP, Python, Ruby, Rust, Scala. [Source code](https://github.com/travis-ci/travis-ci) is available. | GitHub | [Documentation](http://docs.travis-ci.com/user/getting-started/) | [Free for opensource projects](https://travis-ci.com/plans) |
|[Visual Studio Team Services](https://www.visualstudio.com/team-services/) | Cloud-based collaboration services for version control, agile planning, continuous delivery, and analytics application for Visual Studio, Eclipse, Xcode.  | | Visual Studio Team Services, GitHub, Custom |  [Documentation](https://www.visualstudio.com/en-us/docs/overview) | [Free](https://www.visualstudio.com/products/free-developer-offers-vs.aspx) with [monthly build limits](https://www.visualstudio.com/en-us/docs/setup-admin/team-services/get-more-build-or-load-testing-vs) |
|[Wercker](https://app.wercker.com) | Continuous delivery platform | | Docker Hub | [Documentation](https://devcenter.wercker.com/) | | |



### License

[![CC0 Public Domain](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sergey Bronnikov](https://bronevichok.ru) has
waived all copyright and related or neighboring rights to this work.
