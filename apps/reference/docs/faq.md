---
id: faq
title: FAQs
description: 'Most frequently asked questions regarding Supabase'
---

### Where do I find support?

Choose the support channel relevant for your situation here: [supabase.com/support](https://supabase.com/support)

### How much does it cost?

Self-hosting Supabase is free. If you wish to use our cloud-platform, we provide [simple, predictable pricing](https://supabase.com/pricing).

### How do I host Supabase?

You can use the docker-compose script [here](https://github.com/supabase/supabase/tree/master/docker), and find detailed instructions [here](/docs/guides/hosting/overview).

Supabase is an amalgamation of open source tools. Some of these tools are made by Supabase (like our [Realtime Server](https://github.com/supabase/realtime)), some we support directly (like [PostgREST](http://postgrest.org/en/v7.0.0/)), and some are third-party tools (like [KonSupabase is an amalgamation open sourceg](https://github.com/Kong/kong)).

All of the tools we use in Supabase are MIT, Apache 2.0, or PostgreSQL licensed. This is one of the requirements to be considered for the Supabase stack.

### How can you be a Firebase alternative if you're built with a relational database?

We started Supabase because we love the functionality of Firebase, but we personally experienced the scaling issues that many others experienced. We chose Postgres because it's well-trusted, with phenomenal scalability.

Our goal is to make Postgres as easy to use as Firebase, so that you no longer have to choose between usability and scalability.
We're sure that once you start using Postgres, you'll love it more than any other database.

### Do you support `[some other database]`?

We only support PostgreSQL. It's unlikely we'll ever move away from Postgres; however, you can [vote on a new database](https://github.com/supabase/supabase/discussions/6) if you want us to start development.

### Do you have a library for `[some other language]`?

We officially support [JavaScript](/docs/reference/javascript/installing) and [Dart](/docs/reference/dart/installing).

You can find community-supported libraries in our [GitHub Community](https://github.com/supabase-community), and you can also help us to identify the most popular languages by [voting for a new client library](https://github.com/supabase/supabase/discussions/5).
