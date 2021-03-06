  Motivation
================

  The principal goal is to develop an application using virtual reality technology to increase the public engagement in archaeological processes. The overall objective is to create engaging narratives using cost effective VR setup through the manipulation of virtual objects using natural user interfaces through simple gesture and pose controls.


 Current Setup (Functional Requirements)
================================================

1. Technology: WebVR
2. Languages and framework: HTML, CSS, Javascript, A-Frame


 Current Setup (Non-Functional Requirements)
================================================

1. Source Code Repository Manager: Git
2. Platform as a Service (PaaS): Heroku (http://boiling-falls-96383.herokuapp.com/)


 How to Run?
================

1. To run this application locally, nodejs and npm needs to be present on the machine.Run below command from the root folder.

	$>npm install
	$>node server.js

2. Access the application at the browser URL http://localhost:12810/


  Areas of Improvements/Scope for further development
================================================================

1. Enhance the user experience for Samsung GearVR with Diego
2. Backend application to have to store the player information like personal details, pretest results, gameplay summary and posttest results to a NoSQL database
3. Application to display statistical information in graphs and charts
4. Inclusion of any media files like audio, video and texts regarding archaeological domain to make the user experience better
5. (Non-Functional Requirement) Static code analysis using Sonarqube to reduce code duplicacy and improve coding standards

  Testing
================
  Tested with Mozilla Firefox, Google Chrome and Amazon Silk web browsers
  Tested on Ubuntu laptop and Android mobiles


  Known Issues
================

1. SetTimeout is not working, ie timing out immediately, in Google Chrome web browser
2. Audio is loaded twice so as to enable backbround music on laptop Firefox browser
3. Images are not in the power of two so A-frame spends time in converting them to the power of two (width x height in pixels)
4. Faced the error 'Rats! WebGL hit a snag!' on Amazon Silk browser while loading obj model on Kindle Fire


  References
================

1. Map of Scotland
https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Map_of_Scotland_within_the_United_Kingdom.svg/2000px-Map_of_Scotland_within_the_United_Kingdom.svg.png

2. Map edit to retain transparency
http://www168.lunapic.com/editor/

3. A-Frame Docs
https://aframe.io/docs/0.5.0/introduction/

4. Skybox image
https://www.architectsjournal.co.uk/pictures/2000x2000fit/1/0/2/1265102_AJ01___AndrewLee_NMS_4.jpg

5. Skybox image update with google street view
google maps : national museum of scotland
street view panaroma id: F:-HzAAlrq1WUQ/V9IqaOTbsYI/AAAAAAAAidQ/8KOdrpWzouIEE2OA1NEPhs4QQi2LgxRRQCLIB
Panaroma Image courtesy of  Davide Rizzo
Application and Panaroma link : https://istreetview.com/F:-HzAAlrq1WUQ/V9IqaOTbsYI/AAAAAAAAidQ/8KOdrpWzouIEE2OA1NEPhs4QQi2LgxRRQCLIB
Street View 360 Windows application to download as a skybox
(Skybox creation is also possible with google streetview android app)


6. DOM introduction
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

7. Text on plane
https://github.com/aframevr/aframe/blob/master/dist/aframe-master.js
https://github.com/aframevr/aframe/tree/master/examples/test/text


8. Logging in file
https://www.w3schools.com/nodejs/nodejs_filesystem.asp
https://stackoverflow.com/questions/6912584/how-to-get-get-query-string-variables-in-express-js-on-node-js

9. Evaluation screen design
https://www.freshdesignweb.com/css-registration-form-templates/

10. Heroku git repository URL
https://git.heroku.com/boiling-falls-96383.git

11. Heroku application URL
https://boiling-falls-96383.herokuapp.com/

12. Sticker 1
https://rlv.zcache.com/trust_me_im_an_archaeological_museum_keeper_square_sticker-rc8c229401eb542ffbaa8033fc2b76caf_v9wf3_8byvr_324.jpg

13. Sticker 2
https://rlv.zcache.com/i_dig_archaeology_classic_round_sticker-r068df2d2f1fa41cb96b74510dcd8e510_v9waf_8byvr_324.jpg

14. Models of Ava's skull and the beaker (Decimated to around 10MB from 600MB with Blender application)
https://sketchfab.com/models/b7d543087d3d4754834db766b1b247c9
https://sketchfab.com/models/48e90ca2a90a4c118be13b261c03e7b5

15. Archaeological sites
https://canmore.org.uk/site/52068/edinburgh-castle Edinburgh Castle - Edinburgh
https://canmore.org.uk/insites/34 Cladh Hallan prehistoric village - Machair, South Uist
https://canmore.org.uk/insites/27 Delfour ring cairn and stone circle - Alvie, Highland
https://canmore.org.uk/insites/31 Swaites Hill 'Hero's cairn' - South Lanarkshire
https://achavanichbeakerburial.wordpress.com/about/ Achavanich Beaker Burial Project

16. Sound - Scene background music
https://freesound.org/people/frankum/sounds/320497/

17. Tool/Process images
Expert in the Field http://archaeology.mrdonn.org/
Riso Minisys Machine http://www.oxfordauthentication.com/about-us/the-laboratory-and-the-tl-testing-process/reso/
Accelerator Mass Spectrometry https://en.wikipedia.org/wiki/Accelerator_mass_spectrometry
https://www.physics.purdue.edu/ams/introduction/ams.html
Macroscopic Analysis http://enthusio.com/best/13050/Best-Archaeology-Books
Thermoluminescence Dating http://www.scientificarttests.com/images/art-tl-thermo.jpg
Radiocarbon Dating http://722836920996307078.weebly.com/radiocarbon-dating.html
http://rses.anu.edu.au/files/radiocarbon_sub1.jpg

18. Shuffle algorithm
https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array

19. Timer code
https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_countdown
https://stackoverflow.com/questions/1197928/how-to-add-30-minutes-to-a-javascript-date-object


Meeting Notes with Diego and Jun - 17 July 2017
----------------------------------------

instructions + performance + graphics, performance and 7 years old playable - arrows in process - more info with dots - side panel instructions progress text splash screen to have vr image

roomscaping
google blocks
environment component
aframe registry - particles in the air, layout
link traversal and portals
explosion mesh component in the end
turn around on the showVideoTabs
oscillators of sound from diekus
boundary checker
github pages - master page
