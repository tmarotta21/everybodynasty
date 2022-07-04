<script context="module">
	export const prerender = true;
</script>

<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">EVERYBODYNASTY CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Roster</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Positional Breakdown</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Trading</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoOne)}>1.2.1 Trade Collusion</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoTwo)}>1.2.2 Lending Players Prohibition</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoThree)}>1.2.3 Trade Deadline</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFour)}>1.2.4 Trade Mistakes</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFive)}>1.2.5 Veto/Trade Process</h5>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneTwoFive)}>1.2.5 Trading Rookie Picks</h5>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Waiver Wire</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Rookie Drafts</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Standings & Scoring</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Scoring System</h4>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.2 Standings System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwoOne)}>4.2 Consolation Bracket</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.3 Seeding Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Code of Conduct</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.2 Negligence Policy</h4>

        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.3 Personal Integrity Policy</h4>

        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.4 Commissioner Invervention Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Replacing Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Replacing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 New Owner Incentive</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>7.2 Payouts</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>25 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX</li>
        <li>FLEX</li>
        <li>FLEX</li>
        <li>FLEX</li>
        <li>FLEX</li>
        <li>SFLEX</li>
    </ul>
    
    <p>15 Bench</p>

    <p>5 IR Spots (Player must be labeled as IR, Out, Doubtful, or Covid in the Sleeper App)</p>

    <p>5 Taxi Squad (Player must be NFL rookie as defined by Sleeper)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>Trading of players and draft picks (up to 3 drafts away) are allowed. Trades are processed immediately and will be reversed if vetoed or under investigation for collusion. Tradable assets include players, draft picks, FAAB, and future considerations.</p>
    
    <p>All trade proposals sent through the app are active until accepted, rejected, or canceled. Any trades involving future considerations must be disclosed to the league at the time of acceptance.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>If any owners are suspected of accepting bribes/offering bribes to enhance their/another owners team via trade, trading any assets other than fantasy players, draft picks, FAAB, or otherwise found guilty of engaging in any form of collusion, all parties involved in the trade will be susceptible to punishment. The punishments will go as followed:</p>
        
        <ul>
            <li>First Offense – Text warning and reminder of consequences</li>
            <li>Second Offense – Sacrifice 3rd round pick</li>
            <li>Third Offense – Sacrifice 1st round pick</li>
            <li>Fourth Offense – Removal from the league</li>
        </ul>

        <p>If the offender's sacrificed pick is traded away, the next highest round or future year pick will be sacrificed.</p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>You cannot "rent" players to another team. Any trade involving “trade backs” are subject to league vote and is punishable as collusion. See “collusion” for more details.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The trade deadline is after Thanksgiving week games (Week 13). Trades may be accepted until the end of Monday Night Football on Week 13. There are no trades between Weeks 14-17. Trades are allowed after Week 17 games.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Trade Mistakes</h4>
    <div class="subBlock">
        <p>If a trade offer recipient mistakenly accepts the trade, they must tell a commissioner within 12 hours of acceptance (i.e. "same day"). If the accepting party tells a commissioner after the mistake period there will be no reversal.</p>
        
        <p>"Senders sent it" - if an owner protests an accepted trade which they sent in the past, and do not want to go through with the trade anymore ¯\_(ツ)_/¯ tough shit.</p>
    </div>
    
    <h4 bind:this={oneTwoFive}>1.2.5 Veto/Trade Protests</h4>
    <div class="subBlock">
        <p>Any official trade protests require 6 of the 12 owners calling for a league vote to veto. Put another way, half of the league must request a vote to veto a trade.</p>
        
        <p>When a league vote is called, a total of 8 veto votes (two-thirds) are required to veto a trade. Only the assigned team managers votes count - co-owner votes do not count. Teams participating in the trade are allowed to vote.</p>
        
        <p>Voting results can either "approve" or "reject" the trade. If 8 or more votes to reject, players are immediately reverted to their original rosters. If 7 or fewer votes to reject, players stay on their destination rosters.</p>
    </div>
    
    <h4 bind:this={oneTwoFive}>1.2.6 Trading Rookie Picks</h4>
    <div class="subBlock">
        <p>To prevent teams from hemorrhaging their dynasty team future and leaving the league after a few years, league dues are owed when premium rookie picks are traded away. This prevents a potential replacement owner to begin their dynasty team with no picks.</p>

        <p>Trading future 1st round picks will require that owner to pay dues for the year in which they trade away those picks.</p>

        <p>Trading future 2nd round picks will require that owner to pay 1/2 dues for the year in which they trade away those picks.</p>
    </div>
    
    <h3 bind:this={oneThree}>1.3 Waiver Wire</h3>
    
    <p>The waiver wire system is Free Agent Auction Budget (FAAB), with waiver runs processing daily at 9AM EST. Each team begins the season with $1000 and budgets are reset after the league is rolled over into next season. $0 bids are allowed. As per current Sleeper functionality, teams must have a valid roster at the time of submitting a waiver claim.</p>

    <p>Waivers are locked upon completion of Week 17 and remain locked until the offseason Free Agent Auction.</p>
    
    <p>The Free Agent Auction marks the first waiver run of the season, usually scheduled during the first week of NFL training camps. Teams use their in-season budgets, which are not replenished after the Free Agent Auction, and use the same budget throughout the regular season and postseason.</p>




    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings and postseason results. Please see "Consolation Bracket" for details.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rookie drafts will consist of 5 rounds of drafting, with 4 hours alotted for each pick. If the draft timer expires the pick is autopicked by Sleeper.</p>

    <p>Draft timer is paused overnight beginning at 10pm ET and resumed at 9am ET. Picks can still be made during the pause. The draft timer is reset to 4 hours every morning at 9am ET.</p>
    



    <h2 class="sectionHeading" bind:this={three}>Section 3 Standings & Scoring</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring settings can be found on Sleeper. The scoring system will not change without a majority league vote.</p>
    
    <h3 bind:this={threeOne}>3.2 Standings System</h3>
    <p>The league standings system is Roulette Standings. Standings are tracked in a separate document from Sleeper - <a href = "https://docs.google.com/spreadsheets/d/1Pa8a-XfLJ0OwoVeE1l5DMFiK8Pv1z8HzUmiRn-Pi8rQ/edit?usp=sharing">everybodynasty standings</a>.</p>

    <p>Roulette Standings are a standings points system, where teams earn 2 points for a head-to-head win and 1 point for a top-six weekly score. Each week the possible range of outcomes to earn "roulette "points" are:</p>
    
        <ul>
            <li>0 = loss w/o bottom-six score</li>
            <li>1 = loss w/ top-six score</li>
            <li>2 = win w/o bottom-six score</li>
            <li>3 = win w/ top-six score</li>
        </ul>
    
    <p>In the unlikely event of a tie, both teams are awarded 1 roulette point. If two teams tie for the final top-six score, both teams are awarded the top-six roulette point.</p>

    <p>Playoff seeding and top-3 draft picks are determined by regular season roulette standings.</p>




    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>The top six (6) teams make the playoffs based on regular season standings. The first round of playoffs begins in week 15. The top 2 teams in the regular season receive Week 15 byes, and the remaining 4 teams play in Week 15 quarterfinal matchups based on seeding. Week 16 semifinal matchups are reseeded such that the 1st seed plays the lowest remaining seed from the quarterfinals, and the 2nd seed plays the higher remaining seed.</p>

    <p>There is no trading allowed during the postseason and all 12 teams have access to the waiver wire.</p>
    
    <h3 bind:this={fourOne}>4.2 Consolation Bracket</h3>
    <p>The rookie draft order for non-playoff teams is determined by a Hybrid Consolation Bracket. The bottom 3 teams in the regular season receive the 1.01, 1.02, 1.03 picks in reverse order of regular season standings. Tiebreakers for the higher pick are determined by fewer roulette points, then fewer PPG.</p>
    
    <p>The remaining non-playoff teams receive 1.04, 1.05, 1.06 picks as determined by the postseason consolation bracket. The team with the highest consolation bracket finish receives the 1.04 pick. The team with the lowest consolation bracket finish receives the 1.06 pick.</p>
    
    <p>All 6 teams compete in a consolation bracket, with the 7th and 8th seeds receiving a bye. Semifinal consolation matchups are reseeded such that the 7th seed plays the lowest remaining seed from the quarterfinals, and the 8th seed plays the higher remaining seed. A bottom 3 team cannot improve their draft position, but they can still compete in the consolation bracket.</p>
    
    <ul>
        <li>1.01 - Last place regular season team</li>
        <li>1.02 - 11th place reagular season team</li>
        <li>1.03 - 10th place regular season team</li>
        <li>1.04 - Top finisher in consolation bracket</li>
        <li>1.05 - Second finisher in consolation bracket</li>
        <li>1.06 - Lowest finisher in consolation bracket</li>
    </ul>

    <h3 bind:this={fourTwo}>4.3 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same regular season roulette standings points, the tiebreakers are determined by:</p>

        <ul>
            <li>Roulette Standings Points</li>
            <li>Most Points For</li>
            <li>More Head-to-Head Wins</li>
        </ul>
    



    <h2 class="sectionHeading" bind:this={five}>Section 5 Code of Conduct</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>


    <h3 bind:this={fiveOne}>5.2 League Negligence Policy</h3>
    <p>Negligence is a manager's failure to set their roster without reasonable justification.</p>

    <p>If a player in the starting lineup was declared Out before their game:</p>

        <ul>
            <li>Negligence - Will Fuller plays on Thursday and is declared Out with Thursday gameday inactives.</li>
            <li>Negligence - Will Fuller plays on Sunday and is declared Out before Sunday.</li>
            <li>Not Negligence - Will Fuller plays on Sunday and is declared Out with Sunday gameday inactives.</li>
        </ul>
    
    <p>If a manager fails to respond to trade conversations:</p>

        <ul>
            <li>Negligence - Proposing team has to go through commissioner to see if Receiving team got their text.</li>
            <li>Not Negligence - Receiving team does not respond because the Proposing team sends the same trade / cannot take no for an answer.</li>
        </ul>
    
    <h3 bind:this={fiveOne}>5.3 Personal Integrity Policy</h3>
    <p>"Don't Be A Dick" - We all have fun playing fantasy football. In order to maximize fun, competition, and participation, each manager is expected to abide by a basic code of conduct.</p>

    <p>Baseline expectation is to set a competitve starting lineup, respond to trade offers in a timely manner (no counters required), don't cheat, and don't ghost us.</p>

    <h3 bind:this={fiveOne}>5.4 Commissioner Invervention Policy</h3>
    <p>"Best Interest Clause" - Should circumstances, issues, or problems arise for which a remedy is not stated in the rules or bylaws, the commissioner committee reserves the right to take whatever actions he deems necessary in the best interest of the league.</p>




    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>

    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>If a manager decides to leave, he must decide before March free agency begins. Please inform a commissioner of your decision by text or DM. The departing manager will not pay current season fees, unless he has already paid fees as a result of trading future picks.</p>

    <p>If a manager leaves after participating in the rookie draft, that manager will pay dues for the team's replacement manager.</p>
    
    <p>If a manager is non-responsive or kicked out of the league during any point during the season, the commissioners have full authority to determine how that team is managed or replaced by a new manager.</p>
    
    <h3 bind:this={sixThree}>6.3 New Owner Incentives</h3>
    <p>Strong dynasties have a deep bench. If any owner has an interested friend or suggestion for new blood, they should tell the commissioners. Potential avenues for the commissioners are coordinating an expansion draft, creating a spinoff league, or replacing managers.</p>
    
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered their first year with no league dues.</p>



    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are currently set at ${dues}. Dues are collected by commissioners or volunteer treasurer.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payouts</h3>

    <p>League payout is structured as follows:</p>

    <ul>
        <li>1st place: ${dues * 7}</li>
        <li>2nd place: ${dues * 3.5}</li>
        <li>Most Points: ${dues * 1.5}</li>
    </ul>

    <p>Before the championship, competing teams are allowed to split the championship pot as they see fit. Both teams must agree to terms and inform the commissioners before Week 17 games kick off.</p>
    
</div>