GitHub_Messager
===============

Repo:	See <https://github.com/ImmortalPC/GitHub_contributions_calendar_Messager><br />
Author:	NUEL Guillaume (ImmortalPC)<br />
Date:	2013-12-20<br />


Description
-----------
This script displays a message in the contribution calendar.

![ScreenShot](https://raw.github.com/ImmortalPC/GitHub_contributions_calendar_Messager/master/Screenshot.png)


Licence
-------
	GNU GPLv2
	Copyright (C) 2014 ImmortalPC

	GitHub_Messager is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation; either version 2 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/gpl-2.0.html>.
	Or write to the Free Software
	Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA


Usage
-----
1. Make a new repo for this script ! (cf Warning)

2. Edit **GitHub_Messager.py** and change the content of **\_MSG_**<br />
The message must never have a size greater than 51.<br />
Furthermore, the message can not have a height greater than 7.<br />
'+' => commit<br />
'-' => nothings<br />

3. Exec this script:<br />
>	`./GitHub_Messager.py`

4. `git push`

5. Look at the result in your GitHub profile.


	!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
	/!\ WARNING /!\
	Do not forget, this script make commits !!! So use a repo only for this script.
	Github keeps a copy of commits !
	=> So it is impossible to delete a message that was displayed.
	In order to delete the message, you need to delete the concerned repo !

	Note 1: The contents of the modified file is random.
	Note 2: The commit message can be changed in _GIT_COMMIT_MSG_
	Note 3: The commit file can be changed in _GIT_FAKE_FILE_
	!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


Created By
----------
	ImmortalPC <http://immortal-pc.info>


Code Format and Standards
-------------------------
- The code is in UTF-8
- The code is indented with real tabs (\t)
- The code is intended to be displayed with a size of 4 for the tab (\t)
- The line endings type LF (\n)
- Comments are doxygen format.
