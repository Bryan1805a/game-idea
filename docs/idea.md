Project name: Not decided yet.
Project type: Hobby project.
Project time: No deadlines.
Project resource: 0 dollar budget, one person (Author himself).

Author: Bryan Tran (Trần Bửu Ngọc)
# Update Logs
v1.0 - 2/11/2026: Build main core loop, sub core loop, optional goal, business lines, basic UI idea, basic time mechanics, basic resources, basic machine.

v1.1 - 3/11/2026: Add basic description,  the player, AI description, AI Company Archetypes, some ORE class resources, zone competition, contract board, market life cycle and shocks, failure states. Redesign game speed mechanics.

v1.2 - 4/11/2026: Add Human Resources - Installation Team and construction cost, worker’s demand. Add Industrial Machine - Machine complexity multiplier.

v1.3 - 5/11/2026: Add Human Resources - Operation Team, operating cost.

v1.4 - 7/11/2026: Redesign random variance, update Failure States - Hostile acquisition, Reputation hit. Update Human resources - Company employees demand.

v1.5 - 9/11/2026: Reorganise document - change title “Main Core Mechanics” to “Main Core Loop”, “Sub Core Mechanics” to “Core Mechanics”, update Core Mechanics.

v1.6 - 10/11/2026: Redesign Time Mechanics - change from speed tick like Hearts of Iron 4 to Time Increment like Aurora 4X. Reorganise Resource - add definition and move Resource Zone as a subheading.

v1.7 - 11/11/2026: Add Maintenance Team description. Update Trader Business Line - Rent out Logistic Company to transport goods.

# Game Overview
Genre: Grand Strategy, Economy Management, Space, Sci-fi, Simulation.
Target Audience: Players who like strategy games.
Platform: PC
Basic description
A single player, grand management, space economy game.
Inspired by EVE Online, X Foundations, Prosperous Universe, Victoria 3, Aurora 4X.

The player manages a small private company startup, they can extract resources, trading, crafting, research, exploring or managing human resources, joining the space economy and expanding their company.
Main Core Loop
make stuffs -> sell stuffs -> make profit -> expand company -> make more stuff.
Core Mechanics
The company starts on a planet with some money, they can buy some stuff based on their Business Line for early-stage support then complete a few contracts, trading on market, and buy more stuff to expand the company. The bigger the company, the more influence they have. At some point they can influence politics or power structures, even making the entire economy dependent on them - a monopolistic empire.
Optional goal (just for fun)
Become an economic philosopher and wonder “When an Empire is too large and can’t expand more, what will come after that?” or just play the game chilly, try not to crash the whole market and let the game run forever.

# Market
A market is a place or venue where buyers and sellers can exchange goods and services.
Market Life Cycle
Companies make stuff, trading, and stuff will be consumed on war or research projects. At some point, a good economy can help a faction win a war or reach a new innovation like Humanity’s final goal, The machine at the end of time - Isaac Asimov’s last question or Final equation of Black Holes, etc.

## Random Events
Some random events may be trigger and cause prices hard:
- Boom/Bust: demand for a good spikes or collapses (a war breaks out, weapons demand up, a colony fails, food demand down).
- Supply disruption: a rival’s mega factory explodes, products' price triples for a while (Maybe an opportunity or threat).
- Policy shift: a political bloc raises tariffs on goods, and your export margins vanish.
- Blueprint leak: a patented blueprint becomes public, the product you make gets commoditized overnight.
- Raiding: a convoy raid by pirates, lose valuable stuff or important crews.

And more will be added later.

Shocks should be forecastable with partial information like a news feed hints or stock market anomaly, etc.

# Failure States
- Reputation hit: miss a contract, get a black mark, fewer offers, revenue decline, and when there is no longer enough money to keep the company running, it goes bankrupt.
- Credit downgrade: borrow too much, lenders raise your interest rate or cut off, then the company enters a state of insolvency, it goes bankrupt.
- Hostile acquisition: if a player's company’s valuation drops too low relative to a Monopolist AI, it makes a buyout offer and then based on the player's management skill, they can let the player continue to manage the company as a subsidiary of a corporation. If the corporation determines that the player lacks the necessary management skills, they will replace the player, game over.
- Bankruptcy: cash < 0 for a period of time until the company is no longer enough money to keep the company running (See Human Resources for more info).

