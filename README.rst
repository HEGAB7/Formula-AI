Formula-AI
===========================================

Formula 1 is one of the most competitive sports in the world. Engineers and technicians from every team use weather radar screens, provided by Ubimet to the teams, which allows them to track the current weather and make predictions during the race. Race engineers relay precise information to drivers, including:

How many minutes until it starts raining
Intensity of the rain
Which corner will be hit first by the rain
Duration of the rain
Dataset Description

I will go through Formula 1 2021 Weather Data for the Formula AI Hackathon '22 - Challenge 1.

Here is some of the important attributes:
-------------

- SESSION_UID: Unique identifier for the session
- SESSION_TIME: Amount of seconds in the session
- TIMESTAMP: Unique every second for every session UID and player car index.
- Date: Derived column from TIMESTAMP
- TRACK_TEMPERATURE: Track temp. in degrees Celsius
- WEATHER_FORECAST_SAMPLES_M_TRACK_TEMPERATURE: Same but in relation with Weather forecast samples.
- AIR_TEMPERATURE: Air temp. in degrees Celsius
- WEATHER_FORECAST_SAMPLES_M_AIR_TEMPERATURE: Same but in relation with Weather forecast samples.
- NUM_WEATHER_FORECAST_SAMPLES: Number of weather samples to follow
- SEASON_LINK_IDENTIFIER: Identifier for session - persists across saves
- SESSION_TYPE: - 0 = unknown,
          - 1 = P1,
          - 2 = P2,
          - 3 = P3,
          - 4 = Short P,
          - 5 = Q1,
          - 6 = Q2,
          - 7 = Q3,
          - 8 = Short Q,
          - 9 = OSQ,
          - 10 = R,
          - 11 = R2,
          - 12 = Time Trial
          - For practice races (P1, P2, P3) the maximum session length is 1 hour.
          - For qualifying races (Q1, Q2, Q3) the maximum session length is 18 minutes.
- WEATHER_FORECAST_SAMPLES_M_SESSION_TYPE: Same but in relation with Weather forecast samples.
- SESSION_TIME_LEFT: Time left in session in seconds
- SESSION_DURATION: Session duration in seconds
- WEATHER: - 0 = clear,
     - 1 = light cloud,
     - 2 = overcast,
     - 3 = light rain,
     - 4 = heavy rain,
     - 5 = storm
- WEATHER_FORECAST_SAMPLES_M_WEATHER: Same but in relation with Weather forecast samples.
- TRACK_TEMPERATURE_CHANGE: 0 = up, 1 = down, 2 = no change
- AIR_TEMPERATURE_CHANGE: 0 = up, 1 = down, 2 = no change
- RAIN_PERCENTAGE: Rain percentage (0-100)
