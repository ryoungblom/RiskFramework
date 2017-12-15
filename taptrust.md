# Risk Analysis Framework for Ethereum ERC-20 Tokens
<super>_Version 1.1; December 2017_</super>

  
## Introduction

Hello, and welcome to the Tap Trust Risk Analysis Framework! We believe that the "wild west" mentality in the blockchain space has a place, but that it also must be balanced with some amount of user safety. To this end, we haev created an open-source application that can be used as a guidelines when considering the relative safety of a particular token.

This framework uses the following criteria to determine how trustworthy a token project is expected to be:  
* Transparency — the best token projects share their roadmap and have well-defined policies
* Governance — is the project setup in a way that is friendly to its community and limits the powers of its creators?
* Functionality/Progress — How close is the project to being live, and/or achieving its other goals?
* Legal Risk — How likely is this project to risk legal and regulatory issues?

An important element of the Tap Trust framework is that it is decidedly not attempting to provide a direct assessment of the likely growth or return on investment for a token. Such an assessment is highly subjective and open to debate, and the goal for Tap Trust reviews are to converge on a relatively objective estimation of how safe a token is to use, based on empirical data.

### This document is set up to maximize ease of use.

In **part one**, we've introduced the concept.  **Part two** will offer directions for the most efficient way to use this framework, and **part three** will consist of the framework itself.  **Parts four** and **five** will be for the more ambitious readers, with **part four** providing more nuanced guidelines to fine-tune the edge cases, and **part five** linking to some further reading.

### _Please note, this space is very new and almost entirely unregulated._
This framework is intended to be a resource, and ought not be taken as legal or financial advice. Things will change rapidly, and while we will do our best to keep this document updated, we cannot be held responsible for any oversights or outdated information. The value of doing one's own research cannot be overstated when dealing with cryptocurrency, so please inform yourself as much as possible. And as always, please feel free to visit us at [www.taptrust.com](www.taptrust.com) with any questions, suggestions, or concerns!


## Part Two: Directions

As mentioned earlier, there is so much nuance to each analysis that best-case scenario is to merely minimize the edge cases. We've balance this complexity with creating a user-friendly experience, hoping that by providing a tool with enough guidance to weed out the clearly trustworthy or the clearly dangerous, more users will be safer than they would be without this tool.  We recommend exploring the decidely more thorough explantions found in **part four** in the event that a token is found to be "in the bubble", or if extra assurance is desired.

Beyond this, the directions are fairly straightforward.  We've designed an easy-to-use rubric system to help determine the predicted trustworthiness of a token.  Simply fill in the blanks as best you can (although, realistically, the more information you give the rubric, the more accurate the result will be) and we will return an aggregate score, placing your token in either a low, medium, or high-risk category!


## Part Three: Risk Analysis Framework

_This framework is divided into the aformentioned sections: Legal Risk, Project Transparency, Governance Structure, and Token Functionality_

#### Legal Risk:

This section attempts to predict the risk of a token running into legal issues. The most likely scenario is a token violating U.S. securities law, so here, we will be focusing primarily on the _Howey_ test.

<!--- HOWEY TEST --->

<!--- Factor 1: Investment of Money--->

Was there an initial financial investment in new tokens? 
<select name="Legal_Howey_finInvestment">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: are new tokens bought (financial investment), or mined (no investment)?_</sub>

Was there a sale of tokens to fund a pre-existing product?
<select name="Legal_Howey_preExisting">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: was there an ICO to develop the project (non-existing), or to fund an existing product (pre-existing)?_</sub>

Was there a sale of pre-mined coins?
<select name="Legal_Howey_preMined">
  <option value=NULL> </option>
  <option value=75>Yes, with no attached promises (+75)</option>
  <option value=50>Yes, with explicit or implied promises (+50) </option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: were coins pre-mined by deve team and then sold at an ICO or similar?_</sub>


Is there a risk of losing value after the initial investment?
<select name="Legal_Howey_initInvestment">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: Do the tokens provide any **use** within the system?  i.e. allowing access, rights, abilities, etc.? If not, they merely exist._</sub>


<!--- Factor 2: In a Common Enterprise --->

After buying the token, does the value of the token depend on the value of the issuing company?
<select name="Legal_Howey_enterpriseVert">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: if the token is used in a company's proprietary ecosystem, the token is useless of the company goes under_</sub>


<!--- Factor 3: With an expectation of Profit --->

