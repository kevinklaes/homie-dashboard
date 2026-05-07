## Main Screen Elements

**Top bar - Left**
- Dashboard name
- Live clock and date, updated every second

**Top bar - Middle**
- Weather widget — icon, temperature, and condition from your HA weather entity

**Top bar - Right**
- Pet icon — pet stats popup (litter box, feeder, water fountain, litter box usage)
- Calendar icon — upcoming events from multiple HA calendar entities
- Security icon — Alarmo controls
- Theme icon — select from multiple themes

**Notification - Center Top 1/3**
- Hidden notifications from multiple HA `binary_sensor` or `input_boolean`. Useful for reminders like cat maintenance, vitamins not taken, or coffee to prepare for tomorrow.

**Hero area - Center 2/3**
- Full-bleed background image
- Time-aware greeting — Good Morning / Good Afternoon / Good Evening / Good Night
- Home stats grid — up to 10 entity-driven tiles in a 5-column layout

**Now Playing Bar - Center Bottom 3/3**
- When a HA media player is playing, a slim bar slides up from the bottom showing artist, track name, previous/play-pause/next controls, and a live progress bar updated every 2 seconds.
- When nothing is playing the player is hidden
- When music is paused or stops, the players dissappears after a few seconds

**Sensor row pills - Bottom 1/2**
- Floor sensor pill — temperature, humidity, and PM2.5 for up to two floors
- Solar pill — production (kW), today's energy consumption, export (kW), battery state of charge (%), and inverter temperature

**Controls row - Bottom 2/2**
- Chip buttons for each control group (Lights, Scenes, Air Con, Purifiers, Blinds, Bath, Irrigation)
- Active-count badge on each chip (e.g. "3 on")
