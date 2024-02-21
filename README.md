# Very Important Client (VIC) for Kuljetus Tahvo Oy 

Route planner and calculator for crane services.

Not an open source project, paid freelance project so the source code is private.

**Website:** https://vic.kuljetustahvo.fi

## Tech stack:

- Written in *React* with *JavaScript*
- Built with *Vite*
- Hosted in *Azure* as *Web App*
- Authorization and database is done with *Supabase*
- Email sending is done with *EmailJS*
- Google maps is done with *@react-google-maps* library.

## How it works / Features:

### User:
- Made for hardware stores and others that need a crane delivery from a to b.
- User logs in with personal credentials that are made for them by the admin.
- Automaticly calculates the price for the route with given parameters, such as the amount of cargo, how big crane is needed and is there a need for a trailer.
- Allows users to pick a date from calendar.
- Calculator accepts up to two optional waypoints or stops that are included in to the calculation.
- These waypoints are added with the press of "Lisää pysähdys" button.
- Full route is then displayed on the map.
- Distance, price and route with stops are written in text above the map.
- User can then confirm the route by pressing "Lähetä Hyväksyntä" button.
- This opens a confirmation modal and when pressed "Hyväksy" button, website stores the route data to database and sends a confirmation email to the admin.

### Admin:
- Website automatically detects an admin email when logging in.
- Website displays admin page "Hallintasivu" with two tables, users and route history.
- Within the users table, admin can edit and add new users to the authorization/database.
- Route history table only displays all the confirmed routes that are in the database.

## Screenshot from the private repository:
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/7e69a577-5be0-47e8-a543-37f6eabd81b4" width="500px"/>

## Screenshots from the webapp:
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/bc82d47f-3515-44e0-916e-2888739e0ffc" width="500px"/>
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/123f85ec-d4d5-4812-897a-8eb793d2cd8a" width="500px"/>
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/2c71a711-c643-4703-8a90-6fd58a888812" width="500px"/>
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/da6968f3-af1e-41f1-bd2a-dcc6783b3315" width="500px"/>
<img src="https://github.com/Luukalindgren/VIC_Kuljetustahvo/assets/70708962/6f4a4253-a914-430d-8dec-10b051dabcbe" width="500px"/>





