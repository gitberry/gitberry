# gitberry 

SQL / Geofun / HTML / C# and more...

Self described as "curious misfit with a few technical skills"

This github holds repos that demonstrate or "study" various skills/technologies I work with:

## Data ##

1. SQL snippets that include:
   1. random data for testing
   1. PIVOT
  <br />https://github.com/gitberry/SQLSnippets
   1. deriving structure from JSON blurb
   <br />https://github.com/gitberry/SQLSnippets/blob/main/CrudeJsonORM.sql

1. Hash a database structure to know immediately if any structures has changed
   <br />https://github.com/gitberry/sqlHash

## Geofun / GIS ##

1. c# to convert get google KML into something else - VERY crude - for onetime tasks
<br />https://github.com/gitberry/KMLPoints

3. C# to convert Lat/Lon DMS Coordinates to D decimal - handy when geo data doesn't come the way you need it!
<br />https://github.com/gitberry/LatLonDMS2Dec

## HTML / API's / Vuejs ##

1. Mobile first HTML
<br />https://github.com/gitberry/MobileFirstHTMLexample
<br />https://github.com/gitberry/HTMLandJSSimpleSchedule

1. A simple experiment encrypting/decrypting using vuejs
<br />This concept of decrypting at the js client side is powerful - would like to know more about how apps like Bitwarden do it.  In the meantime I must learn some basics - and I decided to try it in vuejs - which is one of my favourite frontend frameworks (so far..)
<br />https://github.com/gitberry/vuejsSimplyEncryptDecrypt

1. A study of vuejs routes in a SPA (plus IIS and subdirectories off of domains)
<br />https://github.com/gitberry/VuejsRoutingIISSubDirExample

1. a crude .net 4.7 API stub (no authentication, no SQL)
<br />https://github.com/gitberry/APIcrudStubExample

1. A study of vuejs using a simple API
<br />https://github.com/gitberry/StudyVuejsUsingsimpleAPI

1. a readonly .net 4.7 API using EF TSQL
<br />https://github.com/gitberry/StudySimpleAPIwSQL

1. tables in vuejs using tanstack
<br />https://github.com/gitberry/vue-tanstack-example

1. JSON Web Token (JWT) API
   <br />The following two projects work hand in hand to provide
   both sides of the JWT action - the JWT token authentication/generation/validation
   between a server and a client.  A lot of fun to do!
   1. Serve/Generate
<br />This example done with .net 4.7 - I'd like to repeat with other stacks..
<br />Source: [https://github.com/gitberry/jwt-demo-backend-net47]
<br />Working Exmple: [https://jwtdemo.northberry.ca/json/swagger/]
   1. Client/Consume
<br />This example was done with Vuejs3, Vite, Pinia stack - to adoringly paraphrase an old musical: "a very modern general.. framework for a very modern major dev stack..."
<br />Source: [https://github.com/gitberry/jwt-demo-frontend-vuevitepinia]
<br />Working Exmple: [https://jwtdemo.northberry.ca/]

1. CRUD - .net API and VueJs3 Frontend
   <br/>Similar to the JWT project above - but full crud (Create Read Update Delete) demo.
   I didn't like how I build the SQL and DTO (Data Transfer Object) code
   and noted it.  I also want to leverage some tanstack tech
   I played with earlier - so this little demo project may get taken down
   and rewritten one of these days.
   <br/>Frontend: https://github.com/gitberry/crud-demo-frontend
   <br/>Backend: https://github.com/gitberry/crud-demo-api

## QR codes / PDFs ##
1. A simple study to make a QR Code windows desktop app - in .NET CORE 5.0
<br />https://github.com/gitberry/QRcodeCreateWindowsForms
1. An older personal project I had done back in 2017 with an older version of iTextSharp
   <br/>it was built to do form populating and page copying and paste automation
   but it also could do QR code generation and image insertion into PDFs
   older but kind cool to look at that.  I'll probably build my next
   stuff in a frontend tech..  stay tuned...
   <br/>https://github.com/gitberry/pdfTool
  

# *** Future Studies / Examples *** #

Below is some of the items on my interest list. In no particular order:

1. A full Authentication API (extra - is 2step extendable.. )
1. In Legacy .NET 4.7: Full CRUD JSON API using EF and MS SQL ( MySQL & sqlite too perhaps) 
1. In .NET 6 or 7 :  Full CRUD JSON  API using EF and MS SQL ( MySQL & sqlite too perhaps)
1. Hyperspectral analysis
   1. Python
   1. ENVI
   1. ArcGIS
   1. ML
1. Python
   1. simple ML (ie character recog)
   1. transactional analysis - reproducing work done here:<br/> https://github.com/laurentran/sequence-labeling
1. Generic Collection app
   1. collecting words/phrases & meta
   1. voting
   1. scheduling notices (ie word of the day)
1. arduino - internet gateway power reset when threshold achieved.
1. raspberryPI, rechargable power source, QR of signed datetime - to fulfill a geo collecting objective. 
   <br />extra: tamper resistant regime (ie avoid theft of signing key)
1. rasberryPI security cam controller
1. rpi air traffic node
1. rasberryPI controller for watering plants, weather station sensors and more.
1. encryption
   1. PKI generate
   1. signing
   1. encrypting
   1. historical summary
   1. deep dive into bitwarden (https://github.com/bitwarden/)
   1. deep dive into 1password (https://github.com/dschuetz/1password)
1. QR codes:
   1. Generate (Windows (done)/Web server/browser JS client) (extra: OSX/Android using Xamarin/MAUI)
   2. extra: decode using camera
   3. extra: decode in a Xamarin/MAUI app
   4. authentication loopback
1. Generic Event organizer
   1. Multi user/type authentication (& public viewing)
   1. Schedule/Location coordination
   1. results output
1. SQL
   1.  follow the same process  the Credit Union project I collaborated with Lauren Tran – a Microsoft Data Scientist for using Machine Learning to process transactional (ie financial transactions) data.   
   Challenges: (with what data? generated data?) (my nerves-induced bobble-headed interview here: https://www.youtube.com/watch?v=mn2Cy-0oiH8 - I think our cool Microsoft host vblogger could hardly keep from laughing out loud…) 
   Lauren's Open source from that project:  https://github.com/laurentran/sequence-labeling
   1. DNA sequence analysis
1. chatgpt / llm's
   1. Sql
   2. c#
   3. python
   4. js & frameworks  
   
