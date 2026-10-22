# Developer handoff notes

## What I delivered
A customer support page for Northstar Services.
It shows a contact email, support hours in Central Time, and a reminder to include an order number.
Added an FAQ section that explains how to check order status by signing in and opening the Orders page.

## How I verified the page
By opening index.html in my browser and confirming the styling loaded.
After adding the FAQ, I refreshed the page and saw the order-number reminder and the FAQ section.
I narrowed the browser window and the text stayed readable.
I went through all five items in support-checklist.md and each one passed.

## Remote change I received
I edited README.md on GitHub.com to add a Support escalation section about sending unresolved billing requests to the billing team after one business day.
My local README did not have it until I ran git pull --ff-only origin main, which downloaded the change.

## Git workflow explanation
We use git commit to save a snapshot to a local repository on one's computer.
GitHub is a separate remote copy, so it did not change until I ran git push origin main to upload my commits.