![](https://komarev.com/ghpvc/?username=ywqd&color=bb2527&abbreviated=true)
<img src="https://img.shields.io/badge/dynamic/json?&label=Stars&color=bb2527&style=flat&query=%24.stars&url=https://api.github-star-counter.workers.dev/user/ywqd" alt="Profile Stars">
<img src="https://img.shields.io/badge/dynamic/json?&label=Forks&color=bb2527&style=flat&query=%24.forks&url=https://api.github-star-counter.workers.dev/user/ywqd" alt="Profile Forks">

```nasm
; profile.asm

section .data
user        db "00ie"
role        db "Senior Ethical Hacker | Senior Cyber Security Specialist"

systems     db "arch linux (favorite) | windows | nyarch linux"
langs       db "js | ts | py | c# | go | nim | rust | bash"

focus       db "systems | security | research (senior level)"

section .text
_start:
    mov rax, focus
    xor rbx, rbx        ; no distractions
    ret
```