Does the token do anything other than merely exist?
<select name="Legal_Howey_profitUtility">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: Do the tokens provide any **use** within the system?  i.e. allowing access, rights, abilities, etc.? If not, they merely exist._</sub>


<!--- Factor 4: from the efforts of a third party --->

Was there an expectation of profit predominantly from the efforts of a third party?
<select name="Legal_Howey_efforts3p">
  <option value=NULL> </option>
  <option value=75>Yes (+75)</option>
  <option value=50>Unknown (+50)</option>
  <option value=0>No (+0)</option>
</select>  
<sub>_ex: is the token going to raise in value primarily due to efforts of a third party (i.e. company marketing, building a working product, etc>)?_</sub>


<!--- Jurisdiction --->

What jurisdiction is the token purchaser?
<select name="Legal_Howey_jx">
  <option value=NULL> </option>
  <option value=75>USA (+50)</option>
  <option value=25>Europe (+25)</option>
  <option value=25> Singapore (+25)</option>
  <option value=50> South Korea (+50)</option>
  <option value=60> China (+60)</option>
  <option value=50>Other (+50)</option>
</select>  
<sub>_ex: is the token going to raise in value primarily due to efforts of a third party (i.e. company marketing, building a working product, etc>)?_</sub>




#### Project Transparency:

This section attempts to quantify how transparent a project is. This includes things like providing sufficient contact information, information about the founders/board members, and regular status updates.

<!--- Contact Information --->

Does the website provide sufficient contact information? 
<select name="Trans_Contact_contactInfo">
  <option value=NULL> </option>
  <option value=0>Yes, all expected channels of communication (+0)</option>
  <option value=25>They have some contact info, but are missing some channels (+25)</option>
  <option value=75>Contact information sparse or missing (+75)</option>
</select>  
<sub>_ex: At this point, things like a slack/telegram, email, facebook, and twitter are non-optional. Bare mininum ("some contact info") would be an email address and one other channel of communication_</sub>


Is there a community chat system? 
<select name="Trans_Contact_commChat">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Slack, Telegram, or similar_</sub>


<!--- Information Accessibility --->

Does the project state a clear goal and use case for its tokens? 
<select name="Trans_Access_stateGoal">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: "We solve X problem" or "We hope to achieve...", as opposed to a company that releases tokens that don't appear to **do** anything._</sub>


Is the project open-source and in a repository?
<select name="Trans_Access_openSource">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=50>Unknown (+50)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Project code should be in a public gitHub or similar repository, and should be open source._</sub>


Is transparent information easiy obtainable from the website?
<select name="Trans_Access_transInfo">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Somewhat (+45)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Contact info, 'about' page, team profile, github, etc. should all be in a reasonable place on the website. Information that is present but buried in unintuitive places on the site ought to be questioned._</sub>


<!--- Team Info --->

Is there sufficient information about team members?
<select name="Trans_Access_teamInfo">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Somewhat (+45)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Important information includes the identities of key team members, founders, board members, and ought to provide information such as previous projects or a linkedin/other website. Bare minimum would be information about the founders._</sub>

Does the core team have experience in a relevant sector?
<select name="Trans_Access_coreExp">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Unclear (+45)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Blockchain, CS/tech, marketing, finance, economics, AI, etc. Be wary of teams with members lacking experience._</sub>

Is there two of: a development team, a marketing team, an executive team, and an advisory board?
<select name="Trans_Access_coreTeams">
  <option value=NULL> </option>
  <option value=0>Yes, all four (+0)</option>
  <option value=0>Yes, 2-3 (+10)</option>
  <option value=-25>No, but project is 100% open source (-25)</option>
  <option value=75>No, one or fewer (+75)</option>
</select>  
<sub>_ex: Solid teams need, at the very least, development and leadership. Complete open-source, decentralized, blockchain-only tokens may only need a dev team ._</sub>



<!--- Timeline --->

Are there regularly-provided status updates?
<select name="Trans_Timeline_statUpdates">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Present, but sparse (+45)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Team should keep token holder appraised of both good news and bad news. Holders should expect regular status updates—silence is not a good sign._</sub>

Is the project meeting benchmarks?
<select name="Trans_Timeline_benchmarks">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Usually, but late (+40)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: team sets the benchmarks, and should meet them. This includes MVPs and updates, all the way through partnerships and product launches._</sub>



#### Governance Structure:

Here, we look at the structure of the project taken as a whole. The goal here is to make sure that the governance structure is both community-friendly and has mechanism designed to limit the power of the creator(s) or otherwise keep it decentralized.


