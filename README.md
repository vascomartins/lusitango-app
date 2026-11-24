# Lisbon Tango Festival 2027 · Mobile app (design prototype)

This repository is the **phone app as a clickable design**: how every screen should look and behave.
It is the **reference for content and features** (program, prices, wording, places), but it is **not connected to
any database**: dancers, rooms, notices and numbers in it are sample data written into the design.

Live demo: https://vascomartins.github.io/lusitango-app/ (updated only when Ocsav says "upload")

## How it relates to the real app

| | **Mobile app (this repository)** | **Web app (the real one)** |
|---|---|---|
| Repository | `vascomartins/lusitango-app` | [`vascomartins/lusitango-platform`](https://github.com/vascomartins/lusitango-platform), folder `web/` |
| Data | Sample data in the design | Live festival database, the same for everyone |
| Role | Design and content reference | Working app for dancers and organizers |
| Only in the phone app | Ticket QR codes and the door scanner for security | — |
| In both | Everything else, including the organizer area | |

The server, the database and the shared festival information (`content/festival.json`) all live in
`lusitango-platform`. When the phone app is built for iPhone and Android, it will use that same server and database.
