# Contributing

**The issue tracker is only for bug reports. If you have a question, please ask it in the [Discord server](https://discord.gg/empyrion) instead of opening an issue – you will get redirected there anyway.**

## Setup

- FAQSelectMenu/PublicInformation.yaml (used for the general public)
- FAQSelectMenu/OfficialMPServerInformation.yaml (used for the Official Multiplayer Servers)

1. Create a fork
	<p>
    <img src="https://raw.githubusercontent.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/main/.github/Assets/CreateFork.png" width="350" alt="FAQ Menu"/></a>
    </p>
2. Make the changes you want to make
	<p>
    <img src="https://raw.githubusercontent.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/main/.github/Assets/EditFile.png" width="250" alt="FAQ Menu"/></a>
    </p>
3. Commit the changes
	<p>
    <img src="https://raw.githubusercontent.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/main/.github/Assets/CommitChanges.png" width="250" alt="FAQ Menu"/></a>

    When commiting follow the "Git Commit Message Convention"
    like:
    ```
    Fix ReplaceBlocksCommand
    Add MyNewYamlKey
    Change RepairBayGuide
    ```
    In the description you explain short what you changed/fixed
    
    <img src="https://raw.githubusercontent.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/main/.github/Assets/CommitWindow.png" width="350" alt="FAQ Menu"/></a>    
    </p>
4. Create a pull request to the main repro (EleonGameStudiosSA/OfficialEmpyrionDiscord)
	<p>
    <img src="https://raw.githubusercontent.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/main/.github/Assets/PullRequest.png" width="1586" alt="FAQ Menu"/></a>
    </p>

## Info

- Follow the YAML Structure. So no tabs are allowed
- Do not modify the file formating
- Do not modify the Intro key and its value
- Discord uses Markdown formatting
- Discord has a 2000 character limit per message. The bot is able to split messages in multiple messages, this is done per 2000 characters. If you provide info longer then then 2000, please structure your info in a good way (example [ReplaceBlocksCommand](https://github.com/EleonGameStudiosSA/OfficialEmpyrionDiscord/blob/main/FAQSelectMenu/PublicInformation.yaml)).
- You are able to create new keys with new info. If you do so be sure to mention this info in your pull-request so the menu can be updated with this.
- If you want your name listed in the Intro, then please provide your Discord UserName or User ID in the pull request description!

### Note: 
> Updated entries will be visible in the FAQ Menu when the pull request is approved and merged.  
For new entries the code needs to be changed.
