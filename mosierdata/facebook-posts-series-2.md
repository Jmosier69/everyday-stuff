# Facebook Post Series 2 — "I wonder if he could build..."
## Drafted for Jim Mosier, May 2026

---

### Post 13 — Agentic commerce (the practical version)

Stripe just released an SDK that lets software make payments on its own. No human clicking "pay." No manual invoicing. The system watches for the right conditions and executes the transaction.

Here's why this matters for custom systems:

Your membership platform could handle renewals, failed payment retries, and prorated upgrades without anyone touching it. Your inventory system could reorder stock when levels drop below a threshold and actually pay for the order. Your billing system could handle complex subscription logic that currently takes a bookkeeper three hours every month.

This isn't sci-fi. The plumbing exists right now. Most businesses just haven't connected it yet.

What would you automate if the payment part handled itself?

---

### Post 14 — WordPress had its era. So does Astro.

I built WordPress sites for years. I took care in my craft. My biggest pet peeve was plugin bloat, so I standardized on plugin stacks that did multiple things. The goal was always five plugins or less. Speed optimization at the foundation. Most agencies never bothered with any of that.

WordPress was great. It still has a place. But it's not the only answer anymore.

Astro is doing things that would have been painful five years ago. Static sites that are fast by default, not because you optimized the heck out of a stack of plugins. There are a handful of modern frameworks now that produce clean, fast, maintainable sites without the update-day anxiety.

WordPress isn't dead. But if you're assuming it's the only way to put a business on the web, you're operating on old information. The toolbelt is bigger now.

Worth a conversation if you're wondering what else is out there.

---

### Post 15 — The SEO trap with AI-built apps

If you're using AI coding tools to build something for your business, here's something you need to know:

A lot of them generate React single-page apps. React SPAs render on the client side. Meaning the page is basically empty HTML until JavaScript runs in the browser. Google can index JavaScript-rendered content, but it's slower, less reliable, and often misses things. Bing and other search engines are worse.

Your beautifully built app might as well be invisible.

The fix isn't complicated. Flatten your pages to static HTML before you deploy. Server-side rendering. Plain old HTML templates. There are a dozen ways to do it. But if nobody tells you, you ship something that can't be found.

If you're goofing around building something yourself and you're not sure whether this applies to you, it probably does. Happy to take a look.

---

### Post 16 — Who actually owns what you built?

There's this thing I keep seeing. Someone starts playing around with Lovable, or Replit, or Base44. They're not setting out to "build a system." They're tinkering. Solving a problem. And before they know it, they've built something genuinely useful for their business.

Here's what they don't realize: they're building on somebody else's platform. The tool that generated the code is also the tool that runs it. You don't have a GitHub repo with your source code. You don't have a backup you can put your hands on. If the platform changes its pricing, or sunsets a feature, or goes down for a day, you're stuck.

There's a real distinction between a closed system you're renting and technology you actually own. Strategic ownership. Business continuity. Legal control of your own data and code.

A fancy user interface built by AI is great. But if you're going to run your business on it, the considerations that actually matter are the boring ones. Where's the source code? Who controls the backups? Can you move it somewhere else if you need to?

If you've built something useful on one of these platforms and you're not sure what you actually own, let's talk.

---

### Post 17 — APIs are everywhere now

Here's something that changed while most people weren't looking:

Every major tool your business uses. QuickBooks, Mailchimp, your CRM, your payment processor, your shipping platform. They all have APIs now. They're designed to talk to each other. The plumbing is there.

The days of "these two systems can't communicate" are pretty much over. You just need someone who knows how to wire them together.

Think about the stuff you're manually moving between systems right now. Export from one, import to another. Copy and paste. Re-type the address. That gap isn't a technology limitation anymore. It's just a connection that hasn't been built yet.

What's the thing you're typing twice?

---

### Post 18 — Everybody wants a dashboard

Dashboards are everywhere right now. Everybody wants a dashboard for this and a dashboard for that. And honestly, I get it.

A good dashboard replaces guesswork with a glance. Instead of digging through reports and spreadsheets and asking three people for numbers, you look at one screen and you know. Sales today. Jobs in progress. Inventory that needs attention. Members up for renewal. Whatever the five numbers are that actually drive your business.

