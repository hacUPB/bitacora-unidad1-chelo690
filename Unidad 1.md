# Unidad 1

## Sesion 1 y 2


//copiar una constante al registro D

@1954
D=A 
@23
D=D+A 


			@1
			D=A
			@2
			D=D+A
			@16
			M=D
(END)
			@END
			0;JMP  

## Sesion 3

@1000
D=A 
@i
M=D
(LOOP)
@i
D=M
@CONT
D;JEQ
@i
M=M-1
@LOOP
0;JMP
(CONT)
@CONT
0;JMP

## Sesion 4



## marcelo villegas