# GHCP loves COBOL

This is a demo repo to demonstrate the capabilities of GitHub Copilot with COBOL code.

It uses the [CICS Banking Sample Application (CBSA)](https://github.com/cicsdev/cics-banking-sample-application-cbsa) and [AWS Mainframe Modernization Card Demo](https://github.com/aws-samples/aws-mainframe-modernization-carddemo).

The prompts in the `.github/prompts` directory are designed guide through project discovery and planning and implementation of a new feature: transaction history. 

## Demo flow
### Basics
0. Use the `0_basic-discovery` prompt to start with basic discovery of the application and COBOL code.
1. Do a deeper dive into transactions, data structures and logging of the application with the `1_transaction-discovery`, `2_data-structures`and `3_logging-discovery` prompts.
2. Create a plan to implement transaction history with the `4_plan-transaction-history` prompt.
3. 
    1. Implement the plan with the `5-1_implement-transaction-history` prompt.
    
    or

    2. Create a GitHub issue for the implementation with the `5-2_github-issue` prompt and have Copilot implement it from there.
4. Add a frontend component to view the transaction history with the `6_frontend-transaction-history` prompt.

### Build and interact with knowledge base
1. Open the `001-reverse-engineer-modules` folder. Explain spec driven development briefly. Show `spec.md` and explain what has been done.
2. Show the results in: https://github.com/jkordick/glc-knowledge-base
3. Open new GHCP chat and show `cobol-knowledge-base.agent.md`.
4. Show prompt `0_basic-discovery` again with the agent.