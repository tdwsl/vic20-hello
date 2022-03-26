A simple hello world program for the VIC20 - load with SYS4352

I made it in VICMON, so it doesn't really have any source code,
but here's a memory map:

$1000		- used during set cursor routine
$1020		- print colour
$1040-$104D	- hello world string
$1100		- entry point
$1200-$121D	- clear screen routine
$1220-$1258	- set cursor xy routine
$1260-$1279	- print char routine
$1280-$129A	- print string routine
