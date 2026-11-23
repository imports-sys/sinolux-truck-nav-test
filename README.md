# SINOLUX TRUCK NAV TEST

Separate experimental UK truck routing/mobile GPS web app. Not approved for vehicle navigation. Uses OpenStreetMap tiles, Nominatim geocoding and public Valhalla truck-routing demonstration endpoint. These external community services have no uptime guarantee, and routing data may omit bridge/weight/road restrictions. Do not use for driving HGV.

Project is isolated from other SINOLUX sites and JARVIS runtime. No API keys, customer data or payments. Geolocation requires explicit browser permission and GPS positioning stays in the browser unless user requests a route from their position; geocoding and routing send requested endpoints to their respective providers.
