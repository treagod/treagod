# Marvin Ahlgrimm

I build web applications and developer tools with Ruby on Rails, Crystal and Marten.

Most of my work is somewhere between application code and the small pieces around it. Forms, models, handlers, background jobs, deployment scripts, admin tools and things that remove manual work.

I like codebases that are still understandable after a few months away from them. Not because every part is simple, but because the structure is clear and the important decisions are easy to follow.

## What I work with

- Ruby on Rails applications and backend systems
- Crystal
- Marten applications and framework extensions
- Deployment tooling with Podman, Quadlets, SSH and Caddy
- Server-rendered interfaces with Hotwire and Turbo-style workflows
- SaaS, analytics and data workflows with a focus on privacy
- Small infrastructure setups for small teams and solo developers

I usually start with server-rendered HTML. A lot of interfaces work well that way, and I prefer using the browser’s built-in behavior where it makes sense.

That does not mean avoiding JavaScript completely. It means using it where it helps, instead of making it the default answer for every interaction.

I think about deployment in a similar way. Kubernetes has its place, but many projects do not need that level of infrastructure. For small teams and solo developers, a normal server with clear commands is often easier to run and easier to debug.

## Open source

- Author of [Meridian](https://github.com/treagod/meridian), a deployment tool inspired by Kamal, built around Podman, Quadlets and simple server deployments
- Contributor to [Marten](https://github.com/martenframework/marten), the Crystal web framework
- Author of [marten-turbo](https://github.com/treagod/marten-turbo), Turbo helpers for Marten applications
- Author of [importmap.cr](https://github.com/treagod/importmap), framework-agnostic import maps for Crystal
- Author of [marten-throttle](https://github.com/treagod/marten-throttle), rate limiting helpers for Marten applications
- Author of [marten-money](https://github.com/treagod/marten-money), Money field integration for Marten models

## What matters to me

I care about software that can run in production without becoming a burden.

For me, that usually means clear data models, predictable behavior and defaults that do not get in the way. I do not mind abstraction, but I want to understand what happens when something breaks.

I also like tools that stay close to the web. Forms should behave like forms. Links should behave like links. A deployment tool should show what it is doing instead of hiding everything behind too much magic.

## Current interests

Right now, I spend a lot of time on Crystal and Marten.

Some of that work is about framework features. Some of it is about the smaller things around a framework that make daily work nicer, like Turbo helpers, import maps, rate limiting and money fields.

I am also working on deployment workflows that are useful without a large platform around them. Podman, Quadlets, SSH and Caddy cover many of the cases I care about, but the workflow can still be improved.

## Links

- GitHub: https://github.com/treagod
- Marten: https://martenframework.com
- Meridian: https://meridian-deploy.dev
