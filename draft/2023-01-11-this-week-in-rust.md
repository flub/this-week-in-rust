Title: This Week in Rust 477
Number: 477
Date: 2023-01-11
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) on Twitter or [@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the Linked Page](https://example.com/my_article)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Official
* [Updating the Android NDK in Rust 1.68](https://blog.rust-lang.org/2023/01/09/android-ndk-update-r25.html)
* [Announcing Rust 1.66.1](https://blog.rust-lang.org/2023/01/10/Rust-1.66.1.html)
* [Security advisory for Cargo (CVE-2022-46176)](https://blog.rust-lang.org/2023/01/10/cve-2022-46176.html)

### Foundation
* [Introducing Our Newest Project Grantees](https://foundation.rust-lang.org/news/community-grants-program-awards-announcement-introducing-our-latest-project-grantees/)

### Newsletters
* [This Month in Rust OSDev: December 2022](https://rust-osdev.com/this-month/2022-12/)
* [Rust Nigeria newsletter Issue 13](https://rustnigeria.curated.co/issues/13)

### Project/Tooling Updates
* [Announcing turmoil](https://tokio.rs/blog/2023-01-03-announcing-turmoil)
* [rust-analyzer changelog #163](https://rust-analyzer.github.io/thisweek/2023/01/09/changelog-163.html)
* [rustc_codegen_gcc: Progress Report #19](https://blog.antoyo.xyz/rustc_codegen_gcc-progress-report-19)
* [Fyrox 0.29 Feature Highlights](https://fyrox.rs/blog/post/feature-highlights-0-29/)

### Observations/Thoughts
* [Rust Atomics and Locks by Mara Bos](https://marabos.nl/atomics/)
* [Oh the Crates You'll Go! A 2022 Retrospective](https://jack.wrenn.fyi/blog/2022-retrospective/)
* [Rust for Java developers, an introduction](https://wcgw.dev/posts/2023/rusty-java-intro/)
* [On Random Numbers](https://matklad.github.io/2023/01/04/on-random-numbers.html)
* [Potential DoS Vulnerability in Rust Hyper](https://jfrog.com/blog/watch-out-for-dos-when-using-rusts-popular-hyper-package/)
* [Is coding in Rust as bad as in C++?](https://quick-lint-js.com/blog/cpp-vs-rust-build-times/)
* [Rust vs C++ Formatting](https://brevzin.github.io/c++/2023/01/02/rust-cpp-format/)
* [My impressions of Rust after a year of working with it](https://reltech.substack.com/p/my-impressions-of-rust-after-a-year)
* [audio] [Fermyon with Matt Butcher](https://rustacean-station.org/episode/matt-butcher/)

### Rust Walkthroughs
* [Testing SIMD instructions on ARM with Rust on Android](https://gendignoux.com/blog/2023/01/05/rust-arm-simd-android.html)
* [Running Zola on WebAssembly](https://dstaley.com/posts/running-zola-on-wasm/)
* [Who needs Haskell? Straight to Rust Hell](https://www.jernesto.com/articles/who_needs_haskell.html)
* [Sharing Data Among Tasks in Rust Embassy: Synchronization Primitives](https://apollolabsblog.hashnode.dev/sharing-data-among-tasks-in-rust-embassy-synchronization-primitives)

### Research

### Miscellaneous

## Crate of the Week

<!-- COTW goes here -->

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Call for Participation

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [Rust Playground - Call for contributors](https://users.rust-lang.org/t/call-for-contributors-to-the-rust-playground-for-upcoming-features/87110)
* [meilisearch - When the `lat` and `lng` are strings the wrong error message is returned](https://github.com/meilisearch/meilisearch/issues/3007)
* [meilisearch - Bad latitude / Bad longitude should share a common message between the invalid sort and invalid filte](https://github.com/meilisearch/meilisearch/issues/3006)
* [meilisearch - When both `lat` and `lng` are missing it doesn't return the right error](https://github.com/meilisearch/meilisearch/issues/3005)
* [meilisearch - We must return an error for when _geo is not an object](https://github.com/meilisearch/meilisearch/issues/3003)
* [diesel - A pure rust postgres diesel connection](https://github.com/sfackler/rust-postgres/issues/890)
* [diesel - A pure rust mysql diesel connection implementation](https://github.com/blackbeam/rust-mysql-simple/discussions/320)

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

## Updates from the Rust Project

<!-- Rust updates go here -->

### Rust Compiler Performance Triage

<!-- Perf results go here -->

### Call for Testing

An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.  The following
RFCs would benefit from user testing before moving forward:

<!-- Pre-Stabilization RFCs go here -->

<!-- RFC and FCP sections go here -->

## Upcoming Events

Rusty Events between 2023-01-11 - 2023-02-08 🦀

### Virtual

* 2023-01-04 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs/)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/qwtdjsyfccbgb/)
* 2023-01-04 | Virtual (Stuttgart, DE) | [Rust Community Stuttgart](https://www.meetup.com/Rust-Community-Stuttgart/)
    * [**Rust-Meetup**](https://www.meetup.com/rust-community-stuttgart/events/dvvtvsyfccbgb/)
* 2023-01-05 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/)
    * [**Part 2: Exploring USB with Rust**](https://www.meetup.com/charlottesville-rust-meetup/events/290122605/)
* 2023-01-10 | Virtual (Dallas, TX, US) | [Dallas Rust](https://www.meetup.com/Dallas-Rust/)
    * [**Second Tuesday**](https://www.meetup.com/dallas-rust/events/vndgwsyfccbnb/)
* 2023-01-11 | Virtual (Boulder, CO, US) | [Boulder Elixir and Rust](https://www.meetup.com/boulder-elixir-rust/) 
    * [**Monthly Meetup**](https://www.meetup.com/boulder-elixir-rust/events/290277662/)
* 2023-01-12 | Virtual (San Francisco, CA, US; Stockholm, SE; New York, NY US) | [Microsoft Reactor San Francisco](https://www.meetup.com/microsoft-reactor-san-francisco/) | [Microsoft Reactor New York](https://www.meetup.com/microsoft-reactor-new-york/)
    * [**Crack code interview problems in Rust - Ep. 1**](https://www.meetup.com/microsoft-reactor-san-francisco/events/290071417/) | [**Stockholm Mirror**](https://www.meetup.com/microsoft-reactor-stockholm/events/290071415/) | [**New York Mirror**](https://www.meetup.com/microsoft-reactor-new-york/events/290071420/)
* 2023-01-12 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/hlvbvsyfccbqb/)
* 2023-01-14 | Virtual | [Rust GameDev](https://gamedev.rs/)
    * [**Rust GameDev Monthly Meetup**](https://www.google.com/url?q=https%3A%2F%2Fdiscord.gg%2FyNtPTb2&sa=D&ust=1666661760000000&usg=AOvVaw13uHY9m-8bJJwgeP58VS8l)
* 2023-01-16 | Virtual (San Francisco, CA, US; São Paulo, BR; New York, NY, US) | [Microsoft Reactor San Francisco](https://www.meetup.com/microsoft-reactor-san-francisco/) and [Microsoft Reactor São Paulo](https://www.meetup.com/microsoft-reactor-sao-paulo/) and [Microsoft Reactor New York](https://www.meetup.com/microsoft-reactor-new-york/)
    * [**Primeros pasos con Rust - Qué es y Configuración el entorno de desarrollo**](https://www.meetup.com/microsoft-reactor-san-francisco/events/290224512/) | [**São Paulo Mirror**](https://www.meetup.com/microsoft-reactor-sao-paulo/events/290224516/) | [**New York Mirror**](https://www.meetup.com/microsoft-reactor-new-york/events/290224515/)
* 2023-01-17 | Virtual (Berlin, DE) | [OpenTechSchool Berlin](https://www.meetup.com/opentechschool-berlin/)
    * [**Rust Hack and Learn**](https://www.meetup.com/opentechschool-berlin/events/289581080/)
* 2023-01-17 | Virtual (San Francisco, CA, US; São Paulo, BR, New York, NY, US) | [Microsoft Reactor San Francisco](https://www.meetup.com/microsoft-reactor-san-francisco/) and [Microsoft Reactor São Paulo](https://www.meetup.com/microsoft-reactor-sao-paulo/) and [Microsoft Reactor New York](https://www.meetup.com/microsoft-reactor-new-york/events/290224518/)
    * [**Primeros pasos con Rust - Creación del primer programa de Rust**](https://www.meetup.com/microsoft-reactor-san-francisco/events/290224517/) | [***São Paulo Mirror**](https://www.meetup.com/microsoft-reactor-sao-paulo/events/290224521/) | [**New York Mirror**](https://www.meetup.com/microsoft-reactor-new-york/events/290224518/)
* 2023-01-17 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc/)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/289015967/)
* 2023-01-18 | Virtual (San Francisco, CA, US; São Paulo, BR; New York, NY US) | [Microsoft Reactor San Francisco](https://www.meetup.com/microsoft-reactor-san-francisco/) and [Microsoft Reactor São Paulo](https://www.meetup.com/microsoft-reactor-sao-paulo/) and [Microsoft Reactor New York](https://www.meetup.com/microsoft-reactor-new-york/events/290224518/)
    * [**Primeros pasos con Rust: QA y horas de comunidad**](https://www.meetup.com/microsoft-reactor-san-francisco/events/290224523/) | [**Sao Paulo Mirror**](https://www.meetup.com/microsoft-reactor-sao-paulo/events/290224522/) | [**New York Mirror**](https://www.meetup.com/microsoft-reactor-new-york/events/290224525/)
* 2023-01-18 | Virtual (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust/)
    * [**Rust Study/Hack/Hang-out**](https://www.meetup.com/vancouver-rust/events/tqvhxsyfccbxb/)
* 2023-01-26 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup/)
    * [**Rust Lightning Talks!**](https://www.meetup.com/charlottesville-rust-meetup/events/290122935/)
* 2023-01-31 | Virtual (Dallas, TX, US) | [Dallas Rust](https://www.meetup.com/Dallas-Rust/)
    * [**Last Tuesday**](https://www.meetup.com/dallas-rust/events/qndgwsyfccbpc/)
* 2023-02-01 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs/)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/qwtdjsyfcdbcb/)

### Asia

* 2023-01-15 | Tokyo, JP | [Tokyo Rust Meetup](https://www.meetup.com/tokyo-rust-meetup)
    * [**Property-Based Testing in Rust**](https://www.meetup.com/tokyo-rust-meetup/events/290667325/)

### Europe

* 2023-01-12 | Enschede, NL | [Dutch Rust Meetup](https://www.meetup.com/dutch-rust-meetup/)
    * [**Rust Meetup - Subject TBA**](https://www.meetup.com/dutch-rust-meetup/events/289021643/)
* 2023-01-20 | Stuttgart, DE | [Rust Community Stuttgart](https://www.meetup.com/Rust-Community-Stuttgart/)
    * [**OnSite Meeting**](https://www.meetup.com/rust-community-stuttgart/events/zmppzsyfccbbc/)
* 2023-01-25 | Paris, FR | [Rust Paris](https://www.meetup.com/rust-paris/)
    * [**Rust Paris meetup #55**](https://www.meetup.com/rust-paris/events/290100223/)


### North America

* 2023-01-05 | Lehi, UT, US | [Utah Rust](https://www.meetup.com/utah-rust/)
    * [**Lightning Talks 'n' Chill (a.k.a. Show & Tell), with Pizza!**](https://www.meetup.com/utah-rust/events/dsbpxsydcqbdc/)
* 2023-01-09 | Minneapolis, MN, US | [Minneapolis Rust Meetup](https://www.meetup.com/minneapolis-rust-meetup/)
    * [**Happy Hour and Beginner Embedded Rust Hacking Session (#2!)**](https://www.meetup.com/minneapolis-rust-meetup/events/289768841/)
* 2023-01-11 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx/)
    * [**Rust Lunch**](https://www.meetup.com/rust-atx/events/290597764/)
* 2023-01-17 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group/)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/rwvwzsyfccbwb/)
* 2023-01-26 | Copenhagen, DK | [Copenhagen Rust group](https://www.meetup.com/copenhagen-rust-meetup-group/)
    * [**Rust Hack Night #32**](https://www.meetup.com/copenhagen-rust-meetup-group/events/290037532/)
* 2023-01-26 | Lehi, UT, US | [Utah Rust](https://www.meetup.com/utah-rust/)
    * [**Building a Rust Playground with WASM and Lane and Food!**](https://www.meetup.com/utah-rust/events/dsbpxsyfccbjc/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org


<!--

Rust Jobs:

TWiR has stopped featuring individual job postings. You can read more about this change here:

https://github.com/rust-lang/this-week-in-rust/issues/3412

-->

## Jobs

Please see the latest [Who's Hiring thread on r/rust](INSERT_LINK_HERE)

# Quote of the Week

<!-- QOTW goes here -->

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [andrewpollack](https://github.com/andrewpollack), [U007D](https://github.com/U007D), [kolharsam](https://github.com/kolharsam), [joelmarcey](https://github.com/joelmarcey), [mariannegoldin](https://github.com/mariannegoldin), [bennyvasquez](https://github.com/bennyvasquez).*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](REDDIT_LINK_HERE)</small>