## bftictactoe
A 2 player game implementation of Tic Tac Toe using Brainfuck.

```
++++++++++++++++++++++++++++++++    ++++++++++++++++[->+>>>>>>>>>>+>    +>+>+>+>+>+>+>+]>[-+>]>>>>>>>>>+
>+>++>+++>++++>+++++>++++++>++++    +++>++++++++>+++++++++>+++++++++    ++++++++++++++++++++++++++++++++
++                            ++    ++++++++++++        ++++++++++++    +++++++++              +++++++++
++                            ++    +++++++++++          +++++++++++    ++++++                    +++++>
++                            ++    +++++++++++          +++++++++++    ++++                        ++++
++     +++++        ++>++     ++    ++++++++++++        ++++++++++++    +++     ++++++++++++++>+     +++
++   ++++[>>>>    >>>>>>>.>   >>    >>>>>>..>>>>>>>>..>>>>>>>>>>...>    ..    >.>..>>>>>>..>>>>>..    >>
>>>>>...>..>.>    ..>>>..>>..>>>    >.,>,[-]>>>>        >>>>>[-++>>>    >>   >>>>][->>>>>>>>>+]>---   --
--------------    --------------    -------------      --->+[>-[-]]>    [[   -][->+>+]>[-+>]>-----------
--------------    --------------    ---------->+[>    -[-]]>[[-]>>>>    >>   [-++>>>]+[>>>-[-]]>[[-]>>>[
-]++++++++++++    ++++++++++++++    ++++++++++++++    ++++++++++++++    ++   +++++++++++++++++++++++++++
+++++]>[-++>>]    +[>>-[-]]>[[-]    >>>[-]++++++++    ++++++++++++++    ++   +++++++++++++++++++++++++++
++++++++++++++    ++++++++++++++    ]+]]>>>>>>>>[-    ++>>>>>>>>>>][    ->   >>>>>>>>>+]>---------------
--------------    --------------    ------->+[>-[-    ]]>[[-][->+>+]    >[   -+>]>----------------------
--------------    --------------    >+[>-[-]]>[[-]    >>>>>>[-++>>>]    +[   >>>-[-]]>[[-]>>>>[-]+++++++
++++++++++++++    ++++++++++++++    ++++++++++++++    ++++++++++++++    ++   +++++++++++++++++++++++]>[-
++>>]+[>>-[-]]    >[[-]>>>>[-]++    ++++++++++++++    ++++++++++++++    ++   +++++++++++++++++++++++++++
++++++++++++++    ++++++]+]]>>>>    >>>>>[-++>>>>>    >>>>>>][->>>>>    >>   >>>>+]>--------------------
--------------    --------------    --->+[>-[-]]>[    [-][->+>+]>[-+    >]   >--------------------------
--------------    ----------->+[    >-[-]]>[[-]>>>    >>>[-++>>>]+[>    >>   -[-]]>[[-]>>>>>[-]+++++++++
++++++++++++++    ++++++++++++++    ++++++++++++++    ++++++++++++++    ++   +++++++++++++++++++++]>[-++
>>]+[>>-[-]]>[    [-]>>>>>[-]+++    ++++++++++++++    ++++++++++++++    ++   +++++++++++++++++++++++++++
++++++++++++++    +++++]+]]>>>>>    >>>>>[-++>>>>>    >>>>>>>][->>>>    >>   >>>>>>+]>------------------
--------------    --------------    ------>+[>-[-]    ]>[[-][->+>+]>    [-   +>]>-----------------------
--------------    --------------    ->+[>-[-]]>[[-    ]>>>>>>[-++>>>    ]+   [>>>-[-]]>[[-]>>>>>>[-   ]+
++++++++++++++    ++++++++++++++    ++++++++++++++    ++++++++++++++    ++    ++++++++++++++++++++    ++
+++++++]>[-++      >>]+[>>-[-]]>    [[-]>>>>>>[-]      +++++++++++++    +++     ++++++++++++++++     +++
+++++++++++++      +++++++++++++    +++++++++++++      +++++]+]]>>>>    >>>>                        >>>[
-++>>>>>>>>>        >>>>][->>>>>    >>>>>>>>+]>-        ------------    ------                    ------
----------            ----------    -------->+            [>-[-]]>[[    -][->+>+]              >[-+>]>--
--------------------------------    ------------------->+[>-[-]]>[[-    ]>>>>>>[-++>>>]+[>>>-[-]]>[[-]>>
>>>>>[-]++++++++++++++++++++++++    ++++++++++++++++++++++++++++++++    ++++++++++++++++++++++++++++++++
                                                                                                        
                                                                                                        
                                                                                                        
                                                                                                        
]>[-++>>]+[>>-[-]]>[[-]>>>>>>>[-    ]+++++++++++++++++++++++++++++++    ++++++++++++++++++++++++++++++++
++++++++++++++++]+]]>>>>>>>>>>>>    [-++>>>>>>>>>>>>>>][->>>>>>>>>>>    >>>+]>--------------------------
--                            --    --------------    ---------->+[>    -[-]]>[[-              ][->+>+]>
[-                            +>    ]>-----------      -------------    ------                    ------
--                            --    -------------      ->+[>-[-]]>[[    -]>>                        >>>>
[-     ++>>>        ]+[>>     >-    [-]]>[[-]>>>        >>>>>[-]++++    +++     ++++++++++++++++     +++
++   +++++++++    +++++++++   ++    ++++++++++++   ++   ++++++++++++    ++    ++++++++++++]>[-++>>    ]+
[>>-[-]]>[[-]>    >>>>>>>[-]++++    +++++++++++    ++    +++++++++++    ++   ++++++++++++++++++++++   ++
++++++++++++++    +++++++++++]+]    ]>>>>>>>>>>   >>>[   -++>>>>>>>>    >>   >>>>>][->>>>>>>>>>>>>>>+]>-
--------------    --------------    ----------    ----    ----------    --   >+[>-[-]]>[[-][->+>+]>[-+>]
>-------------    --------------    ----------   ------   ----------    --   >+[>-[-]]>[[-]>>>>>>[-++>>>
]+[>>>-[-]]>[[    -]>>>>>>>>>[-]    +++++++++    ++++++    +++++++++    ++   +++++++++++++++++++++++++++
++++++++++++++    ++++++++++++++    +++++++]>   [-++>>]+   [>>-[-]]>    [[   -]>>>>>>>>>[-]+++++++++++++
++++++++++++++    ++++++++++++++    ++++++++    ++++++++    ++++++++    ++   ++++++++++++]+]]>>>>>>>>>>>
>>>[-++>>>>>>>    >>>>>>>>>][->>    >>>>>>>>   >>>>>>+]>-   --------    --   ---------------------------
--------------    ---->+[>-[-]]>    [[-][->    +>+]>[-+>]    >------    --   ---------------------------
--------------    ------->+[>-[-    ]]>[[-]   >>>>>>[-++>>   >]+[>>>    -[   -]]>[[-]>>>>>>>>>>[-]++++++
++++++++++++++    ++++++++++++++    ++++++    ++++++++++++    ++++++    ++   +++++++++++++++++++++++++++
+]>[-++>>]+[>>    -[-]]>[[-]>>>>    >>>>>>   [-]+++++++++++   ++++++    ++   +++++++++++++++++++++++++++
++++++++++++++    ++++++++++++++    +++++    ]+]]>>>>>>>>>>    >>>>>    [-   ++>>>>>>>>>>>>>>>>>][->>>>>
>>>>>>>>>>>>+]    >-------------    -----     ------------     -----    --   -------------------->+[>-[-
]]>[[-][->+>+]    >[-+>]>-------    -----                      -----    --   ---------------------------
----------->+[    >-[-]]>[[-]>>>    >>>[                        -++>    >>   ]+[>>>-[-]]>[[-]>>>>>>>>>>>
[-]+++++++++++    ++++++++++++++    ++++      ++++++++++++      ++++    ++   +++++++++++++++++++++++++++
++++++++++++++    ]>[-++>>]+[>>-    [-]]    >[[-]>>>>>>>>>>>    [-]+    ++   ++++++++++++++++++++++   ++
++++++++++++++    ++++++++++++++    +++    ++++++++++++++++++    +++    ]+    ]]>[[-]>>>>>>>>>>>>>    >>
>>>>+[->+>+]>[    -+>]+>--------    -[[    -]->][[-]+[-]>>>>>    >>>    >>>     >>>>>>>>>>>>>>]]     >>>
>>>[-++>>>>>>      ][->>>+]>>>>[    -++    >>>>>>][->>>>+]>>>    >>[    -++>                        >>>>
>][->>>>>+][        --->>][[-]+>    >]      [[-]+>]+>[[-]->]      [[    -][-][                    -]>>>]
>>>>>>>>>>            >[-++>>>>>    >>       >>][->>>>>>+]>       >>    >>>>[-++>              >>>>>>>>]
[->>>>>>>+]>>>>>>>>[-++>>>>>>>>>    ][->>>>>>>>+][--->>][[-]+>>][[-]    +>]+>[[-]->][[-][-][-]>>>]>>>>>>
>>>>>>>>[-++>>>>>>>>>>>>][->>>>>    >>>>+]>>>>>>>>>>[-++>>>>>>>>>>>>    ][->>>>>>>>>>+]>>>>>>>>>>>[-++>>
                                                                                                        
                                                                                                        
                                                                                                        
                                                                                                        
>>>>>>>>>>][->>>>>>>>>>>+][--->>    ][[-]+>>][[-]+>]+>[[-]->][[-][-]    [-]>>>]>>>>>>>>[-++>>>>>>][->>>+
]>>>>>>[-++>>>>>>>>][->>>>>>+]>>    >>>>>>>[-++>>>>>>>>>>][->>>>>>>>    >+][--->>][[-]+>>][[-]+>]+>[[-]-
>]                            [[    -][-][-]>              >>]>>>>>>    >>                           >[-
++                            >>    >>>>>]                    [->>>>    +]                           >>>
>>                            >>    [-++                        >>>>    >>>      >>][->>>>>>>+]>>    >>>
>>     >>>[-        ++>>>     >>    >>>     >>>][->>>>>>>>>>     +][    ---    >>][[-]+>>][[-]+>]+>  [[-
]-   >][[-][-]    [-]>>>]>>   >>    >>    >>>>[-++>>>>>>>>][->    >>    >>+   ]>>>>>>>>[-++>>>>>>>>>>][-
>>>>>>>>+]>>>>    >>>>>>>[-++>>>    >>   >>>>>>>][->>>>>>>>>>>+   ][    ---   >>][[-]+>>][[-]+>]+>[[-]->
][[-][-][-]>>>    ]>>>>>>>>[-++>    >>   >>>][->>>+]>>>>>>>[-++   >>    >>>   >>>>][->>>>>>>+]>>>>>>>>>>
>[-++>>>>>>>>>    >>>][->>>>>>>>    >>   >+][--->>][[-]+>>][[-]   +>    ]+>   [[-]->][[-][-][-]>>>]>>>>>
>>>>>[-++>>>>>    >>>][->>>>>+]>    >>   >>>>[-++>>>>>>>>>][->>   >>    >>>   +]>>>>>>>>>[-++>>>>>>>>>>]
[->>>>>>>>>+][    --->>][[-]+>>]    [[   -]+>]+>[[-]->][[-][-][   -]    >>>   ]]>>>>>>>>>>>.>>>>>>>>>..>
>>>>>>>..>>>>>    >>>>>...>..>.>    ..   >>>>>>..>>>>>..>>>>>>>   ..    .>.   .>.>..>>>..>>..>>>>.[-]+[[
-]>+++++++++++    ++++++++++++++    ++   ++++++++++++++++++++++   ++    +++   +++++++++++++ ++++++++++++
++++.---------    --.----.[-]]>[    [-   ]>>[-]++++++++++++++++   ++    +++     +++++++++   ++++++++++++
++++++++++++++    ++++++++++++++    ++   ++++++>[-]++++++++++++   ++    +++                 ++++++++++++
++++++++++++++    ++++++++++++++    ++   ++++++++++++++++++++>[   -]    +++                 ++++++++++++
++++++++++++++    ++++++++++++++    ++   ++++++++++++++++++++++   ++    +++     +++++++++   ++++++>[-]++
++++++++++++++    ++++++++++++++    ++   >[[-]+++++++++++++++++   ++    +++   +++++++++++++ ++++++++++++
++++++++++++++    ++++++++++++++    ++   +++++++++++.[-]]>[[-].   >>    >>]   ....]>>>>>>>>>>>>>>>>>>>>.
+-->+>>-++>>>>    +>>>++>++>>-++    -+   ->>>+>->+>+++++-+>>+>+   -+    ++-   +>>+++->->+-+-+++>+++>++>-
->>+>-+>+>+>>-    +---+>+->++---    ->   ++>-+>>>++>--->>>+>>>>   ++    -+-   -++++>+>>-+>>+>>->>>>->+++
++++>>+>--+>>+    ++>->+-+++>+++    +>   --+++>-+++>++++++>>>->   >+    >>+   ++>++>-+++->>-+++++++-+>+>
-+->+>+>+>+-+>    ->-++-++>>>---    ++   ++>-+>+>+>+---->++-+++   ++    +>+   +>>+++>+->+>+>>>+->>-+>-++
++++>-+>+>++++    ++---+>---+++-    -+   >>---+>-+->->-+>+>>>>+   -+    +++   +>+++>+>+--+++++-++++>>++>
+>+>+++>+++>>+    -+>+++>+->++->    +-    >->+>+-+>++>+++++>++    +>    >++   >>+>+>>+->+>->+-+++->+>+++
+-+++++>+>>>+>    -++>>+>+++>>++    >+-     -+>>-+-+-+-+->+-     +++    +++    +->++-+>++->+>++-+>+  +>+
+->+->--+>+++      >+->+++>>>+++    >++-                        -+>+    +++      +>++++>+++++->-+    ->-
+++>->++->++        ++++>++++-->    -+++->                    ++-+++    ++                           ++-
+->++->->>            +>+>>>>>++    +>+>->+++              +>>++>>>+    +>                           +>+
>++>--++++++>>+--++++->+>++>>++-    >-+-->+>>+>+>->+>>+>>++-++>->+>+    +--+>>>>++->>+-+>-+>>->>-+>++->-
+>+>--+->>>+>>--++>>-++-->+-++->    +>+>+->->+>>+>+>+->->>+++++-+-++    +++++>-->>++++>->++--+->>---++>>
```

## How to use:

Use your favorite Brainfuck compiler/interpreter on `source/tictactoe` to play the game. [Recommendation](https://github.com/iarba/bfcompiler)

The game also comes with a 64-bit Linux executable, which can be called using:
```
./tictactoe
```
## Game:

[https://en.wikipedia.org/wiki/Tic-tac-toe](https://en.wikipedia.org/wiki/Tic-tac-toe)

There are 2 players, X and O. X starts moving first, then the players start alternating. In order to make a move, insert a number between 1 and 9, representing the position on the map, and then press enter. If it is free, the player's symbol will be placed in that cell.

The first player to get 3 symbols in a line wins. In case nobody achieved that, but there aren't any possible moves, it's a TIE.
