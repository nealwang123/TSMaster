>   **TSMaster Release Note**

>   Features

1.  2022-01-26

[1] New: project directory being used prompt supported

[2] Bug fix: db changes cause hidden panel crash

[3] New: auto generation of C code on compile for Git version compare

1.  2022-01-22

[1] new file type: PT7z (password protected T7z)

[2] TSMaster project directory icon supported

1.  2022-01-21

[1] directory based project management instead of T7z file

[2] Note: all relative paths reference to project directory

[3] Note: temporary directory can be dangerous, please create new directory for
each project

[4] Note: T7z file is now only used to import, export and project exchange

[5] Note: Git can now be used on project directory

1.  2022-01-17

[1] Single signal mode supported in graphics

[2] horizontal cursor and vertical cursor supported in graphics

[3] + - \* / buttons supported in Parameter curve

[4] minor bug fixes in graphics

1.  2022-01-13

[1] New: signal server API supported in mini program

[2] Improved: Numeric now supports replay

1.  2022-01-11

[1] New: Arxml Multiplex signal display supported in Graphics, Numeric, Meter,
Panel

[2] New: Factor and Offset supported in symbol mapping

[3] Improved: Panel high display quality

1.  2022-01-03

[1] Mini program variable change event can associate any system variable

[2] Module Auto start priority can be set in software settings

1.  2021-12-26

[1] Kernel improvement: load database, startup performance, etc.

[2] graphics bug fix: cursor time incorrect

[3] API Improvement: API can be initialized multiple times for LabVIEW

1.  2021-12-21

[1] New: system variables can now be created or deleted by API

[2] Improved: C editor system function names sorted

[3] Bug fix: unsupported arxml multiplexed signals deleted in C editor

[4] Bug fix: delete form in measurement setup causes order incorrect

1.  2021-12-14

[1] Improved: CAN Trace redesigned (arxml pdu supported)

[2] Improved: CAN Trace sort dialog added

[3] Improved: Project load speed increased

[4] Improved: MDI title bar double click handler

1.  2021-12-09

[1] New: [Calibration] Array type Measurement Var monitor, log and replay
supported

[2] Bug fix: enum display in calibration

[3] Bug fix: factor and offset calc. in graphics

1.  2021-12-06

[1] New: CAN Trace Sync. token with Graphics supported

[2] New: C Code snippet supports DB signals and RBS signals

[3] Improved: Graphics horz. and vert. adjust

[4] Improved: Graphics new column: Type

[5] Improved: System messages new filter

[6] Improved: C Code editor compiler default supports multi thread

1.  2021-11-26

[1] New: Get unique computer hw id api added

[2] Improved: TSMaster icon resolution enhanced

[3] Improved: all signals in message can be auto created as pair in symbol
mapping

1.  2021-11-24

[1] Improved: C editor omits duplicated message name while compling

[2] Bug fix: edit signal in sorted list of graphics

1.  2021-11-15

[1] New: tutorial videos in youtube when language is not Chinese

[2] New: drag signals from Calibration database and System variable manager to
STIM

[3] Improved: UI elements in CAN database, CAN Statistics

[4] Bug fix: default byte order in Calibration

[5] Bug fix: force stop connecting in calibration cause crash

1.  2021-11-04

[1] New: Add, Dec, Mul, Div supported in STIM

[2] New: Diagnostics

1.  2021-10-26

[1] New: auto code gen in CAN RBS in popup menu

[2] New: API to set message cycle in CAN RBS

[3] Improved: address in A2L now supports 0xXXXL (non official)

[4] Improved: mouse wheel on signal Y axis in Graphics: scroll to move, Ctrl +
scroll to zoom

[5] Bug fix: get or set vendor detect options API

1.  2021-10-19

[1] New: Counter column in CAN Trace

[2] New: Graphics y axis display option

[3] Improved: quantization error in trace eliminated

[4] Improved: RAM and Flash mapping supported in calibration for A2L generated
by Vector

[5] Bug fix: clear bus stat under baud \<\> 500k

[6] Bug fix: multiplex editor in graphics

1.  2021-10-06

[1] New: Open source CAN tool CANable (candleLight) supported

1.  2021-10-03

[1] Improved: High DPI display

