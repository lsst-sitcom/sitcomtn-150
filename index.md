# Summary of M2 Tests

:::{note}
**This technote is a work-in-progress.**
:::


Abstract
========

This report summarizes all tests performed to verify and validate (V&V) the M2 subsystem for its installation at the telescope. 
After a description on how it is structured the V&V for the M2 subsystem, a discussion on the test cycles is reported and the link to 
all the tests performed for the V&V campaign.



M2 subsystem V&V process
========================

M2 subsystem V&V has the aim to bring the M2 subsystem ready and safe for the installation at the telescope. It is organized in several 
test cycle campaigns each one enabling the following steps in the various AIV phases. 

The main drive in design the test campaign is to enable from the functional and safety point of view all the operations needed to bring the 
M2 cell and the glass secondary mirror in operation. This will permit to demonstrate that the M2 cell can operate safely 
and carry out the operations for which it was designed.

The test campaign is structure in the following cycles:

[LVV-R148](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R148 "LVV-R148") M2 Re-Verification of Glass-Safety Requirements with the Surrogate Mirror at Level 3

[LVV-R248]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R248 "LVV-R248") M2 Verification with the Surrogate Mirror on the TMA - Static Tests

[LVV-R269]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R269 "LVV-R269")  M2 Verification with the Surrogate Mirror on the TMA - Dynamic Tests

[LVV-R271]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R248 "LVV-R271") M2 Re-Verification - Before glass-installation - Location and Movement independent

[LVV-R118]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R118 "LVV-R118") M2 Preliminary Functional Testing and SAL Integration

[LVV-R249]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R249 "LVV-R249") M2 Cell with Glass Verification at Level 3

[LVV-R250]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R250 "LVV-R250") M2 cell with Glass Verification at the TMA - Static

[LVV-R280]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testCycle/LVV-R280 "LVV-R280") M2 cell with Glass Verification at the TMA - Dynamic

LVV-R148 
========

This test cycle is the M2 Re-Verification of Glass-Safety Requirements with the Surrogate Mirror at Level 3.

It is the first test cycle of the campaign and its aim is the Glass safety functional re-verification of the cell at Level 3 facility. The cycle has been ended at April 2024. It is composed 
by 20 tests reported in the table below.

 Key code | Title |
|:---|---:|
| [LVV-T1803]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1803 "LVV-T1803") | M2 Hazard Mitigation Verification on Level 3 |
| [LVV-T1823]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1823 "LVV-T1823") | M2 Mechanical Inspection |
| [LVV-T2873]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2873 "LVV-T2873") | M2 Actuator NO Back Driving - Axial actuators |
| [LVV-T1784]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1784 "LVV-T1784") | M2 Actuator NO Back Driving - Tangent actuators |
| [LVV-T2912]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2912 "LVV-T2912") | M2 LUT (Cart Rotation back and forth) |
| [LVV-T1787]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1787 "LVV-T1787") | M2 LUT L3 - Cart Rotation (rotating 90 deg in one direction) |
| [LVV-T1790]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1790 "LVV-T1790") | M2 Actuator Bump Test |
| [LVV-T1827]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1827 "LVV-T1827") | M2 Inner loop control - open-loop mode |
| [LVV-T1826]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1826 "LVV-T1826") | M2 outer control loop - closed-loop mode - tangent actuators |
| [LVV-T1792]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1792 "LVV-T1792") |  M2 Force Balance System Verification|
| [LVV-T2837]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2837 "LVV-T2837") | M2 Passive Tangent Links Rotation Test |
| [LVV-T1783]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1783 "LVV-T1783") | M2 Actuator Force Limits |
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782 "LVV-T1782") | M2 Rigid Body Motion limits re-verification after glass installation |
| [LVV-T1791]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1791 "LVV-T1791") |Masses new M2 Rigid Body Motion ranges at TMA - deprecated |
| [LVV-T1829]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1829 "LVV-T1829") | Masses new M2 Rigid Body Motion ranges at TMA |
| [LVV-T1799]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1799 "LVV-T1799") | M2 E-Stop Test |
| [LVV-T1820]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1820 "LVV-T1820") | M2 EUI Shutdown Handling |
| [LVV-T1821]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1821 "LVV-T1821") | M2 Tangent Links Heat Dissipation |
| [LVV-T1789]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1789 "LVV-T1789") | M2 Closed-Loop Active Optics Duration Test |
| [LVV-T1788]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1788 "LVV-T1788") | M2 bending modes - Control System Accuracy and Repeatability |


