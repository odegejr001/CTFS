#🧠 Challenge Title
Missing Person (Free Room) - Use your OSINT skills to help the police track down a missing person.
🎯 Objective
“My friend went on holiday in 2025 and shared some photos, but I haven’t heard from him since. Can you help me track him down for the police report?"
🛠️ Tools Used
-	Exiftool (Realised it’s totally not necessary)
-	Google 
🔎 Investigation Process
✅Downloaded the provided files (food.jpg and MotoGP.jpg)
✅Checked files' metadata using Exiftool 
	exiftool food.jpg && exiftool MotoGP.jpg
✅ Reverse search the image with Google
❔Questions and Answers
MotoGP
1.	What is the commercial name of this circuit? 
⚠️ Searching the image with Google Lens. I found where the image was taken from 
Ans: Pertamina Mandalika International Street Circuit
2.	When did the event take place?
⚠️ From checking the properties of the image, I found it was taken on the 5th Oct 2025, but I ran into a problem trying to find the date range. After surfing online, I found the 2026 event ticketing website, and it’s a three-day event, so I just guessed three days back and forward of the fifth. Yeah, that’s bad if it’s in real life, but pardon me, I’m new to this.
Ans: 03-05/10/2025
FOOD
Hint: He sent me a message, this is the last I heard from him:” Went to this cool MotoGP after party, and became friends with one of the local DJs who played that night. We’re going to visit a cave tomorrow.”
3.	He told me he ate delicious Mexican food. What is the name of the restaurant?
⚠️ Searching the image with Google Lens. I found where the image was taken from 
Ans: Cantina Mexicana
4.	At what time was this photo taken? 
⚠️ Exiftool gives this information, but basic image properties also show this information
Ans: 19:55:30 
5.	What is the full address of the bar’s location?
⚠️ Searching Google Maps for the Restaurant, there are actually two bars close to it (Rasta Bar Reborn & Surfer’s bar), which I actually thought it would be the Rasta Bar and started trying to find Information about it but nothing then I read the message again and saw that the Surfer’s Bar has a message in their about section (...plus live DJ performances...)
Ans: Jl. Raya Kuta, Kuta, Kec. Pujut, Kabupaten Lombok Tengah, Nusa Tenggara Bar
6.	What is the DJ's stage name?
⚠️ Dead Ends: I got to a few dead ends on this one. One of the images showed a sign reading "DJ Good Vibe." I zoomed in on images of a DJ playing to see if their name was on the equipment, but it wasn’t.  I also watched the videos visitors posted where there is a DJ playing to see if one of the sounds mentioned the DJ’s stage name, but no.
Breakthrough: Search Google for “sufer bar lombok” and they have an Instagram account (@surfersbar.lombok). Surfing through their page, there is a reel with the title “After MotoGP Party” Listing three DJs to perform that night, and one matched the answer format.
Ans: Bong Leleh
7.	After digging into the DJ's other online accounts, what cave does he take tourists to?
⚠️ Searching Google Maps for “cave kuta lombok”, a Bat Cave is matching our answer and it is the first one there. 
Ans: Gua Sumur
8.	What number did the DJ list for his tour business?
⚠️ Searching Google for “bongleleh” for social media profiles, there an Instagram account, but nothing I found there, there is a Facebook profile with the username “@bongleleh” and the account name is Gua Sumur with the number listed
Ans: 085333137345

🧩 Thing I learned from solving this room
✅Importance of metadata in investigations
✅How hidden data can be embedded in files
✅Practical use of Linux tools in forensics
✅OSINT techniques for real-world investigations
