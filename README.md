# Case studies

Private case studies. Each repository is a cleaned copy: the runnable shape of the project, a written account of the problem and the design, and none of the passwords, databases, invoices, or customer files from the working copy.

The working folders on the machine that built these stay separate. These repositories were created as new histories, so older commits that may have held secrets are not part of this tree. The repositories themselves are private.

## Sales and telephony

- [AI Lead](https://github.com/VladyslavVyparina/ai-lead) — control plane that turns business records into a verified lead, a preview site, a priced proposal, and an outreach draft that a person still has to approve. Pilot market is beauty and wellness in Porto, Lisbon, and Braga.
- [AI Lead Pipeline](https://github.com/VladyslavVyparina/ai-lead-pipeline) — the first-customer engine behind that work: import, dedupe, score, preview, price, and hold the send until consent and suppression checks pass.
- [AI telephony site](https://github.com/VladyslavVyparina/ai-telephony-site) — marketing site for an AI sales manager, with a demo call and a lead form.
- [Voice AI agent](https://github.com/VladyslavVyparina/voice-ai-agent) — Telegram bot plus a SIP proxy, with the agent scripts kept as files next to the call path.
- [Yagidnyk AI agent](https://github.com/VladyslavVyparina/yagidnyk-ai-agent) — intake agent for a berry-buying operation, on Telegram and TikTok, with an admin desk for the people who confirm the loads.

## Shops and invoices

- [Silicon sales bot](https://github.com/VladyslavVyparina/silicon-ai-bot) — Telegram salesperson for a badge and lanyard shop: sizes, colors, prices, delivery, and an invoice that is created in 1C and sent back as a PDF.
- [Silicon 1C handover](https://github.com/VladyslavVyparina/silicon-1c-handover) — the contract and Docker stand for the 1C specialist: counterparty by EDRPOU, invoice create, PDF download. Stamp and signature belong to the 1C print form.

## Communities and broadcasts

- [Academy Essence](https://github.com/VladyslavVyparina/academy-essence) — community bot with event registration and payment.
- [SOLUTION experience bot](https://github.com/VladyslavVyparina/solution-experience-bot) — English and Ukrainian bot for a studio of live events and pocket audio journeys, with human takeover in the admin panel.
- [Sekret Club](https://github.com/VladyslavVyparina/sekret-club) — paid club bot: WayForPay callback, lessons, group invite after payment, Google Sheet of members.
- [Telegram broadcast bot](https://github.com/VladyslavVyparina/telegram-broadcast-bot) — admin broadcasts and scheduled posts to groups, channels, and private chats, with a live progress report.

## Commerce integrations

- [Poster to SendPulse NPS](https://github.com/VladyslavVyparina/poster-sendpulse-nps) — Poster webhook, a delay, quiet hours, and one NPS text via SendPulse, cancelled if the order should not be surveyed.
- [KeyCRM lead push](https://github.com/VladyslavVyparina/keycrm-lead-push) — why a new lead becomes a task: KeyCRM has no mobile push API, and the app already notifies on tasks.
- [KeyCRM to Trello](https://github.com/VladyslavVyparina/keycrm-trello-sync) — pipeline card stage in KeyCRM moves the Trello card to the list named for that status.
- [KeyCRM UTM capture](https://github.com/VladyslavVyparina/keycrm-utm) — browser scripts that keep campaign parameters and attach them to the KeyCRM lead, including OpenCart checkout.
- [SmartSender subscriber proxy](https://github.com/VladyslavVyparina/smartsender-subscriber-proxy) — a small Node process that reads the subscriber id out of a loosely shaped SmartSender body and forwards it.

## Operations bots

- [Inter Logistics bot](https://github.com/VladyslavVyparina/inter-logistics-bot) — freight request funnel in Telegram, posted to an operations chat and a Google Sheet.
- [Transport listings bot](https://github.com/VladyslavVyparina/transport-listings-bot) — the same idea for listings: a funnel, a relay into the working chat, and a sheet row.

## Sites

- [PlasticineZen landing](https://github.com/VladyslavVyparina/plasticinezen-landing) — one-page course landing built to paste into a SendPulse HTML block, with a sample lesson and a thank-you page.
- [Lavide landing](https://github.com/VladyslavVyparina/lavide-landing) — one page for targeting, landing pages, and chat bots.
- [LUMÉRA shop](https://github.com/VladyslavVyparina/lumera-shop) — static preview of a German compression-leggings storefront and the theme slice it was taken from.
- [BSA Global UAE](https://github.com/VladyslavVyparina/bsa-global-uae) — cargo-through-Dubai page in HTML, plus the Webflow paste of the same layout.

## What is never in these trees

Environment files, API tokens, service-account JSON, invoice PDFs, customer databases, call recordings, and deploy archives. Each README names the files that were left behind and how to supply your own before a local run.