For each test the correspoding link of the test case is reported. All the tests have been executed and classified as passed (13) or passed with deviation (5). 

Only two fail the execution i.e. [LVV-T1821](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1821) 
and [LVV-T1790](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1790>).

While the first one has been resolved after [DM-44455](https://rubinobs.atlassian.net/browse/DM-44455) M2 support, 
the second is still under investigation after [LVV-E3752](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/testPlayer/testExecution/LVV-E3752) .

The failed execution is hoewever referred for a test repeated after the installation  at the TMA and probably due to a different adjuestement of some tangent actuators.  Anway repeating newly the test no problems arise.

LVV-R248 
========

This test cycle is the M2 Verification with the Surrogate Mirror on the TMA - Static Tests

Aim of the test cycle is to verify a minimum set of functional test at the TMA, verify if the interlocks work on TMA, verify some requirements
not fully verified at Levelk 3 and verify requirements that need the TMA to be statically positioned at a specific AZ and/or EL angle other than El, Az=0.

 Key code | Title |
|:---|---:|
| [LVV-T2790]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2790 "LVV-T2790") | M2 Hazard Mitigation Verification on TMA  |
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782 "LVV-T1782") | M2 Rigid Body Motion limits re-verification after software upgrade  |
| [LVV-T1794]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1794 "LVV-T1794") | M2 - Minimum Functionality Test  |
| [LVV-T2969]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2969 "LVV-T2969") | M2 outer control loop - closed-loop mode - Axial actuators |
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782 "LVV-T1782") | M2 Rigid Body Motion limits at TMA |
| [LVV-T2943]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2943 "LVV-T2943") | M2 Interlock Verification |
| [LVV-T1810]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1810 "LVV-T1810") | Calibrate M2 Optimal Position and Position Sensor Offset |
| [LVV-T1615]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1615 "LVV-T1615") | Integration of M2 with SAL |
| [LVV-T2963]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2963 "LVV-T2963") | M2 Release for Observing (RFO) Test |

[LVV-T1782](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782) is named in a different way in the link due to a problem with versioning. The right title for this test cycle is related to version 3.0 and not 5.0 which is the last version and refers to test cycle LVV-R250.
Ten tests have been perfomed, four classified as passed, four classified as passed w/ deviation, one formally waiting for the closure and one 
failed [LVV-T1782](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782>)
This last one has been superseed by [LVV-T1782](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782) after the software upgrade.

LVV-R269 
========

This test cycle is the M2 Verification with the Surrogate Mirror on the TMA - Dynamic Tests.

This test cycle comprises test cases to verify requirements that need the TMA to be moved dynamically over a range in AZ, EL, or both axes. 
The cycle has been ended at November 2024. It is composed  by 10 tests reported in the table below

 Key code | Title |
|:---|---:|
| [LVV-T1821]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1821 "LVV-T1821") | M2 Tangent Links Heat Dissipation  |
| [LVV-T3019]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3019 "LVV-T3019") | M2 cell demonstration with the TMA inclinometer readings  |
| [LVV-T3017]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3017 "LVV-T3017") | M2 Dynamic Test, increasing speed, acceleration, jerk - Data Analysis  |
| [LVV-T2999]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2999 "LVV-T2999") | M2 Passive Tangent Links Test during TMA elevation slew  |
| [LVV-T2985]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2985 "LVV-T2985") | M2 LUTs repeatability with TMA elevation |
| [LVV-T2964]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2964 "LVV-T2964") | M2 Force Distribution with/without Force Balance System vs. Azimuth slew |
| [LVV-T2955]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2955 "LVV-T2955") | Gateway Tests for the M2 Dynamic Test - Data Collection |
| [LVV-T2944]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2944 "LVV-T2944") | M2 Dynamic Test, increasing speed, acceleration, jerk - Data Collection |
| [LVV-T2932]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2932 "LVV-T2932") | M2 settling time and hysteresis after TMA slew - Data Analysis |
| [LVV-T1787]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1787 "LVV-T1787") | M2 LUT with glass - M2 cart rotation 180 degrees re-orientation |

