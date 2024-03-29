Siec
===

An interpreted Esoteric Programming Language

Project Setup
-
Each Siec project have to have a code.sc and an inst.sc file <br>
code.sc is where your code belongs<br>
In inst.sc you will write Line Numbers in Base20 that shoud be executed
Each Line Number can only have 2 Digits. This means that your code.sc is limited to jj₂₀ (399₁₀) lines

Benefits
-

* Easy to understand syntax
* Control over Execution via ins.sc
* Variable Names with whitespaces

Commands
-
Commands are used by flags:

| Flag      | Usage                                       | Format                 |
|-----------|---------------------------------------------|------------------------|
| -run      | Runs code.sc with inst.sc                   | siec -run              |
| -build    | Builds code.sc with inst.sc to compiled.scc | siec -build            |
| -runbuild | Runs a builded .scc file                    | siec -runbuild \<file> |


Instructions
-

| Command | Usage                     | Format                                                   |
|---------|---------------------------|----------------------------------------------------------|
| ,       | Println                   | ,\<Text/Variable>                                        |
| .       | Print                     | .\<Text/Value>                                           |
| ^       | Set variable              | ^<var_name>#Value                                        |
| -       | Subtracts from a variable | -<var_name>#<other_var/number>                           |
| +       | Adds to a variable        | +<var_name>#<other_var/number>                           |
| *       | Multiplies a variable     | *<var_name>#<other_var/number>                           |
| /       | Divides a variable        | /<var_name>#<other_var/number>                           |
| ?       | Simpele if line           | ?<!=/==>\<variable>#\<value_to_test>#<command_when_true> |
| ~       | Saves input to a variable | ~\<variable>                                             |