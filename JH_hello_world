; hello world
; By John Hammond (https://www.youtube.com/watch?v=HgEGAaYdABA&ab_channel=JohnHammond)
; with my comments

global _start

section .text:

_start:
    mov eax, 0x4    ; 0x4 = write syscall
    mov ebx, 1      ; ebx= file descriptor > stdout
    mov ecx, hello  ; hello is used as the buffer
    mov edx, hello_lenght  ; supply the lenght
    int 0x80    ; int = interrupt / 0x80 = identifier for running a syscall

    mov eax, 0x1  ; 0x1 = exit
    mov ebx, 0    ; return value, 0 = success
    int 0x80

section .data:
    hello: db "Hello World from ctc", 0xA
    hello_lenght equ $-hello
    
