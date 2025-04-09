
<h1>Hi 👋</h1>

<div style="display: flex; align-items: center; border: 1px solid #ccc; border-radius: 10px; padding: 15px; margin: 20px 0;">
  <div>
    <p>In the following categories, all current and former projects are listed in respect to their finish date and, if applicable, open-source license.</p>
    <br>
    <p>If you have any project you would like to collaborate on, please send a quick message to: <strong>contactmarty.certify938@passinbox.com</strong></p>
  </div>
</div>

</br>

<p align="center">
    <a href="https://katzenkaffee.vercel.app/">
        <img height="150" src="KatzenKaffeClickMe.png" alt="Boom Chess">
    </a>
    </br>
    (Q1 2025)
</p>

</br>

<p align="center">
    <a href="https://gardeningcat.itch.io/boom-chess">
        <img height="150" src="bommchessitchio.png" alt="Boom Chess">
    </a>
    </br>
    (Q1 2024)
</p>

</br>

<h3>Projects Chronologically</h3>

<table style="width:100%;">

<tr>
    <td style="width:50%;">
      <h3>EntropyVisualizer - Arduino-based sensor read-in to serial and LED strip</h3>
      <p>✅ Finished and in Production/Archive</p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> C++</p>
      <p><strong>Time:</strong> Q2 2025</p>
      <p>Microcontroller board equipped with a gas meter, temperature/humidity sensor, microphone, display, and LED strip. Using sensor data to generate randomness, visualizes it with colors on the LED strip, and outputs a random long unsigned integer via its serial interface, which can be read in to try to get close to true randomness.</p>
      <p>Though to the analog data (0-1023) of the microphone and the gas sensor, and the patterned fluctuations it thereby experiences, I suggest testing it out first on any new system to determine the amount of actual entropy achievable in your environment. </p>
      <a href="https://github.com/mklemmingen/EntropyVisualizer">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=EntropyVisualizer&color=yellow&logo=github" alt="GitHub Repo">
      </a>
    </td>
  <td align="center"  style="width:50%;">
      <a>
        <img src="https://raw.githubusercontent.com/mklemmingen/EntropyVisualizer/refs/heads/main/EntropyVisualization.gif" alt="gif of working Entropy Visualization" height="150">
      </a>
    </td>
  </tr>

<tr>
    <td style="width:50%;">
      <h3>TelegramToMap - Automatic Threat-Location Data Mapping</h3>
      <p>🔄 Ongoing Development</p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Python, QGIS</p>
      <p><strong>Time:</strong> Q2 2025</p>
      <p>Scans incoming messages in Telegram groups for Ukrainian air alarms, extracting location data of UAVs, missiles, and planes. Adds a red marker to the map in QGIS, which turns white after some time and eventually disappears.</p>
      <p>Created since I had a hard time keeping up with translating and typing in the translated location to unsecure map-services. This saves time and stays completly local after receiving the telegram information.</p>
      <a href="https://github.com/mklemmingen/TelegramToMap">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=TelegramToMap&color=red&logo=github" alt="GitHub Repo">
      </a>
    </td>
  <td align="center"  style="width:50%;">
      <a>
        <img src="ukraineHeat.png" alt="png of a QGIS user interface with the ukraine map highlighted" height="150">
      </a>
    </td>
  </tr>
  
<!--- MASK - Machine-Learning Assisted Skeleton Kinect Tracking -->
<tr>
    <td style="width:50%;">
      <h3>MASK - Machine-Learning Assisted Skeleton Kinect Tracking </h3>
      <p> 🔄 Ongoing Develoment </p>
      <p>🌐 AGPL-2.0 License</p>
      <p><strong>Tech:</strong> Python, lots of Python</p>
      <p><strong>Time:</strong> Q2Q32025 </p>
      <p>Approach for threshold-based pose recognition in TouchDesigner using a KinectV2, MediaPipe, and their connection via data synchronization and a Kalman filter. The system utilizes machine learning to improve Kinect skeleton tracking and aims to enable precise pose recognition.  </p>
      <p>Designed for triggering subroutines while tracking in a light-noisy environment with relatively fast-moving bodies</p>
      <a href="https://github.com/mklemmingen/MASK">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=MASK&color=yellow&logo=github" alt="GitHub Repo">
      </a>
    </td>
  <td align="center"  style="width:50%;">
      <a>
        <img src="kinect.png" alt="png of a skeletan with nodes" height="150">
      </a>
    </td>
  </tr>