Ten tests have been perfomed, five classified as passed, four classified as passed w/ deviation and one 
failed ([LVV-T3019](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3019)).

This test has to be repeated.

LVV-R271 
========

This test cycle is M2 Re-Verification before glass-installation. It is location and movements independent.

Aim of the test cycle is to execute test cases that must verify requirements not fully passed at level 3 and do not need the M2 cell in a specific 
location or in a specific state of movement.

Key code | Title |
|:---|---:|
| [LVV-T3029]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3029 "LVV-T3029") | M2 surrogate stiffness matrix verification - data analysis  |
| [LVV-T3028]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3028 "LVV-T3028") | M2 cell transport from TMA to Level 3  |
| [LVV-T1829]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1829 "LVV-T1829") | M2 Rigid Body Position - IMS Stability and Repeatability - Position Sensor Verification - L3 Data Analysis  |
| [LVV-T1791]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1791 "LVV-T1791") | Assess new M2 Rigid Body Motion ranges at TMA - deprecated  |
| [LVV-T3024]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3024 "LVV-T3024") | M2 rotation with surrogate (Cart Rotation back and forth) after inclinometer ILC update  |
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3024 "LVV-T1782") | M2 Rigid Body Motion limits re-verification after glass installation  |
| [LVV-T1790]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1790 "LVV-T1790") | MM2 Axial Actuator Bump Test  |
| [LVV-T3023]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3023 "LVV-T3023") | M2 Tangent Links Heat Dissipation data analysis after modification  |
| [LVV-T2852]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2852 "LVV-T2852") | M2 Axial & Tangent Actuator Accuracy, Repeatability, Resolution and Stiffness  |
| [LVV-T2853]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2853 "LVV-T2853") | M2 Passive Tangent Links over 360° rotation  |
| [LVV-T2980]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2980 "LVV-T2980") | M2 Rigid Body Motion Range / Safety Stops clearance inspection  |
| [LVV-T2965]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2965 "LVV-T2965") | M2 Rigid Body Motion - DoF cross-talk - Data Analysis  |
| [LVV-T3028]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3028 "LVV-T3028") | M2 cell transport from TMA to Level 3 |
| [LVV-T1822]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1822 "LVV-T1822") | M2 cell light or electro-magnetic interference |
| [LVV-T2941]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2941 "LVV-T2941") | M2 Motor and Electronics Noise Level Study-(TEA cooling system?) |
| [LVV-T2930]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2930 "LVV-T2930") | M2 Cell Weight |
| [LVV-T1614]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1614 "LVV-T1614") | M2 EUI Characteristics |
| [LVV-T1798]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1798 "LVV-T1798") | Verify M2 SAL Telemetry against EUI Display and the EFD |


14 tests have been closed, ten classified as passed, three classified as passed w/ deviation and one 
failed ([LVV-T3028](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3028)).

Four tests are still to be exectued: [LVV-T2852](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2852), 
[LVV-T2965](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2965>), 
[LVV-T1822](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1822>), 
[LVV-T2941](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2941). 

About the failed test LVV-T3028, this was the Telemetry taking during M2 transpostation from L3 to L8. Because of a failure,  data were not acquired. This test can be moved to test cycle LVV-R280.

About test still pending:

[LVV-T2852](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2852) has to be performed on one spare actuator and so has been posponed. Descoping can be considered.

[LVV-T2965](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2965) Data present from other dataset (rigid body motion test). Script to be written.

[LVV-T1822](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1822) EMC tests on the cell still are pending.

[LVV-T2941](https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2941 ) This test does not trace any requirement. Proposed for Descoping.

LVV-R118 
========

This test cycle is the M2 Preliminary Functional Testing and SAL Integration.

This test cycle is closed. Several test cases were outdated and needed to be deprecated. They are labeled as M2_old_version_test.
The test cycle is kept because the test cases were executed or an execution was started and we want to preserve the results for historical reasons.
All pending test cases are done or moved to other test cycles.

So no discussion on test cases is needed on this test cycle.

LVV-R249 
========

This test cycle is the M2 Cell with Glass Verification at Level 3.

This test cycle intends to verify the beahviour of the cell with glass just mounted at Level 3 to assure that all operations are safe with the glass mounted. 
The cycle is composed by 7 tests,  one of them outdated so we can consider the test cycle concluded in July 24.

