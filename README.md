# EJERCICIO-MOV
mover registros
mov ax,8
mov bx,3
mov cl,7 ; divisor
div cl ; dividendo = ax ; divisor = cl
mov cx,ax ; guardar resultado y resto en cx
mov ax,bx ; multiplicando
mov bx,2 ; multiplicador
mul bx ; resultado en dx ax
ret
