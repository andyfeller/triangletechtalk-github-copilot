# Copilot Capabilities

- [IDE](#ide)
  - [IDE dependency context awareness](#ide-dependency-context-awareness)
  - [Visual Studio Code](#visual-studio-code)
  - [Visual Studio](#visual-studio)
  - [JetBrains](#jetbrains)
  - [Neovim](#neovim)
- [Partner Program](#partner-program)

For more information, see [GitHub Documentation collection](documentation.md)

## IDE

As of February 2024, there is no singular comprehensive source of information about the various GitHub Copilot IDE extensions outside of
[GitHub Docs "Getting started with GitHub Copilot"](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot).

Everything captured here is attempting to aggregate information from separate sources including homepages, documentation, and videos.

### IDE dependency context awareness

Some GitHub Copilot extensions use information about your project dependencies and programming language to improve completions such as:

- Application frameworks
- Build tools
- Core libraries
- Testing frameworks
- Testing libraries

<details>
<summary>
  <b>C / C++</b>
</summary>
<p>

**Application frameworks**

- libc
- libcurl
- libevent
- libuv
- openssl
- zlib

**Build tools**

- autotools
- clang
- cmake
- gcc
- make
- meson
- ninja

**Core libraries**

- libjpeg
- libpng
- libxml2
- mysql
- postgres
- sqlite

**Testing frameworks**

- check
- cmocka
- criterion
- ctest
- minunit
- unity

**Testing libraries**

- cmock
- fakeit
- fff
- trompeloil

</p>
</details> 

<details>
<summary>
  <b>C#</b>
</summary>
<p>

**Application frameworks**

- Microsoft.AspNetCore.App
- Microsoft.NETCore.App

**Build tools**

- Cake
- dotnet
- MSBuild

**Core libraries**

- AutoMapper
- Dapper
- EntityFramework
- FlientValidation
- Hangfire
- MassTransit
- MediatR
- Microsoft.Extensions.Configuration
- Microsoft.Extensions.DependencyInjection
- Microsoft.Extensions.Http
- Microsoft.Extensions.Logging
- Newtonsoft.Json
- Polly
- RabbitMQ.Client
- Serilog

**Testing frameworks**

- NUnit
- SpecFlow
- xunit

**Testing libraries**

- Bogus
- FluentAssertions
- Moq
- RestSharp
- Swashbuckle.AspNetCore

</p>
</details> 

<details>
<summary>
  <b>Dart</b>
</summary>
<p>

**Application frameworks**

- AngularDar
- Flutter

**Build tools**

- build_runner
- pub

**Core libraries**

- dartx
- dio
- equatable
- freezed
- get_it
- hive
- http
- intl
- json_serializable
- moor
- path
- provider
- rxdart

**Testing frameworks**

- flutter_test
- test

**Testing libraries**

- bloc_test
- mockito

</p>
</details> 

<details>
<summary>
  <b>Go</b>
</summary>
<p>

**Application frameworks**

- astaxie/beego
- gin-gonic/gin
- go-chi/chi
- go-martini/martini
- gobuffalo/buffalo
- goji/goji
- gorilla/mux
- hoisie/web
- labstack/echo
- revel/revel

**Build tools**

- ant
- bazel
- boot
- go
- grade
- grunt
- leiningen
- make
- maven
- sbt

**Core libraries**

- encoding/json
- fmt
- io
- math
- net/http
- sort
- strconv
- strings
- time

**Testing frameworks**

- DATA-DOG/godog
- gopkg.in/check.v1
- onsi/ginkgo
- onsi/gomega
- rjeczalik/gotest
- smartystreets/goconvey
- stesla/gospec
- stretchr/testify

**Testing libraries**

- DATA-DOG/godog
- golang/mock
- gopkg.in/check.v1
- onsi/ginkgo
- onsi/gomega
- rjeczalik/gotest
- smartystreets/goconvey
- stesla/gospec
- stretchr/testify

</p>
</details> 

<details>
<summary>
  <b>Java / Kotlin / Scala / Groovy</b>
</summary>
<p>

**Application frameworks**

- [Apache Struts](https://struts.apache.org/)
- [Apache Wicket](https://wicket.apache.org/)
- [Gradle](https://gradle.org/)
- [Grails](https://grails.org/)
- [Hibernate](https://hibernate.org/)
- [Jakarta EE](https://jakarta.ee/)
- [Java EE](https://www.oracle.com/java/technologies/java-ee-glance.html)
- [JavaServer Faces](https://www.oracle.com/java/technologies/javaserverfaces.html)
- [Spring Boot](https://spring.io/projects/spring-boot)

**Build tools**

- [Maven](https://maven.apache.org/)

**Core libraries**

- [Apache Commons Collections](https://commons.apache.org/proper/commons-collections/)
- [Apache Commons IO](https://commons.apache.org/proper/commons-io/)
- [Apache Commons Lang](https://commons.apache.org/proper/commons-lang/)
- [Apache Commons Math](https://commons.apache.org/proper/commons-math/)
- [Apache Commons Net](https://commons.apache.org/proper/commons-net/)
- [Apache POI](https://poi.apache.org/)
- [Google Gson](https://github.com/google/gson)
- [Google Guava](https://github.com/google/guava)
- [Jackson](https://github.com/FasterXML/jackson)
- [Joda-Time](https://www.joda.org/joda-time/)

**Testing frameworks**

- [Arquillian](https://arquillian.org/)
- [Cucumber](https://cucumber.io/)
- [JUnit 4](https://junit.org/junit4/)
- [JUnit 5](https://junit.org/junit5/)
- [Spock](https://spockframework.org/)
- [TestNG](https://testng.org/)

**Testing libraries**

- [AssertJ](https://assertj.github.io/doc/)
- [DBUnit](https://www.dbunit.org/)
- [EasyMock](https://easymock.org/)
- [Gatling](https://gatling.io/)
- [Greenmail](https://greenmail-mail-test.github.io/greenmail/)
- [Hamcrest](https://hamcrest.org/)
- [HTMLUnit](https://htmlunit.sourceforge.io/)
- [JMeter](https://jmeter.apache.org/)
- [JMock](http://jmock.org/)
- [JMockit](https://jmockit.github.io/)
- [Mockito](https://site.mockito.org/)
- [PowerMock](https://powermock.github.io/)
- [REST-Assured](https://rest-assured.io/)
- [Selenium](https://www.selenium.dev/)
- [WireMock](https://wiremock.org/)

</p>
</details> 

<details>
<summary>
  <b>JavaScript / TypeScript / Vue</b>
</summary>
<p>

**Application frameworks**

- [Angular](https://www.npmjs.com/package/@angular/core)
- [Aurelia](https://www.npmjs.com/package/aurelia)
- [Backbone.js](https://www.npmjs.com/package/backbone)
- [Dojo Toolkist](https://www.npmjs.com/package/dojo)
- [Ember](https://www.npmjs.com/package/ember-source)
- [Hyperapp](https://www.npmjs.com/package/hyperapp)
- [Inferno](https://www.npmjs.com/package/inferno)
- [Knockout.js](https://www.npmjs.com/package/knockout)
- [Marionette.js](https://www.npmjs.com/package/marionette)
- [Marko.js](https://www.npmjs.com/package/marko)
- [Meteor](https://www.npmjs.com/package/meteor)
- [Mithril.js](https://www.npmjs.com/package/mithril)
- [Moon.js](https://www.npmjs.com/package/moon)
- [Node.js](https://nodejs.org/en)
- [Polymer](https://www.npmjs.com/package/@polymer/polymer)
- [Preact](https://www.npmjs.com/package/preact)
- [React Native](https://www.npmjs.com/package/react-native)
- [React](https://www.npmjs.com/package/react)
- [Riot.js](https://www.npmjs.com/package/riot)
- [Stencil.js](https://www.npmjs.com/package/@stencil/core)
- [Svelte](https://www.npmjs.com/package/svelte)
- [Vue.js](https://www.npmjs.com/package/vue)

**Build tools**

- browserify
- esbuild
- grunt
- gulp
- npm
- parcel
- rollup
- webpack
- yarn

**Core libraries**

- [Axios](https://www.npmjs.com/package/axios)
- [Cheerio](https://www.npmjs.com/package/cheerio)
- [D3.js](https://www.npmjs.com/package/d3)
- [Express.js](https://www.npmjs.com/package/express)
- [Immutable.js](https://www.npmjs.com/package/immutable)
- [jQuery](https://www.npmjs.com/package/jquery)
- [Lodash](https://www.npmjs.com/package/lodash)
- [Moment.js](https://www.npmjs.com/package/moment)
- [Next.js](https://www.npmjs.com/package/next)
- [Nodemailer](https://www.npmjs.com/package/nodemailer)
- [Puppeteer](https://www.npmjs.com/package/puppeteer)
- [Ramda](https://www.npmjs.com/package/ramda)
- [Recoil](https://www.npmjs.com/package/recoil)
- [Redux](https://www.npmjs.com/package/redux)
- [RxJS](https://www.npmjs.com/package/rxjs)
- [Socket.io](https://www.npmjs.com/package/socket.io)
- [Three.js](https://www.npmjs.com/package/three)
- [Underscore.js](https://www.npmjs.com/package/underscore)

**Testing frameworks**

- [AVA](https://www.npmjs.com/package/ava)
- [Jasmine](https://www.npmjs.com/package/jasmine)
- [Jest](https://www.npmjs.com/package/jest)
- [Mocha](https://www.npmjs.com/package/mocha)
- [QUnit](https://www.npmjs.com/package/qunit)
- [Tape](https://www.npmjs.com/package/tape)

**Testing libraries**

- [Chai](https://www.npmjs.com/package/chai)
- [Cypress](https://www.npmjs.com/package/cypress)
- [Enzyme](https://www.npmjs.com/package/enzyme)
- [Nock](https://www.npmjs.com/package/nock)
- [Protractor](https://www.npmjs.com/package/protractor)
- [React Testing Library](https://www.npmjs.com/package/@testing-library/react)
- [Sinon](https://www.npmjs.com/package/sinon)
- [Supertest](https://www.npmjs.com/package/supertest)

</p>
</details> 

<details>
<summary>
  <b>PHP</b>
</summary>
<p>

**Application frameworks**

- bcosca/fatfree
- cakephp/cakephp
- fuel/fuel
- laravel/framework
- phalcon/cphalcon
- phpixie/framework
- slim/slim
- symfony/symfony
- yiisoft/yii2
- zendframework/zendframework

**Build tools**

- composer
- phing
- phpcbf
- phpcpd
- phpcs
- phpdcd
- phploc
- phpmd
- phpstan
- phpunit

**Core libraries**

- doctrine/orm
- guzzlehttp/guzzle
- monolog/monolog
- php-di/php-di
- phpunit/php-timer
- ramsey/uuid
- symfony/console
- symfony/finder
- symfony/yaml
- vlucas/phpdotenv

**Testing frameworks**

- atoum/atoum
- behat/behat
- codeception/codeception
- kahlan/kahlan
- peridot-php/peridot
- pestphp/pest
- phake/phake
- phpspec/phpspec
- phpunit/phpunit

**Testing libraries**

- mockery/mockery
- padraic/mockery
- php-mock/php-mock
- php-mock/php-mock-phpunit
- phpspec/prophecy
- phpunit/php-code-coverage
- phpunit/php-invoker
- phpunit/php-text-template
- phpunit/php-timer
- phpunit/php-token-stream

</p>
</details> 

<details>
<summary>
  <b>Python</b>
</summary>
<p>

**Application frameworks**

- Django
- FastAPI
- Flask
- Pyramid
- Tornado

**Build tools**

- conda
- flit
- nox
- paver
- pip
- pipenv
- poetry
- scons
- setuptools
- tox

**Core libraries**

- matplotlib
- numpy
- pandas
- requests
- scipy

**Testing frameworks**

- doctest
- nose
- pytest
- unittest

**Testing libraries**

- behave
- hypothesis
- lettuce
- mock
- pyhamcrest
- testify

</p>
</details> 

<details>
<summary>
  <b>Ruby</b>
</summary>
<p>

**Application frameworks**

- Cuba
- Grape
- Hanami
- Nyara
- Padrino
- Rack
- Rails
- Ramaze
- Roda
- Sinatra

**Build tools**

- bundler
- rake

**Core libraries**

- ActiveRecord
- Cassandra
- CouchRest
- DataMapper
- Mongoid
- Neo4j
- Redis
- Riak
- ROM
- Sequel

**Testing frameworks**

- Bacon
- Contest
- Cucumber
- Minitest
- RSpec
- Sohulda
- Spinach
- Test::Unit
- Turnip
- Wrong

**Testing libraries**

- Bourne
- Fabrication
- FactoryBot
- Faker
- FFaker
- FlexMock
- Machinist
- Mocha
- NotAMock
- RR

</p>
</details> 

<details>
<summary>
  <b>Rust</b>
</summary>
<p>

**Application frameworks**

- actix-web
- async-std
- hyper
- rocket
- tokio

**Build tools**

- cargo

**Core libraries**

- futures
- lazy_static
- libc
- log
- rand
- rayon
- regex
- reqwest
- serde
- warp

**Testing frameworks**

- proptest
- quickcheck
- test-case

**Testing libraries**

- double
- mock_derive
- mock_it
- mockall
- mockers
- mockiato
- mocktopus
- rstest

</p>
</details> 

### Visual Studio Code

Visual Studio Code is the premier IDE regarding GitHub Copilot support, backed by support from Microsoft Visual Studio Code and GitHub.

- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) _([docs](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot?tool=vscode))_
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) _([docs](https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide?tool=vscode))_
  _installed with GitHub Copilot extension_
- [VS Code Speech](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-speech)

Beyond information on the various Visual Studio Code extension homepages, the best information comes in the form of [GitHub Youtube videos](https://www.youtube.com/watch?v=vUX5u_4B2AM&list=PL0lo9MOBetEHEHi9h0k_lPn0XZdEeYZDS) like those produced by Christopher Harrison @geektrainer and those produced in the [Visual Studio Code Youtube channel](https://www.youtube.com/@code) like [GitHub Copilot series](https://www.youtube.com/playlist?list=PLj6YeMhvp2S5_hvBl2SE-7YCHYlLQ0bPt).

#### Slash commands, context variables, and agents

Long part of the Visual Studio Code extension experience, slash commands are used in conjunction with GitHub Copilot Chat to perform tasks on selected portions of content.  At [GitHub Universe 2023](https://code.visualstudio.com/blogs/2023/11/13/vscode-copilot-smarter),
these slash commands were reimagined as part of a larger native and custom agent extensibility effort:

- `@workspace` - Ask about your workspace
  - `/explain` - Explain how the selected code works
  - `/tests` - Generate unit tests for the selected code
  - `/fix` - Propose a fix for the problems in the selected code
  - `/new` - Scaffold code for a new workspace
  - `/newNotebook` - Create a new Jupyter Notebook

- `@vscode` - Ask about VS Code
  - `/api` - Ask about VS Code extension development

- `@terminal` - Ask how to do something in the terminal
- `/help` - Ask for help on using VS Code extension

Lastly, Visual Studio Code team has been working on how users can create their own [custom client-side chat agents](https://code.visualstudio.com/blogs/2023/11/13/vscode-copilot-smarter#_extensibility) to expand GitHub Copilot capabilities:

- [Proposed API](https://code.visualstudio.com/api/advanced-topics/using-proposed-api)
- [Sample custom client-side chat agent `@cat`](https://github.com/microsoft/vscode-extension-samples/tree/main/chat-sample) 

### Visual Studio

- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilotvs) _([docs](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot?tool=visualstudio))_
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.VSGitHubCopilot) _([docs](https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide?tool=visualstudio))_

#### Slash commands, context variables

Introduced in [GitHub Blog Jan 30 2024 "Code faster and better with GitHub Copilot's new features in Visual Studio"](https://github.blog/changelog/2024-01-30-code-faster-and-better-with-github-copilots-new-features-in-visual-studio/),
slash commands are used in conjunction with GitHub Copilot Chat to perform tasks on selected portions of content while context variables allow users to include specified files as part of GitHub Copilot requests:

- `/doc` - add a documentation comment
- `/explain` - explain the code
- `/fix` - propose a fix for the problems in the selected code
- `/generate` - generate code to answer your question
- `/help` - get help with Copilot Chat
- `/optimize` - analyze and improve the running time of the selected code
- `/tests` - create unit tests for the selected code

Multiple context variables are available out of the box and with preview features enabled:

- `#file` - specific file to include in request
- `#solution` - preview feature to have Copilot search your solution for relevant code to the question

### JetBrains

- [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot) _([docs](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot?tool=jetbrains), [chat docs](https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide?tool=jetbrains_beta))_
  _GitHub Copilot Chat private beta is _

### Neovim

- [GitHub Copilot plugin](https://github.com/github/copilot.vim)
- [GitHub Copilot Chat plugin (unofficial)](https://github.com/CopilotC-Nvim/CopilotChat.nvim)

## Partner Program

Source: https://youtu.be/NrQkdDVupQE?t=1787
Sign up: https://github.com/features/preview/copilot-partner-program

![Listing of 3rd party partners announced to be working on GitHub Copilot integrations](https://github.com/andyfeller/triangletechtalk-github-copilot/assets/2089743/157b9249-819a-4c3b-9c89-07dd5508e819)

![Demonstration of leveraging GitHub Copilot chat using 3rd party partner](https://github.com/andyfeller/triangletechtalk-github-copilot/assets/2089743/0204a7ea-851d-432d-b2ec-5501a5c73a25)

Listed:

- [42Crunch](https://42crunch.com/)
- [Astronomer](https://www.astronomer.io/)
- [Databricks](https://www.databricks.com/)
- [DataDog](https://www.datadoghq.com/)
- [DataStax](https://www.datastax.com/)
- [Docker](https://www.docker.com/)
- [Endor Labs](https://www.endorlabs.com/)
- [Evinced](https://www.evinced.com/)
- [Honeycomb](https://www.honeycomb.io/)
- [Gretel](https://gretel.ai/)
- [HashiCorp](https://www.hashicorp.com/)
- [LaunchDarkly](https://launchdarkly.com/)
- [Microsoft](https://microsoft.com/)
- [New Relic](https://newrelic.com/)
- [NowSecure](https://www.nowsecure.com/)
- [Octopus Deploy](https://octopus.com/)
- [Plotly](https://plotly.com/)
- [Postman](https://www.postman.com/)
- [Pulumi](https://www.pulumi.com/)
- [Readme](https://readme.com/)
- [Red Hat](https://www.redhat.com/en)
- [Sentry](https://sentry.io/)
- [Split](https://split.io/)
- [Swimm](https://swimm.io/)
- [Tricentis](https://www.tricentis.com/)
- [Trunk](https://trunk.io/)
