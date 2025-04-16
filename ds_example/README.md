# ds_example

This is a copy of the code I received from the author (see <https://github.com/aZholtikov/zh_ds18b20>.) Getting this driver working was a bigger challenge than it should have been since the author provided detailed instructions.

Please note that initializing with `GPIO_NUM_2` maps to the pin D4 on the board. With that understood, the example works to collect one reading and then seems to hang. No attempt to debug this was performed.