<!--- Issuance --->

Is funding released in a controlled manner and measured against benchmarks?
<select name="Gov_Issuance_release">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=45>Unknown (+40)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Allocating certain amounts of the funding to specific projects, and only realeasing the next amount of funding when a benchmark is reached._</sub>

Were 20%-40% of tokens reserved for the team?
<select name="Gov_Issuance_teamStruct">
  <option value=NULL> </option>
  <option value=0>Yes, 20%-40% (+0)</option>
  <option value=-10>Less than 20% (-10)</option>
  <option value=75>More than 40% (+75)</option>
</select>  
<sub>_ex: This should include later employees, bug bounties, etc. Ideally, 60+ percent of tokens should be out of the company's control._</sub>


Does the project have a decentralized governance structure?
<select name="Gov_Issuance_decentralized">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+40)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: A centralized structure may manifest as a corporation controlling the tokens (and therefor votes), centralized nodes, etc._</sub>



<!--- Best Practices --->

Were ICO finances handled via escrow or smart contract?
<select name="Gov_Issuance_icoFin">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Companies should never expect that a tokenholder or ICO participant merely send tokens/money/etc to a personal wallet or similar. Ideally, the funds would be held in some kind of escrow or smart contract, to be released upon benchmarks._</sub>


Are there provisions for delayed founder liquidity?
<select name="Gov_Issuance_founderLiq">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: This ought to encompass anything that similarly prevents the founders/team members from taking the value generated by an ICO or via token sales and simply walking away from the project._</sub>

Was between 20%-40% of tokens offered for sale or otherwise issued?
<select name="Gov_Issuance_tokensIssued">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: The founders/core team should never hold so many tokens that the ecosystem is de facto centralized._</sub>


Did the ICO have a funding goal, and ended when the goal was met?
<select name="Gov_Issuance_fundGoal">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Ideally, an ICO should end early if their goal is met, as that marks the end of the funds that they had planned for. Continuing pas tthe funding goal shows a willingness to accept investor money with no real plan for what to do with it._</sub>


Is there a hard token cap?
<select name="Gov_Issuance_tokenCap">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Without a hard token cap, the supply can just keep rising, diluting value while diluting control of the ecosystem._</sub>



#### Token Functionality:

The goal here is to determine the general status of the project. How close is the token to being live? Are the benchmarks and goals set by the team reasonable? Will the token likely be around for a while, as it solves a real-world issue?

<!---Technical Specifications--->


Is there a quality, easy-to-find whitepaper?
<select name="Func_TechSpec_whitepaper">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: The whitepaper is the blueprint for the project. No whitepaper, a hard-to-find whitepaper, or a shoddy whitepaper ought to raise red flags._</sub>


Is the token "live" and being used?
<select name="Func_TechSpec_live">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: does the team have a functioning product, or is the product coming sometime in the future?._</sub>

Is the token built on a decentralized platform?
<select name="Gov_Issuance_decentralPlatform">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Decentralized platforms are less susceptible to manipulation. When the majority of the has power/tokens/other things that have "control" value are in the hands of individuals, the token can be said to be decentralized._</sub>

Does the token have utility on the platform?
<select name="Gov_Issuance_utility">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: Does the token provide a right, provide access, do anything other than exist and/or act as a method of exchange between other currencies?_</sub>

Is the token necessary for the project or for solving a problem?
<select name="Gov_Issuance_necessary">
  <option value=NULL> </option>
  <option value=0>Yes (+0)</option>
  <option value=40>Unknown (+35)</option>
  <option value=75>No (+75)</option>
</select>  
<sub>_ex: If the project can exist without the token, the token is more likely to be seen as a security or otherwise regulated. A counterexample is bitcoin—without the token, there is no project._</sub>




#### Overall Score:  [score total]




## Part Four: Further Explanations

[in progress]

## Part 5: Additional Links

[CoinBase Risk Analysis Framework; Dec. 2016](https://www.coinbase.com/legal/securities-law-framework.pdf)

[Appcoin Law: ICOs the right way; Oct. 2016](https://www.coindesk.com/appcoin-law-part-1-icos-the-right-way/)

[SEC Statement on Cryptocurrencies and ICOs; Dec. 2017](https://www.sec.gov/news/public-statement/statement-clayton-2017-12-11)

[SEC v. Howey; currently good law](https://supreme.justia.com/cases/federal/us/328/293/case.html)

[Tap Trust](www.taptrust.com)