<!--- Python script to recursively travers a directory structure and check all image files on likelyhood of nsfw by using machine learning -->
<tr>
    <td style="width:50%;">
      <h3> cleanSmut </h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Python </p>
      <p><strong>Time:</strong> Q12025 </p>
      <p>Python script to recursively travers a directory structure and check all image and additionaly video files, to identify potentially NSFW content using a neural model trough a h5 file usage (the OpenNSFW2 library) , and moves flagged files to a separate folder. The script processes files in parallel for efficiency, logs NSFW probabilities, and ensures smooth operation  with built-in error handling and safety measures </p>
      <p>Designed as a tool in data recovery and long-term storage to sort out unwanted files for archiving.</p>
      <a href="https://github.com/mklemmingen/cleanSmut">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=cleanSmut&color=white&logo=github" alt="GitHub Repo">
      </a>
    </td>
  <td align="center"  style="width:50%;">
      <a>
        <img src="machineLearning.png" alt="png of a neural network with NSFW written over its hidden layers" height="150">
      </a>
    </td>
  </tr>

<!--- Javascript Subprocess exif data sorting scripts into media&files -->
<tr>
    <td style="width:50%;">
      <h3> Exif_DataByDate_Sorting </h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Javascript </p>
      <p><strong>Time:</strong> Q12025 </p>
      <p>Automates the organization of files into structured directories based on their creation dates and file types. (processes files, determines their creation dates using EXIF metadata or file system dates, and moves them to appropriate year, month (, datatype) directories) </p>
      <p>Designed as a tool in data recovery and long-term storage to sort files for quick look-up and memory preservation. Uses backups and hash-checks to make sure no corruption appeared though to software layer errors.</p>
      <a href="https://github.com/mklemmingen/Exif_DataByDate_Sorting">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=Exif_DataByDate_Sorting&color=white&logo=github" alt="GitHub Repo">
      </a>
    </td>
   <td align="center"  style="width:50%;">
      <a>
        <img src="fileSorting.gif" alt="gif showing sorting of files in an old office" height="150">
      </a>
    </td>
  </tr>

<!-- R Tutorial with Survey -->
  <tr>
    <td style="width:50%;">
      <h3>R Datamanipulation Tutorial</h3>
      <p> ✅ Finished and in Production/Archive </p>
       <p>📜 MIT License</p>
      <p><strong>Tech:</strong> R, HTML, CSS, Markdown</p>
      <p><strong>Time:</strong> Q12025 </p>
      <p>R-script that, when run, opens a localhosted browser to learn statistical approaches in data sciences through a self-collected dataset interacting with local R-tools.</p>
      <p>Designed as a way to learn fundamental data science stuff more or less visually pleasing.</p>
      <a href="https://github.com/mklemmingen/R_DataScience_Tutorial">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=R_Data_Science_Tutorial&color=green&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center"  style="width:50%;">
      <a href="https://www.youtube.com/playlist?list=PLJR0d_Vv370_5z8SbQHiUYpTRRZ9-fPv3">
        <img src="Hypothese.jpeg" alt="Image showing a hypothese test" height="150">
      </a>
    </td>
  </tr>

<!-- Mixtape -->
  <tr>
    <td style="width:50%;">
      <h3>Mixtape</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p> 🌐 AGPL-3.0 License </p>
      <p><strong>Tech:</strong> TouchDesigner, DaVinci Resolve, Python, Arduino C++</p>
      <p><strong>Time:</strong> Q1 2025</p>
      <p>270° interactive digital art project to experience a life's musical emotions through memories of birthdays.</p>
      <a href="https://github.com/mklemmingen/MIXTAPE">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=MIXTAPE&color=red&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center"  style="width:50%;">
      <a href="https://www.youtube.com/playlist?list=PLJR0d_Vv370_5z8SbQHiUYpTRRZ9-fPv3">
        <img src="https://img.youtube.com/vi/PLJR0d_Vv370_5z8SbQHiUYpTRRZ9-fPv3/0.jpg" alt="Youtube: Trailer zur Installation (Click me :>)" height="150">
      </a>
    </td>
  </tr>

