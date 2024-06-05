# I no longer use GitHub

I will stop distributing projects on GitHub myself. It's clear GitHub doesn't care about git anymore: even their homepage says "The world's leading AI-powered developer platform." This is a significant change of focus that drove me, and potentially others, away from them. Maybe the SFC should revoke their permission to use their name, if they say they're not even related to git?

As a fun fact, the same page only says Git (not counting GitHub) in a "What is Git?" link at the very bottom.

The forced token authentication and 2FA makes pushing to non-critical projects very inconvenient. Not everyone needs top security.

Their front-end, once light and clean, is now also a SPA and full of useless features such as command palettes, popovers, hamburgers, progress bars and a completely custom code viewer that uses a textarea with syntax highlighting overlaid, and they say it's more accessible. It has a cursor that says it's read-only when you try to edit. It's *so broken* the selection doesn't show on GNU/Linux/Chromium!

Not to mention it's always been nonfree, and having one less nonfree software is always a good thing. Based on GNU's criteria it gets an F.

And, in general, Micro$oft is also acting very questionably nowadays. Windows Recall, ARM PCs, Office subscriptions, ads in the file browser, Edge shopping features and more.

I believe in the potential of new technologies to improve the world, but I don't want to use such a bloated platform for code hosting.

## The roundabout

I have created an alternative software called Roundabout that does git hosting in a way I can control. Of course, it's free software (open source) under the AGPL. The URL for the official server is <https://roundabout-host.com>. Everyone is welcome.

The roundabout doesn't currently support everything, but for many it will be enough.

![Project moved to a roundabout](https://img.shields.io/badge/repository-moved-%232196f3?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPCEtLSBDcmVhdGVkIHdpdGggSW5rc2NhcGUgKGh0dHA6Ly93d3cuaW5rc2NhcGUub3JnLykgLS0%2BCjxzdmcgd2lkdGg9IjQ4IiBoZWlnaHQ9IjQ4IiB2ZXJzaW9uPSIxLjEiIHZpZXdCb3g9IjAgMCAxMi43IDEyLjciIHhtbDpzcGFjZT0icHJlc2VydmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BPHBhdGggZD0ibTEyLjcgNi4zNWE2LjM1IDYuMzUgMCAwIDEtNi4zNSA2LjM1IDYuMzUgNi4zNSAwIDAgMS02LjM1LTYuMzUgNi4zNSA2LjM1IDAgMCAxIDYuMzUtNi4zNSA2LjM1IDYuMzUgMCAwIDEgNi4zNSA2LjM1eiIgZmlsbD0iIzIxOTZmMyIgc3Ryb2tlLW1pdGVybGltaXQ9IjgiIHN0cm9rZS13aWR0aD0iLjI2NDU4IiB2ZWN0b3ItZWZmZWN0PSJub24tc2NhbGluZy1zdHJva2UiIHN0eWxlPSItaW5rc2NhcGUtc3Ryb2tlOmhhaXJsaW5lIi8%2BPGcgdHJhbnNmb3JtPSJyb3RhdGUoMjQwKSI%2BPHBhdGggZD0ibS0xMi44MjggMS4yMTA5Yy0wLjYxMjc1IDIuMjg2OCAwLjc1NDIgNC42NTI5IDMuMDQxIDUuMjY1NmwwLjMwODU5LTEuMTQ4NGMtMS42NjUzLTAuNDQ2MjEtMi42NDU0LTIuMTQzMy0yLjE5OTItMy44MDg2eiIgY29sb3I9IiMwMDAwMDAiIGZpbGw9IiNmZmYiIHN0cm9rZS1taXRlcmxpbWl0PSI4IiBzdHlsZT0iLWlua3NjYXBlLXN0cm9rZTpub25lIi8%2BPHBhdGggZD0ibS0xMi4xMzMgNi43NjgyIDEuNDAxOS0xLjUgMC41OTgwOC0xLjk2NDEgMiAzLjQ2NDF6IiBjb2xvcj0iIzAwMDAwMCIgZmlsbD0iI2ZmZiIgc3Ryb2tlLW1pdGVybGltaXQ9IjgiIHZlY3Rvci1lZmZlY3Q9Im5vbi1zY2FsaW5nLXN0cm9rZSIgc3R5bGU9Ii1pbmtzY2FwZS1zdHJva2U6aGFpcmxpbmUiLz48L2c%2BPGcgdHJhbnNmb3JtPSJyb3RhdGUoMTIwKSI%2BPHBhdGggZD0ibS0xLjgyODEtOS43ODcxYy0wLjYxMjc1IDIuMjg2OCAwLjc1MjI1IDQuNjUyOSAzLjAzOTEgNS4yNjU2bDAuMzA4NTktMS4xNTA0Yy0xLjY2NTMtMC40NDYyMS0yLjY0MzUtMi4xNDE0LTIuMTk3My0zLjgwNjZ6IiBjb2xvcj0iIzAwMDAwMCIgZmlsbD0iI2ZmZiIgc3Ryb2tlLW1pdGVybGltaXQ9IjgiIHN0eWxlPSItaW5rc2NhcGUtc3Ryb2tlOm5vbmUiLz48cGF0aCBkPSJtLTEuMTM0NC00LjIzMDMgMS40MDE5LTEuNSAwLjU5ODA4LTEuOTY0MSAyIDMuNDY0MXoiIGNvbG9yPSIjMDAwMDAwIiBmaWxsPSIjZmZmIiBzdHJva2UtbWl0ZXJsaW1pdD0iOCIgdmVjdG9yLWVmZmVjdD0ibm9uLXNjYWxpbmctc3Ryb2tlIiBzdHlsZT0iLWlua3NjYXBlLXN0cm9rZTpoYWlybGluZSIvPjwvZz48cGF0aCBkPSJtMi4xOTczIDUuMjM2M2MtMC42MTI3NSAyLjI4NjggMC43NTIyNSA0LjY1NDggMy4wMzkxIDUuMjY3NmwwLjMwODU5LTEuMTUwNGMtMS42NjUzLTAuNDQ2MjEtMi42NDM1LTIuMTQzMy0yLjE5NzMtMy44MDg2eiIgY29sb3I9IiMwMDAwMDAiIGZpbGw9IiNmZmYiIHN0cm9rZS1taXRlcmxpbWl0PSI4IiBzdHlsZT0iLWlua3NjYXBlLXN0cm9rZTpub25lIi8%2BPHBhdGggZD0ibTIuODkxMyAxMC43OTQgMS40MDE5LTEuNSAwLjU5ODA4LTEuOTY0MSAyIDMuNDY0MXoiIGNvbG9yPSIjMDAwMDAwIiBmaWxsPSIjZmZmIiBzdHJva2UtbWl0ZXJsaW1pdD0iOCIgdmVjdG9yLWVmZmVjdD0ibm9uLXNjYWxpbmctc3Ryb2tlIiBzdHlsZT0iLWlua3NjYXBlLXN0cm9rZTpoYWlybGluZSIvPjxwYXRoIGQ9Im0wIDBoMTIuN3YxMi43aC0xMi43eiIgZmlsbD0ibm9uZSIgc3Ryb2tlLW1pdGVybGltaXQ9IjgiIHN0cm9rZS13aWR0aD0iMS4xOTA2Ii8%2BPC9zdmc%2BCg%3D%3D&labelColor=ffffff)

<a href="https://roundabout-host.com">
  <img src="https://github.com/Secret-chest/Secret-chest/assets/74449186/7bf7f91b-9a3a-4bc5-a7de-c0b4c52b8d0a" width="100%">
</a>
