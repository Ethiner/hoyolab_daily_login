# Genshin Daily Check-In

Automate HoYoLAB Daily Check-In Using Github Actions

[JP](README.ja.md)

# Instructions

1. Fork the repository
2. Go to Settings -> Secrets
3. Click "New repository secret" button
4. Make `LTUID`, `LTOKEN` secrets with your authentication data, following the instructions below
5. Go to Actions, Click on `Enable Actions Workflow` button
6. Click `HoYoLAB Attendance` on left Workflows list, and Press Enable Workflow button
7. You're all set! It will be automatically run your attendance every 16:00 UTC+0

# How can I get my Auth Datas?

Instruction based on Chrome Dev Tools:

1. Go to [HoYoLAB](http://hoyolab.com)
2. Log-In to your account
3. Press F12 to open Developer Tools
4. Go to Application -> Cookies -> `https://www.hoyolab.com`
5. Copy `ltuid` and `ltoken`

# License

[MIT License](LICENSE)
