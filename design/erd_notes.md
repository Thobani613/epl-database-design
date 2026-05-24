Team

One Team has many Players
One Team has one Stadium
One Team has many Matches
One Team plays in many Competitions through a Season
One Team has one Manager

Player

One Player belongs to one Team currently
One Player has many Transfers
One Player has many MatchEvents
One Player has many PlayerStats records — one per season

Manager

One Manager manages one Team

Stadium

One Stadium hosts many Matches
One Stadium belongs to one Team

Season

One Season has many Matches
One Season belongs to one Competition

Competition

One Competition has many Seasons
One Competition has many Teams through Seasons

Match

One Match belongs to one Season
One Match has one home Team and one away Team
One Match is played at one Stadium
One Match is assigned one Referee
One Match has many MatchEvents

MatchEvent

One MatchEvent belongs to one Match
One MatchEvent involves one Player

Referee

One Referee officiates many Matches

Transfer

One Transfer involves one Player
One Transfer has one origin Team
One Transfer has one destination Team

PlayerStats

One PlayerStats record belongs to one Player
One PlayerStats record belongs to one Team
One PlayerStats record belongs to one Season
