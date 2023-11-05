# ConnextRouterTrack (Update 05.11)

## What is the Contributor Program?

The Contributor Program is a way for leaders in the community to step up and help push Connext forward in different ways. Connext’s official announcement gives you a detailed explanation of what the Contributor Program is. Here’s a summary:
> The Contributor Program is a community incentive program designed to encourage community members of different backgrounds and skillsets to steward and take ownership of key aspects of our ecosystem. The program consists of 5 Tracks (Community Leadership, Builders, Content & Education, Routers, and Grants), that are operated by Track Operators, experienced leaders within the community that are not part of the core team.

Participants of the program will be given points based on the quality of their contributions to the ecosystem using evaluation criteria developed by Track Operators. When the NEXT token goes live, we plan to submit a proposal to the Connext DAO to retroactively reward participants proportional to points received.

Be sure to join Connext's official Discord server to receive updates about the Content & Education track: https://discord.gg/connext, you can find us in the channel #router-track

## What is a router?

Routers are the liquidity and infrastructure providers of the Connext network. Their main purpose is to relay funds and calldata across chains. In exchange, they receive fees for their services.

# Router Track Program Eligibility - How to Apply

The application process consists of several steps. **You** **must complete all of these steps** to participate:

1. [Join our discord.](https://discord.gg/connext)
2. Fill out the [Contributor Program application form](https://form.typeform.com/to/tSBsjYxh).
3. After completing the form you will be sent an email with a KYC link and a document to sign.
4. The KYC process can take up to 24 hours to complete - if approved, you will receive an email confirming your acceptance into the program.

# Router Track Proposals

Router Track participants will have the possibility to send proposals to build various tools for the Router community, that will improve the Router experience. Head out to "proposals" directory within this repository and create a .md file with your github handle, an example of a file would be: "fmanea.md".

The content of the file should contain the discord handle of the participant (or if it's a group of people working on a big feature, their discord handles).
Also, the content of the file should contain any kind of proposal that you would want to build.

> Note: `We will accept pull requests only if the .md file matches the github handle`

# Router Track Submissions

Head out to "submissions" directory within this repository and create a .md file with your Github handle, an example of a file would be: "fmanea.md". 

The content of the file should contain the discord handle of the participant (or if it's a group of people working on a big feature, their discord handles).
Also. all the submissions and work that a Router track participant has made should be written in that file.

> Note: `We will accept pull requests only if the .md file matches the github handle`

# Router Track Missions

Each week there will be some missions for the Router Track participants in which they will be rewarded with some points for delivering that activity.


## Router Track Mission 1 (09.05-16.05)

1. Spinning up a router on the testnet (10-30 points that depends on feedback /improvements proposals)
2. Choose the activity which you intend to work on over the course of the program (5 points)
3. Answer questions and help others to run router in this Discord channel (1-10 points)

### How to get maximum points? 

Key evaluation criteria are quality (for docs/ guides/mentoring) and impact (for improvement proposals,  feedback and tools). Connext should aim to be a self served platform also for routers, and we need to make sure documentations and guides serve this purpose.

## Router Track Mission 2 (16.05-23.05)

1. Video guide with a step-by-step running router in any language (5-100 points)
2. Guides and your experience articles about running router in socials (medium etc.) in any language (5-50 points)
3. Answer questions and help others to run router in this Discord channel (1-10 points)
4. Feedback/improvement proposals/building high impact tools (5-500 points)

## Router Track Mission 3 (23.05-30.05)
1. Testnet Upgrade - Add liquidity to the new contract (10-30 points)
2. Flash Challanges (10-100 points)
3. Router Connext Quests (10-500 points)


# Flash Challange

The flash challenge is quality based, and the sumissions that are picked for this activity will receive rewards. 

## Flash Challenge 1 - Explore all guides, and gather them in one place in Docs 

1. Create Guides page in Docs https://docs.connext.network/routers/guides
2. Explore every guide written by other routers, group them by type (text/video), running way (AWS/Google/DO, Dedicated server, local home computer, kubernetes),  language, etc. Links to the guides you can find here https://github.com/fmanea/ConnextRouterTrack/tree/main/submissions 
3. Guides should be numbered
4. Brief overviews are welcome for those guides which have something special (highlight uniqueness)

## Flash Challenge 2 - Complete the routers documentation intro

Now we have "page no found" status, when we follow the link https://docs.connext.network/Routers/intro/ 

You should fix it - add detailed info on the following topics:
- who are routers
- why do we need them in Connext
- security assumptions and risks 
- business model

The basic info is presented in the blog but it may be improved, You should review, figure out what information is missing

Github for PR https://github.com/connext/documentation

## Flash Challenge 3 - Propose a custody integration to improve the process for managing keys/liquidity

We are looking for the mechanisms to improve the process for managing keys/liquidity and make it more robust with minimum efforts right now (using a 3rd party custody solution as the recipient of the router liquidity)

Your proposal should include
- description of custody integration
- which projects are already use it?
- how it can improve the current process
- instruction/your experience how to set up it and use for managing keys/liquidity

# Router Connext Quests 

These Challanges are more complex and are not time based. They require approval for starting working on it. How does it work? 
1. Submit a proposal on this repository, in the "proposals" directory (Check Router Track Proposal Guide above). Propassal should include
- Name of the challenge/quest you are applying for
- Briefly describe your project
- Detailed project proposal 
- Project roadmap and milestones
- KPIs (how can we measure the success of your project?)
- Your professional background
- Have you already worked on similar projects?
3. Open a private thread in router-track discord channel and get approval for starting the work on this challange;
4. The Track Leaders will move the approved proposals into the "approved_proposals" folder where the progress will be tracked;

## Quest 1 - Build Tools (10-500 points)

Build high impact tools to improve the router experience. We are waiting for your proposals:)

## Quest 2 - Quick router setup (10-500 points)

Router setup scripts for quick-running routers on cloud platforms and dedicated servers. 

Examples: 
- Setup based on any kind of scripting language (Ex: Bash Scripts,Python);
- Setup automate deployment using any kind of Infrastructure as a Code;(Ansible, Terraform or any other) 
- Develop a router setup using npm or yarn instead of using docker-compose
- Develop a router setup using helm or any kind of kubernetes manifests



The goal would be a tool for running routers with just 1 click. Don’t hesitate to propose any tools which will simplify the process. Be creative, we are looking for different approaches. 

Every submits needs a guide or documentation on how to use them, submitting without a doc we will be not taken into consideration.

## Quest 3 - Alerting system for Routers (10-500 points)

Create an alerting tool (telegram bot/slack/ etc.)

Examples:
- Integrate Alert Manager into the Docker Compose;
- Use Alert Manager to send alerts to Slack / Telegram/ Discord Channels; 
- Use Grafana to send alerts on slack and integrate with a on-call tools

We are also open the new ideas, please feel free to propose any alerting approaches.

## Quest 4 - Monitoring tools for Routers (10-500 points)

Implement different  monitoring deployments or dashboard for the router

Example:
- Use different tools for deploying an observability stack(Ex: ElasticSearch, Kibana, CloudWatch)
- Create Grafana dashboard

Our dream is to have different approches to monitor the router metrics and logs. Each router deployment can be easily integrate with any kind of infrastructure.



