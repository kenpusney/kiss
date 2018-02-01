# KISS: Scripting in Kernel Mode Done Right


## What

KISS is a compiler and a bytecode engine for kernel mode scripting. It provides 2 components:
a compiler to generate the bytecode on user mode and the execution engine on kernel mode.

Which would be very useful in driver development or kernel customization.

## How

KISS is just act as a glue to concatenate individual components in kernel mode and execute dynamically.
