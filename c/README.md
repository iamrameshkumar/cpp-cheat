# C

1.  Introduction
    1. [Standards](standards.md)
    1. [Implementations](implementations.md)
    1. [Undefined behaviour](undefined-behaviour.md)
    1. [Style guides](style-guides.md)
    1. [Linting tools](linting-tools.md)
    1. [Pros and cons](pros-and-cons.md)
    1. [Trivia](trivia.md)
    1. [Bibliography](bibliography.md)
1.  [main.c](main.c): huge dump that is being split up into smaller sections
1.  Sanity
    1. [hello_world.c](hello_world.c)
    1. [min.c](min.c)
    1. [template.c](template.c)
1.  Language
    1.  Data
        1.  [Identifier](identifier.c)
        1.  [void](void.c)
        1.  [Array](array.c)
            1. [String](string.c)
            1. [VLA](vla.c)
        1.  [Type qualifier](type_qualifier.c)
            1. [const](const.c)
            1. [restrict](restrict.c)
            1. [auto](auto.c)
            1. [register](register.c)
            1. [volatile](volatile.c)
        1.  User defined types
            1. [enum](enum.c)
            1. [typedef](typedef.c)
            1. [struct](struct.c)
            1. [union](union.c)
        1.  Compile time operations
            1.  [sizeof()](sizeof.c)
            1.  [_Generic](generic.c)
            1.  [Constant expression](constant_expression.c)
                1. [_Static_assert](static_assert.c)
    1.  [Function](function.c)
        1. [Function pointer](function_pointer.c)
        1. [inline](inline.c)
        1. [Static array argument](static_array_argument.c)
        1. [_Noreturn](noreturn.c)
    1.  [Preprocessor](preprocessor.c)
        1. [cpp](cpp.sh)
    1.  [Signal](signal.c)
    1.  Multi-file
        1.  [static](static.c)
        1.  [extern](extern.c)
1.  stdlib
    1.  [assert.h](assert_h.c)
        1. [NDEBUG](ndebug.c)
        1. [assert fail](interactive/assert_fail.c)
    1.  [stdio.h](stdio_h.c)
    1.  [stdint.h](stdint_h.c)
    1.  stdlib.h
        1. [malloc()](malloc.c)
        1. [exit()](exit.c)
        1. [atexit()](atexit.c)
        1. [abort()](interactive/abort.c.off)
    1.  stddef.h
        1. [offsetof()](offsetof.c)
    1.  [string.h](string_h.c)
    1.  [ctype.h](ctype_h.c)
    1.  [time.h](time_h.c)
        1. [clock()](interactive/clock.c)
    1.  [limits.h](limits_h.c)
    1.  [stdbool.h](stdbool_h.c)
    1.  [float.h](float_h.c)
    1.  [math.h](math_h.c)
    1.  [complex.h](complex_h.c)
    1.  [varargs_h](varargs_h.c)
    1.  [errno.h](errno_h.c)
    1.  [iso646.h](iso646_h.c)
1.  Applications
    1. [User input](interactive/user_input.c.off)
    1. [Design patterns](design_patterns.c)
    1. [Virtual memory](virtual_memory.c)
    1. [Profiling](interactive/profiling.c)