Extends the sequencing pattern with safety interlock logic: a latched fault state triggered by an e-stop, which can only be cleared by an operator reset while the e-stop is confirmed no longer active. The fault check runs unconditionally every scan, above the main sequence's CASE statement, so it can interrupt the process from any state.

Build Version: TwinCat3 Build 4024.78

Skills demonstrated: Safety-first logic design, latched fault states, unconditional interlock patterns (safety logic independent of normal program flow, a core IEC 61131-3 safety concept).
