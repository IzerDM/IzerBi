Military Planner

Offline desktop app for planning military duty rosters, built with Electron, Tailwind CSS, and packaged for Windows.

Features

Weekly duty schedule generation

Tabbed UI: Planning, Personnel, History

Offline-friendly

Electron .exe with custom icon and splash


Setup

git clone https://github.com/IzerDM/IzerBi
cd yourrepo
npm install
npm start   # run locally

Package as .exe

npm run package

The final .exe will appear in out/make/squirrel.windows/x64/

Folder Structure

├── assets/
│   ├── css/            # Tailwind, FontAwesome, custom CSS
│   ├── js/             # app.js core logic
│   ├── icon.ico        # Installer/app icon
│   └── installer.gif   # Installer splash
├── index.html          # UI
├── main.js             # Electron entry
├── package.json        # App config
├── github/workflows/   # CI/CD for GitHub Actions
└── README.md           # Project instructions

License

MIT

