# Lootear BOX FULL
[MACRO] Lootear BOX FULL

SCRIPT:
#IfWinActive, Tibia
#NoEnv
#Warn
#SingleInstance Force
#MaxHotkeysPerInterval 99000000
#HotkeyInterval 99000000
#KeyHistory 0
CoordMode, Pixel, Screen
CoordMode, Mouse, Screen
ListLines Off
SendMode Input
SetBatchLines, -1
SetKeyDelay, -1, -1
SetMouseDelay, -1
SetDefaultMouseSpeed, 0
SetWinDelay, -1
SetControlDelay, -1

RandSleep(x,y) {
Random, rand, %x%, %y%
Sleep %rand%
}



'::
    Send, {Shift down}
	RandSleep(150,200)
    Click, Right, 740, 290
	RandSleep(150,200)
    Click, Right,  740, 350
	RandSleep(150,200)
    Click, Right,  740, 410
	RandSleep(150,200)
    Click, Right,  800, 410
	RandSleep(150,200)
    Click, Right,  860, 410
	RandSleep(150,200)
    Click, Right,  860, 350
	RandSleep(150,200)
    Click, Right,  860, 290
	RandSleep(150,200)
    Click, Right,  800, 290
	RandSleep(150,200)
    Click, Right,  800, 350
	RandSleep(150,200)
    Send, {Shift up}
return
