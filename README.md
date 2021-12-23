# DeltaruneDocuments
<h1><i>NOTE: This is only for chapter 1.</i></h1>
<h1>Links</h1>
<p>Before you start reading, you will need these two things if you wish to do any of this.</p>
<p>1: <a href="https://www.cheatengine.org/">Cheat Engine</a> (I usually call it CE)</p>
<p>2: <a href="https://deltarune.com/">Deltarune</a></p>
<h1>Key</h1>
<h3>One run = Me playing for 200+ minutes, and waiting ~a day before the next run.</h3>
<h1>Tips on using CE with Deltarune:</h1>
<p>Always search using the scan type "Double". If you can not find the variable when you search with Double, check again, and then search for "All".</p>
<p>For your first search on charatcer stats, you should search from 0000000000000000 to 0000f77777777777 (easiest way to remember is 16 0's and 11 7's), but when you figure out where at least 2 of your character stats are stored, you should search from at least 1 letter <b>before</b> the second character, with zeroes at the end of the number, and for the end, at least 1 letter <b>after</b> the second character, with zeroes at the end. An example is shown below:</p>
<p>If my character stats were stored at 0E305D80 and 0E3055F0, I'd search from 0D300000 and 0F300000.</p>

  <h1>Ideas for this project:</h1>
<p>I know that I name stuff terribly, if you have any better names for this stuff, please change them.</p>
<p>If you have any ideas for this, I will gladly accept them! This project needs a lot of improvement.
  <h1>Information on variables:</h1>
 <h2>D$</h2>
<p>D$ is stored differently from character stats, EX: In this run, character stats are stored from 0E305600-700, but D$ is stored at 09F287A0.</p>
<p>(During run 2) D$ was last stored at 09F287A0, but is (next time opening) now stored at 09F287C0. It seems to be kinda persistent.</p>
<p>Another note, I have set my D$ to be 23+ numbers long, and the game did not crash for me.<p>
<p>Here is where D$ was stored across 3 runs.</p>
<p>1: 09F287C0</p>
<p>2: 09F287C0</p>
<p>3: 09F287A0</p>

 <h2>Fonts</h2>
<!----2: 0B20E330---->
<p>Some more info on Fonts. (*=works)</p>
 <p>(This does NOT change the font for all menus.)</p>
<p>1: *</p>
<p>2: *</p>
<p>3: *</p>
<p>4: *</p>
<p>5: *</p>
<p>6: *</p>
<p>7: *</p>
<p>8: *</p>
<p>9: *</p>
<p>10: *</p>
<p>11: *</p>
<p>12: *</p>
<p>13: Only numbers show, decently sized numbers.</p>
<p>14: Only numbers, in gold.</p>
<p>15: Only numbers, same as 14 but smaller and isn't in gold.</p>
<p>16: Same as 13.</p>
<p>17: Same as 15.</p>
<p>18: *</p>
<p>19+: Same as 18.</p>
 <p><h2>Selected on CMenu</h2></p>
<p><h4>This is basically which slot you have selected on the menu. What the value means (and how to find it) is here:</h4></p>
<p>0: Item, the first one shown.</p>
<p>1: Equip, the second one shown.</p>
<p>2: Talk, not shown but maybe it'll be used later on.</p>
<p>3: Power, third one shown.</p>
<p>4: Config, fourth and last one shown.</p>
<p>5+: 5 restarts to 0, 6=1, 7=2, 8=3, etc.</p>
<!----<p><h4>Here is where it was stored across runs:</h4></p>
<p>Run 3: 0C29BE00---->
 <h2>First, Second, and Third Party Member</h2>
<p><b>WARNING:<i> If you set any of these to 4+, your game will crash. Be careful when setting these variables.</i></b></p>
<p>There are three options for setting these variables: 1 (Kris), 2 (Susie), and 3 (Ralsei). Anything else <b>will</b> crash your game.</p>
<h4>Here is where they were stored:</h4>
<p>First Party Member:</p>
<p>0E305D80 (2nd run)</p>
<p>0E305C80 (3rd run)</p>
<p>Second Party Member: </p>
<p>0E305C90 (3rd run)</p>


 <h2>Ralsei's Variables</h2>
<h3>I'm only putting these down becuase everyone else's variables are stored similarly (if not exactly) like Ralsei's.</h3>
<h3>Just like D$, I have set all of these vairables (on all characters) to be 23+ numbers long, even infinite - and the game has not broke for me.</h3>
<h4></i>(Numbers=Run#)</i></h4>
<p>Ralsei's Maximum HP</p>
<p>1: 0E2755B0</p>
<p>2: 0C29BA30</p>
<p>3: 0E3055B0</p>
<p>Ralsei's Current HP</p>
<p>1: 0E2755F0</p>
<p>2: 0C29BC30</p>
<p>3: 0E3055F0</p>
<p>Ralsei's Attack</p>
<p>1: 0E275570</p>
<p>2: 0C29B830</p>
<p>3: 0E305570</p>
<p>Ralsei's Defense</p>
<p>1: 0E275530</p>
<p>2: 0C29E230</p>
<p>3: 0E305530</p>
<p>Ralsei's Magic</p>
<p>1: 0E2754F0</p>
<p>2: 0C29E430</p>
<p>3: 0E3054F0</p>
  <h1>CE Layout</h1>
<h5><i><b>TIP: If you restart the game, you may have to redo every single one of these. Sometimes, it's better to keep it simple.</b></i></h5>
<p>Here the layout I use when I'm playing Deltarune with Cheat Engine. If anything has a '()' around it, it is a address. If it does not, it is a group.<b> It is also available for <a href=https://github.com/z5tm/DeltaruneDocuments/releases/latest>download<a>.</b></p>

-----------------------------------------

<p>Kai</p>
<p>&nbsp&nbsp  HP</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Current HP)</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Max HP)</p>
<p>&nbsp&nbsp  AT</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (AT)</p>
<p>&nbsp&nbsp  DF</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (DF)</p>
<p>Ralsei</p>
<p>&nbsp&nbsp  HP</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Current HP)</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Max HP)</p>
<p>&nbsp&nbsp  AT</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (AT)</p>
<p>&nbsp&nbsp  DF</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (DF)</p>
<p>&nbsp&nbsp  MG</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (MG)</p>
<p>Susie</p>
<p>&nbsp&nbsp  HP</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Current HP)</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (Max HP)</p>
<p>&nbsp&nbsp  AT</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (AT)</p>
<p>&nbsp&nbsp  DF</p>
<p>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp    (DF)</p>
<p>Misc</p>
<p>&nbsp&nbsp  (D$)</p>
<p>&nbsp&nbsp  (First Party Member),</p>
<p>&nbsp&nbsp  (Second Party Member),</p>
<p>&nbsp&nbsp  (Third Party Member),</p>
<p>&nbsp&nbsp  (Selected on CMenu),</p>
  
-----------------------------------------
