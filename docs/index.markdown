---
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# To build locally:
# [sudo] gem install jekyll
# bundle exec jekyll serve
layout: home
title: About Me
tags: ios, engineer, staff, senior, software, buf, protobuf, grpc, grpc-web, protocol, buffers, california, lyft, airbnb, mobile, apis, networking, connect, path, travel, envoy, app
---

![ProfilePhoto]({{ site.asset_baseurl }}/full/profile.png){:style="float: right; margin-right: 7px; margin-top: 7px; width: 200px; height: 200px;"}
Hey there! I'm Michael Rebello. I've been doing iOS development since iOS 4,
and am currently a Staff Engineer on Airbnb's Client Data & Networking team.

Most recently, I worked as a cross between a software engineer and a
product manager at [Buf](https://buf.build) where I authored and still maintain
[Connect-Swift](https://github.com/connectrpc/connect-swift),
a Protobuf RPC library that is [part of the CNCF](https://github.com/cncf/sandbox/issues/63).
Prior, I was a [Staff Engineer at Lyft](#lyft) for 6 years and
[co-founded a social travel company called Path](#path). Before that,
I worked in enterprise SaaS and started and sold two small software companies.

As a way of giving back, my wife and I created and run the [Papai Foundation](#papai-foundation),
and I am on the board of [The 25 Group](#the-25-group).

I currently live in San Diego with my wife Milla, our daughter Kaya,
and our 3 cats (Bailey, June, and Walter).
In my free time, I enjoy baking, hiking, surfing, bouldering, and learning
to speak Russian.

This page contains a little bit about my work background – feel free to
[contact me](mailto:me@michaelrebello.com).

# Open Source

- [Connect-Swift](https://github.com/connectrpc/connect-swift): Author and current maintainer
- [Envoy Mobile](https://github.com/envoyproxy/envoy/blob/main/mobile/README.md): Founding member and former maintainer

# Public Talks

- (2023) Swift TO Conference: [A Better Way to Build APIs in Swift](https://www.youtube.com/watch?v=MO2aNPd363E)
- (2022) App Performance Cafe Podcast: [Abstracting Networking from the Application Layer](https://open.spotify.com/episode/1rDAnNa7YtbvNh0ZWKfup2)
- (2019) BA Swiftable Conference: [Envoy Mobile & The Upcoming Networking Revolution](https://www.youtube.com/watch?v=rMBrVfoQ7-g)
- (2019) Lyft Mobile Podcast: [Mobile Networking](https://lyftmobilepodcast.libsyn.com/mobile-networking)
- (2018) Swift Language User Group: [gRPC & iOS at Lyft](https://www.youtube.com/watch?v=Go3_72i8bjI)

# Featured Posts

- Buf: [The real reason to use Protobuf is not performance](https://buf.build/blog/the-real-reason-to-use-protobuf)
- Buf: [Announcing Connect-Swift: You'll actually want to use Protobuf on iOS](https://buf.build/blog/announcing-connect-swift)
- Buf: [Connect-Swift v1.0](https://buf.build/blog/connect-swift-v1)
- Lyft Engineering: [Lyft's Journey Through Mobile Networking](https://eng.lyft.com/lyfts-journey-through-mobile-networking-d8e13c938166)
- Lyft Engineering: [Recovering from Crashes with Safe Mode](https://eng.lyft.com/recovering-from-crashes-with-safe-mode-77ff572fdfda)

# Work Experience

## <a name="airbnb"></a>[Airbnb](https://airbnb.com) - Staff (iOS) Engineer (2023 - Present)

I'm currently on the Client Data & Networking team at Airbnb. The team is responsible for Airbnb's in-house Web, iOS, and Android GraphQL clients, as well as for related infrastructure pertaining to schema discovery, runtime observability, and client schema development. I've recently been building some new infrastructure to automate GraphQL data mocking, and uploaded a short demo video [here](https://www.youtube.com/watch?v=gM3T_k6kR_o).

## <a name="buf"></a>[Buf](https://buf.build) - Member of Technical Staff (2022 - 2023)

I'm the author and a maintainer of [Connect-Swift](https://github.com/connectrpc/connect-swift), an open-source Protobuf RPC library in the [Connect ecosystem](https://www.connectrpc.com/) which recently [joined the CNCF](https://github.com/cncf/sandbox/issues/63). I was responsible for defining and leading other projects such as Buf's [breaking change governance flow](https://buf.build/solutions/prevent-breaking-changes) and [gateway solutions](https://buf.build/solutions/govern-apis-at-the-edge), represented the company at conferences, and managed its blog.

## <a name="lyft"></a>[Lyft](https://www.lyft.com) - Staff (iOS) Engineer (2016 - 2022)

After leading an architecture effort on the iOS driver app, I formed a “lab” team with 2 other iOS engineers to build and ship a [redesigned rider app](https://techcrunch.com/2017/11/08/lyft-is-testing-a-new-rider-experience-with-a-small-percentage-of-users) which boosted ride bookings and became the foundation for the current Lyft app. I led [Lyft's mobile-wide adoption of Protobuf APIs](https://eng.lyft.com/lyfts-journey-through-mobile-networking-d8e13c938166), authoring a Swift Protobuf generator in Go and partnering with product teams to achieve 100% adoption across mobile APIs at the company. I was also a founding member and maintainer of the open-source [Envoy Mobile](https://github.com/envoyproxy/envoy/blob/main/mobile/README.md) project (now part of the CNCF), and was responsible for writing Lyft's experimentation, analytics, and gRPC streaming components on iOS. Lastly, I led a new team on mobile infrastructure focused on networking and reliability, and was an editor of the [Lyft Engineering Blog](https://eng.lyft.com/).

## <a name="path"></a>[Path](https://www.crunchbase.com/organization/path-travel) - Co-Founder & CTO (2020 - 2022)

Co-founded [Path](https://www.crunchbase.com/organization/path-travel), a platform to find the best spots through short-form, relatable video reviews from local experts and recommendations from friends. In 2021, the company raised a funding round led by [75 & Sunny Ventures](https://www.75andsunny.vc/labs). As the sole technical team member, I built Path's backend server and iOS app from the ground up. My co-founder and I interviewed countless users, shipped >250 builds, and launched several marketing campaigns over 2 years of working towards product-market-fit, but eventually decided to wind the company down, returning the majority of funds back to investors. Screenshots can be found in [this portfolio album](https://photos.app.goo.gl/MdCb2D1k6getLFtD9).

## [ActivityHub/NEXMachine](https://www.crunchbase.com/organization/nexmachine-llc) - iOS Product & Architecture (2014 - 2016)

Joined ActivityHub (NEXMachine) to build their iOS calendar app and backend which integrated with several external services. A few months later, they acquired my company (Scholastic Connections), and I began leading product development for both initiatives before later closing down Scholastic Connections as ActivityHub refocused on the enterprise space as a Salesforce partner. I then led product engineering, hired new engineers, contributed as an IC, and participated in investor meetings.

## [Flounder Apps](https://www.crunchbase.com/organization/flounder-apps-llc) (Acquired in 2016) - Co-Founder (2013 - 2016)

Co-founded Flounder Apps, focused on building [Ambition: Strategy War Game](https://appadvice.com/app/ambition-strategy-war-game/850863885) – an iOS app designed as a complex, turn-based strategy game. The product was acquired by another organization in 2016.

## [Scholastic Connections](https://www.crunchbase.com/organization/scholastic-connections-llc) (Acquired in 2015) - Founder (2014 - 2015)

Founded [Scholastic Connections](https://www.crunchbase.com/organization/scholastic-connections-llc), a company that partnered with classroom management providers to create an iOS app which provided teachers and families with easy access to their students' data. In 2015, the company was acquired by ActivityHub (NEXMachine), but was later wound down when ActivityHub pivoted towards the enterprise space.

## Independent iOS Developer (2011 - 2014)

Contracted independently on iOS projects for several companies. Additionally, I created a few of my own apps which were distributed on the App Store, some of which were eventually sold off.

# Nonprofits

## Papai Foundation

My wife Milla and I created and run the [Papai Foundation](https://www.papai.foundation) with the mission to create a better future for some of the most marginalized and forgotten people in India and Central Asia: Vulnerable children and women. We do this by developing partnerships with grassroots organizations abroad and funding projects related to orphanages, childcare, and education.

## The 25 Group

I am on the board of [The 25 Group](https://www.the25group.org/), a Christian nonprofit organization that provides advocacy and funding to serve marginalized communities worldwide, focusing on the six areas of ministry outlined in Matthew 25: Feeding the hungry, providing water for the thirsty, healing those who are sick, welcoming strangers, ministering to free the captive, and clothing those in need.