Key code | Title |
|:---|---:|
| [LVV-T1994]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1994 "LVV-T1994") | M2 - Minimum Functionality Test  |
| [LVV-T1787]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1787 "LVV-T1787") | M2 LUT with glass - M2 cart rotation 180 degrees re-orientation |
| [LVV-T3027]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3027 "LVV-T3027") | M2 glass stiffness matrix verification - data analysis
| [LVV-T3031]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3031 "LVV-T3031") | M2 Tangent Links Force Balance system re-verification after glass installation
| [LVV-T1795]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1795 "LVV-T1795") | M2 Mirror Weight
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782 "LVV-T1782") | M2 Rigid Body Motion limits re-verification after glass installation
| [LVV-T3025]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3025 "LVV-T3025") | M2 ILC Firmware Upgrade and Downgrade capability Testing

Six tests have been perfomed, five classified as passed, one classified as passed w/ deviation. One has been considered outdated (LVV-T3025).

LVV-R250 
========

This test cycle is the M2 cell with Glass Verification at the TMA - Static.

This test cycle intends verify the beahviour of the cell with glass mounted at TMA in a Static situation. The cycle is composed by 7 tests reported in the 
table below and it is still ongoing.

Key code | Title |
|:---|---:|
| [LVV-T1990]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1990 "LVV-T1990") | M2 Axial Actuator Bump Test |
| [LVV-T3032]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3032 "LVV-T3032") | M2 behaviour in case of earthquake at the horizon - data analysis |
| [LVV-T2872]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2872 "LVV-T2872") | M2 Interlock Verification |
| [LVV-T1782]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1782 "LVV-T1782") | M2 Rigid Body Motion limits re-verification after glass installation |
| [LVV-T1822]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1822 "LVV-T1822") | M2 cell light or electro-magnetic interference |
| [LVV-T1994]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1994 "LVV-T1994") | M2 - Minimum Functionality Test |
| [LVV-T1794]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1794 "LVV-T1794") | M2 temperature |

Only one test has been perfomed and passed with deviation (LVV-T3032). The other tests are ongoing or only planned.


LVV-R280 
========

This test cycle is the M2 cell with Glass Verification at the TMA - Dynamic.

This test cycle intends to verify the beahviour of the cell with glass mounted at TMA in a dynamic situation. The cycle is composed by 9 tests reported in the 
table below and it is still ongoing.

Key code | Title |
|:---|---:|
| [LVV-T3019]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3019 "LVV-T3019") | M2 cell demonstration with the TMA inclinometer readings |
| [LVV-T2932]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2932 "LVV-T2932") | M2 settling time and hysteresis after TMA slew - Data Analysis |
| [LVV-T1821]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1821 "LVV-T1821") | M2 Tangent Links Heat Dissipation |
| [LVV-T1796]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T1796 "LVV-T1796") | M2 minimum vibration frequency verification |
| [LVV-T3015]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3015 "LVV-T3015") | M2 Improvement elevation LUT from Force Balance Offsets - Data Collection |
| [LVV-T3034]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3034 "LVV-T3034") | M2 closed-loop break-out during TMA slew - Gateway test |
| [LVV-T2944]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2944 "LVV-T2944") | M2 Dynamic Test, increasing speed, acceleration, jerk - Data Collection |
| [LVV-T3017]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T3017 "LVV-T3017") | M2 Dynamic Test, increasing speed, acceleration, jerk - Data Analysis |
| [LVV-T2845]( https://rubinobs.atlassian.net/projects/LVV?selectedItem=com.atlassian.plugins.atlassian-connect-plugin:com.kanoah.test-manager__main-project-page#!/v2/testCase/LVV-T2845 "LVV-T2845") | M2 surface control down to optical image budget |

Only one test has been perfomed and passed with deviation (LVV-T3032). The other tests are ongoing or only planned.

Conclusions 
===========

The nine test cycles for the V&V of the M2 subsystem have been reported here with all the link to the tests that have been planned and/or performed. 
5 Test cycles are mostly closed (LVV-R148, LVV-R248, LVV-R269 and LVV-R271 and LVV-R249), one is considered deprecated and it is here only for historical reasons (LVV-R118). 
The last two (LVV-R250 and LVV-R280) are still ongoing and will be closed during the commissioning of the telescope.

