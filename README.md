# easyappoint

Appointment bot and web calendar for self-employed specialists in Max and Telegram.

[easyappoint.online](https://easyappoint.online) · [User guide, in Russian](https://easyappoint.online/help/) · [Changelog](CHANGELOG.md)

easyappoint replaces a specialist's paper notebook and the evening round of phone calls. The specialist keeps appointments in a chat bot and in a web cabinet. The evening before a visit, the client gets a reminder with "Приду" and "Не смогу", so the specialist knows who is coming. The service has been live since October 2026 and works in Russian.

This repository is the project's public page and changelog. The source code is private.

## Who it is for

| Who | What they do in easyappoint |
| --- | --- |
| Specialist | Writes appointments in the bot, answers booking requests, reads the evening summary, keeps the calendar, the clients and the profile in the web cabinet |
| Client | Finds a specialist in the catalog or by their link, books a free time on the specialist's page or in the bot, gets reminders in Max or Telegram, sees every visit in the client cabinet |
| Studio or salon | Creates an organization, invites specialists, fills in its page and books the members' visits in a shared calendar |

It suits anyone who keeps their own clients: beauty, massage, fitness, tutors, psychologists, car service, home repair, photo and video.

## How it works

1. A specialist opens the bot from easyappoint.online and sets up services and working hours in a few messages.
2. The specialist shares a booking link. Clients pick a free time on that page, or the specialist writes the visit in the bot.
3. The evening before, each client gets a reminder and answers it. The specialist gets a summary of tomorrow.

## Price

- Free: appointments, reminders, the evening summary, the calendar, the client list, the booking page and the catalog.
- Analytics for a specialist: 390 ₽ a month or 3 490 ₽ a year, first month free.
- Analytics for an organization: 1 490 ₽ a month or 14 900 ₽ a year.

## Built with

Java 21 and Spring Boot 4, PostgreSQL 16, React 18 with TypeScript and Vite. The bots use the Telegram and Max bot APIs, and texts and photos are checked by models that run on the server. Everything runs in Docker Compose on one server.

## Author

Built and run by Rodion Masalov ([@byrodi](https://github.com/byrodi)).

## License

All rights reserved, see [LICENSE](LICENSE). The code is not open source.