The reason they're having a moment is that you can pretty much connect anything to anything these days. Your POS, your CRM, your shipping platform, your accounting software. They all have APIs. The data is there. It's just sitting in different places.

A dashboard pulls it into one place and updates in real time. That used to be expensive. It's not anymore.

What five numbers would you want to see every morning?

---

### Post 19 — Field work is still broken

I keep running into businesses where the people in the field. Technicians, inspectors, delivery drivers, installers. Still filling out paper forms or calling the office to get information.

In 2026.

A simple mobile web app changes everything. The guy in the truck can look up a part, log a job, capture a signature, and upload photos before he starts the engine. The office knows what happened in real time instead of finding out when the paper stack shows up on Friday.

This isn't expensive anymore. It's not complicated. It's just a connection that hasn't been made yet between the field and the office.

You know a business like this. Who comes to mind?

---

### Post 20 — Real-time vs. "last month's report"

Most business owners are making decisions based on last month's numbers. Maybe last week's if they're on top of things.

The data exists in real time. The transactions are happening right now. The inventory is moving. The jobs are being completed. The only reason you're looking at stale information is that nobody built the pipeline from what's happening to what you can see.

A live dashboard doesn't have to be complicated. It can be a single screen with the five numbers that actually matter, updating as things happen. That's it. But the difference between deciding based on what happened last month versus what's happening right now. That's not small.

What would you want to know in real time?

---

### Post 21 — The "build vs buy" math has changed

For a long time, the rule was: if you can buy it off the shelf, buy it. Custom software was for enterprises with million-dollar budgets.

The math has shifted. The tools to build custom software are faster and cheaper than they've ever been. Meanwhile, off-the-shelf software keeps getting more expensive. Monthly per-seat pricing, annual contracts, feature tiers that never quite fit.

I'm not saying build everything from scratch. I'm saying the old assumption that buying is always cheaper isn't automatically true anymore. Sometimes a custom system pays for itself in the first year just by eliminating license fees, never mind the efficiency gains.

Run the math on your own stack sometime. You might be surprised.

---

### Post 22 — The second-brain system

Here's an idea I keep coming back to:

Every business has institutional knowledge that lives in people's heads. Which clients need special handling. Which parts are interchangeable. Which steps in the process can be skipped under which conditions. The stuff that isn't written down anywhere.

What if you built a system that captured that. Not as a wiki or a training manual, but as software that actually guided the process? The system knows what Susan knows. It prompts the right questions at the right time. It warns you when you're about to make the mistake everyone makes once.

This isn't AI hype. It's decision trees and conditional logic. Stuff developers have been doing for decades. The difference is now it's cheap enough to build for a 20-person business instead of a 2,000-person enterprise.

What's the thing only one person in your company knows?

---

### Post 23 — Embrace your boring

What's boring in your business?

I mean genuinely boring. The repetitive stuff. The thing you do the exact same way every time, 40 times a day, that takes 90 seconds and nobody questions it because it's always been done that way.

Most of the time, the highest-impact thing you can automate is small and boring.

One client had a problem: every time a new order came in, someone had to manually create a folder on the shared drive, copy a template, rename it, and send a notification to three people. Took 90 seconds. Happened 40 times a day. That's an hour of someone's day spent on something a script can do in milliseconds.

We fixed it in an afternoon. Cost them a few hundred bucks. They got an hour a day back forever.

Embrace your boring. The boring stuff is where the leverage lives. What's the 90-second task that happens 40 times a day in your business?

---

### Post 24 — The conversation I keep having

I'll tell you the conversation I've had most often in the last six months.

Someone runs a business. Usually 10 to 50 employees, been around a while, successful enough. They've outgrown whatever they've been holding together. The spreadsheets don't scale. The software they bought five years ago doesn't fit anymore. They know something needs to change but they can't quite name what the solution looks like.

They're not looking for a pitch. They're looking for someone who understands the problem well enough to help them describe it.

If that's you. Not the person who knows exactly what they need, but the person who knows something isn't working and can't quite articulate what's next. That's the conversation I'm best at having.

No pitch. Just figuring it out together.
