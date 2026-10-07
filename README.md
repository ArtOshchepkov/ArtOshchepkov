# Hey, I'm Artem (Tim) 👋

Backend engineer (Java, geospatial and data-intensive systems) with 7+ years in production.
I turn terabytes of GPS, census and road data into products people pay for: map matching, road networks, ETL pipelines, and the maps on top.
Founding engineer of [Map AI](https://interactive-map-ai.com), a US location-intelligence SaaS I built from the first commit.

📍 Tbilisi, Georgia (GMT+4) · remote, open to relocation within the EU

<img width="3200" height="1488" alt="Map AI: interactive demographic map of the USA" src="https://github.com/user-attachments/assets/f6e66045-a178-4a72-a1f3-1d45a70a9b66" />

---

## 🚀 What I've built

**[Map AI](https://interactive-map-ai.com)** - interactive demographic map of the USA (founding engineer, de-facto CTO, 2022 - now)
- Took the product from idea to **2,000 MAU**; designed the architecture, wrote the core backend and the Angular + Mapbox frontend, hired and mentored the team.
- **Spring Batch ETL over the entire US census**: 100+ parameters into 3M geo cells in under 60 hours (plain JDBC, tuned batching, parallelism and GC).
- Demographic profile for **any arbitrary US geometry in under 30 s** (JTS); REST API over millions of cells with bulk requests **under 300 ms**.
- **AI map agent** ([try it](https://interactive-map-ai.com/chat)): Python + Pydantic AI, combining the Mapbox MCP server with an MCP server I built into our Spring backend; it draws its answers on a live map.
- Proposed and built programmatic SEO: 30,000+ indexed pages, Google Search impressions **from zero to 500K+**.
- End-to-end Stripe subscription billing that carries all company revenue.

**[Ticon](https://ticon.co) / [TrafficZoom](https://trafficzoom.co)** - US traffic analytics from GPS traces (2020 - now)
- GPS pipeline over **terabytes of raw GPS** with **HMM map matching** (the topic of my Master's thesis): millions of points per report in under 2 minutes after deep profiling.
- US road-network topology from the full OpenStreetMap extract (PostGIS + JTS); **3M+ traffic detectors** from all 50 state DOTs matched to road segments.
- Invented a visitor-estimation algorithm on map-matched trips, the basis of a $2,000 Sales Projection report.
- Truck-traffic model trained on 555K detector samples I collected (R² 0.83, MAE 132 trucks/day); founded the Kotlin census microservice.
- Core geospatial endpoint from 5 s to 600 ms on a 1 TB table; a Redis Lua script took an admin endpoint from 1 hour to under 1 second.

**[WC In Time](https://t.me/wcintime_bot)** - find the nearest toilet, anywhere.  
300,000+ locations from OpenStreetMap, PostGIS search, live on Telegram.

**[Lamopad](https://lamopad.ru/samosval/game/)** - the site of my music project, with browser games built in.  
I also write [statistics explainers](https://lamopad.ru/strategy/) there (in Russian), with interactive calculators, Bayes in four different ways.

**Acoustic direction finder** - my Bachelor's thesis.  
STM32 device in C that finds the direction to a sound source in real time with a microphone array and on-chip DSP. [Watch it on YouTube →](https://www.youtube.com/watch?v=VJK4P9Nlrfc)

---

## 📄 Research and open source

**[JTS Topology Suite](https://github.com/locationtech/jts/issues/662)** - found a bug in the grid generator, located the exact line, proposed the fix; merged upstream.

**[Emission probability in vehicle map matching via Hidden Markov Models](emission-probability-in-vehicle-map-matching-via-hmm.pdf)** - white paper, unpublished.  
Shows that road width and geometry representation matter for HMM map matching; GPS error sigma of 4.5 m estimated on 10M+ real points.

**[Investigating Longevity in the US Using High-Resolution Data and Location Intelligence Tool](https://www.researchgate.net/publication/382896321_Investigating_Longevity_in_the_US_Using_High-Resolution_Data_and_Location_Intelligence_Tool)** - co-author.  
Life expectancy vs income and education across major US cities on 1-mile granular data from the tool I built.

**[Why you can't find a job in 2026. Lemons.](https://habr.com/ru/articles/1056172/)** - Habr article (in Russian) on the "market for lemons" in IT hiring, and why signals beat keywords.

---

## 🛠 Stack

**Expert:** Java 21 · Spring Boot / Batch / Security / Data · PostgreSQL · PostGIS · JTS · H3 · OpenStreetMap · map matching · performance tuning  
**Strong:** Python (FastAPI, NumPy, pandas, ML) · Angular + TypeScript · Mapbox GL · Redis · AWS (EC2, S3, Batch, Lambda, CDK) · Docker · Nginx · LLM agents, MCP, RAG  
**Working:** Kotlin (founded a production microservice) · Kafka · Citus · Spark · Martin vector tiles · Stripe  
**Had fun with** *(university and side projects)*: C · C++ · x86 Assembly (a Forth interpreter) · STM32 · FPGA (HLS) · Qt · WebGL shaders · Rust · Brainfuck

---

## 📚 Education

**MSc**, Neurotechnologies and Software Engineering, ITMO University, 2020 - 2022.  
Thesis: Map Matching Algorithm for GPS Tracks Using Hidden Markov Models.

**BSc**, Computer Science, ITMO University, 2016 - 2020.  
Thesis: Real-time Acoustic Direction Finding System Based on STM32.

> ITMO is the university behind the Kotlin programming language and the most decorated team in ICPC World Championship history.

---

## 📬 Get in touch

[Telegram](https://t.me/art_oshk) · tim.oshchepkov@gmail.com · [LinkedIn](https://www.linkedin.com/in/artem-oshchepkov-0b7938234/)

*Old GitHub account: [semitro](https://github.com/semitro)*

> 🏝️ Fun fact: I once traveled to Lombok island just because of the Java library name.
