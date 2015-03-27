##Section 0: Readme
####l4d2-tourney-rules
This file provides a standardized ruleset for Left 4 Dead 2
tournaments.

- [Homepage](https://github.com/Attano/l4d2-tourney-rules)

##Section 1: League administration

#####1.1 Staff

The League Director will be:
- [Dragon](http://steamcommunity.com/id/dragonchowmein)

The Assistant League Director(s) will be:
- [Visor](http://steamcommunity.com/profiles/76561198009400276/)

#####1.2 Disputes
The League directors are the arbiters and court of last resort for
all disputes. Their decisions are final and cannot be appealed.

#####1.3 Sanctions
The League directors reserve the right to impose any sanction on any
team or individual player at their sole discretion as circumstances may
warrant.

#####1.4 Conflicts of interest
Staff may participate in the league. Where there may be an
appearance of a conflict of interest, a league director will yield
to a counterpart if possible.

#####1.5 Official communication
Official communication will take place via [the official cup group](http://steamcommunity.com/groups/eqcup2) and [forum on L4Dnation.com](http://www.l4dnation.com/community-news/eq-nations-world-cup-2014/).

#####1.6 Changes
The league directors reserve the right to make any changes or updates deemed necessary regarding anything to do with the league.

#####1.7 Server bans
The league directors do not have the authority to demand server admins rescind player bans on their servers if a banned player is trying to play a match. It is to the server admin's discretion whether the player's ban may be temporarily rescinded.

##Section 2: League format, standings, and tiebreaks

#####2.1 Format
This will be an international league comprising an even number of competing teams. On the league table, a match win will score 3 points; a tie scores 1 point; a loss or forfeit scores 0 points. Because this is a league format, there will be no secondary phase or elimination brackets.

######2.1.1 Pairings
All teams will play each other once in the international league, the order in which they play each other is completely arbitrary and is determined throughout the league's duration regardless of the respective performances of all the teams. 

######2.1.2 Double jeopardy
Under no circumstances will two competitors face each other more than once during the entirety of the league.

######2.1.3 Awarding a bye
In the event that a round must be paired with an uneven number of participants, a bye will be awarded at random to any one of the remaining teams.

######2.1.4 Tiebreakers
If more than one team has achieved the same amount of points when the league season has concluded, ties in the league table will be decided by which teams have the higher average score per map (ASPM) which is calculated by taking the sum of all the total scores accumulated and then dividing that tally by the number of individual maps (4 or 5 maps per campaign) to give the ASMP.

#####2.2 Deadlines
All teams must schedule and play their matches within the deadline. 

Unless teams make the effort to communicate with the admins to explain any potential difficulties within reasonable time of the deadline, there will be a *ZERO TOLERANCE* policy for matches that remain unscheduled or unreported past the round deadline.

#####2.3 Maps
- Dead Center
- Dark Carnival
- Swamp Fever
- Hard Rain
- The Parish
- No Mercy
- Death Toll
- Dead Air
- Blood Harvest
- Detour Ahead
- Haunted Forest
- Open Road

All listed custom campaigns can be downloaded [here.](http://31.186.250.11/addons/)

######2.3.2 Finales
Finales are optional; it is the choice of the home team to decide if finales are played. The only exception to this rule is on custom campaigns and Dead Center where it is mandatory to play finales.

##Section 3: Team registration

#####3.1 Registration
Teams may register by signing up [here.](http://steamcommunity.com/groups/eqcup2/discussions/0/540736965908236393/)

#####3.2 Double registration
Competitors may be registered for only one team in the league. A competitor who drops from a roster must explain to the league directors why they have left the team and wish to play for a different one. The player must gain admin approval and be aiming for a team with less than the maximum limit of 6 players, before being cleared to join a new team.

##Section 4: Servers
Game servers will be selected according to the following criteria:

#####4.1 Hosting
Servers must be chosen from the official server list.

#####4.2 Configuration
The server will have an up-to-date and working installation of the EQ 2.2 configuration and plugins.

#####4.3 Web-cast support
Servers will have enough slots for a minimum of one cameraman, one caster, a cup admin and/or
a server admin if one can be present. Support for the spechud addon is highly desirable.

#####4.4 Tickrate
Servers with tickrates ranging from 30-100 are allowed.

#####4.5 DOS protection
Servers with [DoS Protection](https://github.com/SirPlease/IPTables) are preferred.

#####4.6 Continental and international draws

#####4.6.1 Neutral Matches
Continental matches (EU vs EU, NA vs NA, etc) will be played on their respective home servers. International matches will be played on the most neutral server possible for both teams - the servers that offer the least amount of ping disparity between the two teams.

#####4.6.2 PCP
PCP = Ping Compensation Points - it's a system that further balances neutral games by recognising that one team is disadvantaged more than the other in terms of collective latency and thus compensates a team which would normally be faced with an uphill struggle and fighting a losing battle if it were playing a team of equal calibre with the palpable home advantage.

In international matches, one player from either team must go to console and type ping and then either take a screenshot, or copy-paste the information to a league admin. Note that the ping values displayed on the TAB menu are NOT the figures used for determining the true latency readings of each player and thus they are not valid when it comes to calculating PCP.

PCP will also be mandatory for a few continental matches but only if the ping disparity is great enough to justify it - if 3 players have yellow pings or 2 players have a minimum of one red and one yellow ping when the opposing team is comprised of at least 3 players with green ping, then PCP must be taken into account.

#####4.6.3 PCP Calculation
If there are no league admins available to help calculate the PCP bonus, then any player who takes the screenshot can do it. The basic formula for it is this followed by an example of how to determine the exact values:

(Total Latency of Away Team - Total Latency of Home Team) x Total Campaign Value = PCP

Away Team has players with: 150 ms, 123 ms, 101 ms and 136 ms = 510 ms of Total Latency
Home Team has players with: 66 ms, 59 ms, 50 ms and 45 ms = 220 ms of Total Latency

Now, 510 - 220 = 290 ms difference. 290 is this example's value of the first part of the formula. In order to determine the Total Campaign Value, we must equate the value of the ms difference to 1 so that we get a fair and accurate base for a campaign multiplier. Then, we equate the custom map distance of each individual map in a campaign to its decimal value (for example, a map of 500 distance points = 0.5 on the Total Campaign Value). This way, the system works regardless of whether teams choose to play finales or not. Let's pick Hard Rain as an example while taking the optional finale into consideration:

Base multiplier of 1 + (Map 1) 0.4 + (Map 2) 0.6 + (Map 3) 0.6 + (Map 4) 0.4 [+ (Map 5) 0.6] = 3 [3.6]

Now that we have the Total Campaign Value, we can complete the formula and work out what the PCP should be. So here goes the final formula:

(510 - 220) x 3 = 870 PCP - with the finale included, 290 x 3.6 = 1044 PCP

#####4.6.4 Ping Spikes
If a player is experiencing higher latency that is neither expected nor indicative of the connection from their location to the designated server, then both teams must wait until it has settled down before typing 'ping' in console and then starting the match. If the ping does not settle down but the team still wishes to continue fielding the player with the legitimately troublesome connection, their latency will be calculated to be the average of the other members of the team in order to proceed with PCP.

#####4.6.5 PCP Exploitation
If the admins suspect that any player or team is deliberately raising their latency artifically for the sole purpose of exploiting the PCP system to score extra compensation points that they are not entitled to, then the violation of this rule will constitute as an act of cheating and will be severely punished according to how the league directors deem fit. The penalty can range from match bans or league bans for individual players, or the outright disqualification of an entire team if there are multiple offenders deemed guilty of breaking this rule.

#####4.6.6 Allocated servers
Note: this table is still subject to change based on any further server testing carried out.

Region | Europe | Russia | North America | South America | Japan | Asia | Oceania  
--- | --- | --- | --- | --- | --- | --- | ---  
Europe | EUROPE | *Europe* | *East Coast* | *East Coast* | *Dallas* | *West Coast* | *West Coast*  
Russia | *Europe* | RUSSIA | *East Coast* | *East Coast* | *Chicago* | *Dallas/West Coast* | *West Coast* 
North America | *East Coast* | *East Coast* | CHICAGO/DALLAS | *East Coast* | *West Coast* | *West Coast* | *West Coast*  
South America | *East Coast* | *East Coast* | *East Coast* | *SA* | *West Coast* | *West Coast* | *West Coast*
Japan | *Dallas* | *Chicago* | *West Coast* | *West Coast* | JAPAN | *Asia* | *West Coast*
Asia | *Dallas* | *Chicago* | *West Coast* | *West Coast* | *Asia* | *Asia* | *West Coast*  
Oceania | *West Coast* | *West Coast* | *West Coast* | *West Coast* | *West Coast* | *West Coast* | *Oceania* 

SERVER = Continental Matches

*Server* = International Matches (PCP mandatory)


##Section 5: Match scheduling and match rules

#####5.1 Rounds and scheduling
Pairings for each round will be posted weekly on Monday.

Althought not mandatory, players can use the free online scheduling tool
at [doodle.com](http://doodle.com): it is free, functional, does not
require registration, and supports time zones.

######5.1.1 Scheduling deadline
Teams are encouraged to begin negotiating the schedule early; delinquent
scheduling must be brought to the attention of the staff before the
deadline.

######5.1.2 Reporting deadline
Results must be submitted, with a screenshot, by the following Sunday at
midnight. Failure to report weekly round results accompanied with a screenshot of the final score for confirmation, will be recorded in a score of 1-0 for the winning team instead of .

######5.1.3 Scheduling duties
Any player on the roster may perform scheduling duties.


#####5.2 Casting
The players agree that the matches may be casted according to the usual
process. Access to mumble servers for ‘war rooms’ is appreciated
but not required.

#####5.3 Spectators and admins

######5.3.1 Requests for Oversight
Any team may request that an admin be present at their match. The staff
will honour reasonable requests to the best of their ability, weighing
conflicting obligations, the significance of the match to the league
results, and the seriousness of concerns about improper behaviour that
may take place.

######5.3.2 Spectators
Aside from staff and authorised casters, no spectators whatsoever will
be allowed in the server during matches.

#####5.4 Ringers
Ringers are allowed, so long as they are not registered with another competing team. A player who has already been called as a ringer for another team, may only ring if the opposing team is fine with it. The minimum penalty for the violation of this rule will be an official warning to both the ringer and the team captain. The severity of the penalty may increase depending on certain circumstances which will be decided by the admins.

######5.4.1 Double agents
No registered competitor may ring for another team unless their team has
withdrawn from the league or they have been removed from the roster.

#####5.5 Pauses

######5.5.1 Excessive pausing
Intentionally affecting the result of the round through excessive
pausing may be brought to the attention of the league directors.

The penalty for abuse of the pause function can range from an official warning to a more severe form of punishment.

#####5.6 Screenshots and demos

######5.6.1 Demos are mandatory
Each participant is required to record and save demos of their match
play. All demos must be stored until the end of the league, and
must be submitted promptly to a league director on request.

######5.6.2 How-to record demos
To record a demo, open the console and type `record <demoname>`.  It is
not necessary to re-record after a map change, but it is necessary to
re-record after disconnecting from the server for any reason.

######5.6.3 Screenshots are mandatory
Each team is allowed up to one (1) pause per round to request
screenshots.

Each competitor must take a screenshot whenever asked by anyone in the
server.

######5.6.4 Demo investigations
Tournament administrators have the authority to request and investigate any demos
believed to contain footage of suspicious activity from any participant. Casters
and participants may request demos from another participant for the same reason,
as long as the casters and participants were in the same match that the supposed
moment(s) occured.

In the interests of good faith and vigilance, it is mandatory for the approached 
participant(s) to comply with this request. But no participant is obliged to hand over 
their demos to viewers or participants with no involvement in the specified match.

######5.6.5 Responsibility is with you
It is each competitor’s individual responsibility to ensure that demos
and screenshots are recorded, uncorrupted, and submitted in a timely
manner.

Failure to submit demos or screenshots on the request of the staff will
result at minimum in a zero score for the associated rounds, and
possible suspension of the player from the league.

#####5.7 Illegal techniques

######5.7.1 AI pathing exploits
It is illegal to intentionally exploit AI pathing by moving to an area
that causes NPC infected to stop attacking. This includes re-entering the
safe-room and standing behind a dynamic prop that the witch cannot
navigate around. However, is permitted to exploit witch pathing in a way
that causes her to climb over objects repeatedly.

The minimum penalty for intentionally exploiting AI pathing will be 500 points deducted.

######5.7.2 Tank parking
If an AI tank stops advancing for any reason, the survivors must be
notified in a reasonable time. Intentionally positioning a tank so that
it cannot advance when AI controlled is not allowed.

The minimum penalty for intentional tank parking will be an official warning for the one responsible. The maximum penalty will be decided by the league directors if deemed necessary.

######5.7.3 Spectating
Players may spectate if and only if they have unintentionally become
stuck in a clip brush or other entity and cannot move.

The minimum penalty for abuse of the spectate command will be an official warning for the one responsible. The maximum penalty will be decided by the league directors if deemed necessary.

#####5.8 Glitches

######5.8.1 Rescue vehicles
In the event of a finale rescue vehicle glitch (most common on Swamp
Fever, but also possible on Dark Carnival and Hard Rain) the half will
be replayed following a restart round. If necessary the final scores
will be calculated manually.

######5.8.2 Unclearable survivors
If a pinned survivor is unclearable after an infected player gains
control of the tank, either team can request that the round be
replayed. If requested, the league directors may review demos and
determine if the result of the replayed round will be used, or if some
other action will be taken according to the circumstances.

##Section 6: Addons and configuration
The following guidelines will assist the competitors in understanding
the intentions of the league directors. However, the league
directors may choose to sanction competitors for any addons or
modifications at their sole and arbitrary discretion (per Section 1.3).

All competitors are urged strongly to discuss any modifications with
the league directors to ensure they are fully in compliance with
the rules before making any changes. The best way to avoid the severe
penalties associated with bending or breaking these rules is to play
with a stock configuration.

#####6.1 Penalties
The minimum penalty for illegal modifications or addons is a forfeit
loss for the match. There is no maximum penalty, which may include team
expulsion from the league and forfeiture of already played matches.

#####6.2 Permitted modifications
The following modifications are PERMITTED:

######6.2.1 Menu
All modifications to the Left 4 Dead 2 user interface that do not alter,
nor interact with the in-game user experience, nor provide additional
information about the game state (e.g. ZoneMenu, menu music, menu fonts,
menu shortcuts, console fonts, etc) are allowed.

######6.2.2 HUDs
Modifying or removing HUDs, crosshairs, and pain pointers is allowed.

######6.2.3 Gun models
Modifying or removing gun models and reload animations is allowed.

######6.2.4 Tank music
Modifying or removing “tank music” including altering the volume is
allowed.

######6.2.5 Round end music
Modifying or removing music played at the end of the round after a wipe,
saferoom door closed, or player death is allowed.

######6.2.5 Blue tint
Modifying or removing the blue tint while spawning special infected in
“ghost mode” is allowed.

######6.2.6 Red tint
Modifying or removing the red tint that appears while spawned as special
infected or tank is allowed.

######6.2.7 Console variables ("cvars")
Source engine configuration files and scripts that do not exploit
“cheat” cvars, as noted on the official List of cvars, and do not
circumvent cvars blocked by the competitive configuration (e.g.
`mat_hdr`) are allowed.

######6.2.8 Command-line arguments
All command-line arguments that do not exploit nor allow the player to
exploit “cheat” cvars are allowed.

######6.2.9 GUI options
Any configuration setting that can be altered using the standard
in-game menu options or legal console variables is allowed.

#####6.3 Forbidden modifications
Aside from the above, no modifications to game files or materials, nor
use of third-party software and applications that affect gameplay will
be allowed, without the public, prior, and written authorization of the
tournament director(s). This includes but IS NOT LIMITED to:

######6.3.1 Visual elements
Any changes whatsoever to the stock survivor or infected models, map
textures, skyboxes, props, or other materials and files used for
rendering the in-game environment are forbidden.

######6.3.2 Audio elements
Any changes whatsoever to game sounds (excluding Sections 6.2.4-5) are
forbidden.

######6.3.3 Third-party hooks
Any third-party applications, programs, or macros that read or modify
memory in a method for affecting gameplay, or that provide information
about the game state to the player, or that simulate mouse movement
(aiming) while the game is running are forbidden.

######6.3.4 Wait commands
Any use of the wait commands is forbidden.

#####6.4 Lerp toggling
After the ready-up for the first half of the first map, changing `cl_interp`
and `cl_interp_ratio` values is forbidden for the remainder of the match. It is only permissable to toggle the values for any player when they have to reconnect to the server and reset the values to how they were before the first map went live. 

#####6.5 Addon toggling
Aside from exceptions provided in Section 6.2.1, enabling or disabling
addons or modifying files after the first ready-up is strictly
forbidden, even when disconnecting or reconnecting from the server.

#####6.6 Cheating

Any act of cheating (which includes any form of aim assistance, wallhacking, mathacking, speedhacking and more) will result in the offending individual player being banned from the remainder of the league regardless of whether it occurred during an official match or outside of it. If more than one player from the same team has been caught cheating during the duration of the league, then the entire team will be disqualified from the league. Any loopholes that are exercised due to potential lack of clarification in the rules and which the admins deem to be a violation of this rule, will be discussed and decided upon to the discretion of the league directors, while reserving the right to hand out similar penalties.

##Section 7: Behavior and etiquette

#####7.1 Conduct
Players are expected to conduct themselves politely and professionally
during the match. Abusive or harassing conduct toward other players,
spectators, or league administrators will not be tolerated.

#####7.2 Sound effects
Players may not use console commands or radial menus to trigger
sound-effects that taunt, harass, annoy, or confuse other players. This
includes but IS NOT LIMITED to:

* Survivor laughter or coughing vocalizations
* User-controlled special infected vocalizations of any kind whatsoever
* Survivor death sounds, or other vocalizations associated with player
  state or health (such as incapacitation or being “black and white”)
* Triggered vocalizations or sound effects associated with director
  events (such as the rescue vehicle’s arrival, etc)

#####7.3 Sprays
Players may not use sprays that imitate or resemble environmental
objects, such as: weapons, other players, infected models, props, or any
other recognizable game element.

Players may not use sprays that are grotesque, violent, obscene, or
depict other disturbing or offensive imagery such as pornography,
racist logos, or “shock” images.

<!--
vim: filetype=markdown wrapmargin=79
-->

####Legal
Copyright (C) 2014 by Ryan Delaney. Permission is granted to copy,
distribute and/or modify this document under the terms of the GNU Free
Documentation License, Version 1.3 or any later version published by the
Free Software Foundation; with no Invariant Sections, no Front-Cover
Texts, and no Back-Cover Texts. A copy of the license is included in the
file titled "LICENSE".

Valve, the Valve logo, Left 4 Dead, Left 4 Dead 2, Steam, and the Steam
logo are trademarks and/or registered trademarks of Valve Corporation.
All other trademarks are property of their respective owners.
