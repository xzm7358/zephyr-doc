:orphan:

.. title:: PINMUX_GALILEO_EXP1_NAME

.. option:: CONFIG_PINMUX_GALILEO_EXP1_NAME:
.. _CONFIG_PINMUX_GALILEO_EXP1_NAME:

The name of the GPIO expander labelled as EXP1 in the schematic.



:Symbol:           PINMUX_GALILEO_EXP1_NAME
:Type:             string
:Value:            ""
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Name of the GPIO expander 1" if PINMUX && BOARD_GALILEO (value: "n")
:Default values:

 *  "EXP1"
 *   Condition: PINMUX && BOARD_GALILEO (value: "n")
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 PINMUX && BOARD_GALILEO (value: "n")
:Locations:
 * ../boards/x86/galileo/Kconfig:29