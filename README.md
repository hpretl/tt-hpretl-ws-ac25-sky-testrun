![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg) ![](../../workflows/fpga/badge.svg)

# Tiny Tapeout Test Project by Harald Pretl

This is a tesrun project for the Tiny Tapeout workshop at Austrochip 2025. It implements a snake displayed on the 7-segment LED. It only uses `clk` (should be around 10kHz). The circuit is self-resetting after a few clock cycles to get into the correct more.

That's about it, it can do no more. Digital inputs and digital inouts are not used.

**Important information**: For some technology runs, `DFFSR` are not supported. It is best not to use them, only use `DFF` and implement synchronous set/reset operation via the data input.