[2] New: compiler parameters in C Editor

1.  2021-09-29

[1] New: Test system parameters can now be loaded from ini file

[2] New: Test system parameters list load and save with csv supported

1.  2021-09-28

[1] New: Drag drop from Trace to Graphics, Meter, Numeric, Panel

[2] New: Drag drop from Calibration database to Graphics, Numeric, Parameter
Curve, Panel

[3] New: Drag drop from CAN Database to Graphics, Numeric, Panel

[4] New: Drag drop from LIN Database to Graphics, Numeric, Panel

[5] New: Drag drop from System Var Mgmt to Graphics, Numeric, Panel

[6] New: Default settings options for STIM, CAN Transmit, CAN Trace, LIN
Transmit, LIN Trace, Graphics

[7] Improved: Calibration log file name supports absolute dir

[8] Improved: Graphics signal list header popup menu added

1.  2021-09-25

[1] Improved: App Host options

[2] Bug fix: calibration new ecu cause crash

1.  2021-09-22

[1] New: API for ini files read and write

[2] Improved: var on written and on change distinguished in mini program

[3] Improved: Graphics and STIM now highlights deleted signals

[4] Bug fix: calibration CRC DWORD algorithm selected as ARC

[5] Bug fix: calibration hex export with address range \> 0xFFFF

1.  2021-09-16

[1] Improved: stop measurement in each MDI is invoked before app disconnect

[2] Improved: batch modification in graphics

[3] Improved: value table of system variable is now ordered

[4] Improved: Calibration measurement list highlights n.a. signals

[5] Improved: Calibration measurement list filter implemented

[6] Bug fix: set double signal in mini program

[7] Bug fix: keydown enter twice in graphics

[8] Bug fix: prevent graphics eat mouse click after right mouse button down

[9] Bug fix: Non-ISO cannot be selected in TS FD hardware config

[10] Bug fix: value table lost in copied message in CAN FD Transmit window

1.  2021-09-11

[1] Improved: Graphics now supports undo and redo

[2] Improved: Graphics grid color alpha set to 20%

[3] Improved: Graphics X axis font color same as X axis color

[4] Improved: Graphics Y axis increment max count can be set

[5] Improved: Numeric window now supports offline bus signal replay display

[6] Improved: Calibration error code message display added

[7] New: Prompt user input in MP API

[8] Bug fix: panel drag control over container causes hang

1.  2021-09-03

[1] Improved: Graphics supports signal color customization

[2] Improved: Graphics zoom feature

[3] Improved: Kill focus on panel input output box

[4] New: Calibration CRC algorithm: CRC_BYTE, CRC_DWORD, CRC_2_WORD

[5] Bug fix: Panel enable property

[6] Bug fix: blf write API without timestamp causes incorrect measurement start
time

[7] Bug fix: first sample point not displayed in graphics

1.  2021-08-31

[1] Bug fix: large raw signal modify in CAN FD transmit

[2] Improved: MDI form borders are easily to drag

[3] Improved: Graphics signal list width persistance

1.  2021-08-29

[1] New: Graphics goto specific time

[2] New: Sync scroll among all Graphics, based on their “Sync. Token” property

[3] New: fixed form mode (cannot resize and move)

[4] Bug fix: format display in calibration

1.  2021-08-26

[1] Bug fix: IEEE float 32 and 64 factor and offset not calculated

[2] New: Graphics signal can switch to vertical line junction style

[3] Updated: save measurement dialog add delete file option

1.  2021-08-25

[1] Bug fix: Panel pasted control drag causes shadow

1.  2021-08-24

[1] Bug fix: calibration stop uploading while connecting cause hang

[2] Bug fix: CCP byte order cannot be changed

[3] Bug fix: blf BL_OBJ_TYPE_CAN_FD_MESSAGE_64 parse

[4] Improved: up and down button affect all selected signals in STIM

[5] Improved: Graphics drag drop multiple signals supported

[6] Improved: Curve drag drop multiple signals supported

1.  2021-08-18

[1] New: Graphics line style and width options

[2] New: mat file read write api added

[3] Updated: Calibration Curve order list by dragging

[4] Bug fix: some panel configuration lost after one of multiple panels deleted

