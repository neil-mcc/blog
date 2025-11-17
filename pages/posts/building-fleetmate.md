---
title: Building FleetMate
date: 2025/11/15
description: A personal story about building a vehicle management app to escape being the family's unofficial fleet manager, while learning Next.js 14, Auth0, and the joys of serverless databases.
tag: side projects
author: Neil McClelland
---

# Building FleetMate: How I Automated My Family's Favorite Question: "Neil, Can You Just...?"

You know that moment when your phone buzzes and you immediately know it's going to be a "quick question", one you should know the answer to at the top of your head? For me, it's usually one of these:

- "Neil, when my MOT is due?"
- "Neil, when was the last time my car got serviced?"
- "Neil, when is my insurance up next?"

Somewhere along the way, I became the unofficial fleet manager for the McClelland family. I didn't apply for this position. There was no interview. No salary negotiation. But apparently, being "good with computers" automatically qualifies you to manage the administrative chaos of multiple family vehicles.

So I did what any reasonable developer would do: I built an app to automate myself out of the job.

## The Perfect Excuse

Here's the thing - I actually don't mind that much. Yes, it may be annoying trying to be some kind of walking DVLA database, but it gave me something more valuable: **a genuinely useful project idea**.

I've been meaning to sharpen up my skills with some newer technologies, but I was tired of building yet another todo app or weather dashboard that I'd never actually use. FleetMate was different. This was a real problem that would save me actual time and mental energy.

The learning goals were clear:
- Get hands-on with **Next.js 14** and the App Router (because the Pages Router was feeling a bit 2022)
- Properly implement **Auth0** for authentication (beyond just copy-pasting the quick start guide)
- Build something with **Prisma ORM** and actually understand database relationships
- Use **shadcn/ui** and **Tailwind CSS** to make it look decent without spending three hours on button hover states

## The Tech Stack

I went with Next.js 14 because I wanted to understand the App Router properly. Everyone was talking about Server Components and I was tired of nodding along in conversations pretending I knew the difference between server and client components beyond "one runs on the server, probably?"

The stack ended up being:
- **Next.js 14** with TypeScript
- **Prisma ORM** with SQLite for local dev
- **Auth0** for authentication
- **shadcn/ui** for components
- **React Query** for state management
- **Tailwind CSS** for styling

## What I Actually Built

FleetMate is pretty straightforward: it's a dashboard where you can track vehicles and all the annoying bits that come with them. Each vehicle has:
- Registration number
- Make and model
- MOT expiry date
- Insurance renewal date
- Tax renewal date
- Service history

## Why This Project Matters to Me

FleetMate isn't going to change the world. It's not going to be the next big SaaS product. But it matters to me for a few reasons:

**First**, it solved a real problem. I'm no longer the human notification system for my family's car admin. That alone makes this worth it.

**Second**, I learned a ton. I went from vaguely understanding Next.js 14 to actually building something with it. I got comfortable with Auth0, Prisma, and modern React patterns. These are skills I can apply to bigger projects.

**Third**, it's mine. There's something deeply satisfying about building something from scratch that actually works and that people (okay, my family) actually use.

## What's Next?

FleetMate v1 is live and working, but like any good side project there are a long list of //TODOs:

- **Migrate to PostgreSQL** for proper production deployment
- **Add actual email notifications** (currently just in-app reminders)
- **Build a mobile app** (because convincing family members to bookmark a website is harder than you'd think)
- **Add expense tracking** for fuel and maintenance costs
- **Create shared fleet management** for families or small businesses
- **Add notes section** for general history 
- **Intergrate with real MOT API** to query gov.uk

Realistically, these TODO's may never be checked off and my next project is probably going to be something completely different. That's the beauty of side projects - you get to chase whatever sounds interesting.

## Final Thoughts

If you're looking for an excuse to learn new technologies, I highly recommend finding a problem you actually have and building a solution for it. It's more motivating than a tutorial, more educational than following a guide, and infinitely more satisfying when it works.

Plus, you get to say things like "I built an app for that" when your family asks you to do something, which is its own reward.

Check out [FleetMate on GitHub](https://github.com/neil-mcc/FleetMate) or try it yourself at [fleet-mate.xyz](https://fleet-mate.xyz).