# Business Lines
Industry: Metal, steel, material refining, etc.
Heavy Industry: Spaceship, vessel, weapons, space station project, large infrastructure, etc.
Energy: Fuel, oil, electrics, solar infrastructure, etc.
Food: Anything that people can eat, etc.
Science: Explore rare material or for sale, rent science knowledge, etc.
Logistics: Sell, rent out transport ships, receive transport requests and collect fees, etc.
Trader: Make profit from price differences, etc. They can transport goods on their own or rent Logistic Company services.
Academic: Training crews, specialists, make profits from tuition fees, etc.
Private Military: make profits from war, convoy escort or hunting pirates, etc.
Mining: Mining resources, material from planets or asteroids and selling them, etc.
Construction: Rent out workers or selling material or even handle a construction project from start to finish, etc.
And I will add some more later.

Players can mix them freely in one company if they want or group companies into a Corporation.

# UI
The game will be a complex, heavy text, spreadsheet game, no 3D models or fancy graphics, just monitors with lots of information.


# Time Mechanics
Based on Aurora 4X Time Mechanics. The player chooses a Time Increment (turn length) and the game then advances, until either the chosen time increment has passed.
## Turn 
Time Increment, allows the player to speed in-game time. Choose how long you wish to advance time by choosing one of the Time Control menus (5 seconds - 30 days). Early game when not much is happening you may be using 1-day or even 30-day increments. During the approach phase of a war you might select 1 hour or 20 minute increments and when you are in an important event will probably select 5 second increments to give you more time to think.

The player should be careful with using Time Increment because if they choose increments too large, they may miss some important events.

# The Player
The player is not the main character, they are just a cog in a giant economic machine.

They arrived in this world with a small sum of money to start a business, their business can be a small shop on a planet, a fuel station in the middle of the stars, or an Energy Empire with control across the galaxy. They may be too small for the stars to notice or may be too large like a threat but the giant economic machine can continue working without them.

# The AI
The AIs don't care about the player, they just focus on their benefits, market and expansion.

At times, there may be reactions if the market fluctuates, or if the presence of a player is perceived as contrary to their interests - or even as a threat.
Possible reactions include predatory pricing, monopolizing goods, or forming alliances with a player’s rival firms, market manipulation, etc.

## Some AI Company Archetypes
The Expander:
Aggressively claims zones, builds fast, tolerates low margins. It can snap up the good mining zones before the player, flood markets and crash prices.

The Hoarder:
Buys and stockpiles resources/blueprints, sell only at high prices. It creates artificial scarcity, the player can’t buy the machine they need.

The Undercutter:
Undercuts on any product it can make, races to the bottom. It erodes your profit margins on mature products.

The Monopolist:
Vertically integrates one product chain, tries to own it end-to-end. It can squeeze you out of a whole industry, and may lobby politics later.

The Broker:
Pure trader/logistic, it doesn’t produce, it arbitrages. It competes with your Trader/Logistics lines, moving prices you rely on.

The Patron:
It funds megastructures, invites partners, and buys equity. It is an opportunity and threat - if the player joins its project, they are a junior partner.

The Mega Corporation:
It can exert an influence on politics, indirectly manipulating the market through political power. It may disrupt the calculations and market forecasts made by the player.

The War Machine:
It consumes lots of resources on the market for funding war. It can lead to the depletion or scarcity of a product, driving prices up.

# Resource
Resources are all the materials available in the environment which are technologically accessible, economically feasible and culturally sustainable and help to satisfy needs and wants.

## Resource Zone
A Resource Zone is an area containing extractable resources, it will have 2 attributes: Yield and Capacity.
Resource Zone Yield is the amount produced or generated from a Resource Zone in a period of time.
Resource Zone Capacity is the amount of Industrial Machine that a Resource Zone can contain.

