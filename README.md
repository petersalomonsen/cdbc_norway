Thoughts on Central Bank Digital Currency (CBDC) in Norway
==========================================================

*Written by Peter Salomonsen (https://petersalomonsen.com) - June 2023*

These are my own thoughts on why and how a central bank digital currency could be implemented in a country like Norway, using blockchain technology with smart contracts.

# Purpose

CBDC creates opportunities to accelerate, open up and be more inclusive in our economic system. We can reduce obstacles and complexity when it comes to paying for consumption or getting paid for providing, by applying blockchain technology to automate settlements and reporting on a national and also international scale.

## Examples of areas to improve

- Tax reporting and collection: smart contracts can automatically deduct taxes in the same moment as a transaction takes place
- Payments: International standardized digital payments solutions
- Credit: collateral, terms, guarantors, collection handled by smart contracts
- Banking: Interbank settlements, more inclusive banking
- International development funding: Pin-pointing and following the monetary flow
- Small business establishment: accounting, bureaucracy, payment services
- Asset ownership and transfers: settlement and record of ownership change
- Financial crime: Provide a platform for surveilling money and asset transfers
- Privacy: Establish standards for ensuring disclosure of sensitive information only to authorized parties
  
# Technological solution

For a souverign state, it's important to be in control of the technology that powers its monetary flow. It must be possible for the people, through the elected government and authorities to make decisions and have them implemented in the technical solution. A digital currency, implemented with blockchain technology that also facilitates smart contracts, enables fully automated and integrated processes where there are manual actions or multiple IT systems interacting today. Applying a system that has the capability to "evolve on its own", must not result in a system that cannot be controlled by authorities.

Still interoptability with other currencies and authorities is beneficial. Blockchain and smart contracts makes it possible for agreements between authorities to be written and executed in computer programs that all transactions must pass through. On an international level, one must work together on agreeing on standard interfaces, and also even finding common technological solutions through open source software.

The technological solution must also encourage participation in the society. There must be incentives for private financial institutions to contribute to and maintain the system. Blockchain technology/cryptocurrencies are examples generating incentives for such contribution: both for operation, maintenance and evolution, and open source software to ensure independent security reviews, reuse of technology, and clear understanding on the mechanics of the solution.

Blockchain technology has been around long before central banks started to look into on how to take advantage of it. An attribute that distinguish it from traditional banking is that all participants in a blockchain use the same open source software and technology, while interfaces between banks today are APIs that encapsulates closed proprietary software solutions. The open source communities, the constant chase of security vulnerabilities and continuous mitigation of these that we see in public decentralized blockchains are on a level never seen before. Obtaining a "battle proven" system that can withstand cyber-attacks increasing in scale has a better chance by embracing the technologies and communities that powers the large public decentralized blockchains. This means that a CBDC blockchain also is better off building on such technologies and also bridging with the decentralized blockchains. Bridging would in practice mean also issuing tokens pegging the CBDC on these chains.

So why not run everything on a public decentralized chain? The answer here is that it's crucial for a state to keep the control within its borders. The governance of a decentralized chain is a product by participants from all over the world, and might not be in line with the needs of a small country like Norway.

A dedicated CBDC blockchain in Norway could be under the authority of the Ministry of Finance. The Financial Supervisory Authority ( Finanstilsynet ) could approve validators, which would likely be existing financial institutions in Norway.

For validating and consensus, it can be discussed if "Proof of Stake" (PoS) should be applied versus "Proof of Authority" (PoA). PoS has some advantages when it comes to rewarding participation, and also gives the public a chance to choose which actor to stake with. Still not everyone should be able to become a validator, so mechanisms for verifying a license issued by authorities must also be in place.

The diagram below shows how todays banks in Norway can become validators in a national blockchain. Consumers can stake with the validator of their preference. Banks can also act as custodians, safeguarding private keys of their customers, and also provide assistance or tailored user experiences for interacting with the technology.

The blockchain itself features smart contracts for several use cases like:

- Primarily the Fungible Token of the national central bank digital currency with built in logic on for example:
  - VAT on purchases
  - Income tax collection
  - and more
- Fungible tokens bridged from other central banks ( e.g. Swedish e-krona )
- Employment contracts
  - Monthly wage
  - Bonus
- Asset ownership
  - Settlement and transfer of ownership in one transaction
  - Tax on profit/loss
- Voting ( elections, boards, general assembly )
- Insurance

and there are many more use cases.

The diagram also shows the Central Banks role in governing the chain, maintaining the public gateways, issuing protocol upgrades, and maintaining the software. A role of the Central Bank would also be to maintain the transactions fees, which has similarities to the central banks role of controlling the interest rate.

Furthermore the diagram shows bridging to other central bank chains and public decentralized blockchains. Here the CBDC is also represented with fungible tokens (e.g. ERC-20 on ETH or NEP-141 on Nearprotocol) on these other chains. Bridging with the decentralized chains would also help in targeting and following the flow of funds for international development. Today this is an area with extensive frameworks and adminstration staff for applying for funds and reporting the usage. It represent a significant amount of the state budget, but the development of the rest of the world has significant impact on us in Norway. Being even more connected to the world economic system enables us to monitor, improve and achieve better results for the money we invest in development countries. So even though we make a digital currency system for ourselves here up north, it will be even more valuable if we also think about how it could integrate with and influence the economic systems all over the world.

![](https://www.plantuml.com/plantuml/png/ZLHDRzim3BthLn3fsLYphfUY2D2FT2W6f4LJzDBa85kC8zYH34bkrWtzxwC-xDH9C5GdYO-a7fyesaggXXk-0QK5McnWV7hAR6yrN5MTbV72QGCD6glLU73wFZYTCVRwmcifEDaMwdPslGHkGQXyO9zf8v07I8Nj09qJ0Spf-d7miFrnu3MLLSo0j1aWrpFmxW7CbTyobgXdGczLDl5y4lraYJGk5Yg4Gj5QfpVa0TPnagG4WOssqjc5sagtXa8hsv93SBSfsLbA5XWnWuNZggmHHbJlbhz3NkkYAjPSgb4gdQpX32TtTpzemLy6j5ulyydiuHVSjQgKEMLurXKgVwap9FVbjtooK2zNpw0LDAsX51Q9sRqgY3Gu_ZlKld9zildqlycIkyLAwJvckcbg_Rv1vGvzCM287T07tPCir3a57iR83kgTNxJpqXvulWLxxtPbBJeWPKdajMpsP9YH1iFIR6oiLFu-rUnrBOL0jGnlbPnwRaFq4v6apX3tTtnGonF96_JfwzW-UWNnoIF537xgDpJAN-1FZqOxNUWQsgOqNFYdo-3fyGPAxf2YkezHeWtfg3dyeYxcHSLBQgZzs-PR95AXgspOxkBEppyrrLVxuAjTc0AKhb9CslSo6LckNHPIVh0Eh77bRN01kP6YHERnpXfata6ig7KhOFJWrlJR11QnSla7nQV_P4TmSXjMAhPNQkhZiDq4RP1-RiH3VOFYd2zkLm-v1iUFORhPzEe9clH-yHSZDrzDwdrJrgZmNDTSyMKyN4jNQAcMdL948MkRFQ5Ibds0qKZRZR9khB0ureu0kw5w1FJpwuWvpj8Z0DlrgkSrMRb_)