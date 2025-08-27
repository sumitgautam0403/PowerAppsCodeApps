# PowerAppsCodeApps


sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm install

added 188 packages, and audited 189 packages in 18s

48 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm run dev

> appfromscratch@0.0.0 dev
> vite


  VITE v7.1.3  ready in 216 ms

  ➜  Local:   http://localhost:3000/
  ➜  Network: http://192.168.1.35:3000/
  ➜  press h + enter to show help

^C
sumitgautam@Sumits-MacBook-Pro AppFromScratch % pac auth create
'sumit.sharma@ibotix.in' authenticated successfully.
Validating connection...
Connected to... IBOTIX (default)
Default organization: IBOTIX (default)
Authentication profile created
    * UNIVERSAL                                : sumit.sharma@ibotix.in                   Public https://org7039b80e.crm8.dynamics.com/  

sumitgautam@Sumits-MacBook-Pro AppFromScratch % pac env select -env https://orgcaea0e20.crm8.dynamics.com/
Connected as sumit.sharma@ibotix.in
Looking for environment 'https://orgcaea0e20.crm8.dynamics.com/'
Validating connection...
Connected to... Telus
Selected org 'Telus' 'https://orgcaea0e20.crm8.dynamics.com/' for current authentication profile.
sumitgautam@Sumits-MacBook-Pro AppFromScratch % pac code init --displayname "Test Code App"
Connected as sumit.sharma@ibotix.in
Created power.config.json for Test Code App.
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm install --save-dev "@pa-client/power-code-sdk@https://github.com/microsoft/PowerAppsCodeApps/releases/download/v0.0.4/7-31-pa-client-power-code-sdk-0.0.1.tgz"

added 2 packages, and audited 191 packages in 3s

48 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm run dev

> appfromscratch@0.0.0 dev
> vite

10:53:39 PM [vite] (client) Re-optimizing dependencies because lockfile has changed

  VITE v7.1.3  ready in 404 ms

  ➜  Local:   http://localhost:3000/
  ➜  Network: http://192.168.1.35:3000/
  ➜  press h + enter to show help
10:55:08 PM [vite] vite.config.ts changed, restarting server...
10:55:08 PM [vite] server restarted.
10:55:09 PM [vite] vite.config.ts changed, restarting server...
10:55:09 PM [vite] server restarted.
^C
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm run dev

> appfromscratch@0.0.0 dev
> vite && pac code run


  VITE v7.1.3  ready in 76 ms

  ➜  Local:   http://localhost:3000/
  ➜  Network: http://192.168.1.35:3000/
  ➜  press h + enter to show help
^C
sumitgautam@Sumits-MacBook-Pro AppFromScratch % run build
zsh: command not found: run
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm ru build
Unknown command: "ru"

To see a list of supported npm commands, run:
  npm help
sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm run build

> appfromscratch@0.0.0 build
> tsc -b && vite build

vite.config.ts:3:23 - error TS2307: Cannot find module 'path' or its corresponding type declarations.

3 import * as path from 'path'
                        ~~~~~~

vite.config.ts:15:25 - error TS2304: Cannot find name '__dirname'.

15       "@": path.resolve(__dirname, "./src"),
                           ~~~~~~~~~


Found 2 errors.

sumitgautam@Sumits-MacBook-Pro AppFromScratch % npm install react 

up to date, audited 191 packages in 7s

48 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
sumitgautam@Sumits-MacBook-Pro AppFromScratch % 