<!-- Modern Offroad Vehicle Infotainment System -->
  <tr>
    <td style="width:50%;">
      <h3>Modern Offroad Vehicle Infotainment System</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>📜 MIT License</p>
      <p><strong>Tech:</strong> FIGMA, HTML</p>
      <p><strong>Time:</strong> Q1 2025</p>
      <p>Infotainment system design for a family outdoor car, with improved machine control and entertainment.</p>
      <a href="https://github.com/mklemmingen/OutdoorInfotainment">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=OutdoorInfotainmentsystem&color=green&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center"  style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/raw/main/OutdoorInfotainment.gif" alt="Outdoor Infotainment System" height="150">
    </td>
  </tr>

<!-- KatzenKaffee -->
  <tr>
    <td style="width:50%;">
      <h3>KatzenKaffee</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> NextJS, React, SQLite</p>
      <p><strong>Time:</strong> Q4 2024</p>
      <p>Website to learn sustainable cat owning. <a href="https://katzenkaffee.vercel.app/">Visit here</a></p>
      <a href="https://github.com/mklemmingen/KatzenKaffeeWeb">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=KatzenKaffee&color=yellow&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center"  style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/raw/main/KatzenKaffee.gif" alt="KatzenKaffee" height="150">
    </td>
  </tr>

<!-- HIDmibbi -->
  <tr>
    <td style="width:50%;">
      <h3>HIDmibbi</h3>
      <p>🟡 Finished, Standing by for Issue Creations </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> C++, Arduino</p>
      <p><strong>Time:</strong> Q3 2024</p>
      <p>Windows 11 admin gain via cheap USB microcontrollers to visualize rubber ducky exploits by UI.</p>
      <a href="https://github.com/mklemmingen/HIDmibbi">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=HIDmibbi&color=grey&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/raw/main/HIDmibbi.gif" alt="HIDmibbi" height="150">
    </td>
  </tr>

<!-- BoardGame Jam Framework (Blank) -->
  <tr>
    <td style="width:50%;">
      <h3>BoardGame Jam Framework (Blank, Free to Use!)</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Java</p>
      <p><strong>Time:</strong> Q3 2024</p>
      <a href="https://github.com/mklemmingen/GameJamFramework">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=BareBoardGameJam&color=purple&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/blob/main/boardgameGameJam.png" alt="BoardGame Framework Image" height="150">
    </td>
  </tr>

<!-- BoardGame Jam Framework (Chess) -->
  <tr>
    <td style="width:50%;">
      <h3>BoardGame Jam Framework (Chess, Free to Use!)</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Java</p>
      <p><strong>Time:</strong> Q3 2024</p>
      <a href="https://github.com/mklemmingen/GameJamChess">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=GameJamChess&color=green&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/blob/main/FrameworkChessCheckers.png" alt="BoardGame Framework Image" height="150">
    </td>
  </tr>

<!-- BoardGame Jam Framework (Checkers) -->
  <tr>
    <td style="width:50%;">
      <h3>BoardGame Jam Framework (Checkers, Free to Use!)</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Java</p>
      <p><strong>Time:</strong> Q3 2024</p>
      <a href="https://github.com/mklemmingen/GameJamCheckers">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=GameJamCheckers&color=red&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img src="https://github.com/mklemmingen/mklemmingen/blob/main/BoardGameMenu.png" alt="BoardGame Framework Image" height="150">
    </td>
  </tr>

<!-- CSS Art Tutorial -->
  <tr>
    <td style="width:50%;">
      <h3>CSS Art Tutorial</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> HTML, CSS</p>
      <p><strong>Time:</strong> Q3 2024</p>
      <p>Quick, short, and easy tutorial on how to create dynamic animated logos with CSS.</p>
      <a href="https://github.com/mklemmingen/CSSArtTutorial">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=CSSArtTutorial&color=grey&logo=github" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
     <img align="right" height="230" src="https://github.com/mklemmingen/mklemmingen/raw/main/cssArt.gif"  />
    </td>
  </tr>