[5] Bug fix: Trace dislay LIN 3C 3D signal crash

1.  2021-08-12

[1] Bug fix: CAN FD transmit window, signal init value is always 0

1.  2021-08-10

[1] New: CAN Trace set reference under chronological mode

[2] New video: calibration automation

[3] Bug fix: Calibration cache enable option persistent

1.  2021-08-08

[1] New demo: Convert Blf to signal based CSV

[2] Updated: real-time comment is now shown in Graphics charting area

1.  2021-08-06

[1] Bug fix: calibration crash when stopping in polling mode

[2] Updated: C Code Editor var and timer highlighted, method popup supported

1.  2021-08-05

[1] New: udp APIs added in ioip

[2] Bug fix: Panel circular reference problem

[3] Bug fix: Align of child objects in panel is now persistent

[4] Bug fix: channel selection dialog select all and deselect all

1.  2021-08-04

[1] New: Auto Mapping Code generation for TSMaster SDK

1.  2021-08-03

[1] New: file and directory API added

[2] New: UDP broadcast API added

1.  2021-08-02

[1] New: Global rx filter added for all supported CAN interfaces

[2] New: Feature select with project templates

[3] New: video link added: Global Rx filter

[4] Bug fix: Panel start before mini program causes system var link incorrect

1.  2021-07-30

[1] New: video link added: Mini Program tutorial 2

[2] New: Feature select dialog

[3] New: text file APIs in mini program

1.  2021-07-29

[1] New: video links added in Calibration window, C Editor, System Var Mgmt,
Hardware

[2] New: AN0005 How to transmit LIN frames

[3] Bug fix: CAN trace display mode change causes frame lost

[4] Updated: Calibration A2L group with no parent will be shown in root

1.  2021-07-27

[1] New: calibration parameters can be inserted to hex

[2] New: TSDB added in out of process server

[3] New: system variables can be read or write by COM server

[4] New: video links added in C Code editor and CAN RBS windows

[5] Improved: TSMaster setup file may not be killed by some virus software

[6] Improved: TC1005 driver performance enhanced

[7] Updated: TSMaster Calibration document AN0001

1.  2021-07-23

[1] New: Measurement window: Numeric

[2] New: server response API functions added in ioip in mini program

[3] New: calibration parameters can be imported from hex

[4] New: buttons on quick customization bar on main ribbon

[5] Bug fix: panel input-output box initial value is always n.a.

[6] Bug fix: calibration map batch modification not work

1.  2021-07-15

[1] Mini program VC++ project can be generated directly in editor

[2] MDI now supports colorful window title color

1.  2021-07-14

[1] SYSTEM_CONSTANT related compu methods supported in calibration

[2] TSMaster plugin can also be implemented as mini program library

[3] Offline calibration mode supported in XCP

[4] Offline calibration mode supported in CCP

1.  2021-07-13

[1] realtime comments now supported in bus log

[2] APIs added for blf realtime comments

[3] APIs added for realtime comments in app environment

[4] Blf_Logging example updated for realtime comments

[5] Build checksum supported in XCP

[6] Build checksum supported in CCP

1.  2021-07-08

[1] Graphics all columns can now be sorted

[2] Trace fixed display logic re-written

1.  2021-07-07

[1] CAN Trace fixed mode stress test (100000 frames/sec per channel) passed

[2] Graphic signals support sorting by name

[3] Bug fix: Calibration large address cause crash (not tested)

[4] Bug fix: Test system report automation image template generation

[5] Added: post process script supported in Test system report automation

1.  2021-07-01

[1] CCP hex file can be exported after calibration

[2] Bug fix: bkgd color read crash in panel

[3] Bug fix: TS virtual channel mapping incorrect

[4] XCP hex file can be exported after calibration

[5] XCP hex file can be uploaded and downloaded

1.  2021-06-26

