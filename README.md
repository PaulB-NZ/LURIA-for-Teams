# Release for Teams
## Purpose
LURIA was originally created for Skype for Business Server (SFBS) to collect all objects where a Line URI has been assigned and display this information in a single pane. This allows for quick identification of free and used DID\DDI numbers, search for used numbers as well as validating assigned policies.

Microsoft Teams of course also has Line URI assignments, thus LURIA has now been expanded to include Teams URIs.

## Pre-requisites
For reading the Line URI data for Teams users you will need to have:-
* Skype for Business PowerShell Module installed
* MicrosoftTeams module installed 
* An Admin account with Teams User Admin permissions

For reading the Line URI data for Skype for Business Server (SFBS) objects you will need to have:-
* access to SFBS via Skype for Business PowerShell

## Known limitations
None

## Version History
* 3.1 Read Teams data
* 3.2 Read CQ and AA data
* 3.3 Support for PowerShell V7 and use "connect-MicrosoftTeams"