<!-- Q1Q2 2024 Study-Projects -->
  <tr>
    <td style="width:50%;">
      <h3>Q1Q2 2024 Study-Projects</h3>
     <p> ✅ Finished and in Production/Archive </p>
      <p>📜 MIT License</p>
      <p><strong>Tech:</strong> C++, C#, Java, Python</p>
      <ul>
        <li>Levenshtein Distance Corruption-Restorer (C++)</li>
        <li>Producer-Consumer-Problem Displayer via AWT (Java)</li>
        <li>Function Graph Display (Python with Tkinter)</li>
        <li>PGM Filter Operations with Custom Canvasing Display</li>
      </ul>
      <a href="https://github.com/mklemmingen/Q1Q2Projects2024">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=Q1Q22024Projects&color=red&logo=applearcade" alt="GitHub Repo">
      </a>
    </td>
   <td align="center" style="width:50%;">
     <img align="right" height="230" src="https://github.com/mklemmingen/mklemmingen/raw/main/StudyProjects2024Q12.gif"  />
    </td>
  </tr>

<!-- Boom Chess! -->
  <tr>
    <td style="width:50%;">
      <h3>Boom Chess</h3>
      <p>🟡 Finished, Standing by for Issue Creations </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Java, libGDX</p>
      <p><strong>Time:</strong> Q3 2023 - Q1 2024</p>
      <p>Military-Pixel Pieces with Health and complex relations fight it out on the modern chess board. Features 3 different bot modes, challenge modes, multiple team colors, and music by Artist Wambutz.</p>
      <a href="https://github.com/mklemmingen/boom-chess">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=BoomChessDesktop&color=blue&logo=applearcade" alt="GitHub Repo">
      </a>
      <a href="https://github.com/mklemmingen/BoomChess-Android">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=BoomChessAndroid&color=blue&logo=applearcade" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img align="right" height="200" src="https://github.com/mklemmingen/mklemmingen/raw/main/boomChessGiffy.gif"  />
  </td>
  </tr>

<!-- Senet: A Simple Workers Game -->
  <tr>
    <td style="width:50%;">
      <h3>Senet: A Simple Workers Game</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Java, libGDX</p>
      <p><strong>Time:</strong> Q4 2023</p>
      <p>The oldest known board game, re-created as a speedrun challenge with the libGDX Framework.</p>
      <a href="https://github.com/mklemmingen/senet-boom">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=senet-boom-desktop&color=orange&logo=applearcade" alt="GitHub Repo">
      </a>
    </td>
  <td align="center" style="width:50%;">
      <img align="right" height="200" src="https://github.com/mklemmingen/mklemmingen/raw/main/senetboom.gif"  />
  </td>
   </tr>

<!-- Tropico 6 - Advanced Teams -->
  <tr>
    <td style="width:50%;">
      <h3>Tropico 6 - Advanced Teams</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌍 Creative Commons Zero Universal (CC0)</p>
      <p><strong>Tech:</strong> Unreal Engine 4, C++</p>
      <p><strong>Time:</strong> Q4 2023</p>
      <p>Adds team features to the multiplayer - no cooldown on team money transfer. A simple Unreal Engine 4 asset overwrite.</p>
      <a href="https://github.com/mklemmingen/Tropico6_Advanced-Team">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=Tropico-6&color=yellow&logo=steam" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img align="right" height="200" src="https://github.com/mklemmingen/mklemmingen/raw/main/tropico6.jpg"  />
  </td>
  </tr>

<!-- Space Mouse -->
  <tr>
    <td style="width:50%;">
      <h3>Space Mouse: The Special Operodent</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🌍 Creative Commons Zero Universal (CC0)</p>
      <p><strong>Tech:</strong> Python</p>
      <p><strong>Time:</strong> Q2 2023</p>
      <p>A randomly generated 3D maze-solving game with a space mouse searching for cheese.</p>
      <a href="https://github.com/mklemmingen/space-mouse">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=space-mouse&color=yellow&logo=python" alt="GitHub Repo">
      </a>
    </td>
 <td align="center" style="width:50%;">
        <img align="right" height="200" src="./spacemouse.gif" alt="gif showing the maze solving space mouse in action." />
    </td>
   </tr>