The Resource quantity (Yield) will be unlimited but spaces (Capacity) will be limited.

Example: a zone display “Iron Ore - 28, Capacity 100” that means it can extract 28 Iron ores per day per extraction machine and if each machine occupies 50, that means the company can only place 2 machines.

A resource can be refining, smelting, crafting to another resource like Iron Ore can be smelted to Iron or grain with some oxy and water can be bread or somehow electronic chip, etc.

## Resource categories
Update later.

# Human resources
Include employees, workers, company personnels, workforces involved in the company's operations and receive instructions from the chief executive officer.

## Company employees demand
Company employees will consume Basic Goods based on the job, workload, they also need some Advanced Goods to increase productivity and of course - Salary, they also need Support Equipment like exoskeletons for working in a strong gravity environment, protection suits for working in a lab, extreme environments, etc.

If demand for Advanced Goods is not satisfied, employee productivity will stop at 100%. If Advanced Good is satisfied, productivity will increase to 120%.

If demand for Basic Goods is not satisfied, employees will stop working immediately, productivity decreases to 0% and they will leave the company over time, the employee turnover rate per week will be a random variable from 5-10% of the total number of employees, and company reputation will decrease 2 points per day. If Basic Goods is satisfied, productivity will increase to 100% max, and if Advanced Goods is satisfied, productivity can increase to 120% max.

If demand for Work equipment is not satisfied, employee productivity will drop sharply to 50% and the rate of workplace accidents will rise significantly to 20%.

If demand for Salary is not satisfied, employee productivity will drop sharply to 40% and they will leave the company. The employee turnover rate per week will be a random variable from 15-20% of the total number of employees.

## Human resource types
### Installation Team
They are required when companies need to construct infrastructure. Their cost is based on machine complexity, the scale and duration of a project, and one-time cost.

Construction cost formula:
Update later

### Operation Team
Every industrial machine or infrastructure requires a certain number of personnel for operations.They are called Operation Team - a mandatory requirement.

Operating cost is charged per unit produced.

Example: each Iron Ore costs 0.40, an Extractor can extract 28 Iron Ore in 24 hours then 0.40 * 28 = 11.20.

### Maintenance Team
The workforce responsible for carrying out repairs and maintenance, and ensuring that machinery and infrastructure remain in optimal condition.

# The Zone Competition
New resource zones can be claimed. Claiming costs money and time, maybe immediately or some ticks.

If the player and a rival both want it, an auction or a bidding war resolves it.

Universe is vast, the player can find another zone if they want but distance will be an obstacle.

# The Contract Board (reputation and deadlines)
A contract board looks like “Deliver 500 steel to zone X within 72 hours in-game”.

Contracts have:
Deadlines are measured in game-hours so speed is matter and missing one cost reputation + penalty.
Competition: AI companies can bid on the same contracts
Reputation score: high reputation = access to bigger contracts.


# Industrial machine
Extractor, refining, smelting, crafting and related machinery require a blueprint, materials to manufacture or the player can buy it directly on market.
A machine will need an installation team, operation team and maintenance team depending on the complexity of the machine.

Example: if the companies wants to build an extraction machine at an Iron mine, they can buy it on the market then transport and assign installation team and install it at the mine site, or buy a blueprint and necessary materials, then craft one or two machines by themselves if it is cheaper in long-term profit, they will also need an Operation Team.

## Level of Machine complexity
Low complexity multiplier/Random variance : 1.5
Medium complexity multiplier/Random variance: 2
High complexity multiplier/Random variance: 3
Extreme complexity multiplier/Random variance: 5

# Mega Structure
Mega structure requires lots of resources, materials, human resources, consumes lots of time and must be initiated via a construction project paper, and cannot be built directly.
The company can invite other companies to help building via equity investment or profit sharing. 

Example: A company can initiate a project about a Zero-G laboratory in the moon’s orbit, the company can build it alone if they have enough capability or invite other companies and let them use your lab as payback.
This document is just basic ideas, and will be updated in the future.
