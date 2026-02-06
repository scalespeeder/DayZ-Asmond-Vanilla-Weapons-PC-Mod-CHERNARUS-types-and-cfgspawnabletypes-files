DayZ Asmond Vanilla Weapons PC Mod Chernarus types & cfgspawnabletypes xml Files Instructions,  Changelog & Terms Of Use

These files & code snippets will spawn the weapons included in Asmondians "Vanilla Weapons Mod" in the DayZ Chernarus Map, mimicking their Vanilla counterparts (but not replacing them.)

I WOULD CONSIDER THESE FILES A "STARTING POINT" TO GET THE WEAPONS SPAWNING AND ADVISE YOU CUSTOMIZE THEM TO YOUR NEEDS.

types created with the help of GROK AI.

Limited Testing on  PC Chernarus Local Server DAYZ Version 1.28 Feb 2026.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.


-----------------------

PLEASE CAREFULLY READ THE INSTRUCTIONS ON HOW TO INSTALL THESE FILES 

-----------------------


Subscribe to Asmond Vanilla Weapons Mod in the DayZ Steam Workshop:

https://steamcommunity.com/sharedfiles/filedetails/?id=3640419203

& install onto your server as you normally would a mod, rembering to copy the key to your servers key folder, and editing your startup .bat folder.

-----------------------

Stop your server.

To make the management of extra files easier, on your server create a "custom" folder inside the Chernarus Mission Folder  eg: mpmissions\dayzOffline.chernarusplus\custom

Now upload asmo-extra-cfgspawnabletypes.xml & asmo-extra-types.xml into that custom folder.

Next open up your vanilla cfgeconomycore.xml, and near the bottom, above the closing

</economycore>

tag,

paste this:

	<ce folder="custom">
	<file name="asmo-extra-types.xml" type="types" />
	<file name="asmo-extra-cfgspawnabletypes.xml" type="cfgspawnabletypes" />
	</ce>
	
If you already have some extra CE files listed, just paste in the extra lines:

	<file name="asmo-extra-types.xml" type="types" />
	<file name="asmo-extra-cfgspawnabletypes.xml" type="cfgspawnabletypes" />
	
	
Save the file and re-upload if necessary.

-----------------------
		

Restart your server & changes should start to take effect. 


GOOD LUCK!