<!-- Hangman 2 -->
  <tr>
    <td style="width:50%;">
      <h3>Hangman 2 - The Dictionaries Strike Back</h3>
      <p> ✅ Finished and in Production/Archive </p>
      <p>🔓 The Unlicense</p>
      <p><strong>Tech:</strong> Python</p>
      <p><strong>Time:</strong> Q2 2023</p>
      <p>A complex word-guessing game using datasets and hash maps to calculate the most likely word.</p>
      <a href="https://github.com/mklemmingen/hangman-2">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=hangman-2&color=blue&logo=steam" alt="GitHub Repo">
      </a>
    </td>
    <td align="center" style="width:50%;">
      <img align="right" height="200" src="https://github.com/mklemmingen/hangman-2/blob/e97240877eaf6d5c9ca147802d78cb2639509e25/hangman2_intro.gif"  />
    </td>
  </tr>

<!-- Stop the Token -->
  <tr>
    <td style="width:50%;">
      <h3>StopTheToken</h3>
      <p> 🔄 Ongoing Develoment </p>
      <p>🔓 The Unlicense</p>
      <p><strong>Tech:</strong> Plain text</p>
      <p><strong>Time:</strong> Ongoing</p>
      <p>A community-fed Pi-hole blocklist of websites that make use of AI-generation for their unoriginal articles—just to save bucks on human labor—ultimately draining the soul from journalism and the internet.</p>
      <a href="https://github.com/mklemmingen/StopTheToken">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=StopTheToken&color=grey&logo=github" alt="GitHub Repo">
      </a>
    </td>
  </tr>
</table>

<h3>Development Backlog</h3>

<table style="width:100%;">

<tr>
    <td style="width:50%;">
      <h3>LogChirpy - ornithological archival app</h3>
       <p> 🔄 Ongoing Develoment </p>
      <p>🌐 AGPL-3.0 License</p>
      <p><strong>Tech:</strong> Javascript, React Native, SQL, Firebase</p>
      <p><strong>Time:</strong> Q2-Q3 2025</p>
      <p></p>
      <a href="https://github.com/mklemmingen/LogChirpy">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=LogChirpy&color=brown&logo=github" alt="GitHub Repo">
      </a>
    </td>
  
  </tr>



<!--- AudioBlendr - android app to create own background noise out of premade sounds and manually added ones -->
<tr>
    <td style="width:50%;">
      <h3> AudioBlendr </h3>
      <p> 🔄 Development in Backlog </p>
      <p>🌐 AGPL-2.0 License</p>
      <p><strong>Tech:</strong> Kotlin </p>
      <p><strong>Time:</strong> Q2Q32025 </p>
      <p>Android app to create own background noise out of premade sounds and manually added ones  </p>
      <p>Designed as a on the fly solution to misophonia triggering environments.</p>
      <a href="https://github.com/mklemmingen/AudioBlendr">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=AudioBlendr&color=white&logo=github" alt="GitHub Repo">
      </a>
    </td>
  </tr>
  
  <tr>
    <td style="width:50%;">
      <h3>BrandAway - Brand Origin Identification</h3>
      <p> 🔄 Development in Backlog </p>
       <p>📜 MIT License</p>
      <p><strong>Tech:</strong> Kotlin, Firebase</p>
      <p><strong>Time:</strong> Q2Q32025 </p>
      <p>App for android letting you look up where a brand is from by manual input or scanning. build in Kotlin with a Firebase Backend. </p>
      <p>Designed as a tool for BuyFrom...-Movements as a on-the-fly solution. </p>
      <a href="https://github.com/mklemmingen/BrandAway">
        <img src="https://img.shields.io/static/v1?label=mklemmingen&message=BrandAway&color=blue&logo=github" alt="GitHub Repo">
      </a>
    </td>
  </tr>

</table>

<h3>Retro-Game Guides</h3>

<p> 🔄 Ongoing Develoment </p>
<a href="https://github.com/mklemmingen/turn.and.burn.no-fly.zone">
  <img src="https://img.shields.io/static/v1?label=mklemmingen&message=TurnandBurn-NoFlyZone&color=red&logo=applearcade" alt="GitHub Repo">
</a>

<h3 align="center">Thanks for scrolling!</h3>

<div align="center">
  <img src="https://profile-counter.glitch.me/mklemmingen/count.svg?" alt="Profile Visitor Counter" />
</div>
