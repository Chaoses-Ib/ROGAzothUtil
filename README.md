# ROGAzothUtil
## Remapping
Azoth does not have Home and End keys. Instead, they can be triggered by `Fn + PgUp` and `Fn + PgDn`. However, this can be inconvenient if you need to use `Shift + Home` and `Shift + End` a lot. While you can remap them in Armoury Crate, but Fn functions cannot be remapped. Here is a software solution of this problem for Windows users:

Original | Remap 1 | Remap 2
--- | --- | ---
Ins (Pause) | PgUp (Ins) | Home (Ins)
Del (ScrLk) | PgDn (Del) | End (Del)
PgUp (Home) | Home (Pause) | PgUp (Pause)
PgDn (End) | End (ScrLk) | PgDn (ScrLk)

To apply remapping, download [remap1.ahk](remap1.ahk) or [remap2.ahk](remap2.ahk) and execute it via [AutoHotkey](https://www.autohotkey.com/).

<details><summary>Registry</summary>

Original | Remap 1 | Remap 2
--- | --- | ---
Ins (Pause) | PgUp (Pause[^pause]) | Home (Pause)
Del (ScrLk) | PgDn (Del) | End (Del)
PgUp (Home) | Home (Ins) | PgUp (Ins)
PgDn (End) | End (ScrLk) | PgDn (ScrLk)

To apply remapping:
1. Download [remap1.reg](reg/remap1.reg) or [remap2.reg](reg/remap2.reg) and execute it
2. Reboot

To unmap, download [unmap.reg](reg/unmap.reg) and execute it.

Todos:
- [ ] `Shift + Home` and `Shift + End` do not work
- [ ] Mutliple keyboards

</details>


[^pause]: Pause cannot be remapped: [windows - What is the scancode of "Pause/Break" key? - Stack Overflow](https://stackoverflow.com/questions/38846347/what-is-the-scancode-of-pause-break-key)