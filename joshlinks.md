# Josh's Links

This list is a compilation of useful links, resources and advice from throughout the starstruck season.

Some Advice:

To stay up to date on current robots, matches, and record on the internet, create a folder of bookmarks. The folder should contain search queries designed to turn up recent posts related to a topic (i.e. reveal, intake, lift, skills run etc.). Common sites for these search queries are Youtube, the Vex Forums, and Google. Be sure to arrange by most recent in the search. Open all the bookmarks in the folder often to check on recently released robots and concepts. It's never bad to be ahead of the game.

# Table of Contents
1. [Motors](#Motors)
    1. [PTC Info](#PTC-Info)
    2. [Gears and Ratios](#Gears-and-Ratios)
    3. [Friction](#Friction)
2. [Scouting Values](#Scouting-Values)
    1. [OPR](#OPR)
    2. [Cholesky Decomposition](#Cholesky-Decomposition)
    3. [Neural Net](#Neural-Net)
3. [PID Loops](#PID-Loops)  
4. [Linkage Analysis](#Linkage-Analysis)
    1. [Optimization](#Optimization)
5. [Programming](#Programming)
    1. [Kalman Filter](#Kalman-Filter)
    2. [Motor Current Prediction](#Motor-Current-Prediction)
    3. [LCD](#LCD)
    4. [Wiring](#Wiring)
    5. [Position Tracking](#Position-Tracking)
    6. [Troubleshooting](#Troubleshooting)
    7. [Gyro](#Gyro)
6. [Scouting](#Scouting)
7. [VEX Forums Rulings](#VEX-Forums-Rulings)
    1. [Judging and Technicals](#Judging-and-Technicals)
8. [Excel/Google Sheets Resource](#Excel/Google-Sheets-Resource)
    1. [vexdb.io and JSON](#vexdb.io-and-JSON)
9. [External Power Supply](#External-Power-Supply)
10. [FRC](#FRC)
11. [Steel v Aluminum](#Steel-v-Aluminum)
12. [Videos](#Videos)
    1. [News](#News)
13. [Nothing but Net Links](#Nothing-but-Net-Links)
14. [AutoCAD](#AutoCAD)
15. [Mechanisms](#Mechanisms)



## Motors <a name="Motors"></a>

[Joystick Motor Control Remapping](https://www.vexforum.com/index.php/9800-24c-s-motor-control-value-remapping/0)

[Turbo Joystick Remapping](https://www.vexforum.com/index.php/21242-truespeed-for-turbo-motors/0/)

[Estimating PTC Trip Temp Using Motor Current](https://vamfun.wordpress.com/2012/07/18/estimating-the-ptc-temperature-using-motor-current-first-try-no-luck/)

[Understanding DC Motors](http://www.me.umn.edu/courses/me2011/arduino/technotes/dcmotors/motor-tutorial/)

[DC Motors EN11104](http://uav.ece.nus.edu.sg/~bmchen/courses/EG1108_DCmotors.pdf)

[DC Motor Characteristics](http://lancet.mit.edu/motors/motors3.html)

[DC Motor Calculations](http://www.me.mtu.edu/~wjendres/ProductRealization1Course/DC_Motor_Calculations.pdf)

[SimpleMotor: Calcualtions](http://simplemotor.com/calculations/)

[Further DC Motor Calcuations](https://ewbelsalvador.wikispaces.com/file/view/Electric+Motors.pdf)

[DC Motors and Generators](http://pemclab.cn.nctu.edu.tw/W3lib/books/ElectroCraft85/ch2.dcmotor.pdf)

[Characteristic of DC Motors](http://www.rci.rutgers.edu/~dbirnie/solarclass/MotorPrimerGaTech.pdf)

[Theory Construction and Operation: DC Motors](http://geosci.uchicago.edu/~moyer/GEOS24705/Readings/Klempner_Ch1.pdf)

[Losses in DC Motors](https://www.electrical4u.com/losses-in-dc-machine/)

[DC Motor: How it works](http://www.learnengineering.org/2014/09/DC-motor-Working.html)

[DC Motor Operation](http://hyperphysics.phy-astr.gsu.edu/hbase/magnetic/motdc.html)

[DC Motors Principles of operation](http://solarbotics.net/starting/200111_dcmotor/200111_dcmotor2.html)

[Working or Operating Principle of DC Motor](https://www.electrical4u.com/working-or-operating-principle-of-dc-motor/)

[Cortex Motor Speed Testing: Jpearman](https://www.vexforum.com/index.php/7942-cortex-motor-speed-testing/0)

[Pros Introduction post: VEXFourms](https://www.vexforum.com/index.php/9401-introducing-the-purdue-robotics-os-pros-for-cortex/0)

[Motor Speed Experiement](https://www.vexforum.com/index.php/20901-interesting-motor-experiment/0/)

[Speed torque curves vexfourms: jpearman](https://www.vexforum.com/index.php/7868-motor-torque-speed-curves/0)

[Speed Toqrue Curves rev2](https://www.vexforum.com/index.php/8089-motor-torque-speed-curves-rev2/0)

[Max power of motors](https://www.vexforum.com/index.php/362-how-to-find-max-power-curve-of-motors/p1#p2354)

### PTC Info <a name="PTC-Info"></a>

[VEX PTC Manufacturer Data](http://www.hr-ptc.com/en/hr30/79-hr30-090.html)

[PTC Tripping: VEXMEN](http://www.vexmen.com/2014/02/troubles-tripping-circuit-breakers-with-10-big-393-motors/)

[PTC Performance Measurements: Jpearman](https://www.vexforum.com/index.php/7208-ptc-performance-measurements/0)

[PTC Cortex and motor Schematic (internal wirirng)](https://vamfun.files.wordpress.com/2012/11/vex-power-distribution-schematic-showing-ptc-resistances.jpg) 

### Gears and Ratios <a name="Gears-and-Ratios"></a>

[VEX Lift Gear Ratio Calculator](http://polynomic3d.com/user/smith/vex-lift-calc.html)

[VEX Lift Gear Ratio Calc. Source](view-source:http://polynomic3d.com/user/smith/vex-lift-calc.html)

[Top Drive Speeds: Stanley Shi](https://www.vexforum.com/index.php/16895-drive-top-speeds)

[Jpearman Planetary Gear Animation](https://jpearman.smugmug.com/Robotics/Misc/i-hS24cJx)

[Drive Types](http://www.simbotics.org/resources/mobility/omnidirectional-drive)

[Designing Drives for Competitive Edge](http://designcenter.gates.com/wp-content/uploads/2015/06/Gates-Designing-Drives-for-Competitive-Edge-White-Paper.pdf)

[Torsion of Shafts](http://www.engineeringtoolbox.com/torsion-shafts-d_947.html)

[Shear Stress Equations](http://www.engineersedge.com/material_science/shear-stress.htm)

### Friction <a name="Friction"></a>

[Gear Efficiency](http://www.roymech.co.uk/Useful_Tables/Drive/Gear_Efficiency.html)

[More Gear Efficiency](http://www.ihpva.org/HParchive/PDF/hp50-2000.pdf)

[The complete Guide to Chain](http://tsubaki.ca/pdf/library/the_Complete_guide_to_chain.pdf)

[Efficiency Analysis of Planetary Gear Box](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A397023&dswid=1630)

## Scouting Values <a name="Scouting-Values"></a>

[TRSP Calculation VEXFourms](https://www.vexforum.com/index.php/8703-sp-ranking-system-ideas/33)

[R project for statistical computing](https://www.r-project.org/)

### OPR <a name="OPR"></a>

[Chief Delphi OPR Calculations](https://www.chiefdelphi.com/forums/showthread.php?t=101390)

[FRC OPR File DUmp](https://www.chiefdelphi.com/media/papers/2174)

### Cholesky Decomposition <a name="Cholesky-Decomposition"></a>

[Reshish Matrix Calculator](http://matrix.reshish.com/)

[Cholesky decomposition](https://rosettacode.org/wiki/Cholesky_decomposition)

[Cholesky decomposition calc + other matrix operations](http://comnuan.com/cmnn01014/)

[Cholesky decomposition Excel Macro](http://www.real-statistics.com/linear-algebra-matrix-topics/cholesky-decomposition/)

[Matrix Inversion Using Cholesky Decomposition](https://arxiv.org/ftp/arxiv/papers/1111/1111.4144.pdf)

### Neural Net <a name="Neural-Net"></a>

[Neuroph: Neural Net Framework](http://neuroph.sourceforge.net/)

[Neuroph: example/tutorial](http://neuroph.sourceforge.net/tutorials/SportsPrediction/Premier%20League%20Prediction.html)

[how-to-choose-the-number-of-hidden-layers-and-nodes-in-a-feedforward-neural](https://stats.stackexchange.com/questions/181/how-to-choose-the-number-of-hidden-layers-and-nodes-in-a-feedforward-neural-netw)

[how to normalize data](https://stats.stackexchange.com/questions/70801/how-to-normalize-data-to-0-1-range)

## PID Loops <a name="PID-Loops"></a>

[PID Youtube Playlist tutorial (general)](https://www.youtube.com/playlist?list=PLCozfyh08FMgbZWeTbGOMw7o3biDlnvec)

[Introduction to PID Control Loops](https://docs.google.com/document/d/1D61dinGqP__CHzRfc9yNugnS9K-JTa395_r0qP7L5W8/edit)

[PID loop simluation 1](www.engineers-excel.com/Apps/PID_Simulator/PID.xls)

[PID Loop simulation 2](https://www.cs.cmu.edu/afs/cs/academic/class/15883-f15/lectures/cerebellum-controller/pid.xls)

## Linkage Analysis <a name="Linkage-Analysis"></a>

[4-bar linkage animations + full linkage simulator](http://dynref.engr.illinois.edu/aml.html)

[Four-Bar Linkage Analysis and Synthesis](https://www.softintegration.com/chhtml/toolkit/mechanism/fourbar/)

[Four-Bar Linkage Positions Analysis](https://www.softintegration.com/chhtml/toolkit/mechanism/fourbar/fourbarpos.html)

[Four-Bar Linkage Online Sim](http://www.mekanizmalar.com/fourbar.html)

[Optimization of Watt’s Six-bar Linkage to Generate Straight and Parallel Leg Motion ](http://cdn.intechopen.com/pdfs-wm/36561.pdf)

[Planar Kinetic Modeling and Analysis](http://sbel.wisc.edu/Courses/ME451/BookHaugVolONE/Chapter5.pdf)

[Fundamentals of Linkage Design](http://web.mit.edu/2.75/fundamentals/FUNdaMENTALs%20Book%20pdf/FUNdaMENTALs%20Topic%204.PDF)

[Algebraic Methods of Sythesis using displacement equations](http://ebooks.library.cornell.edu/k/kmoddl/pdf/013_011.pdf)

[Same as above:](http://www.upet.ro/annals/mechanical/pdf/2010/Annals-Mechanical-Engineering-2010-a27.pdf)

[4-bar linkage analysis](https://synthetica.eng.uci.edu/mechanicaldesign101/McCarthyNotes-2.pdf)

[Position Analysis via Complex means](http://ocw.metu.edu.tr/pluginfile.php/5791/mod_resource/content/8/ch3/3-7.htm)

[POSITION, VELOCITY AND ACCELERATION ANALYSES FOR PLANAR MECHANISMS USING COMPLEX NUMBER METHOD](http://moodlearn.ariel.ac.il/pluginfile.php/841376/mod_resource/content/1/%D7%9E%D7%A1%D7%A4%D7%A8%D7%99%D7%9D%20%D7%9E%D7%A8%D7%95%D7%9B%D7%91%D7%99%D7%9D.pdf)

[Hoeken's Linkage](http://www.designofmachinery.com/DOM/Chap_03_3ed_p134.pdf)

### Optimization <a name="Optimization"></a>

[Nimbus: interactive multiobjective optimization system](https://wwwnimbus.it.jyu.fi/)

[Simple Linear Equation Calculator](https://quickmath.com/webMathematica3/quickmath/equations/solve/advanced.jsp)

[Simplify Equations](https://www.symbolab.com/solver/simplify-calculator/)

[Ansys optimization software: student package](http://www.ansys.com/products/academic/ansys-student)

[Ansys Tutorial](https://www.scribd.com/doc/101372637/978-1-58503-725-4-2)

[Ansys Workbench guide](https://www.scribd.com/document/338623817/Tutorial-Week-3c-MECH3361-Workbench-Guide-pdf)

## Programming <a name="Programming"></a>

[Git Tutorial](https://git-scm.com/docs/gittutorial)

[Github for beginners](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)

[Jpearman Smart Motor Library (github)](https://github.com/jpearman/smartMotorLib/blob/master/SmartMotorLib.c)

[2V Skyrise Code (github)](https://github.com/RobertsonMark/2V_Main)

[Code Library for BNS (github)](https://github.com/JMarple/BNSLibrary)

[BNSLib advanced library](https://www.vexforum.com/index.php/13416-introducing-bnslib-an-advanced-programming-library-from-team-bn/0)

[BNSLib File](http://www.mediafire.com/file/5ezn0n151rvsm32/2016+BNS+CAD+Library+%28beta%29.zip)

[BCI Github](https://github.com/Octogonapus/BCI)

[2442A Code Github](https://github.com/Octogonapus/2442A-Code)

[Cody's VEX Tossup PROS Code Github](https://github.com/csmith105/VEX-Toss-Up-Robot-Code-PROS)

[Penguin Robotics Code](https://github.com/leungtimothy/penguinrobotics1617)

[Spur Flies Library](https://github.com/VTOW/SpurFlysLibrary)

[Using Encoders to Drive Straight](http://www.robotc.net/wikiarchive/Tutorials/Arduino_Projects/Mobile_Robotics/VEX/Using_encoders_to_drive_straight)

### Kalman Filter <a name="Kalman-Filter"></a>

[Wikipedia Kalman Filter](https://en.wikipedia.org/wiki/Kalman_filter)

[how-a-kalman-filter-works-in-pictures](http://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)


### Motor Current Prediction <a name="Motor-Current-Prediction"></a>

[Jpearman: estimating motor current](https://www.vexforum.com/index.php/7955-estimating-motor-current/0)

[Jpearman: estimating motor currnet part 2](https://www.vexforum.com/index.php/8095-estimating-269-motor-current-based-on-h-bridge-models/0)

[Jpearman: estimating motor current part 3](https://www.vexforum.com/index.php/8390-estimating-motor-current-part-3/0)

[VEX Motor Stall Data](https://www.vexforum.com/index.php/attachment/56464d7f8111b_VEX%20motor%20Stall%20tests%2005-25-2012-%20Raw%20Chart%20Data.txt)

[VEX 393 PWM Stall Graph](https://www.vexforum.com/index.php/attachment/56464d7f8199a_Motor%20393%20Stall%20Chart.pdf)

[VEx 292 PWN Stall Graph](https://www.vexforum.com/index.php/attachment/56464d7f814f1_Motor%20269%20Stall%20Chart.pdf)

### LCD <a name="LCD"></a>

[Advance advanced-applications-with-the-vex-lcd](http://www.robotc.net/blog/2012/05/18/advanced-applications-with-the-vex-lcd/)

[LCD for Multiple Autons](https://www.vexforum.com/index.php/9399-lcd-for-multiple-autonomous/0)

[Robot LCD Selection](https://www.vexforum.com/index.php/10510-robotc-lcd-autonomous-selection)

### Wiring <a name="Wiring"></a>

[Encoder Error in ports 4 and 10](https://www.vexforum.com/index.php/8874-quadrature-encoder-values-not-working-from-robotc-tech-forum/p1#p83607)

[Power Expander Voltage Status](https://www.vexforum.com/index.php/7604-robotc-power-expander-status-battery-voltage/0)

### Position Tracking <a name="Position-Tracking"></a>

[X-drive position tracking](https://www.vexforum.com/index.php/20635-x-drive-position-tracking/0)

[Holo Position Tracking](https://www.vexforum.com/index.php/21223-position-tracking-device/0#p186219)

### Troubleshooting <a name="Troubleshooting"></a>

[Cortex wouldnt connect to computer](https://www.vexforum.com/index.php/23778-cortex-won-t-connect-to-computer/0)

[Cortex not recognized](https://www.vexforum.com/index.php/21695-cortex-not-recognized-by-computer/0)

[Cortex not recognized 2](https://www.vexforum.com/index.php/7553-cortex-not-recognized-by-computer/0)

[Cortex Not communicating](http://www.robotc.net/forums/viewtopic.php?t=5819&p=26471)

[VEX Cortex PC Troubleshooting](http://cdn.robotc.net/pdfs/cortex/support/smartboard_cortex_fix.pdf)

### Gyro <a name="Gyro"></a>

[Gyro: Vamfun](https://vamfun.wordpress.com/2011/05/09/note-vex-gyro/)

## Scounting <a name="Scounting"></a>

[Worlds Arts Division Scounting Sheet: Example and Data](https://docs.google.com/spreadsheets/d/1V28NFvrStnL1mmGljFCvl4kWgJzAPS0bj5FVBjygZM0/edit#gid=2040176559)

[Scout OS](https://docs.google.com/document/d/1LSbxVR6eSoucEVSEhtdeS3jBZsiwaNjYvyTsN-1w7gg/edit)

## VEX Fourms Rulings <a name="VEX-Forums-Rulings"></a>

[Twist Ties for Cable Management](https://www.vexforum.com/index.php/18807-answered-use-of-twist-ties-on-robot-official-q-a-post)

[VEX Velcro](https://www.vexrobotics.com/275-1257.html)

[VEX Clinch Strap](https://www.vexrobotics.com/275-1258.html)

[VEX Velcro II](https://www.vexrobotics.com/275-1259.html)

[Acceptable Substitutes for Velcro: VEXFourms](https://www.vexforum.com/index.php/10190-answered-acceptable-substitutes-for-velcro)

[velcro: VEXFourms](https://www.vexforum.com/index.php/17697-velcro)

[Velcro Type Acceptable](https://www.vexforum.com/index.php/5354-answered-velcro-type-of-acceptable/0#p45721)

### Judging and Technicals <a name="Judging-and-Technicals"></a>

[Championship Qualifying Crit](http://www.roboticseducation.org/documents/2016/08/vrc-qualifying-criteria.pdf)

[VEX Tournament Manager](https://vextm.dwabtech.com/)

## Excel/Google Sheets Resource <a name="#Excel/Google-Sheets-Resource"></a>

[vlookup Multiple Values - Return MULTIPLE corresponding values for ONE Lookup Value](http://www.globaliconnect.com/excel/index.php?option=com_content&view=article&id=119)

[Return Multiple Items with One Lookup Value: Youtube](https://www.youtube.com/watch?v=wclmIcTsbtg)

[Understanding R-square value in compensation analysis](http://compensationinsider.com/understanding-r-square-value-in-compensation-analysis/)

[Logger Pro Graphing Guide](http://www2.vernier.com/manuals/ga3manual.pdf)

[Logger Pro Parametric Lines](https://www.desmos.com/calculator/nqom2ih05g)

### vexdb.io and JSON <a name="vexdb.io-and-JSON"></a>

[Brief vexdb.io tutorial: Vex Fourms](https://www.vexforum.com/index.php/11378-database/0)

[Handling JSON like a boss in PHP](http://nitschinger.at/Handling-JSON-like-a-boss-in-PHP/)

[Stars Wars API (practice database)](https://swapi.co/)

[JSON Viewer Online](https://codebeautify.org/jsonviewer)

[JSON Explained](http://www.json.org/)

[Import JSON data into Google Spreadsheets](https://medium.com/@paulgambill/how-to-import-json-data-into-google-spreadsheets-in-less-than-5-minutes-a3fede1a014a)

[Import JSON Google Sheets Script](http://blog.fastfedora.com/projects/import-json)

## External Power Supply <a name="External-Power-Supply"></a>

[Direct DC Power Supply for Cortex: vex forums](https://www.vexforum.com/index.php/14502-direct-dc-power-supply-for-cortex/0)

[VEX Power Outlet Adaptor: vex fourms](https://www.vexforum.com/index.php/2720-vex-power-outlet-adapter/0)

[External Power: vex fourms](https://www.vexforum.com/index.php/1794-problem-solved-using-external-power-servos/0)

## FRC <a name="FRC"></a>

FRC Motors:

[775Pro](https://www.vexrobotics.com/vexpro/all/217-4347.html)

[CIM](https://www.vexrobotics.com/vexpro/all/217-2000.html)

[Mini CIM](https://www.vexrobotics.com/vexpro/all/217-3371.html)

[BAG](https://www.vexrobotics.com/vexpro/all/217-3351.html)

[Versa Planetary Gear Box](https://www.vexrobotics.com/vexpro/all/versaplanetary.html)

[2017 FRC Control System Hardware Overview](http://wpilib.screenstepslive.com/s/4485/m/24166/l/144968-2017-frc-control-system-hardware-overview)

[User Manual: NI roboRIO](http://www.ni.com/pdf/manuals/374474a.pdf)

[Power Distribution User's Guide](https://content.vexrobotics.com/vexpro/pdf/217-4244-PDP-Users-Guide-20150305.pdf)

[Motors and Power Transmission](https://www.youtube.com/watch?feature=player_embedded&v=WPX3z-qLSk0)

[Denso Motor Specifications](https://firstfrc.blob.core.windows.net/frc2016manuals/Denso-Window-Motor.pdf)

[2016 FIRST Robotics Competition Motor Info](http://team4248.com/doco/2016-MotorManual.pdf)

[JVN's Design Calculator](https://www.chiefdelphi.com/media/papers/3188?langid=2)

## Steel v Aluminum <a name="Steel-v-Aluminum"></a>

[Wolfram Alpha: 5052-H32 vs a1008 steel](https://www.wolframalpha.com/input/?i=5052-H32+vs+a1008+steel)

[Wolfram Alpha: a1008 steel](https://www.wolframalpha.com/input/?i=a1008+steel&rawformassumption=%7B%22EHC%22,+%22Alloy%22,+%22UNSG10080%22%7D+-%3E+%7B%22UNSG10080::Shape:Sheet::Thickness:1.6To5.8Millimeters%22%7D)

[Wolfram Alpha: UNS A95052](https://www.wolframalpha.com/input/?i=UNS+A95052&rawformassumption=%7B%22EHC%22,+%22Alloy%22,+%22UNSA95052%22%7D+-%3E+%7B%22UNSA95052::StrengtheningProcess:StrainHardened::HardeningPercentage:25Percent::HeatTreatmentProcess:Stabilized::TemperDesignation:H32%22%7D)

[AK Cold rolled Steels](http://www.aksteel.com/pdf/markets_products/carbon/ak-cold-rolled-steel-201209.pdf)

[Cold Rolled Steel Standards](http://www.jfe-steel.co.jp/en/products/sheets/catalog/b1e-002.pdf)

[Cold Rolled Sheet Steel](https://www.ussteel.com/products-solutions/products/cold-rolled-sheet-steel)

## Videos <a name="Videos"></a>

[Cut to Bot's Videos: Fourm](https://www.vexforum.com/index.php/20300-vex-worlds-2016-match-videos-videos-by-team/0#p180607)

[Cut to Bots: Youtube](https://www.youtube.com/channel/UCyLxFCeZJSPbCY3Vd8kHc-w)

[NBN BCIT Livestream](https://www.youtube.com/watch?v=UydPkBdsslc&feature=youtu.be)

Team Ten Ton Font: [Base Runner JNL](http://fontsgeek.com/fonts/Base-Runner-JNL-Regular)

### News <a name="News"></a>

[North Shore News 2017 article](http://www.nsnews.com/news/programmed-for-change-1.8720834)

[North Shore News 2016 article](http://www.nsnews.com/news/students-follow-passions-at-north-shore-academies-1.2157581)

## Nothing But Net Links <a name="Nothing-but-Net-Links"></a>

[Physics of the Flywheel Launcher](https://www.vexforum.com/index.php/14274-physics-of-the-flywheel-launcher/)

[PID Constants for FLywheel](https://www.vexforum.com/index.php/17797-pid-constants)

[Trajectory of a Projectile](https://en.wikipedia.org/wiki/Trajectory_of_a_projectile#Angle_required_to_hit_coordinate_.28x.2Cy.29)

[Robot Position Calculator](https://www.vexforum.com/index.php/14430-robot-position-calculation/0)

[Aimbot Posistion](https://www.vexforum.com/index.php/14757-x-drive-finding-position-on-field-using-encoders/0)

[Love2d: Animation Tool](https://love2d.org/)

[Balistic Projections with drag](https://docs.google.com/spreadsheets/d/1oKwUFD7xEqpMLxCOx2qk7nH2bIw87NLKUVSOSr8OSMA/edit#gid=0)

[Calculating Flywheel Velocity](https://www.vexforum.com/index.php/17323-how-to-calculate-motor-flywheel-velocity-in-robotc)

[Flywheel PID Tuning](https://www.vexforum.com/index.php/17314-flywheel-pid-tuning)

[Fan DESIGN REsearch: Turbomachinery](http://www.engr.mun.ca/~yuri/Courses/MechanicalSystems/Turbomachinery.pdf)


## AutoCAD <a name="AutoCAD"></a>

[Inventor Tutorial](https://www.youtube.com/watch?v=1qZL494b2qE)

[parts Library 2016](http://www.mediafire.com/file/nfhyn9jk3vhc1a1/VEX+Parts+Library+2016.zip)

Video Tutorials:

[Autodesk Uni: Joints](http://au.autodesk.com/au-online/classes-on-demand/class-catalog/2015/fusion-360/cp10165#chapter=0)

[CP10778: From Crisp Design to Clean Documentation—An Introduction to Fusion 360 Drawings](http://au.autodesk.com/au-online/classes-on-demand/class-catalog/2015/fusion-360/cp10778#chapter=0)

[CP12977: Simulation for Fusion 360](http://au.autodesk.com/au-online/classes-on-demand/class-catalog/2015/fusion-360/cp12977#chapter=0)

[MA3514: Creating Assemblies with Autodesk® Fusion 360](http://au.autodesk.com/au-online/classes-on-demand/class-catalog/2012/autodesk-fusion-360/creating-assemblies-with-autodesk-fusion-360#chapter=0)

## Mechanisms <a name="Mechanisms"></a>

[locking mech 1](https://www.youtube.com/watch?v=riIIPMkrjZQ)
