# Security

## Reporting a vulnerability

Report it privately to [operations@webanion.com](mailto:operations@webanion.com). Do not open a public issue, and do not put the details in a pull request or a discussion thread.

A useful report says what you found, where you found it, what an attacker could do with it, and enough detail to reproduce it. A proof of concept helps. If you are not sure whether something is a real issue, send it anyway and say so.

## What to expect

We acknowledge reports within a few working days, usually sooner. After that you get an assessment of whether it is a vulnerability, how serious we think it is and what we intend to do, and we tell you when it is resolved.

If you want credit when the fix ships, say so in your first message. There is no bug bounty and no paid disclosure programme here.

## Scope

Most repositories in this organization are private client work, so what you can see publicly is a small part of what is deployed. If you find something in a product Webanion built or runs rather than in public code, report it the same way. We route it to the right owner and tell you it landed.

When you are testing, stay off anything that degrades a live service or reaches other people's data. Do not run denial of service tests, do not attempt to access accounts that are not yours, and stop at the point where you have demonstrated the issue rather than exploring what else it opens.

## Credentials in public code

If you find a live credential, key or token committed anywhere in this organization, treat it as a vulnerability and report it by email rather than opening an issue. Say where you saw it and nothing more, and do not test whether it still works.
