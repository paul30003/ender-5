***WARNING***

These configuration files are for reference only.  If you choose to use these to compile a binary for your printer, then you do so at your own risk.
I shall not be held responsible for any loss, fire or damages whatsoever.

*****************************************************************************************************************************************************

# ender-5 Marlin 2.0.6.1 config files.
Creality Ender 5 configuration on BTT SKR v1.4 turbo.

Hardware Setup:

Creality Ender 5 Pro.
Stock stepper motors, hotend & extruder.
Bigtreetech SKR v1.4 turbo with BTT TMC2209 stepper drivers
External mosfets on bed and hot end.
BLTouch probe connected to probe socket (Pin 0.10)

Running Marlin 2.0.6.1

Basic configured options.

Microstepping 1/64
Sensorless homing.


TMC2209 dump.

Recv: 		X	Y	Z	E
Recv: Address		0	0	0	0
Recv: Enabled		true	true	true	true
Recv: Set current	700	700	700	800
Recv: RMS current	673	673	673	795
Recv: MAX current	949	949	949	1121
Recv: Run current	21/31	21/31	21/31	25/31
Recv: Hold current	10/31	10/31	10/31	12/31
Recv: CS actual	21/31	21/31	21/31	25/31
Recv: PWM scale
Recv: vsense		1=.18	1=.18	1=.18	1=.18
Recv: stealthChop	true	true	true	true
Recv: msteps		64	64	64	64
Recv: tstep		1123	818	max	112119
Recv: PWM thresh.
Recv: [mm/s]
Recv: OT prewarn	false	false	false	false
Recv: triggered
Recv:  OTP		false	false	false	false
Recv: pwm scale sum	58	31	56	88
Recv: pwm scale auto	0	0	0	-4
Recv: pwm offset auto	83	47	80	58
Recv: pwm grad auto	28	23	29	28
Recv: off time	4	4	4	4
Recv: blank time	24	24	24	24
Recv: hysteresis
Recv:  -end		2	2	2	2
Recv:  -start		1	1	1	1
Recv: Stallguard thrs	71	80	0	0
Recv: uStep count	984	59	965	374
Recv: DRVSTATUS	X	Y	Z	E
Recv: sg_result	114	68	0	142
Recv: stst		*	*
Recv: olb
Recv: ola
Recv: s2gb
Recv: s2ga
Recv: otpw
Recv: ot
Recv: 157C
Recv: 150C
Recv: 143C
Recv: 120C
Recv: s2vsa
Recv: s2vsb
Recv: Driver registers:
Recv: 		X	0xC0:15:00:00
Recv: 		Y	0xC0:15:00:00
Recv: 		Z	0xC0:15:00:00
Recv: 		E	0xC0:19:00:00
Recv: 
Recv: 
Recv: Testing X connection... OK
Recv: Testing Y connection... OK
Recv: Testing Z connection... OK
Recv: Testing E connection... OK
Recv: ok





