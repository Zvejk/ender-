G90 ;  absolute positioning
G28 ; home all axis

G1 Z5 ; lift Z axis
G1 X30 Y30 ; Move to position LF
G1 Z0 ; Move to Z0
M0 ; Pause print 

G1 Z5 ; lift Z axis
G1 X205 Y205 ; Move to position RF
G1 Z0 ; Move to Z0
M0 ; Pause print 

G1 Z5 ; lift Z axis
G1 X205 Y205 ; Move to position RR
G1 Z0 ; Move to Z0
M0 ; Pause print 

G1 Z5 ; lift Z axis
G1 X30 Y30 ; Move to position LR
G1 Z0 ; Move to Z0
M0 ; Pause print 

G1 Z5 ; lift Z axis
G1 X117,5 Y117,5 ; Move to position C
G1 Z0 ; Move to Z0
M0 ; Pause print 

G28 ; home all axis 
M84 ;Disable motors
