<!--

	DELTARUNE MapID/SAVE Information.

    Copyright (C) 2018 SiroQ

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

-->

# Attention
I'm not good at English, so If you found any bad English, open a issue or send a pull request, please.  
# DELTARUNE Save data
DELTARUNE's save data is stored in  
`%localappdata%\DELTARUNE`(Windows)  or
`/Users/YourUserName/Library/Application Support/com.tobyfox.deltarune`(Macintosh)   
(filech1_0 is save slot 1; filech1_1 is save slot 2; filech1_2 is save slot 3. filech1_3 - filech1_5 marks save slot completion, filech_9 is a temproary save file.)  
and, you can edit save data information in title screen by editing dr.ini.  
also, you can change language by editing true_config.ini.  
# Meaning of the value
- Line 1: Creator name  
- Line 2: Vessel name  
- Line 8: First member of party (1:Kris, 2:Susie, 3:Ralsei)  
- Line 9: Second member of party (1:Kris, 2:Susie, 3:Ralsei)  
- Line 10: Third member of party (1:Kris, 2:Susie, 3:Ralsei)  
- Line 11: D$
- Line 16: Event flag (0:Normal world, 1:Underground, Over 2:Unknown)  
- Line 71: Current HP of first party member  
- Line 72: Max HP of first party member  
- Line 73: Attack of first party member  
- Line 74: Defense of first party member  
- Line 75: Magic of first party member  
- Line 77: First item of first party member  
- Line 78: Second item of first party member  
- Line 79: Third item of first party member  
- Line 125: Current HP of second party member  
- Line 126: Max HP of second party member  
- Line 127: Attack of second party member  
- Line 128: Defense of second party member  
- Line 129: Magic of second party member  
- Line 131: First item of second party member  
- Line 132: Second item of second party member  
- Line 133: Third item of second party member  
- Line 179: Current HP of third party member  
- Line 180: Max HP of third party member  
- Line 181: Attack of third party member  
- Line 182: Defense of third party member  
- Line 183: Magic of third party member  
- Line 185: First item of third party member  
- Line 186: Second item of third party member  
- Line 187: Third item of third party member  
- Line 10316: Event flag (Set 0 for reset all event)  
- Line 10317: Current MAP ID ([MAP ID List](https://github.com/SiroQ/DELTARUNE/blob/master/MAP_EN.md))  
- Line 10318: Played time  
