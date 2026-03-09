# Self-Hosted-SAAS
Curated list of self-hosted open-source SaaS &amp; tools to deploy on your own server.
# 🚀 Awesome Self-Hosted SaaS & Tools

> Curated list of **self-hosted open-source SaaS applications** you can deploy on your own server, VPS, or homelab. Perfect for developers, system admins, and cybersecurity enthusiasts.

# 📚 Table of Contents

- [VPN](#-vpn)
- [Music Streaming](#-music-streaming)
- [Photo Hosting](#-photo-hosting)
- [eBooks Catalog](#-ebooks-catalog)
- [Google Docs & Office](#-google-docs--office)
- [Media Streaming](#-media-streaming-netflix-alternative)
- [Notes](#-notes)
- [Bookmarks](#-bookmarks)
- [URL Shortener](#-url-shortener)
- [Calendar](#-calendar)
- [Cloud Storage](#-cloud-storage)
- [DNS](#-dns)
- [AdBlock](#-adblock)
- [Email Servers](#-email-servers)
- [Chat Servers](#-chat-servers)
- [Video Calls](#-video-calls)
- [Publishing Systems](#-publishing-systems)
- [Comments System](#-comments-system)
- [Web Analytics](#-web-analytics)
- [Google Search](#-google-search)
- [Cloud Backup](#-cloud-backup)
- [Web Archive](#-web-archive)
- [File Sharing](#-file-sharing)
- [Information & Wiki](#-information--wiki)
- [Password Managers](#-password-managers)
- [Read It Later](#-read-it-later)
- [RSS Reader](#-rss-reader)
- [Git Servers](#-git-servers)
- [Gist/Pastebin](#-gistpastebin)
- [Mailchimp Alternative](#-mailchimp-alternative)
- [Kanban Boards](#-kanban-boards)
- [GPS Tracking](#-gps-tracking)
- [Personal Finance](#-personal-finance)
- [Smart Home](#-smart-home)
- [IFTTT Automation](#-ifttt-automation)
- [2FA / Google Authenticator](#-2fa--google-authenticator)
- [Twitch / Streaming](#-twitch--streaming)
- [Container Management](#-container-management)

---
🙊 Deploy your own VPN
OpenVPN — full-featured open source VPN solution. (Digital Ocean tutorial)
dockovpn.io — stateless OpenVPN dockerized server which doesn't require persistent storage.
WireGuard — faster, simpler, leaner, and more useful than IPsec. It intends to be considerably more performant than OpenVPN. (Digital Ocean tutorial)
Algo VPN — set of Ansible scripts that simplify the setup of a personal Wireguard and IPsec VPN.
🎧 Deploy your own Music streaming service
Ampache — web based audio/video streaming application and file manager.
Madsonic — web-based media library and media streamer with jukebox functionality.
Mopidy — extensible music server.
Koel — simple web-based personal audio streaming service. (GitHub)
Funkwhale — web-based music library with Airsonic compatibility. (GitLab)
AzuraCast — web radio management suite, with a modern web app. (GitHub)
Black Candy — music streaming server with web UI and iOS/Android apps.
Audiobookshelf — audiobook and podcast server. (GitHub)
📷 Deploy your own Photo hosting
Immich — high performance photo and video solution with familiar UI. (GitHub)
Chevereto — powerful and fast image hosting script that allows you to create your very own image hosting website in just minutes.
PhotoPrism — personal photo management with Ai classification and lots of features. (GitHub)
Lychee — upload, manage and share photos like from a native application. (GitHub)
Photo-Stream — super-simple, jekyll-based, self-hosted photo stream.
Piwigo — PHP image gallery. (GitHub)
Pinry — your own Pinterest with boards and tags. (GitHub)
📚 Deploy your own eBooks catalog
Calibre — e-book manager, packed with all you need features (including server).
COPS — Calibre OPDS and HTML server. (Urown tutorial)
Calibre-Web — web UI for Calibre database.
📄 Deploy your own Google Docs
Collabora — LibreOffice in the cloud with collaboration features. (tutorial for OwnCloud)
ONLYOFFICE CE — private cloud office with collaboration features. CE version distributed as Docker image. (GitHub)
SeaTable — your own Airtable where spreadsheets meets database.
Baserow — your own API-focused Airtable with plugins.
Nocodb — Airtable alternative could be based on top of MySQL, PostgreSQL, SQL Server, SQLite & MariaDB with solid GUI (GitHub)
🎬 Deploy your own Netflix
Jellyfin — media system that puts you in control of managing and streaming your media. (GitHub)
📝 Deploy your own Notes
CodiMD — realtime collaborative markdown notes.
Standard Notes — clean and simple web app with E2E encryption, extensions and clients. How to self-host tutorial
TinyList — your own Google Keep. Simple and clean. (GitHub)
Leanote — your own Evernote. (GitHub)
Bangle.io — web only WYSIWYG note taking app that saves notes locally in markdown. (GitHub)
Memos — memo hub with knowledge management and socialization. (GitHub)
🏷 Deploy your own Bookmarks service
Unmark — application for bookmarks. (Tutplus tutorial from 2014)
Bookmarks — self-hosted bookmarking app that can import bookmarks from delicious and chrome.
xBrowserSync — secure and anonymous bookmarking server with browser plugins and mobile app. (GitHub)
Nextcloud Bookmarks — bookmark app for Nextcloud with browser plugins, mobile and desktop apps. (GitHub)
LinkAce — bookmark archive with tags, lists and sharing features. (GitHub)
Linkding — simple bookmarks with tags and neat UI.
Benotes — bookmark taking web app with additional note taking feature.
Briefkasten — bookmark web app with REST API, OAuth, drag-n-drop and browser extension.
Hoarder — bookmark-everything app with AI-based tagging and full text search. (GitHub)
Readeck — selfhosted bookmarking app with the modern UI, smart features and browser extension. (Codeberg)
🔤 Deploy your own URL shortener
Yourls — Your Own URL Shortener.
Kutt — modern URL shortener with support for custom domains. (GitHub)
Delta — a file uploader and URL shortener packed with features and CLI.
Shlink — URL shortener with neat UI, API and analytics. (GitHub).
CLI based approach
🗓 Deploy your own Calendar
Radicale — CalDAV and CardDAV Server made with Python.
Sabre — CardDAV, CalDAV and WebDAV server made with PHP.
Calendar Server — Calendar and contacts server made by Apple.
🗄 Deploy your own Cloud storage
OwnCloud — personal cloud which runs on your own server. (tutorial)
Nextcloud — enhanced OwnCloud fork with tons of additional services like calendars, mail, contacts, video calls, etc (GitHub).
Syncthing — continuous file synchronization program.
MinIO — object storage server compatible with Amazon S3 APIs.
Teedy — lightweight document management system with workflows (GitHub)
Filestash — easily turn popular backends like SFTP, S3, GitHub etc into web-based file manager (GitHub)
🕸 Deploy your own DNS
Unbound — validating, recursive, caching DNS resolver. (Urown tutorial)
🛑 Deploy your own AdBlock
Pi-hole — network-wide ad blocking software you can deploy to local Raspberry Pi or always-free instance of Google Cloud. Yes, you've got the irony right. (GitHub)
AdGuard Home — network-wide DNS resolver with encryption for blocking ads & tracking. (GitHub)
✉️ Deploy your own Email server
Mailu — dockerized, secured mail suite which is easy to install and maintain.
Mailcow — dockerized mail server suite based on Postfix, Dovecot, Nginx, PHP, MariaDB, Rspamd and more. (GitHub)
iRedMail — mail server suite with vast of options.
Mail-in-a-Box — another mail server suite based on Postfix, Dovecot, Z-Push, Roundcube, Nextcloud, Apache SpamAssassin, Postgrey, Nginx. (GitHub)
Roundcube — browser-based IMAP client with an application-like user interface.
Postal — a fully featured mail server with web UI. (GitHub)
Maddy — a composable all-in-one mail server written in Golang. (GitHub)
💬 Deploy your own Chat server
Prosody IM — modern XMPP communication server. (Urown tutorial)
Zulip — team chat which combined the immediacy of real-time chat with an email threading model. (GitHub)
Rocket Chat — WebChat platform. (GitHub)
Mattermost — private cloud, Slack-alternative. (GitHub)
Mumble — low-latency, high quality voice chat for gaming. (GitHub)
Matrix — ecosystem for open federated Instant Messaging and VoIP. (GitHub)
Riot — multi platform chat app based on Matrix protocol.
📹 Deploy your own Video calls
Jitsi — Multi-platform open-source video conferencing. (GitHub)
Nextcloud Talk — chat or video calls via web or mobile apps, including screen sharing and webinar functionality. (GitHub)
✍️ Deploy your own Publishing system
Jekyll — static websites and blogs. (GitHub)
Hugo — static site generators with amazing speed.
Ghost — headless Node.js CMS for professional publishing.
Gatsby — React-based framework that helps developers build fast websites and apps. (GitHub)
🗣 Deploy your own Disqus comments
Isso — lightweight commenting server. It aims to be a drop-in replacement for Disqus. (GitHub)
Remark42 — self-hosted, lightweight, and simple commenting system, which doesn’t spy on users (GitHub)
Staticman — commenting server for static sites which stores all user generated content into your own repository. (GitHub)
Code It Yourself approach by Tania Rascia
📈 Deploy your own Web analytics engine
Ackee — self-hosted, Node.js based analytics tool for those who care about privacy.
Matomo — open analytics platform.
GoAccess — real-time web log analyzer and interactive viewer that runs in a terminal or through browser. (GitHub)
Fathom Lite — Simple, privacy-focused website analytics.
Shynet — Privacy-friendly, detailed web analytics that works without cookies or JS.
GoatCounter — Easy analytics without tracking.
🔍 Deploy your own Google search
Whoogle — Deploy your own search engine that privately uses Google results.
📦 Deploy your own Cloud backup
Duplicity — backs up directories by producing encrypted tar-format volumes and uploading them to a remote or local file server.
Borg — deduplicating archiver with compression and encryption.
ElkarBackup — backup solution based on RSync/RSnapshot.
Restic — encrypted, deduplicated & simple backups with an easy-to-use CLI. (GitHub)
🔗 Deploy your own Web archive
ArchiveBox — self-hosted web archive. (GitHub)
Archivy — knowledge repository that allows you to preserve content. (GitHub)
🍕 Deploy your own file sharing server
Send — simple, private file sharing with encryption. A Firefox Send fork.
FilePizza — peer-to-peer file transfers with only browser.
Lufi — convenient file sharing with E2E encryption.
Linx — simple file/code/media sharing website.
XBackBone — PHP file manager that support the instant sharing tools like ShareX, uPic, etc (GitHub)
Enclosed — Minimalistic web app designed for sending private and secure notes. (Github)
📂 Deploy your own Information storing and organization system
Bookstack — platform to create documentation/wiki content built with PHP & Laravel.
MediaWiki — collaboration and documentation platform with enormous capabilities.
Dokuwiki — simple wiki that doesn't require a database. (GitHub)
Outline — fastest wiki and knowledge base for growing teams with markdown support and clean UI. (GitHub)
Wiki.js — lightweight and extensible wiki made with Node.js. (GitHub)
Hypothes.is — web annotating system with search, storing, collaboration, sharing and integrations. (GitHub)
🔑 Deploy your own Password manager
Bitwarden — easiest and safest way to store, share, and sync sensitive data. (GitHub)
LessPass — stateless password manager. (GitHub)
🤥 Deploy your own Read it Later
Shiori — simple bookmarks manager written intended as a simple clone of Pocket.
Wallabag — self hostable application for saving web pages.
Shaark — knowledge storage for web links, notes, pictures and passwords with clean web UI.
🗞 Deploy your own RSS reader
Selfoss — multipurpose rss reader, live stream, mashup, aggregation web application.
FreshRSS — rss aggregator with responsive UI.(GitHub)
Tiny Tiny RSS — web-based news feed reader and aggregator.
Miniflux — minimalist and opinionated feed reader.
🇫🇮 Deploy your own Git server
GitLab CE — turn-key git hosting solution. (Digital Ocean tutorial)
Gitolight — git hosting on a server, with very fine-grained access control and many powerful features.
Gitea — lightweight and powerful git server made with Go, so you can deploy it even on Raspberry Pi. (GitHub)
Pagure — lightweight, powerful, and flexible git-centered forge with decentralization features.
Forgejo — lightweight, git-based software forging infrastructure with decentralised features. Base of Codeberg platform.
🗑 Deploy your own Gist/PasteBin
Privatebin — minimalist, online pastebin where the server has zero knowledge of pasted data. (GitHub)
0bin — client side encrypted pastebin that can run without a database. (GitHub)
Opengist — git-powered pastebin.
🐵 Deploy your own Mailchimp
Listmonk — newsletter and mailing list manager with a modern dashboard.
🥋Deploy your own Kanban board
Wekan — collaborative Kanban board.
Kanboard — project management software that focuses on the Kanban methodology. (GitHub)
Taiga — project management software with a kanban board, sprints, wiki and tickets. (GitHub)
Phabricator — a collection of web apps which contains bug tracker, kanban board, wiki, chat and everything you need to build software. (GitHub)
Planka — Kanban board which looks and feels exactly like Trello. (GitHub)
🛰 Deploy your own GPS tracking system
OwnTracks — lightweight program for storing and accessing location data published via MQTT or HTTP by the OwnTracks apps.
µlogger server — web application for real-time collection of geolocation data, tracks viewing and management.
Dawarich - Self-hosted alternative to Google Location History
💳 Deploy your own Personal finance tracker
Firefly III — financial manager to help you keep track of expenses, income, budgets and everything in between. (GitHub)
Ledger — plain text double-entry accounting with 3rd party UI like Prudent. Entry point to plain text accounting
Beancount — plain text double-entry accounting with 3rd party web UI like Fava
ezBookkeeping — a lightweight personal finance app with a user-friendly interface and powerful bookkeeping features. (GitHub)
🏠 Deploy your own Smart home
Home Asisstant — home automation hub which can be deployed on Raspberry Pi (GitHub)
OpenHAB — vendor-neutral, hardware/protocol-agnostic home automation hub (GitHub)
Home Bridge — lightweight server that emulates the iOS HomeKit API so you can work with smart home devices that do not support the HomeKit protocol. (GitHub)
🌀 Deploy your own IFTTT
Activepieces - a no-code open-source business automation tool. (GitHub)
n8n — node-based Workflow Automation Tool with visual editor. (GitHub)
Beehive — a flexible event/agent & automation system made with Go.
Huginn — system for building agents that perform automated tasks for you online. Written in Ruby.
Kibitzr — tiny server to notify about (almost) anything in the web. (GitHub)
🔐 Deploy your own Google Authenticator (2FA, OTP)
2FAuth — a web app to manage your Two-Factor Authentication. (GitHub)
🎙 Deploy your own Twitch
Lightspeed — a self-contained OBS → FTL → WebRTC live streaming server.
🐳 Deploy your own Container Management System
Portainer — container management tool. It allows anyone to deploy and manage containers without the need to write code. (GitHub)
Yacht — a web interface for managing docker containers with an emphasis on templating to provide 1 click deployments.
Pterodactyl — game server management panel. It runs game servers in isolated containers while exposing a beautiful web UI to the users. (Github)
Umbrel — either a docker image or OS that provides you with the most beautiful web interface to manage containerized web services. (Github)

# ⭐ Support
Star ⭐ this repo, fork 🍴 it, and share 📢 with friends!  

---
streaming`, `photo hosting`, `chat`, `email`
