```bash
Tue May 22 11:46:33 2018 : network read
Tue May 22 11:46:33 2018 : proto_radius_udp - Received Accounting-Request ID 72 length 262 proto udp server * port 1813
Tue May 22 11:46:33 2018 : Network received packet size 262
Tue May 22 11:46:33 2018 : 	checking timeouts
Tue May 22 11:46:33 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:33 2018 : Ready to process requests
Tue May 22 11:46:33 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:33 2018 : 	requests 10, decoded 10, replied 10 active 0
Tue May 22 11:46:33 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:33 2018 : 	--> data
Tue May 22 11:46:33 2018 : 	received request 11
Tue May 22 11:46:33 2018 : 	checking timeouts
Tue May 22 11:46:33 2018 : Worker 0 found request to decode
Tue May 22 11:46:33 2018 : (10)  proto_radius decode packet
  Code:		Accounting-Request
  Id:		72
  Length:	262
  Vector:	65fbd9ac7fce701b6762b2b3e06b5cad
		28  06  00 00 00 02 
		2d  06  00 00 00 01 
		01  09  73 79 73 74 65 6d 6e 
		1e  1b  31 38 2d 41 36 2d 46 37 2d 37 37 2d 33 34 2d 32 
			30 3a 55 5f 6e 65 65 64 3f 
		3d  06  00 00 00 13 
		06  06  00 00 00 02 
		05  06  00 00 00 02 
		1f  13  33 38 2d 32 44 2d 44 31 2d 33 32 2d 36 31 2d 31 
			45 
		4d  18  43 4f 4e 4e 45 43 54 20 35 34 4d 62 70 73 20 38 
			30 32 2e 31 31 67 
		2c  12  36 37 34 45 46 44 37 41 37 36 31 32 37 38 46 44 
		ba  06  00 0f ac 04 
		bb  06  00 0f ac 04 
		bc  06  00 0f ac 01 
		19  25  61 69 3a 62 62 35 37 37 31 31 62 30 39 61 66 33 
			34 33 38 61 30 64 36 31 35 35 34 66 38 33 33 37 
			63 33 34 
		37  06  5b 03 d7 f0 
		29  06  00 00 00 00 
		2e  06  00 00 00 10 
		2f  06  00 00 00 a3 
		30  06  00 00 00 41 
		2a  06  00 00 35 d3 
		34  06  00 00 00 00 
		2b  06  00 00 32 bf 
		35  06  00 00 00 00 
		31  06  00 00 00 01 
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Status-Type
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 02 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Status-Type len 4 ... 240
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Authentic
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 01 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Authentic len 4 ... 234
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> User-Name
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 73 79 73 74 65 6d 6e 
msg: src/protocols/radius/decode.c:1043: Parent User-Name len 7 ... 228
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Called-Station-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 31 38 2d 41 36 2d 46 37 2d 37 37 2d 33 34 2d 32 
hex: src/protocols/radius/decode.c:1041: 0010: 30 3a 55 5f 6e 65 65 64 3f 
msg: src/protocols/radius/decode.c:1043: Parent Called-Station-Id len 25 ... 219
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> NAS-Port-Type
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 13 
msg: src/protocols/radius/decode.c:1043: Parent NAS-Port-Type len 4 ... 192
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Service-Type
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 02 
msg: src/protocols/radius/decode.c:1043: Parent Service-Type len 4 ... 186
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> NAS-Port
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 02 
msg: src/protocols/radius/decode.c:1043: Parent NAS-Port len 4 ... 180
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Calling-Station-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 33 38 2d 32 44 2d 44 31 2d 33 32 2d 36 31 2d 31 
hex: src/protocols/radius/decode.c:1041: 0010: 45 
msg: src/protocols/radius/decode.c:1043: Parent Calling-Station-Id len 17 ... 174
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Connect-Info
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 43 4f 4e 4e 45 43 54 20 35 34 4d 62 70 73 20 38 
hex: src/protocols/radius/decode.c:1041: 0010: 30 32 2e 31 31 67 
msg: src/protocols/radius/decode.c:1043: Parent Connect-Info len 22 ... 155
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Session-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 36 37 34 45 46 44 37 41 37 36 31 32 37 38 46 44 

msg: src/protocols/radius/decode.c:1043: Parent Acct-Session-Id len 16 ... 131
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-Pairwise-Cipher
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 04 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-Pairwise-Cipher len 4 ... 113
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-Group-Cipher
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 04 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-Group-Cipher len 4 ... 107
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-AKM-Suite
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 01 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-AKM-Suite len 4 ... 101
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Class
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 61 69 3a 62 62 35 37 37 31 31 62 30 39 61 66 33 
hex: src/protocols/radius/decode.c:1041: 0010: 34 33 38 61 30 64 36 31 35 35 34 66 38 33 33 37 
hex: src/protocols/radius/decode.c:1041: 0020: 63 33 34 
msg: src/protocols/radius/decode.c:1043: Parent Class len 35 ... 95
msg: src/protocols/radius/decode.c:1169: Type "octets" (2)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Event-Timestamp
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 5b 03 d7 f0 
msg: src/protocols/radius/decode.c:1043: Parent Event-Timestamp len 4 ... 58
msg: src/protocols/radius/decode.c:1169: Type "date" (22)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Delay-Time
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 00 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Delay-Time len 4 ... 52
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Session-Time
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 10 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Session-Time len 4 ... 46
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Input-Packets
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 a3 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Input-Packets len 4 ... 40
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Output-Packets
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 41 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Output-Packets len 4 ... 34
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Input-Octets
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 35 d3 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Input-Octets len 4 ... 28
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Input-Gigawords
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 00 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Input-Gigawords len 4 ... 22
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Output-Octets
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 32 bf 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Output-Octets len 4 ... 16
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Output-Gigawords
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 00 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Output-Gigawords len 4 ... 10
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Terminate-Cause
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 01 
msg: src/protocols/radius/decode.c:1043: Parent Acct-Terminate-Cause len 4 ... 4
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
Tue May 22 11:46:33 2018 : Resetting worker 30 cleanup timer to +0s
Tue May 22 11:46:33 2018 : (10)  running request
Tue May 22 11:46:33 2018 : (10)  Received Accounting-Request ID 72
Tue May 22 11:46:33 2018 : (10)    Acct-Status-Type = Stop
Tue May 22 11:46:33 2018 : (10)    Acct-Authentic = RADIUS
Tue May 22 11:46:33 2018 : (10)    User-Name = "systemn"
Tue May 22 11:46:33 2018 : (10)    Called-Station-Id = "18-A6-F7-77-34-20:U_need?"
Tue May 22 11:46:33 2018 : (10)    NAS-Port-Type = Wireless-802.11
Tue May 22 11:46:33 2018 : (10)    Service-Type = Framed-User
Tue May 22 11:46:33 2018 : (10)    NAS-Port = 2
Tue May 22 11:46:33 2018 : (10)    Calling-Station-Id = "38-2D-D1-32-61-1E"
Tue May 22 11:46:33 2018 : (10)    Connect-Info = "CONNECT 54Mbps 802.11g"
Tue May 22 11:46:33 2018 : (10)    Acct-Session-Id = "674EFD7A761278FD"
Tue May 22 11:46:33 2018 : (10)    WLAN-Pairwise-Cipher = 1027076
Tue May 22 11:46:33 2018 : (10)    WLAN-Group-Cipher = 1027076
Tue May 22 11:46:33 2018 : (10)    WLAN-AKM-Suite = 1027073
Tue May 22 11:46:33 2018 : (10)    Class = 0x61693a6262353737313162303961663334333861306436313535346638333337633334
Tue May 22 11:46:33 2018 : (10)    Event-Timestamp = May 22 2018 11:42:24 MSK
Tue May 22 11:46:33 2018 : (10)    Acct-Delay-Time = 0
Tue May 22 11:46:33 2018 : (10)    Acct-Session-Time = 16
Tue May 22 11:46:33 2018 : (10)    Acct-Input-Packets = 163
Tue May 22 11:46:33 2018 : (10)    Acct-Output-Packets = 65
Tue May 22 11:46:33 2018 : (10)    Acct-Input-Octets = 13779
Tue May 22 11:46:33 2018 : (10)    Acct-Input-Gigawords = 0
Tue May 22 11:46:33 2018 : (10)    Acct-Output-Octets = 12991
Tue May 22 11:46:33 2018 : (10)    Acct-Output-Gigawords = 0
Tue May 22 11:46:33 2018 : (10)    Acct-Terminate-Cause = User-Request
Tue May 22 11:46:33 2018 : (10)  Running 'recv Accounting-Request' from file /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default
Tue May 22 11:46:33 2018 : unlang_push called with instruction <none> - args UNLANG_NEXT_STOP UNLANG_TOP_FRAME
Tue May 22 11:46:33 2018 : unlang_push called with instruction recv Accounting-Request - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_push_section - substack begins
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           recv
Tue May 22 11:46:33 2018 : (10)    debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : ###### unlang_run is starting
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           recv
Tue May 22 11:46:33 2018 : (10)    debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_run - interpreter entered
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           recv
Tue May 22 11:46:33 2018 : (10)    debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  recv Accounting-Request {
Tue May 22 11:46:33 2018 : (10)    ** [2] unlang_frame_eval >> group
Tue May 22 11:46:33 2018 : unlang_push called with instruction acct_unique - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           acct_unique
Tue May 22 11:46:33 2018 : (10)      debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)      next           files
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           recv
Tue May 22 11:46:33 2018 : (10)      debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    acct_unique {
Tue May 22 11:46:33 2018 : (10)      ** [3] unlang_frame_eval >> group
Tue May 22 11:46:33 2018 : unlang_push called with instruction if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i) - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)      ** [4] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)      ----- Begin stack debug [depth 4] -----
Tue May 22 11:46:33 2018 : (10)      [4] Frame contents
Tue May 22 11:46:33 2018 : (10)        type           if
Tue May 22 11:46:33 2018 : (10)        name           if
Tue May 22 11:46:33 2018 : (10)        debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)        next           else
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         ...
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [3] Frame contents
Tue May 22 11:46:33 2018 : (10)        type           group
Tue May 22 11:46:33 2018 : (10)        name           acct_unique
Tue May 22 11:46:33 2018 : (10)        debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)        next           files
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         ...
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [2] Frame contents
Tue May 22 11:46:33 2018 : (10)        type           group
Tue May 22 11:46:33 2018 : (10)        name           recv
Tue May 22 11:46:33 2018 : (10)        debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         ...
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [1] Frame contents
Tue May 22 11:46:33 2018 : (10)        instruction = NULL
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      yes
Tue May 22 11:46:33 2018 : (10)        result         noop
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [0] Frame contents
Tue May 22 11:46:33 2018 : (10)        instruction = NULL
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         reject
Tue May 22 11:46:33 2018 : (10)        priority       0
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      ----- End stack debug [depth 4] -------
Tue May 22 11:46:33 2018 : (10)      if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i) {
Tue May 22 11:46:33 2018 : (10)        ** [4] unlang_frame_eval >> if
Tue May 22 11:46:33 2018 : (10)        EXPAND TMPL XLAT STRUCT
Tue May 22 11:46:33 2018 : (10)        EXPAND %{string:Class}
Tue May 22 11:46:33 2018 : (10)           --> ai:bb57711b09af3438a0d61554f8337c34
Tue May 22 11:46:33 2018 : (10)        Copying 8 bytes to (nil) from offset 0
Tue May 22 11:46:33 2018 : No matches
Tue May 22 11:46:33 2018 : Adding 2 matches
Tue May 22 11:46:33 2018 : (10)        Added request data 0x2b6d3c0 at 0x2be8c00:-1379995904
Tue May 22 11:46:33 2018 : unlang_push called with instruction update request - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)        ** [5] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:33 2018 : (10)        [5] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           update
Tue May 22 11:46:33 2018 : (10)          name           request
Tue May 22 11:46:33 2018 : (10)          debug_name     update request
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [4] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           if
Tue May 22 11:46:33 2018 : (10)          name           if
Tue May 22 11:46:33 2018 : (10)          debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [3] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           group
Tue May 22 11:46:33 2018 : (10)          name           acct_unique
Tue May 22 11:46:33 2018 : (10)          debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)          next           files
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [2] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           group
Tue May 22 11:46:33 2018 : (10)          name           recv
Tue May 22 11:46:33 2018 : (10)          debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [1] Frame contents
Tue May 22 11:46:33 2018 : (10)          instruction = NULL
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      yes
Tue May 22 11:46:33 2018 : (10)          result         noop
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [0] Frame contents
Tue May 22 11:46:33 2018 : (10)          instruction = NULL
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         reject
Tue May 22 11:46:33 2018 : (10)          priority       0
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:33 2018 : (10)        update request {
Tue May 22 11:46:33 2018 : (10)          ** [5] unlang_frame_eval >> update
Tue May 22 11:46:33 2018 : unlang_push called with instruction xlat - args UNLANG_NEXT_STOP UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 6] -----
Tue May 22 11:46:33 2018 : (10)          [6] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           xlat_eval
Tue May 22 11:46:33 2018 : (10)            name           xlat
Tue May 22 11:46:33 2018 : (10)            debug_name     xlat
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 6] -------
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_frame_eval >> xlat_eval
Tue May 22 11:46:33 2018 : unlang_push called with instruction xlat - args UNLANG_NEXT_STOP UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)          ** [7] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 7] -----
Tue May 22 11:46:33 2018 : (10)          [7] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           xlat_eval
Tue May 22 11:46:33 2018 : (10)            name           xlat
Tue May 22 11:46:33 2018 : (10)            debug_name     xlat
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [6] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           xlat_eval
Tue May 22 11:46:33 2018 : (10)            name           xlat
Tue May 22 11:46:33 2018 : (10)            debug_name     xlat
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 7] -------
Tue May 22 11:46:33 2018 : (10)          ** [7] unlang_frame_eval >> xlat_eval
Tue May 22 11:46:33 2018 : (10)          1/2 Found: bb57711b09af3438a0d61554f8337c34 (32)
Tue May 22 11:46:33 2018 : (10)          EXPAND %{Acct-Session-ID}
Tue May 22 11:46:33 2018 : (10)            --> 674EFD7A761278FD
Tue May 22 11:46:33 2018 : (10)          ** [7] unlang_frame_eval << calculate-result (-1)
Tue May 22 11:46:33 2018 : (10)          ** [7] unlang_calculate_result - have (... -1) module returned (... -1)
Tue May 22 11:46:33 2018 : (10)          ** [7] unlang_frame_eval - done current subsection with (... -1)
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 6] -----
Tue May 22 11:46:33 2018 : (10)          [6] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           xlat_eval
Tue May 22 11:46:33 2018 : (10)            name           xlat
Tue May 22 11:46:33 2018 : (10)            debug_name     xlat
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 6] -------
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 6] -----
Tue May 22 11:46:33 2018 : (10)          [6] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           xlat_eval
Tue May 22 11:46:33 2018 : (10)            name           xlat
Tue May 22 11:46:33 2018 : (10)            debug_name     xlat
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 6] -------
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_frame_eval >> xlat_eval
Tue May 22 11:46:33 2018 : (10)          EXPAND %{md5:,%{Acct-Session-ID}}
Tue May 22 11:46:33 2018 : (10)                (%{md5:bb57711b09af3438a0d61554f8337c34,674EFD7A761278FD})
Tue May 22 11:46:33 2018 : (10)            --> 84cdbd94df9226be575e9a4879323e1f
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_frame_eval << calculate-result (-1)
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_calculate_result - have (... -1) module returned (... -1)
Tue May 22 11:46:33 2018 : (10)          ** [6] unlang_frame_eval - done current subsection with (... -1)
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 5] -------
Tue May 22 11:46:33 2018 : (10)          ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:33 2018 : (10)          [5] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           update
Tue May 22 11:46:33 2018 : (10)            name           request
Tue May 22 11:46:33 2018 : (10)            debug_name     update request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         yes
Tue May 22 11:46:33 2018 : (10)          [4] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           if
Tue May 22 11:46:33 2018 : (10)            name           if
Tue May 22 11:46:33 2018 : (10)            debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [3] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           acct_unique
Tue May 22 11:46:33 2018 : (10)            debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)            next           files
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [2] Frame contents
Tue May 22 11:46:33 2018 : (10)            type           group
Tue May 22 11:46:33 2018 : (10)            name           recv
Tue May 22 11:46:33 2018 : (10)            debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         ...
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [1] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      yes
Tue May 22 11:46:33 2018 : (10)            result         noop
Tue May 22 11:46:33 2018 : (10)            priority       -1
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          [0] Frame contents
Tue May 22 11:46:33 2018 : (10)            instruction = NULL
Tue May 22 11:46:33 2018 : (10)            next           <none>
Tue May 22 11:46:33 2018 : (10)            top_frame      no
Tue May 22 11:46:33 2018 : (10)            result         reject
Tue May 22 11:46:33 2018 : (10)            priority       0
Tue May 22 11:46:33 2018 : (10)            unwind         0
Tue May 22 11:46:33 2018 : (10)            repeat         no
Tue May 22 11:46:33 2018 : (10)          ----- End stack debug [depth 5] -------
Tue May 22 11:46:33 2018 : (10)          ** [5] unlang_frame_eval >> update
Tue May 22 11:46:33 2018 : (10)          &Acct-Unique-Session-Id := "84cdbd94df9226be575e9a4879323e1f"
Tue May 22 11:46:33 2018 : (10)          ** [5] unlang_frame_eval << calculate-result (1)
Tue May 22 11:46:33 2018 : (10)        } # update request (noop)
Tue May 22 11:46:33 2018 : (10)        ** [5] unlang_calculate_result - have (... -1) module returned (noop 1)
Tue May 22 11:46:33 2018 : (10)        ** [5] unlang_calculate_result - over-riding result from higher priority to (noop 1)
Tue May 22 11:46:33 2018 : (10)        ----- Begin stack debug [depth 4] -----
Tue May 22 11:46:33 2018 : (10)        [4] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           if
Tue May 22 11:46:33 2018 : (10)          name           if
Tue May 22 11:46:33 2018 : (10)          debug_name     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i)
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [3] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           group
Tue May 22 11:46:33 2018 : (10)          name           acct_unique
Tue May 22 11:46:33 2018 : (10)          debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)          next           files
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [2] Frame contents
Tue May 22 11:46:33 2018 : (10)          type           group
Tue May 22 11:46:33 2018 : (10)          name           recv
Tue May 22 11:46:33 2018 : (10)          debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         ...
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [1] Frame contents
Tue May 22 11:46:33 2018 : (10)          instruction = NULL
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      yes
Tue May 22 11:46:33 2018 : (10)          result         noop
Tue May 22 11:46:33 2018 : (10)          priority       -1
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        [0] Frame contents
Tue May 22 11:46:33 2018 : (10)          instruction = NULL
Tue May 22 11:46:33 2018 : (10)          next           <none>
Tue May 22 11:46:33 2018 : (10)          top_frame      no
Tue May 22 11:46:33 2018 : (10)          result         reject
Tue May 22 11:46:33 2018 : (10)          priority       0
Tue May 22 11:46:33 2018 : (10)          unwind         0
Tue May 22 11:46:33 2018 : (10)          repeat         no
Tue May 22 11:46:33 2018 : (10)        ----- End stack debug [depth 4] -------
Tue May 22 11:46:33 2018 : (10)      } # if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/i) (noop)
Tue May 22 11:46:33 2018 : (10)      ** [4] unlang_calculate_result - have (... -1) module returned (noop 1)
Tue May 22 11:46:33 2018 : (10)      ** [4] unlang_calculate_result - over-riding result from higher priority to (noop 1)
Tue May 22 11:46:33 2018 : (10)      ** [4] unlang_run - done current subsection with (noop 1)
Tue May 22 11:46:33 2018 : (10)      ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)      [3] Frame contents
Tue May 22 11:46:33 2018 : (10)        type           group
Tue May 22 11:46:33 2018 : (10)        name           acct_unique
Tue May 22 11:46:33 2018 : (10)        debug_name     acct_unique
Tue May 22 11:46:33 2018 : (10)        next           files
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         ...
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [2] Frame contents
Tue May 22 11:46:33 2018 : (10)        type           group
Tue May 22 11:46:33 2018 : (10)        name           recv
Tue May 22 11:46:33 2018 : (10)        debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         ...
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [1] Frame contents
Tue May 22 11:46:33 2018 : (10)        instruction = NULL
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      yes
Tue May 22 11:46:33 2018 : (10)        result         noop
Tue May 22 11:46:33 2018 : (10)        priority       -1
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      [0] Frame contents
Tue May 22 11:46:33 2018 : (10)        instruction = NULL
Tue May 22 11:46:33 2018 : (10)        next           <none>
Tue May 22 11:46:33 2018 : (10)        top_frame      no
Tue May 22 11:46:33 2018 : (10)        result         reject
Tue May 22 11:46:33 2018 : (10)        priority       0
Tue May 22 11:46:33 2018 : (10)        unwind         0
Tue May 22 11:46:33 2018 : (10)        repeat         no
Tue May 22 11:46:33 2018 : (10)      ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    } # acct_unique (noop)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (... -1) module returned (noop 1)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - over-riding result from higher priority to (noop 1)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_run - continuing after subsection with (noop 1)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           files
Tue May 22 11:46:33 2018 : (10)      debug_name     files
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           recv
Tue May 22 11:46:33 2018 : (10)      debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - files (files)
Tue May 22 11:46:33 2018 : (10)    files (noop)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (1)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (noop 1) module returned (noop 1)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           recv
Tue May 22 11:46:33 2018 : (10)      debug_name     recv Accounting-Request
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  } # recv Accounting-Request (noop)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_calculate_result - have (... -1) module returned (noop 1)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_calculate_result - over-riding result from higher priority to (noop 1)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_run - done current subsection with (noop 1)
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 1] -----
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 1] -------
Tue May 22 11:46:33 2018 : (10)  ** [1] unlang_run - over-riding stack->result from higher priority to (noop 1)
Tue May 22 11:46:33 2018 : (10)  ** [1] unlang_run - interpreter exiting, returning noop
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 0] -----
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 0] -------
Tue May 22 11:46:33 2018 : (10)  Running 'send Accounting-Response' from file /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default
Tue May 22 11:46:33 2018 : unlang_push called with instruction <none> - args UNLANG_NEXT_STOP UNLANG_TOP_FRAME
Tue May 22 11:46:33 2018 : unlang_push called with instruction send Accounting-Response - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_push_section - substack begins
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           send
Tue May 22 11:46:33 2018 : (10)    debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : ###### unlang_run is starting
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           send
Tue May 22 11:46:33 2018 : (10)    debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_run - interpreter entered
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)  [2] Frame contents
Tue May 22 11:46:33 2018 : (10)    type           group
Tue May 22 11:46:33 2018 : (10)    name           send
Tue May 22 11:46:33 2018 : (10)    debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         ...
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  send Accounting-Response {
Tue May 22 11:46:33 2018 : (10)    ** [2] unlang_frame_eval >> group
Tue May 22 11:46:33 2018 : unlang_push called with instruction detail - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           detail
Tue May 22 11:46:33 2018 : (10)      debug_name     detail
Tue May 22 11:46:33 2018 : (10)      next           unix
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - detail (detail)
Tue May 22 11:46:33 2018 : (10)    detail - EXPAND /usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/detail-%Y%m%d
Tue May 22 11:46:33 2018 : (10)    detail -   /usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/detail-%Y%m%d
Tue May 22 11:46:33 2018 : (10)    detail -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    detail -     literal --> /usr/local/stow/freeradius-4/var/log/radius/radacct/
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    detail -       attribute --> Packet-Src-IP-Address
Tue May 22 11:46:33 2018 : (10)    detail -       {
Tue May 22 11:46:33 2018 : (10)    detail -         ref  2
Tue May 22 11:46:33 2018 : (10)    detail -         list 1
Tue May 22 11:46:33 2018 : (10)    detail -         tag 0
Tue May 22 11:46:33 2018 : (10)    detail -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    detail -       attribute --> Packet-Src-IPv6-Address
Tue May 22 11:46:33 2018 : (10)    detail -       {
Tue May 22 11:46:33 2018 : (10)    detail -         ref  2
Tue May 22 11:46:33 2018 : (10)    detail -         list 1
Tue May 22 11:46:33 2018 : (10)    detail -         tag 0
Tue May 22 11:46:33 2018 : (10)    detail -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    detail -     literal --> /detail-
Tue May 22 11:46:33 2018 : (10)    detail -     percent --> Y
Tue May 22 11:46:33 2018 : (10)    detail -     percent --> m
Tue May 22 11:46:33 2018 : (10)    detail -     percent --> d
Tue May 22 11:46:33 2018 : (10)    detail - --> /usr/local/stow/freeradius-4/var/log/radius/radacct/192.168.1.3/detail-2018522
Tue May 22 11:46:33 2018 : (10)    detail - /usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/detail-%Y%m%d expands to /usr/local/stow/freeradius-4/var/log/radius/radacct/192.168.1.3/detail-2018522
Tue May 22 11:46:33 2018 : (10)    detail - EXPAND %t
Tue May 22 11:46:33 2018 : (10)    detail -   %t
Tue May 22 11:46:33 2018 : (10)    detail -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    detail -     percent --> t
Tue May 22 11:46:33 2018 : (10)    detail - --> Tue May 22 11:46:33 2018
Tue May 22 11:46:33 2018 : (10)    detail (ok)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (... -1) module returned (ok 2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - over-riding result from higher priority to (ok 2)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           unix
Tue May 22 11:46:33 2018 : (10)      debug_name     unix
Tue May 22 11:46:33 2018 : (10)      next           radutmp
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ok
Tue May 22 11:46:33 2018 : (10)      priority       2
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - unix (unix)
Tue May 22 11:46:33 2018 : (10)    unix (ok)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (ok 2) module returned (ok 2)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           radutmp
Tue May 22 11:46:33 2018 : (10)      debug_name     radutmp
Tue May 22 11:46:33 2018 : (10)      next           sradutmp
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ok
Tue May 22 11:46:33 2018 : (10)      priority       2
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - radutmp (radutmp)
Tue May 22 11:46:33 2018 : (10)    radutmp - EXPAND /usr/local/stow/freeradius-4/var/log/radius/radutmp
Tue May 22 11:46:33 2018 : (10)    radutmp -   /usr/local/stow/freeradius-4/var/log/radius/radutmp
Tue May 22 11:46:33 2018 : (10)    radutmp -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    radutmp -     literal --> /usr/local/stow/freeradius-4/var/log/radius/radutmp
Tue May 22 11:46:33 2018 : (10)    radutmp - --> /usr/local/stow/freeradius-4/var/log/radius/radutmp
Tue May 22 11:46:33 2018 : (10)    radutmp - EXPAND %{User-Name}
Tue May 22 11:46:33 2018 : (10)    radutmp -   %{User-Name}
Tue May 22 11:46:33 2018 : (10)    radutmp -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    radutmp -     attribute --> User-Name
Tue May 22 11:46:33 2018 : (10)    radutmp -     {
Tue May 22 11:46:33 2018 : (10)    radutmp -       ref  2
Tue May 22 11:46:33 2018 : (10)    radutmp -       list 1
Tue May 22 11:46:33 2018 : (10)    radutmp -       tag 0
Tue May 22 11:46:33 2018 : (10)    radutmp -     }
Tue May 22 11:46:33 2018 : (10)    radutmp - --> systemn
Tue May 22 11:46:33 2018 : (10)    radutmp (ok)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (ok 2) module returned (ok 2)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           sradutmp
Tue May 22 11:46:33 2018 : (10)      debug_name     sradutmp
Tue May 22 11:46:33 2018 : (10)      next           sql
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ok
Tue May 22 11:46:33 2018 : (10)      priority       2
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - sradutmp (radutmp)
Tue May 22 11:46:33 2018 : (10)    sradutmp - EXPAND /usr/local/stow/freeradius-4/var/log/radius/sradutmp
Tue May 22 11:46:33 2018 : (10)    sradutmp -   /usr/local/stow/freeradius-4/var/log/radius/sradutmp
Tue May 22 11:46:33 2018 : (10)    sradutmp -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sradutmp -     literal --> /usr/local/stow/freeradius-4/var/log/radius/sradutmp
Tue May 22 11:46:33 2018 : (10)    sradutmp - --> /usr/local/stow/freeradius-4/var/log/radius/sradutmp
Tue May 22 11:46:33 2018 : (10)    sradutmp - EXPAND %{User-Name}
Tue May 22 11:46:33 2018 : (10)    sradutmp -   %{User-Name}
Tue May 22 11:46:33 2018 : (10)    sradutmp -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sradutmp -     attribute --> User-Name
Tue May 22 11:46:33 2018 : (10)    sradutmp -     {
Tue May 22 11:46:33 2018 : (10)    sradutmp -       ref  2
Tue May 22 11:46:33 2018 : (10)    sradutmp -       list 1
Tue May 22 11:46:33 2018 : (10)    sradutmp -       tag 0
Tue May 22 11:46:33 2018 : (10)    sradutmp -     }
Tue May 22 11:46:33 2018 : (10)    sradutmp - --> systemn
Tue May 22 11:46:33 2018 : (10)    sradutmp (ok)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (ok 2) module returned (ok 2)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           sql
Tue May 22 11:46:33 2018 : (10)      debug_name     sql
Tue May 22 11:46:33 2018 : (10)      next           attr_filter.accounting_response
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ok
Tue May 22 11:46:33 2018 : (10)      priority       2
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - sql (sql)
Tue May 22 11:46:33 2018 : (10)    sql - EXPAND %{tolower:type.%{Acct-Status-Type}.query}
Tue May 22 11:46:33 2018 : (10)    sql -   %{tolower:type.%{Acct-Status-Type}.query}
Tue May 22 11:46:33 2018 : (10)    sql -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sql -     xlat --> tolower
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> type.
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Status-Type
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> .query
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : Worker alloced xlat thread instance (0x2bd9630/(nil))
Tue May 22 11:46:33 2018 : (10)    sql - --> type.stop.query
Tue May 22 11:46:33 2018 : (10)    sql - Using query template 'query'
Tue May 22 11:46:33 2018 : (10)    sql - Reserved connection (5)
Tue May 22 11:46:33 2018 : (10)    sql - EXPAND %{User-Name}
Tue May 22 11:46:33 2018 : (10)    sql -   %{User-Name}
Tue May 22 11:46:33 2018 : (10)    sql -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sql -     attribute --> User-Name
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       ref  2
Tue May 22 11:46:33 2018 : (10)    sql -       list 1
Tue May 22 11:46:33 2018 : (10)    sql -       tag 0
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : (10)    sql - --> systemn
Tue May 22 11:46:33 2018 : (10)    sql - SQL-User-Name set to 'systemn'
Tue May 22 11:46:33 2018 : (10)    sql - EXPAND UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(%{integer:Event-Timestamp}), acctsessiontime	= %{%{Acct-Session-Time}:-NULL}, acctinputoctets	= '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', acctoutputoctets = '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}', acctterminatecause = '%{Acct-Terminate-Cause}', connectinfo_stop = '%{Connect-Info}' WHERE acctuniqueid = '%{Acct-Unique-Session-Id}'
Tue May 22 11:46:33 2018 : (10)    sql -   UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(%{integer:Event-Timestamp}), acctsessiontime	= %{%{Acct-Session-Time}:-NULL}, acctinputoctets	= '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', acctoutputoctets = '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}', acctterminatecause = '%{Acct-Terminate-Cause}', connectinfo_stop = '%{Connect-Info}' WHERE acctuniqueid = '%{Acct-Unique-Session-Id}'
Tue May 22 11:46:33 2018 : (10)    sql -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(
Tue May 22 11:46:33 2018 : (10)    sql -     xlat --> integer
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> Event-Timestamp
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ), acctsessiontime	= 
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Session-Time
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> NULL
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> , acctinputoctets	= '
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Input-Gigawords
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> 0
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ' << 32 | '
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Input-Octets
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> 0
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ', acctoutputoctets = '
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Output-Gigawords
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> 0
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ' << 32 | '
Tue May 22 11:46:33 2018 : XLAT-IF {
Tue May 22 11:46:33 2018 : (10)    sql -       attribute --> Acct-Output-Octets
Tue May 22 11:46:33 2018 : (10)    sql -       {
Tue May 22 11:46:33 2018 : (10)    sql -         ref  2
Tue May 22 11:46:33 2018 : (10)    sql -         list 1
Tue May 22 11:46:33 2018 : (10)    sql -         tag 0
Tue May 22 11:46:33 2018 : (10)    sql -       }
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : XLAT-ELSE {
Tue May 22 11:46:33 2018 : (10)    sql -       literal --> 0
Tue May 22 11:46:33 2018 : }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ', acctterminatecause = '
Tue May 22 11:46:33 2018 : (10)    sql -     attribute --> Acct-Terminate-Cause
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       ref  2
Tue May 22 11:46:33 2018 : (10)    sql -       list 1
Tue May 22 11:46:33 2018 : (10)    sql -       tag 0
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ', connectinfo_stop = '
Tue May 22 11:46:33 2018 : (10)    sql -     attribute --> Connect-Info
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       ref  2
Tue May 22 11:46:33 2018 : (10)    sql -       list 1
Tue May 22 11:46:33 2018 : (10)    sql -       tag 0
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> ' WHERE acctuniqueid = '
Tue May 22 11:46:33 2018 : (10)    sql -     attribute --> Acct-Unique-Session-Id
Tue May 22 11:46:33 2018 : (10)    sql -     {
Tue May 22 11:46:33 2018 : (10)    sql -       ref  2
Tue May 22 11:46:33 2018 : (10)    sql -       list 1
Tue May 22 11:46:33 2018 : (10)    sql -       tag 0
Tue May 22 11:46:33 2018 : (10)    sql -     }
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> '
Tue May 22 11:46:33 2018 : Worker alloced xlat thread instance (0x2bd96a0/(nil))
Tue May 22 11:46:33 2018 : (10)    sql - --> UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(1526978544), acctsessiontime	= 16, acctinputoctets= '0' << 32 | '13779', acctoutputoctets = '0' << 32 | '12991', acctterminatecause = 'User-Request', connectinfo_stop = 'CONNECT 54Mbps 802.11g' WHERE acctuniqueid = '84cdbd94df9226be575e9a4879323e1f'
Tue May 22 11:46:33 2018 : (10)    sql - EXPAND /usr/local/stow/freeradius-4/var/log/radius/sqllog.sql
Tue May 22 11:46:33 2018 : (10)    sql -   /usr/local/stow/freeradius-4/var/log/radius/sqllog.sql
Tue May 22 11:46:33 2018 : (10)    sql -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    sql -     literal --> /usr/local/stow/freeradius-4/var/log/radius/sqllog.sql
Tue May 22 11:46:33 2018 : (10)    sql - --> /usr/local/stow/freeradius-4/var/log/radius/sqllog.sql
Tue May 22 11:46:33 2018 : (10)    sql - Executing query: UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(1526978544), acctsessiontime	= 16, acctinputoctets	= '0' << 32 | '13779', acctoutputoctets = '0' << 32 | '12991', acctterminatecause = 'User-Request', connectinfo_stop = 'CONNECT 54Mbps 802.11g' WHERE acctuniqueid = '84cdbd94df9226be575e9a4879323e1f'
Tue May 22 11:46:33 2018 : rlm_sql_mysql - Rows matched: 1  Changed: 1  Warnings: 0
Tue May 22 11:46:33 2018 : (10)    sql - SQL query returned: success
Tue May 22 11:46:33 2018 : (10)    sql - 1 record(s) updated
Tue May 22 11:46:33 2018 : (10)    sql - Released connection (5)
Tue May 22 11:46:33 2018 : (10)    sql - Need 4 more connections to reach 10 spares
Tue May 22 11:46:33 2018 : (10)    sql - Opening additional connection (6), 1 of 26 pending slots used
Tue May 22 11:46:33 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:33 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:33 2018 : (10)    sql (ok)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (ok 2) module returned (ok 2)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:33 2018 : (10)    [3] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           module
Tue May 22 11:46:33 2018 : (10)      name           attr_filter.accounting_response
Tue May 22 11:46:33 2018 : (10)      debug_name     attr_filter.accounting_response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ok
Tue May 22 11:46:33 2018 : (10)      priority       2
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:33 2018 : (10)    [3] unlang_module - attr_filter.accounting_response (attr_filter)
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response - EXPAND TMPL XLAT
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response - EXPAND %{User-Name}
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -   %{User-Name}
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -   Parsed xlat tree:
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -     attribute --> User-Name
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -     {
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -       ref  2
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -       list 1
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -       tag 0
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response -     }
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response - --> systemn
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response - Copying 8 bytes to (nil) from offset 0
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response - Matched entry DEFAULT at line 12
Tue May 22 11:46:33 2018 : (10)    attr_filter.accounting_response (updated)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_frame_eval << calculate-result (3)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - have (ok 2) module returned (updated 3)
Tue May 22 11:46:33 2018 : (10)    ** [3] unlang_calculate_result - over-riding result from higher priority to (updated 3)
Tue May 22 11:46:33 2018 : (10)    ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:33 2018 : (10)    [2] Frame contents
Tue May 22 11:46:33 2018 : (10)      type           group
Tue May 22 11:46:33 2018 : (10)      name           send
Tue May 22 11:46:33 2018 : (10)      debug_name     send Accounting-Response
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         ...
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [1] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      yes
Tue May 22 11:46:33 2018 : (10)      result         noop
Tue May 22 11:46:33 2018 : (10)      priority       -1
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    [0] Frame contents
Tue May 22 11:46:33 2018 : (10)      instruction = NULL
Tue May 22 11:46:33 2018 : (10)      next           <none>
Tue May 22 11:46:33 2018 : (10)      top_frame      no
Tue May 22 11:46:33 2018 : (10)      result         reject
Tue May 22 11:46:33 2018 : (10)      priority       0
Tue May 22 11:46:33 2018 : (10)      unwind         0
Tue May 22 11:46:33 2018 : (10)      repeat         no
Tue May 22 11:46:33 2018 : (10)    ----- End stack debug [depth 2] -------
Tue May 22 11:46:33 2018 : (10)  } # send Accounting-Response (updated)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_calculate_result - have (... -1) module returned (updated 3)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_calculate_result - over-riding result from higher priority to (updated 3)
Tue May 22 11:46:33 2018 : (10)  ** [2] unlang_run - done current subsection with (updated 3)
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 1] -----
Tue May 22 11:46:33 2018 : (10)  [1] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      yes
Tue May 22 11:46:33 2018 : (10)    result         noop
Tue May 22 11:46:33 2018 : (10)    priority       -1
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 1] -------
Tue May 22 11:46:33 2018 : (10)  ** [1] unlang_run - over-riding stack->result from higher priority to (updated 3)
Tue May 22 11:46:33 2018 : (10)  ** [1] unlang_run - interpreter exiting, returning updated
Tue May 22 11:46:33 2018 : (10)  ----- Begin stack debug [depth 0] -----
Tue May 22 11:46:33 2018 : (10)  [0] Frame contents
Tue May 22 11:46:33 2018 : (10)    instruction = NULL
Tue May 22 11:46:33 2018 : (10)    next           <none>
Tue May 22 11:46:33 2018 : (10)    top_frame      no
Tue May 22 11:46:33 2018 : (10)    result         reject
Tue May 22 11:46:33 2018 : (10)    priority       0
Tue May 22 11:46:33 2018 : (10)    unwind         0
Tue May 22 11:46:33 2018 : (10)    repeat         no
Tue May 22 11:46:33 2018 : (10)  ----- End stack debug [depth 0] -------
Tue May 22 11:46:33 2018 : (10)  Sent code 5 Id 72 from 192.168.1.169:1813 to 192.168.1.3:49040 via enp2s0 length 0
Tue May 22 11:46:33 2018 : (10)  done request
Tue May 22 11:46:33 2018 : (10)  proto_radius encode packet
  Code:		Accounting-Response
  Id:		72
  Length:	20
  Vector:	0ee4e7ce1651689e4fc7c081247765a7
Tue May 22 11:46:33 2018 : (10)  finished request.
Tue May 22 11:46:33 2018 : freeing request
Tue May 22 11:46:33 2018 : Ready to process requests
Tue May 22 11:46:33 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:33 2018 : 	requests 11, decoded 11, replied 11 active 0
Tue May 22 11:46:33 2018 : data <--
Tue May 22 11:46:33 2018 : received reply 11
Tue May 22 11:46:33 2018 : proto_radius_udp - cleaning up ID 72
Tue May 22 11:46:33 2018 : Sending reply to socket 17
Tue May 22 11:46:33 2018 : 	checking timeouts
Tue May 22 11:46:33 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:33 2018 : Ready to process requests
Tue May 22 11:46:33 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:33 2018 : 	requests 11, decoded 11, replied 11 active 0
Tue May 22 11:46:33 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:33 2018 : 	--> data
Tue May 22 11:46:33 2018 : 	--> empty-ack
Tue May 22 11:46:33 2018 : 	checking timeouts
Tue May 22 11:46:33 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:33 2018 : Ready to process requests
Tue May 22 11:46:33 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:33 2018 : 	requests 11, decoded 11, replied 11 active 0
Tue May 22 11:46:33 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:34 2018 : network read
Tue May 22 11:46:34 2018 : proto_radius_udp - Received Access-Request ID 131 length 196 proto udp server * port 1812
Tue May 22 11:46:34 2018 : Network received packet size 196
Tue May 22 11:46:34 2018 : 	checking timeouts
Tue May 22 11:46:34 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:34 2018 : Ready to process requests
Tue May 22 11:46:34 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:34 2018 : 	requests 11, decoded 11, replied 11 active 0
Tue May 22 11:46:34 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:34 2018 : 	--> data
Tue May 22 11:46:34 2018 : 	received request 12
Tue May 22 11:46:34 2018 : 	checking timeouts
Tue May 22 11:46:34 2018 : Worker 0 found request to decode
Tue May 22 11:46:34 2018 : (11)  proto_radius decode packet
  Code:		Access-Request
  Id:		131
  Length:	196
  Vector:	0676579ae0ebd01f81f4e7096f3b19c6
		01  09  73 79 73 74 65 6d 6e 
		1e  20  36 30 2d 45 33 2d 32 37 2d 37 32 2d 42 46 2d 35 
			41 3a 44 45 76 43 68 61 74 61 5f 6e 65 77 
		3d  06  00 00 00 13 
		06  06  00 00 00 02 
		05  06  00 00 00 01 
		1f  13  33 38 2d 32 44 2d 44 31 2d 33 32 2d 36 31 2d 31 
			45 
		4d  18  43 4f 4e 4e 45 43 54 20 35 34 4d 62 70 73 20 38 
			30 32 2e 31 31 67 
		2c  12  36 30 39 31 46 45 33 38 45 45 36 46 42 37 30 45 
		ba  06  00 0f ac 04 
		bb  06  00 0f ac 02 
		bc  06  00 0f ac 01 
		0c  06  00 00 05 78 
		4f  0e  02 fa 00 0c 01 73 79 73 74 65 6d 6e 
		50  12  a3 99 23 df 06 25 a2 77 7d 35 12 e6 a3 68 9a 1c 
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> User-Name
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 73 79 73 74 65 6d 6e 
msg: src/protocols/radius/decode.c:1043: Parent User-Name len 7 ... 174
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Called-Station-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 36 30 2d 45 33 2d 32 37 2d 37 32 2d 42 46 2d 35 
hex: src/protocols/radius/decode.c:1041: 0010: 41 3a 44 45 76 43 68 61 74 61 5f 6e 65 77 
msg: src/protocols/radius/decode.c:1043: Parent Called-Station-Id len 30 ... 165
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> NAS-Port-Type
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 13 
msg: src/protocols/radius/decode.c:1043: Parent NAS-Port-Type len 4 ... 133
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Service-Type
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 02 
msg: src/protocols/radius/decode.c:1043: Parent Service-Type len 4 ... 127
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> NAS-Port
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 00 01 
msg: src/protocols/radius/decode.c:1043: Parent NAS-Port len 4 ... 121
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Calling-Station-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 33 38 2d 32 44 2d 44 31 2d 33 32 2d 36 31 2d 31 
hex: src/protocols/radius/decode.c:1041: 0010: 45 
msg: src/protocols/radius/decode.c:1043: Parent Calling-Station-Id len 17 ... 115
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Connect-Info
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 43 4f 4e 4e 45 43 54 20 35 34 4d 62 70 73 20 38 
hex: src/protocols/radius/decode.c:1041: 0010: 30 32 2e 31 31 67 
msg: src/protocols/radius/decode.c:1043: Parent Connect-Info len 22 ... 96
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Acct-Session-Id
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 36 30 39 31 46 45 33 38 45 45 36 46 42 37 30 45 

msg: src/protocols/radius/decode.c:1043: Parent Acct-Session-Id len 16 ... 72
msg: src/protocols/radius/decode.c:1169: Type "string" (1)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-Pairwise-Cipher
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 04 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-Pairwise-Cipher len 4 ... 54
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-Group-Cipher
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 02 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-Group-Cipher len 4 ... 48
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> WLAN-AKM-Suite
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 0f ac 01 
msg: src/protocols/radius/decode.c:1043: Parent WLAN-AKM-Suite len 4 ... 42
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Framed-MTU
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: 00 00 05 78 
msg: src/protocols/radius/decode.c:1043: Parent Framed-MTU len 4 ... 36
msg: src/protocols/radius/decode.c:1169: Type "uint32" (14)
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> EAP-Message
msg: src/protocols/radius/decode.c:1563: Concat attribute
msg: src/protocols/radius/decode.c:1530: decode context changed radius -> Message-Authenticator
hex: src/protocols/radius/decode.c:1041: -- fr_radius_decode_pair_value --
hex: src/protocols/radius/decode.c:1041: 0000: a3 99 23 df 06 25 a2 77 7d 35 12 e6 a3 68 9a 1c 

msg: src/protocols/radius/decode.c:1043: Parent Message-Authenticator len 16 ... 16
msg: src/protocols/radius/decode.c:1169: Type "octets" (2)
Tue May 22 11:46:34 2018 : Resetting worker 30 cleanup timer to +0s
Tue May 22 11:46:34 2018 : (11)  running request
Tue May 22 11:46:34 2018 : (11)  Received Access-Request ID 131
Tue May 22 11:46:34 2018 : (11)    User-Name = "systemn"
Tue May 22 11:46:34 2018 : (11)    Called-Station-Id = "60-E3-27-72-BF-5A:DEvChata_new"
Tue May 22 11:46:34 2018 : (11)    NAS-Port-Type = Wireless-802.11
Tue May 22 11:46:34 2018 : (11)    Service-Type = Framed-User
Tue May 22 11:46:34 2018 : (11)    NAS-Port = 1
Tue May 22 11:46:34 2018 : (11)    Calling-Station-Id = "38-2D-D1-32-61-1E"
Tue May 22 11:46:34 2018 : (11)    Connect-Info = "CONNECT 54Mbps 802.11g"
Tue May 22 11:46:34 2018 : (11)    Acct-Session-Id = "6091FE38EE6FB70E"
Tue May 22 11:46:34 2018 : (11)    WLAN-Pairwise-Cipher = 1027076
Tue May 22 11:46:34 2018 : (11)    WLAN-Group-Cipher = 1027074
Tue May 22 11:46:34 2018 : (11)    WLAN-AKM-Suite = 1027073
Tue May 22 11:46:34 2018 : (11)    Framed-MTU = 1400
Tue May 22 11:46:34 2018 : (11)    EAP-Message = 0x02fa000c0173797374656d6e
Tue May 22 11:46:34 2018 : (11)    Message-Authenticator = 0xa39923df0625a2777d3512e6a3689a1c
Tue May 22 11:46:34 2018 : (11)  No &request:State attribute, can't restore &session-state
Tue May 22 11:46:34 2018 : (11)  Running 'recv Access-Request' from file /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default
Tue May 22 11:46:34 2018 : unlang_push called with instruction <none> - args UNLANG_NEXT_STOP UNLANG_TOP_FRAME
Tue May 22 11:46:34 2018 : unlang_push called with instruction recv Access-Request - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_push_section - substack begins
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           recv
Tue May 22 11:46:34 2018 : (11)    debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : ###### unlang_run is starting
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           recv
Tue May 22 11:46:34 2018 : (11)    debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - interpreter entered
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           recv
Tue May 22 11:46:34 2018 : (11)    debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  recv Access-Request {
Tue May 22 11:46:34 2018 : (11)    ** [2] unlang_frame_eval >> group
Tue May 22 11:46:34 2018 : unlang_push called with instruction filter_username - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           filter_username
Tue May 22 11:46:34 2018 : (11)      debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)      next           chap
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    filter_username {
Tue May 22 11:46:34 2018 : (11)      ** [3] unlang_frame_eval >> group
Tue May 22 11:46:34 2018 : unlang_push called with instruction if (&State) - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)      ** [4] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:34 2018 : (11)      ----- Begin stack debug [depth 4] -----
Tue May 22 11:46:34 2018 : (11)      [4] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           if
Tue May 22 11:46:34 2018 : (11)        name           if
Tue May 22 11:46:34 2018 : (11)        debug_name     if (&State)
Tue May 22 11:46:34 2018 : (11)        next           elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [3] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           filter_username
Tue May 22 11:46:34 2018 : (11)        debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)        next           chap
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [2] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           recv
Tue May 22 11:46:34 2018 : (11)        debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [1] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      yes
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [0] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       0
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      ----- End stack debug [depth 4] -------
Tue May 22 11:46:34 2018 : (11)      if (&State) {
Tue May 22 11:46:34 2018 : (11)        ** [4] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : (11)        ...
Tue May 22 11:46:34 2018 : (11)        ** [4] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)      }
Tue May 22 11:46:34 2018 : (11)      ----- Begin stack debug [depth 4] -----
Tue May 22 11:46:34 2018 : (11)      [4] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           elseif
Tue May 22 11:46:34 2018 : (11)        name           elseif
Tue May 22 11:46:34 2018 : (11)        debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [3] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           filter_username
Tue May 22 11:46:34 2018 : (11)        debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)        next           chap
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [2] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           recv
Tue May 22 11:46:34 2018 : (11)        debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [1] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      yes
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [0] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       0
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      ----- End stack debug [depth 4] -------
Tue May 22 11:46:34 2018 : (11)      elseif (&User-Name) {
Tue May 22 11:46:34 2018 : (11)        ** [4] unlang_frame_eval >> elseif
Tue May 22 11:46:34 2018 : unlang_push called with instruction if (&User-Name =~ / /) - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)        ** [5] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if (&User-Name =~ / /)
Tue May 22 11:46:34 2018 : (11)          next           if (&User-Name =~ /@[^@]*@/ )
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if (&User-Name =~ / /) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if (&User-Name =~ /@[^@]*@/ )
Tue May 22 11:46:34 2018 : (11)          next           if (&User-Name =~ /\.\./ )
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if (&User-Name =~ /@[^@]*@/ ) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if (&User-Name =~ /\.\./ )
Tue May 22 11:46:34 2018 : (11)          next           if ((&User-Name =~ /@/) && (&User-Name !~ /@[^.]+(\.[^.]+)+$/))
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if (&User-Name =~ /\.\./ ) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if ((&User-Name =~ /@/) && (&User-Name !~ /@[^.]+(\.[^.]+)+$/))
Tue May 22 11:46:34 2018 : (11)          next           if (&User-Name =~ /\.$/)
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if ((&User-Name =~ /@/) && (&User-Name !~ /@[^.]+(\.[^.]+)+$/)) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if (&User-Name =~ /\.$/)
Tue May 22 11:46:34 2018 : (11)          next           if (&User-Name =~ /@\./)
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if (&User-Name =~ /\.$/) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           if
Tue May 22 11:46:34 2018 : (11)          name           if
Tue May 22 11:46:34 2018 : (11)          debug_name     if (&User-Name =~ /@\./)
Tue May 22 11:46:34 2018 : (11)          next           update session-state
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        if (&User-Name =~ /@\./) {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> if
Tue May 22 11:46:34 2018 : No matches
Tue May 22 11:46:34 2018 : (11)          ...
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << continue (-1)
Tue May 22 11:46:34 2018 : (11)        }
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 5] -----
Tue May 22 11:46:34 2018 : (11)        [5] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           update
Tue May 22 11:46:34 2018 : (11)          name           session-state
Tue May 22 11:46:34 2018 : (11)          debug_name     update session-state
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 5] -------
Tue May 22 11:46:34 2018 : (11)        update session-state {
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval >> update
Tue May 22 11:46:34 2018 : (11)          &Session-State-User-Name := &User-Name -> "systemn"
Tue May 22 11:46:34 2018 : (11)          ** [5] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:34 2018 : (11)        } # update session-state (noop)
Tue May 22 11:46:34 2018 : (11)        ** [5] unlang_calculate_result - have (... -1) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)        ** [5] unlang_calculate_result - over-riding result from higher priority to (noop 2)
Tue May 22 11:46:34 2018 : (11)        ----- Begin stack debug [depth 4] -----
Tue May 22 11:46:34 2018 : (11)        [4] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           elseif
Tue May 22 11:46:34 2018 : (11)          name           elseif
Tue May 22 11:46:34 2018 : (11)          debug_name     elseif (&User-Name)
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [3] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           filter_username
Tue May 22 11:46:34 2018 : (11)          debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)          next           chap
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [2] Frame contents
Tue May 22 11:46:34 2018 : (11)          type           group
Tue May 22 11:46:34 2018 : (11)          name           recv
Tue May 22 11:46:34 2018 : (11)          debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         ...
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [1] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      yes
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       -1
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        [0] Frame contents
Tue May 22 11:46:34 2018 : (11)          instruction = NULL
Tue May 22 11:46:34 2018 : (11)          next           <none>
Tue May 22 11:46:34 2018 : (11)          top_frame      no
Tue May 22 11:46:34 2018 : (11)          result         reject
Tue May 22 11:46:34 2018 : (11)          priority       0
Tue May 22 11:46:34 2018 : (11)          unwind         0
Tue May 22 11:46:34 2018 : (11)          repeat         no
Tue May 22 11:46:34 2018 : (11)        ----- End stack debug [depth 4] -------
Tue May 22 11:46:34 2018 : (11)      } # elseif (&User-Name) (noop)
Tue May 22 11:46:34 2018 : (11)      ** [4] unlang_calculate_result - have (... -1) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)      ** [4] unlang_calculate_result - over-riding result from higher priority to (noop 2)
Tue May 22 11:46:34 2018 : (11)      ** [4] unlang_run - done current subsection with (noop 2)
Tue May 22 11:46:34 2018 : (11)      ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)      [3] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           filter_username
Tue May 22 11:46:34 2018 : (11)        debug_name     filter_username
Tue May 22 11:46:34 2018 : (11)        next           chap
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [2] Frame contents
Tue May 22 11:46:34 2018 : (11)        type           group
Tue May 22 11:46:34 2018 : (11)        name           recv
Tue May 22 11:46:34 2018 : (11)        debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         ...
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [1] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      yes
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       -1
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      [0] Frame contents
Tue May 22 11:46:34 2018 : (11)        instruction = NULL
Tue May 22 11:46:34 2018 : (11)        next           <none>
Tue May 22 11:46:34 2018 : (11)        top_frame      no
Tue May 22 11:46:34 2018 : (11)        result         reject
Tue May 22 11:46:34 2018 : (11)        priority       0
Tue May 22 11:46:34 2018 : (11)        unwind         0
Tue May 22 11:46:34 2018 : (11)        repeat         no
Tue May 22 11:46:34 2018 : (11)      ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    } # filter_username (noop)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (... -1) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - over-riding result from higher priority to (noop 2)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_run - continuing after subsection with (noop 2)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           chap
Tue May 22 11:46:34 2018 : (11)      debug_name     chap
Tue May 22 11:46:34 2018 : (11)      next           mschap
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       2
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - chap (chap)
Tue May 22 11:46:34 2018 : (11)    chap (noop)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (noop 2) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           mschap
Tue May 22 11:46:34 2018 : (11)      debug_name     mschap
Tue May 22 11:46:34 2018 : (11)      next           digest
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       2
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - mschap (mschap)
Tue May 22 11:46:34 2018 : (11)    mschap (noop)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (noop 2) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           digest
Tue May 22 11:46:34 2018 : (11)      debug_name     digest
Tue May 22 11:46:34 2018 : (11)      next           eap
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       2
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - digest (digest)
Tue May 22 11:46:34 2018 : (11)    digest (noop)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (2)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (noop 2) module returned (noop 2)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           eap
Tue May 22 11:46:34 2018 : (11)      debug_name     eap
Tue May 22 11:46:34 2018 : (11)      next           files
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       2
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - eap (eap)
Tue May 22 11:46:34 2018 : (11)    eap - Peer sent EAP Response (code 2) ID 250 length 12
Tue May 22 11:46:34 2018 : (11)    eap - Peer sent EAP-Identity.  Returning 'ok' so we can short-circuit the rest of authorize
Tue May 22 11:46:34 2018 : (11)    eap - &control:Auth-Type = eap
Tue May 22 11:46:34 2018 : (11)    eap (ok)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (-1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (noop 2) module returned (ok -1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - action says to return with (ok 0)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           recv
Tue May 22 11:46:34 2018 : (11)      debug_name     recv Access-Request
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  } # recv Access-Request (ok)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - have (... -1) module returned (ok 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - over-riding result from higher priority to (ok 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - done current subsection with (ok 0)
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 1] -----
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 1] -------
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - over-riding stack->result from higher priority to (ok 0)
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - interpreter exiting, returning ok
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 0] -----
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 0] -------
Tue May 22 11:46:34 2018 : (11)  Running 'authenticate eap' from file /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default
Tue May 22 11:46:34 2018 : unlang_push called with instruction <none> - args UNLANG_NEXT_STOP UNLANG_TOP_FRAME
Tue May 22 11:46:34 2018 : unlang_push called with instruction authenticate eap - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_push_section - substack begins
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           authenticate
Tue May 22 11:46:34 2018 : (11)    debug_name     authenticate eap
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         notfound
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : ###### unlang_run is starting
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           authenticate
Tue May 22 11:46:34 2018 : (11)    debug_name     authenticate eap
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         notfound
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - interpreter entered
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           authenticate
Tue May 22 11:46:34 2018 : (11)    debug_name     authenticate eap
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         notfound
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  authenticate eap {
Tue May 22 11:46:34 2018 : (11)    ** [2] unlang_frame_eval >> group
Tue May 22 11:46:34 2018 : unlang_push called with instruction eap - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           eap
Tue May 22 11:46:34 2018 : (11)      debug_name     eap
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           authenticate
Tue May 22 11:46:34 2018 : (11)      debug_name     authenticate eap
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         notfound
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - eap (eap)
Tue May 22 11:46:34 2018 : (11)    eap - New eap_session_t 0x2bfabc0
Tue May 22 11:46:34 2018 : (11)    eap - Added request data 0x2bfabc0 at (nil):1
Tue May 22 11:46:34 2018 : (11)    eap - Peer sent packet with EAP method Identity (1)
Tue May 22 11:46:34 2018 : (11)    eap - Calling submodule eap_md5
Tue May 22 11:46:34 2018 : (11)    eap - Issuing MD5 Challenge
Tue May 22 11:46:34 2018 : (11)    eap - Submodule eap_md5 returned
Tue May 22 11:46:34 2018 : (11)    eap - Sending EAP Request (code 1) ID 251 length 22
Tue May 22 11:46:34 2018 : (11)    eap (handled)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (-1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (... -1) module returned (handled -1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - action says to return with (handled 0)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           authenticate
Tue May 22 11:46:34 2018 : (11)      debug_name     authenticate eap
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         notfound
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  } # authenticate eap (handled)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - have (... -1) module returned (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - action says to return with (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - done current subsection with (handled 0)
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 1] -----
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         notfound
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 1] -------
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - over-riding stack->result from higher priority to (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - interpreter exiting, returning handled
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 0] -----
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 0] -------
Tue May 22 11:46:34 2018 : (11)  Running 'send Access-Challenge' from file /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default
Tue May 22 11:46:34 2018 : unlang_push called with instruction <none> - args UNLANG_NEXT_STOP UNLANG_TOP_FRAME
Tue May 22 11:46:34 2018 : unlang_push called with instruction send Access-Challenge - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_push_section - substack begins
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           send
Tue May 22 11:46:34 2018 : (11)    debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         noop
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : ###### unlang_run is starting
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           send
Tue May 22 11:46:34 2018 : (11)    debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         noop
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - interpreter entered
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)  [2] Frame contents
Tue May 22 11:46:34 2018 : (11)    type           group
Tue May 22 11:46:34 2018 : (11)    name           send
Tue May 22 11:46:34 2018 : (11)    debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         ...
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         noop
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  send Access-Challenge {
Tue May 22 11:46:34 2018 : (11)    ** [2] unlang_frame_eval >> group
Tue May 22 11:46:34 2018 : unlang_push called with instruction attr_filter.access_challenge.post-auth - args UNLANG_NEXT_CONTINUE UNLANG_SUB_FRAME
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << pushed-child (-1)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           attr_filter.access_challenge.post-auth
Tue May 22 11:46:34 2018 : (11)      debug_name     attr_filter.access_challenge.post-auth
Tue May 22 11:46:34 2018 : (11)      next           handled
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           send
Tue May 22 11:46:34 2018 : (11)      debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - attr_filter.access_challenge (attr_filter)
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - EXPAND TMPL XLAT
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - EXPAND %{User-Name}
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -   %{User-Name}
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -   Parsed xlat tree:
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -     attribute --> User-Name
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -     {
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -       ref  2
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -       list 1
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -       tag 0
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge -     }
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - --> systemn
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Copying 8 bytes to (nil) from offset 0
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Matched entry DEFAULT at line 12
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Message-Authenticator = 0x00000000000000000000000000000000 allowed by Message-Authenticator =* 0x
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Attribute "Message-Authenticator" allowed by 1 rules, disallowed by 0 rules
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - EAP-Message = 0x01fb001604107460322ee07c3ae8e1f889dfb6a43dc1 allowed by EAP-Message =* 0x
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Attribute "EAP-Message" allowed by 1 rules, disallowed by 0 rules
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - State = 0x3f9f781499b41d2b50289f378de187e4 allowed by State =* 0x
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge - Attribute "State" allowed by 1 rules, disallowed by 0 rules
Tue May 22 11:46:34 2018 : (11)    attr_filter.access_challenge.post-auth (updated)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (4)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (... -1) module returned (updated 4)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - over-riding result from higher priority to (updated 4)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 3] -----
Tue May 22 11:46:34 2018 : (11)    [3] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           module
Tue May 22 11:46:34 2018 : (11)      name           handled
Tue May 22 11:46:34 2018 : (11)      debug_name     handled
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         updated
Tue May 22 11:46:34 2018 : (11)      priority       4
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           send
Tue May 22 11:46:34 2018 : (11)      debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 3] -------
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval >> module
Tue May 22 11:46:34 2018 : (11)    [3] unlang_module - handled (always)
Tue May 22 11:46:34 2018 : (11)    handled (handled)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_frame_eval << calculate-result (-1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - have (updated 4) module returned (handled -1)
Tue May 22 11:46:34 2018 : (11)    ** [3] unlang_calculate_result - action says to return with (handled 0)
Tue May 22 11:46:34 2018 : (11)    ----- Begin stack debug [depth 2] -----
Tue May 22 11:46:34 2018 : (11)    [2] Frame contents
Tue May 22 11:46:34 2018 : (11)      type           group
Tue May 22 11:46:34 2018 : (11)      name           send
Tue May 22 11:46:34 2018 : (11)      debug_name     send Access-Challenge
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         ...
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [1] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      yes
Tue May 22 11:46:34 2018 : (11)      result         noop
Tue May 22 11:46:34 2018 : (11)      priority       -1
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    [0] Frame contents
Tue May 22 11:46:34 2018 : (11)      instruction = NULL
Tue May 22 11:46:34 2018 : (11)      next           <none>
Tue May 22 11:46:34 2018 : (11)      top_frame      no
Tue May 22 11:46:34 2018 : (11)      result         reject
Tue May 22 11:46:34 2018 : (11)      priority       0
Tue May 22 11:46:34 2018 : (11)      unwind         0
Tue May 22 11:46:34 2018 : (11)      repeat         no
Tue May 22 11:46:34 2018 : (11)    ----- End stack debug [depth 2] -------
Tue May 22 11:46:34 2018 : (11)  } # send Access-Challenge (handled)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - have (... -1) module returned (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_calculate_result - action says to return with (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [2] unlang_run - done current subsection with (handled 0)
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 1] -----
Tue May 22 11:46:34 2018 : (11)  [1] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      yes
Tue May 22 11:46:34 2018 : (11)    result         noop
Tue May 22 11:46:34 2018 : (11)    priority       -1
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 1] -------
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - over-riding stack->result from higher priority to (handled 0)
Tue May 22 11:46:34 2018 : (11)  ** [1] unlang_run - interpreter exiting, returning handled
Tue May 22 11:46:34 2018 : (11)  ----- Begin stack debug [depth 0] -----
Tue May 22 11:46:34 2018 : (11)  [0] Frame contents
Tue May 22 11:46:34 2018 : (11)    instruction = NULL
Tue May 22 11:46:34 2018 : (11)    next           <none>
Tue May 22 11:46:34 2018 : (11)    top_frame      no
Tue May 22 11:46:34 2018 : (11)    result         reject
Tue May 22 11:46:34 2018 : (11)    priority       0
Tue May 22 11:46:34 2018 : (11)    unwind         0
Tue May 22 11:46:34 2018 : (11)    repeat         no
Tue May 22 11:46:34 2018 : (11)  ----- End stack debug [depth 0] -------
Tue May 22 11:46:34 2018 : (11)  Saving &session-state
Tue May 22 11:46:34 2018 : (11)    &session-state:Session-State-User-Name = "systemn"
Tue May 22 11:46:34 2018 : State ID 8 created, value 0x3f9f781499b41d2b50289f378de187e4, expires 15s
Tue May 22 11:46:34 2018 : (11)  RADIUS State - saved
Tue May 22 11:46:34 2018 : (11)  Sent code 11 Id 131 from 192.168.1.169:1812 to 192.168.1.2:44165 via enp2s0 length 0
Tue May 22 11:46:34 2018 : (11)    Message-Authenticator = 0x00000000000000000000000000000000
Tue May 22 11:46:34 2018 : (11)    EAP-Message = 0x01fb001604107460322ee07c3ae8e1f889dfb6a43dc1
Tue May 22 11:46:34 2018 : (11)    State = 0x3f9f781499b41d2b50289f378de187e4
Tue May 22 11:46:34 2018 : (11)  done request
stk: src/protocols/radius/encode.c:1560: Currently in fr_radius_encode_pair
stk: src/protocols/radius/encode.c:1560: > [0] octets: Message-Authenticator, vendor: 0x0 (0), attr: 0x50 (80)

stk: src/protocols/radius/encode.c:1440: Currently in encode_rfc_hdr
stk: src/protocols/radius/encode.c:1440: > [0] octets: Message-Authenticator, vendor: 0x0 (0), attr: 0x50 (80)

		50 12 ...
stk: src/protocols/radius/encode.c:1568: Currently in fr_radius_encode_pair
stk: src/protocols/radius/encode.c:1568: > [0] octets: EAP-Message, vendor: 0x0 (0), attr: 0x4f (79)

stk: src/protocols/radius/encode.c:1035: Currently in encode_concat
stk: src/protocols/radius/encode.c:1035: > [0] octets: EAP-Message, vendor: 0x0 (0), attr: 0x4f (79)

		4f 02  hex: src/protocols/radius/encode.c:1059: -- Done concat --
hex: src/protocols/radius/encode.c:1059: 0000: 01 fb 00 16 04 10 74 60 32 2e e0 7c 3a e8 e1 f8 
hex: src/protocols/radius/encode.c:1059: 0010: 89 df b6 a4 3d c1 
stk: src/protocols/radius/encode.c:1560: Currently in fr_radius_encode_pair
stk: src/protocols/radius/encode.c:1560: > [0] octets: State, vendor: 0x0 (0), attr: 0x18 (24)

stk: src/protocols/radius/encode.c:1440: Currently in encode_rfc_hdr
stk: src/protocols/radius/encode.c:1440: > [0] octets: State, vendor: 0x0 (0), attr: 0x18 (24)

stk: src/protocols/radius/encode.c:1092: Currently in encode_rfc_hdr_internal
stk: src/protocols/radius/encode.c:1092: > [0] octets: State, vendor: 0x0 (0), attr: 0x18 (24)

stk: src/protocols/radius/encode.c:606 : Currently in encode_value
stk: src/protocols/radius/encode.c:606 : > [0] octets: State, vendor: 0x0 (0), attr: 0x18 (24)

		18 12  hex: src/protocols/radius/encode.c:1125: -- Done RFC header --
hex: src/protocols/radius/encode.c:1125: 0000: 3f 9f 78 14 99 b4 1d 2b 50 28 9f 37 8d e1 87 e4 

Tue May 22 11:46:34 2018 : (11)  proto_radius encode packet
  Code:		Access-Challenge
  Id:		131
  Length:	80
  Vector:	a43d422628fea7de23035fa3e644e378
		50  12  df 24 b4 6a e5 17 92 e2 44 81 92 a3 ec d9 aa 1e 
		4f  18  01 fb 00 16 04 10 74 60 32 2e e0 7c 3a e8 e1 f8 
			89 df b6 a4 3d c1 
		18  12  3f 9f 78 14 99 b4 1d 2b 50 28 9f 37 8d e1 87 e4 
Tue May 22 11:46:34 2018 : (11)  finished request.
Tue May 22 11:46:34 2018 : freeing request
Tue May 22 11:46:34 2018 : Ready to process requests
Tue May 22 11:46:34 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:34 2018 : 	requests 12, decoded 12, replied 12 active 0
Tue May 22 11:46:34 2018 : data <--
Tue May 22 11:46:34 2018 : received reply 12
Tue May 22 11:46:34 2018 : Sending reply to socket 16
Tue May 22 11:46:34 2018 : 	checking timeouts
Tue May 22 11:46:34 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:34 2018 : Waking up in 4.9 seconds.
Tue May 22 11:46:34 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:34 2018 : 	requests 12, decoded 12, replied 12 active 0
Tue May 22 11:46:34 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:34 2018 : 	--> data
Tue May 22 11:46:34 2018 : 	--> empty-ack
Tue May 22 11:46:34 2018 : 	checking timeouts
Tue May 22 11:46:34 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:34 2018 : Waking up in 4.9 seconds.
Tue May 22 11:46:34 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:34 2018 : 	requests 12, decoded 12, replied 12 active 0
Tue May 22 11:46:34 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:39 2018 : TIMER - proto_radius_udp - cleanup delay for ID 131
Tue May 22 11:46:39 2018 : 	checking timeouts
Tue May 22 11:46:39 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:39 2018 : Ready to process requests
Tue May 22 11:46:39 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:39 2018 : 	requests 12, decoded 12, replied 12 active 0
Tue May 22 11:46:39 2018 : Worker 0 was sleeping, not re-signaling



enDDDDDdddddddddddddddddddddddddddddddddddddd


^CTue May 22 11:47:07 2018 : 	checking timeouts
Tue May 22 11:47:07 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:47:07 2018 : Ready to process requests
Tue May 22 11:47:07 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:47:07 2018 : 	requests 12, decoded 12, replied 12 active 0
Tue May 22 11:47:07 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:47:07 2018 : Signalled to terminate
Tue May 22 11:47:07 2018 : 	checking timeouts
Tue May 22 11:47:07 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:47:07 2018 : Exiting normally
Tue May 22 11:47:07 2018 : Worker cleaning up xlat thread instance (0x2b710f0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up xlat thread instance (0x2b71330/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up xlat thread instance (0x2b71210/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up xlat thread instance (0x2b70fd0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up dynamic_clients thread instance data (0x2b606d0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up unix thread instance data (0x2b709b0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up exec thread instance data (0x2b61ea0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up eap thread instance data (0x2b61520/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up attr_filter thread instance data (0x2b60210/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up attr_filter thread instance data (0x2b5fe80/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up attr_filter thread instance data (0x2b600e0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up cache thread instance data (0x2b60470/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up attr_filter thread instance data (0x2b5ffb0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up radutmp thread instance data (0x2b70180/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up logintime thread instance data (0x2b619e0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up exec thread instance data (0x2b60e90/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up radutmp thread instance data (0x2b6fb90/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up eap thread instance data (0x2b60b00/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up linelog thread instance data (0x2b618b0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up soh thread instance data (0x2b6ff20/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up stats thread instance data (0x2b702b0/0x2b70350)
Tue May 22 11:47:07 2018 : Worker cleaning up radius thread instance data (0x2b625c0/0x2b62660)
Tue May 22 11:47:07 2018 : Worker cleaning up detail thread instance data (0x2b60800/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up files thread instance data (0x2b612c0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up linelog thread instance data (0x2b61780/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up attr_filter thread instance data (0x2b5fd50/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up expr thread instance data (0x2b61060/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b6fcc0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b61fd0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b61190/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up passwd thread instance data (0x2b60d60/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b70cb0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b61650/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b70b80/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b61c40/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up pap thread instance data (0x2b62230/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up pam thread instance data (0x2b62100/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b61d70/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up mschap thread instance data (0x2b61b10/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up sql thread instance data (0x2b70050/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up detail thread instance data (0x2b6fdf0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up detail thread instance data (0x2b60340/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up detail thread instance data (0x2b62360/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up detail thread instance data (0x2b62490/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up exec thread instance data (0x2b60c30/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up dhcpv4 thread instance data (0x2b60930/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up always thread instance data (0x2b613f0/(nil))
Tue May 22 11:47:07 2018 : Worker cleaning up chap thread instance data (0x2b605a0/(nil))
Tue May 22 11:47:07 2018 : Freeing state tree 0x2b39d40
Tue May 22 11:47:07 2018 : State ID 8 unlinked
Tue May 22 11:47:07 2018 : Freeing request data 0x2bfabc0 (eap_session_t) at (nil):1 via destructor
Tue May 22 11:47:07 2018 : Freeing eap_session_t 0x2bfabc0
Tue May 22 11:47:07 2018 : State ID 8 freed
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Removing connection pool
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (6)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (5)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (4)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (3)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (2)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (1)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql (sql) - Closing connection (0)
Tue May 22 11:47:07 2018 : rlm_sql_mysql - Socket destructor called, closing socket
Tue May 22 11:47:07 2018 : rlm_sql_mysql unloaded.  Handle address 0x2a22110, symbol address 0x7fcd5742b3c0
Tue May 22 11:47:07 2018 : rlm_sql unloaded.  Handle address 0x2a177b0, symbol address 0x7fcd576393e0
Tue May 22 11:47:07 2018 : rlm_mschap unloaded.  Handle address 0x2a10c90, symbol address 0x7fcd578482c0
Tue May 22 11:47:07 2018 : rlm_dhcpv4 unloaded.  Handle address 0x29cd470, symbol address 0x7fcd57c5a140
Tue May 22 11:47:07 2018 : rlm_expiration unloaded.  Handle address 0x29cc240, symbol address 0x7fcd57e5e140
Tue May 22 11:47:07 2018 : rlm_pap unloaded.  Handle address 0x29ca7e0, symbol address 0x7fcd5806a600
Tue May 22 11:47:07 2018 : rlm_pam unloaded.  Handle address 0x29c8840, symbol address 0x7fcd586a30c0
Tue May 22 11:47:07 2018 : rlm_always unloaded.  Handle address 0x29ba680, symbol address 0x7fcd588a6080
Tue May 22 11:47:07 2018 : rlm_passwd unloaded.  Handle address 0x29b7bb0, symbol address 0x7fcd58aac100
Tue May 22 11:47:07 2018 : rlm_expr unloaded.  Handle address 0x29b3370, symbol address 0x7fcd58cb8460
Tue May 22 11:47:07 2018 : rlm_chap unloaded.  Handle address 0x29b1e00, symbol address 0x7fcd58ebd200
Tue May 22 11:47:07 2018 : rlm_detail unloaded.  Handle address 0x29af200, symbol address 0x7fcd590c3300
Tue May 22 11:47:07 2018 : rlm_radius_udp unloaded.  Handle address 0x29a7c80, symbol address 0x7fcd592d3600
Tue May 22 11:47:07 2018 : rlm_radius unloaded.  Handle address 0x29a51a0, symbol address 0x7fcd594ddb20
Tue May 22 11:47:07 2018 : rlm_utf8 unloaded.  Handle address 0x29a40a0, symbol address 0x7fcd596e0060
Tue May 22 11:47:07 2018 : rlm_files unloaded.  Handle address 0x29a1400, symbol address 0x7fcd598e5180
Tue May 22 11:47:07 2018 : rlm_soh unloaded.  Handle address 0x299fda0, symbol address 0x7fcd59ae9240
Tue May 22 11:47:07 2018 : rlm_stats unloaded.  Handle address 0x299e880, symbol address 0x7fcd59cee120
Tue May 22 11:47:07 2018 : rlm_digest unloaded.  Handle address 0x299d670, symbol address 0x7fcd59ef4340
Tue May 22 11:47:07 2018 : rlm_linelog unloaded.  Handle address 0x29907a0, symbol address 0x7fcd5a0fc240
Tue May 22 11:47:07 2018 : rlm_logintime unloaded.  Handle address 0x298bc60, symbol address 0x7fcd5a302200
Tue May 22 11:47:07 2018 : rlm_radutmp unloaded.  Handle address 0x29890f0, symbol address 0x7fcd5a507100
Tue May 22 11:47:07 2018 : rlm_eap_sim unloaded.  Handle address 0x2986130, symbol address 0x7fcd5a930600
Tue May 22 11:47:07 2018 : rlm_eap_peap unloaded.  Handle address 0x29831e0, symbol address 0x7fcd5ab3a660
Tue May 22 11:47:07 2018 : rlm_eap_ttls unloaded.  Handle address 0x297f3e0, symbol address 0x7fcd5ad44540
Tue May 22 11:47:07 2018 : rlm_attr_filter unloaded.  Handle address 0x2973450, symbol address 0x7fcd5af49220
Tue May 22 11:47:07 2018 : rlm_client unloaded.  Handle address 0x2971e70, symbol address 0x7fcd5b14e160
Tue May 22 11:47:07 2018 : rlm_cache_rbtree unloaded.  Handle address 0x2a6d480, symbol address 0x7fcd5615f120
Tue May 22 11:47:07 2018 : rlm_cache unloaded.  Handle address 0x296eeb0, symbol address 0x7fcd5b3562e0
Tue May 22 11:47:07 2018 : rlm_unix unloaded.  Handle address 0x296d7f0, symbol address 0x7fcd5b55b380
Tue May 22 11:47:07 2018 : rlm_exec unloaded.  Handle address 0x296b1a0, symbol address 0x7fcd5b75f0c0
Tue May 22 11:47:07 2018 : rlm_eap_tls unloaded.  Handle address 0x29688e0, symbol address 0x7fcd5b963360
Tue May 22 11:47:07 2018 : rlm_eap_mschapv2 unloaded.  Handle address 0x29664b0, symbol address 0x7fcd5bb6a5e0
Tue May 22 11:47:07 2018 : rlm_eap_gtc unloaded.  Handle address 0x2964d90, symbol address 0x7fcd5bd6e2c0
Tue May 22 11:47:07 2018 : rlm_eap_md5 unloaded.  Handle address 0x2963f50, symbol address 0x7fcd5bf73160
Tue May 22 11:47:07 2018 : rlm_eap unloaded.  Handle address 0x29615b0, symbol address 0x7fcd5c38f360
Tue May 22 11:47:07 2018 : rlm_unpack unloaded.  Handle address 0x2960310, symbol address 0x7fcd5c5930e0
```