[1] Released: Mini Program SDK (<https://github.com/TOSUN-Shanghai>)

[2] CCP hex file can be uploaded and downloaded

1.  2021-06-20

[1] Panel controls now support value table from system variables

[2] Graphics refreshes during offline replay

[3] Bug fix: CAN RBS not run first time when a configuration is loaded

[4] TSMaster T7z file is now compatible with 7zip file format, replace files in
project configuration manually is allowed

1.  2021-06-17

[1] Panel input output box bkgd and border color, font can now be customized

[2] new API: app.get_tsmaster_version

[3] value table supported in STIM window

[4] A2L parser now supports "ECU" as module name

[5] Panel bug fix: copy paste controls cause some objects missing

[6] dialog added for unexpected start of CAN RBS engine in panel editor

1.  2021-06-14

[1] Test system example updated: insert screenshots into word report

[2] Test API added: retrieve_current_result_folder

[3] Test API added: write_result_image

[4] Test system new example: Excel test system report automation

1.  2021-06-12

[1] Excel test system report process script demo added

1.  2021-06-11

[1] Improved: A2L loading speed increased by 10x

[2] Bug fix: TC1011 baud rate UI not refreshed after CAN core switched

[3] Bug fix: custom signal channel read only in graphics

1.  2021-06-08

[1] New Feature: TCP Server, TCP Client, UDP Server and UDP Client are supported
in Mini program API

[2] Bug fix: First value display error in Calibration Curve under Motorola byte
order

[3] System variable now supports unit display, value table display, accuracy,
format to string, affects display of Calibration signals also

[4] New Ethernet demo added: Generic TCP UDP Communication

1.  2021-06-04

[1] Bug fix: CCP fixed CAN ID DAQ packet data corrupt

[2] Bug fix: Calibration save log dialog null value cause crash

[3] Signal comments in transmit window are now persistent

[4] Channel display added in database selector poped by C Editor

[5] online replay engine stop criteria changed to \> 1000 Tx errors

1.  2021-06-02

[1] CCP DAQ with fixed CAN identifier and event channel supported

[2] MP API header fixed: excel_get_cell_value

[3] MP API added: get_configuration_file_name

[4] MP API added: get_configuration_file_path

1.  2021-05-31

[1] New Feature: Window layout control

[2] Bug fix: dbc cycle parse

1.  2021-05-29

[1] Bug fix: CAN RBS load configuration not refresh UI

[2] Bug fix: display of AXIS_PTS in calibration database window

1.  2021-05-26

[1] Bug fix: crash on connection to some HW

1.  2021-05-25

[1] CAN transmit window signal step settings are now persistent

[2] mini program library dependency is now persistent

[3] CAN RBS node selection is now persistent

[4] CCP commands SET_S_STATUS and SELECT_CAL_PAGE supported

[5] dbc parse speed 100x faster

1.  2021-05-21

[1] Timer accuracy optimized

1.  2021-05-20

[1] CAN RBS topology chart added

1.  2021-05-14

[1] max LIN frames in schedule table set to 150

1.  2021-05-13

[1] Blf logging API demo configuration added

[2] Bug fix for extended frame id in asc conversion

1.  2021-05-10

[1] Each MDI window's z-order is now remembered

[2] Blf file API added

1.  2021-05-05

[1] mini program library dependencies configuration supported

1.  2021-05-02

[1] TSMaster plugin manager released

1.  2021-04-28

[1] minor bug fixes

1.  2021-04-23

[1] Signal relation graphics added in panel

1.  2021-04-22

[1] TSMaster software architecture completely redesigned

1.  2021-04-16

[1] minor bug fixes

1.  2021-04-13

[1] minor bug fixes

1.  2021-04-09

[1] carlibration par file import supported

[2] fifo module supported in COM API

[3] graphics cursor zoom feature supported (default right cursor)

[4] bug fix: bus logger generates additional frame

1.  2021-04-02

[1] improved support for arxml import

[2] multiple databases in arxml can be extracted

1.  2021-04-01

[1] editing of measurement data comment supported in graphics

1.  2021-03-31

[1] CCP feature release

[2] measurement cursor in graphics: left click to position, right click to
cancel position

1.  2021-03-26

[1] TSMaster and API overall performance improvement

[2] feature added: dbc, ldf, excel test case auto reload after edit

[3] default upload all calibration variables on connection

[4] calibration comments can be displayed when cursor hovers mat file

[5] par file export in calibration

[6] bug fix: chinese char in transmit and graphics window not display

1.  2021-03-22

[1] TSMaster file preview shell components supported

[2] shortcuts (F9, F10 and ESC) supported in graphics

[3] string type supported in Text, input-output box and selector in panel

[4] real-time comment supported during measurement (ALT + C)

[5] graphics integral time display supported and made default

[6] calibration database list display mode added

1.  2021-03-17

[1] bug fix: caption rename of curve form

[2] wildcard search supported in calibration, CAN DB, LIN DB, system variables
and symbol mapping

[3] comments dialog support for calibration measurement files

[4] parameter curve undo redo supported

[5] parameter curve copy paste supported

[6] STIM multiple change supported

[7] STIM undo redo supported

1.  2021-03-15

[1] all calibration scalar signals are now supported in panel

[2] curve and map data multi-select-modify supportd

[3] curve and map data interpolation supported

1.  2021-03-12

[1] Bug fix for Calibration data timestamp display

[2] Bug fix for Map COLUMN_DIR display

[3] Bug fix for graphics system variable display

1.  2021-03-10

[1] Calibration log can be exported to MATLAB replay model

[2] TSMaster LIN API updated

1.  2021-03-09

[1] Curves and Maps supported in calibration

[2] MF4, MDF and DAT log files import supported in Calibration (2.00, 2.10,
2.14, 3.00, 3.10, 3.20, 3.30, 4.00, 4.10, 4.11, 4.20) from CANape and INCA

1.  2021-03-02

[1] MDF log files export supported in Calibration (2.00, 2.10, 2.14, 3.00, 3.10,
3.20, 3.30, 4.00, 4.10, 4.11, 4.20) for CANape and INCA

[2] A2L parser crash problem fixed

1.  2021-02-25

[1] API for UI automation added

1.  2021-02-24

[1] COM_AXIS supported in XCP Curve

[2] COMPU_VTAB, COMPU_TAB, FFORMULA supported in XCP

[3] Graphics will show never-appear signals as n.a.

[4] fixed: empty blf file replay cause TSMaster never connect

[5] time axis also shows realtime value in Graphics

1.  2021-02-22

[1] STIM custom signal file import and export supported

[2] Excel Test module released

1.  2021-02-20

[1] PEAK CAN FD device supported

[2] Bug fix: FCOEFFS_LINEAR parse in XCP

1.  2021-02-10

[1] Video step method in AN0004 document updated

[2] shortcuts supported in video replay

[3] TSMaster features document updated

[4] LIN diagnostics API Demos added

[5] github link added: https://github.com/TOSUN-Shanghai/TSMaster

1.  2021-02-06

[1] video step supported in video replay

[2] C\# API updated

1.  2021-02-05

[1] writeable measurement signal supported in XCP

[2] array parameter supported in XCP

[3] Axis parameter supported in XCP

[4] mini program library API exported

[5] LIN diagnostics API exported

[6] curve with fixed axis supported in XCP

[7] video replay with blf feature supported

[8] application note AN0004 added: video replay

1.  2021-01-25

[1] motorola supported in XCP module

[2] bug fix for TC10xx USB transfer protocol

[3] CAN multiplexor signal and multiplexed signal supported in Graphics

1.  2021-01-24

[1] CAN multiplexor signal and multiplexed signal supported in trace window

[2] CAN multiplexor signal and multiplexed signal supported in transmit window

[3] CAN signal sorted by position in trace window

[4] CAN multiplexor signal and multiplexed signal supported in CAN RBS

[5] CAN multiplexor signal and multiplexed signal supported in APIs

1.  2021-01-21

[1] Solved: panel align persistency

[2] panel objects hierarchy is now displayed in tree

[3] variables and timers documents now available in c editor

[4] comments translated in c editor

[5] group name of radio button persistency added in panel

[6] alignment of signal text in CAN trace

[7] xcp manual configuration without a2l supported

[8] selector in panel will not display "=" in the future

[9] special thanks list updated

[10] C Mini program now supports C++ 11 standard

1.  2021-01-18

[1] system variable logging in calibration done

[2] system variable replay in calibration done

[3] symbol mapping from CAN signal to system variable done

[4] legacy TC1005 firmware supported

[5] Calibration module translated

[6] application note feature added, which can be found on top-right area of
TSMaster standard form, for example, Calibration form

[7] application note for Calibration added: AN0001: How to use TOSUN Calibration
XCP controller

[8] application note for Calibration added: AN0002: Seed and Key algorithm
implementation in XCP controller

[9] application note for Calibration added: AN0003: TOSUN XCP controller mat log
file format

1.  2021-01-09

[1] Scalar signals in XCP module now available

1.  2021-01-04

[1] TSMaster Pre-Tx API added in C version

1.  2020-12-30

[1] TSMaster C API released, which can be found in
“bin\\Data\\SDK\\examples\\C\\”

1.  2020-12-24

[1] Mini program library demo project added: Simple Gateway Implementation

[2] The running state of Mini program library can be triggered by system
variable

[3] The running state of calibration can be triggered by system variable

[4] The value of Internal System variable can be modified directly in "System
Variable Manager"

[5] Add dialog support for blf logging file save operation

[6] Default point count of Graphics set to 100000, can be adjusted

[7] Stimulation feature added

1.  2020-11-28

[1] Panel LED now has Threshold property, under threshold mode, threshold high
and low properties are active, otherwise, single ONValue is active

[2] F5 and F6 shortcuts are added for starting and stopping application

1.  2020-11-27

[1] TS virtual channel com server removed

[2] asc file time supported

1.  2020-11-19

[1] bug fix: can error frame read in blf

[2] c code can be generated from tx and trace window

1.  2020-11-18

[1] Bug fix: CAN trace add filter

[2] Bug fix: panel graphics and pie edit signal index out of bounds

[3] Panel enable property added

[4] C\# SDK updated

[5] LabVIEW SDK added

[6] C\# docs updated

[7] Bug fix: graphics signal selection display in y axis

1.  2020-11-16

[1] panel select enhanced: normal select and invert select

[2] precision property supported in panel text

[3] classification of auto start modules

1.  2020-11-15

[1] translated: all dynamic languages

[2] bug fix: j1939 dbc cause can rbs crash

[3] panel ui refresh rate can be set

[4] input output box in panel has label width property

[5] switch in panel has label property

[6] path button in panel has label property

[7] system lang auto detect supported

1.  2020-11-14

[1] translated: all dynamic languages

[2] bug fix: j1939 dbc cause can rbs crash

[3] panel ui refresh rate can be set

[4] input output box in panel has label width property

[5] switch in panel has label property

[6] path button in panel has label property

1.  2020-11-13

[1] printf supported in mini program

[2] translated: channel selection

[3] translated: check update

[4] translated: documents

[5] translated: graphics

[6] translated: LIN database

[7] translated: LIN RBS

[8] translated: LIN trace

[9] translated: LIN transmit

[10] bug fix: panel display with more than 2

[11] translated: logging

[12] translated: matlab controller

[13] translated: measurement data filter

[14] translated: measurement setup

[15] translated: meter

[16] translated: mini program library

[17] translated: panel

[18] translated: playback

[19] translated: settings

[20] translated: symbol mapping

[21] translated: system variable mgmt

[22] translated: system messages

[23] panel width and height properties now supported

1.  2020-11-10

[1] ICS VCAN3 channel 2 MSCAN supported

[2] translated: form manager

[3] translated: test system

[4] translated: hardware configuration

[5] translated: ribbon

[6] translated: automotive converter

[7] translated: C2Stateflow

[8] translated: CAN / CAN FD Trace

[9] translated: CAN RBS

[10] translated: bus statistics

[11] translated: C Code editor

[12] translated: channel mapping

[13] translated: vendor selection

[14] panel: press esc to select parent control

[15] splash screen not top most

[16] panel: control name can be hidden by option

1.  2020-10-31

[1] translated: form manager

[2] bug fix: PEAK receive interface

1.  2020-10-30

[1] Object list added in Panel

[2] Arbitrary python scripts can be executed sync or async in mini program and
TSMaster APIs

[3] max single log file size can be controlled in logging window

[4] multi-language translated: CAN Database

1.  2020-10-26

[1] Panel label display format supported

[2] Panel Graphics bkgd color and transparent properties added

[3] Panel Units can be displayed in graphics

[4] Panel input output box initial value corresponds to RBS value

1.  2020-10-22

[1] Single J1939 message can be transmit in CAN Transmit window

[2] Bug fix: Trace not refreshed after J1939 dbc channel switch

1.  2020-10-20

[1] dbc to c source default output non-floating points

[2] output encoding in automotive file converter can be switched between ANSI
and utf-8

[3] API bug fix: show single form by API should hide splash

[4] API bug fix: load TSMaster.dll should not change current dir

[5] J1939 single frame can now be displayed in trace with signals expanded

1.  2020-10-19

[1] Enumerate Hardware API added

1.  2020-10-16

[1] ARXML AutoSAR format supported

[2] Automotive file converter added in Tools page, supported 10 format:

-   dbc

-   arxml

-   xlsx

-   xls

-   dbf

-   yaml

-   sym

-   csv

-   json

-   fibex

[3] dbc to C source code feature added in Automotive file converter

1.  2020-10-13

[1] minor bug fixes in TSMaster API

1.  2020-10-12

[1] Application Shortcuts supported: ctrl+O, ctrl+N, ctrl+S, ctrl+TAB,
ctrl+shift+TAB

[2] hex display on/off will immediately trigger UI refresh

[3] Trace expanded nodes will be remembered

[4] Shortcuts list collected in project overview

[5] life time free components listed in About window

1.  2020-10-10

[1] Panel section completed in help manual

[2] Project details page in backstage added

1.  2020-10-09

[1] TC1005 and IntrepicCS now support CAN Transmit API Sync. operation

[2] Help Manual updated, RBS and C Code Editor chapters completed

1.  2020-10-08

[1] CAN RBS (Remaining Bus Simulation) API added in automation

[2] example added: RBSInExe.py, control RBS in python

[3] example added: CAN Remaining Bus Simulation Scripting.T7z

1.  2020-10-07

[1] CAN RBS API added in mini program, TSMaster.dll

[2] CAN online replay API added in mini program

1.  2020-10-06

[1] Test system demo added

1.  2020-10-05

[1] CAN database message layout chart added

[2] Demo added: “how to use preTx event to implement checksum and rolling
counter gracefully”

[3] Measurement window “auto start” feature can now be quickly checked on
right-top of window area

[4] Panel controls can now be copied, pasted, moved, aligned, arranged by
multiple selection

[5] Title text added in LED control in panel

1.  2020-10-01

[1] UI: Application button added

[2] Credits added

1.  2020-09-29

[1] C Sharp SDK samples added

1.  2020-09-28

[1] Panel UI completed, user can associate signals and monitor, manipulate
signals

1.  2020-09-23

[1] Graphics now supports y axis auto scaling

[2] PEAK auto reset on bus off feature added

[3] Graphics now supports y axis mouse wheel zooming

1.  2020-09-18

Example projects added, which can be found in “bin\\Data\\Demo\\Projects”

1.  2020-09-14

TSMaster beta version update supported

TSMaster can be installed in user mode

1.  2020-09-03

Documents added.

1.  2020-08-31

System variable feature supported. System variables can be accessed in mini
program, graphics and variable management window.

1.  2020-08-15

[1] Measurement Setup window implemented.

[2] Measurement filter window implemented.

1.  2020-08-03

[1] new project configuration now supports template

[2] Graphics now supports split view and value table in Y axis

[3] IntrepidCS HSCAN devices supported:

-   NEODEVICE_BLUE

-   NEODEVICE_ECU_AVB

-   NEODEVICE_DW_VCAN

-   NEODEVICE_RADGIGALOG

-   NEODEVICE_FIRE

-   NEODEVICE_VCAN3

-   NEODEVICE_RED

-   NEODEVICE_ECU

-   NEODEVICE_OBD2_PRO

-   NEODEVICE_PLASMA

-   NEODEVICE_ION

-   NEODEVICE_VCAN44

-   NEODEVICE_VCAN42

-   NEODEVICE_FIRE2

-   NEODEVICE_RADGALAXY

-   NEODEVICE_RADSTAR2

-   NEODEVICE_VIVIDCAN

-   NEODEVICE_OBD2_SIM

    1.  2020-07-27

ZLG CAN devices supported:

-   USBCAN-8E-U

-   USBCAN-4E-U

-   USBCAN-2E-U

-   USBCAN-E-U

-   USBCAN-I

-   USBCAN-II

-   USBCAN2A

-   USBCAN-E-mini

    1.  2020-07-21

Kvaser CAN devices supported.

1.  2020-07-18

PEAK USB CAN devices supported.

1.  2020-07-13

Automation API for online replay implemented.

1.  2020-07-08

Online replay feature added, which is capable of replaying multiple log files
according to their own replay settings.

1.  2020-06-23

TSMaster in-process server “comTSMaster.dll” is functional. Please check the
demo “TestCOMTSMaster.py” under “bin\\Data\\Demo\\Automation\\InProcess\\”.

TSMaster out-of-process server “TSMaster.exe” is functional. Please check the
demo “TestTSMaster.py” under “bin\\Data\\Demo\\Automation\\OutOfProcess\\”.

1.  2020-06-10

[1] Test system feature added, which enables the user to create own test system
to perform test cases automatically and creating test reports freely.

[2] Mini program library feature added, mini program can now be used as a
library by other mini programs. This is useful for test cases and automation
scripts design with test plugin support.

1.  2020-05-23

CAN and LIN signals can be added to Graphics and Meter windows from CAN or LIN
Trace windows by popup menu.

1.  2020-05-20

Matlab automation window added, which enables the user:

[1] quick find variables in base workspace, plot variables

[2] convert existing C code to pure stateflow, to meet the requirements of
stateflow programming guide, the C code should be implemented only using “if”
and “else”, other grammars of C code are not supported.

[3] quick add subsystems and charts using known inputs and outputs

1.  2020-05-18

Magnetic form feature added.

1.  2020-05-15

“CAN Transmit Window” and “CAN Trace Window” are deleted permenantly in future
release, use “CAN / CAN FD Transmit Window” and “CAN / CAN FD Trace Window”
instead.

1.  2020-05-12

Firmware version and date of TS USB device are now displayed in TS Channel
Mapping window.

1.  2020-05-11

CAN FD error frame info display of XL devices.

Comment display added under each meter object.

1.  2020-05-08

CAN databases supported in TS Mini Program.

1.  2020-05-03

TS Mini Program with C code support released, which can be found in “Simulation”
ribbon tab.

1.  2020-04-04

Turbo mode is added into hardware settings tab. Checking this option will
minimize all hardware channel latencies at the expense of consuming more CPU
usage. Users who concern very much for hardware performance are recommended to
check this option.

1.  2020-03-26

CAN RBS feature added

1.  2020-03-24

Max CAN, LIN channel count set to 32

>   Bug Fixes

1.  2021-01-15

[1] Bug fix: libTSH transmit frames lost issue

1.  2020-12-03

[1] Bug fix: trace filter for J1939 id

[2] Bug fix: panel selector crash after signal selected

1.  2020-11-21

[1] bug fix: RBS UI refresh

[2] bug fix: Graphics signal value table display

1.  2020-11-17

[1] Bug fix: J1939 PGN display in Trace

[2] Bug fix: read fd error frame in blf

[3] Bug fix: write log file with TC1005

[4] Bug fix: CAN database filter with msg identifier

[5] Bug fix: liblog.dll not found, please use latest TSMaster.dll in API

1.  2020-10-07

[1] offline replay range playback incorrect behavior

[2] graphics y axis scaling incorrect behavior

1.  2020-10-06

[1] extended frame conversion from asc to blf

1.  2020-09-24

[1] Panel crash on startup fixed

[2] Replay hang when frame count \> 100000

[3] bug fix for dbc signal calculation with factor \< 0

1.  2020-09-16

Transmit and display problems of signals with mixed value table and factor and
offset values.

1.  2020-09-01

ZLG baudrate config now supports devices except “E” series.

1.  2020-05-15

Key trigger of CAN message transmission is not functional.

Ordering of CAN message transmission column is now persistent.

Visibility of CAN message transmission column is now persistent.

1.  2020-05-12

Classical CAN transmission in XL may cause crash.

CAN and LIN databases channel selection treeview display additional “+” button
when all child nodes are removed.

Physical step CAN transmit cannot be modified.

1.  2020-05-11

Display error of TOSUN icon in 150% text size mode in win10.

1.  2020-03-24

LIN message “Active” property cannot be modified after deploy.
