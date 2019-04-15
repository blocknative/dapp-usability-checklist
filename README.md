# dapp-usability-checklist
A dapp usability checklist

This is a checklist of usability items that dapp product teams can use as a quick reference when designing and building their products. This is not meant to be a list of requirements. Your dapp may not require certain items. This is also not an exhaustive list. Please send pull requests with contributions!

## Onboarding Support

- [ ] If you decide to not support mobile browsers, ensure you are checking for this and warning users of mobile browsers
- [ ] Warn the user when they are in an unsupported browser
- [ ] Warn the user when they do not have a wallet -- e.g. MetaMask -- installed
- [ ] Tell the user they need to unlock their wallet
- [ ] Tell the user they need to authorize their wallet (EIP-1102)
- [ ] Make sure user is on the right network
- [ ] Make sure the user has Ether

## Transaction Support

- [ ] Notify the user if there is a transaction in MetaMask's queue waiting for confirmation or rejection
- [ ] Notify the user if they reject the transaction from the MetaMask window
- [ ] Warn the user when it appears they are about to execute a duplicate transaction
- [ ] Warn on insufficient funds

## Transaction Notifications

- [ ] Notify a user when a transaction is pending
- [ ] Notify a user when a transaction has succeeded
- [ ] Notify a user when a transaction has failed
- [ ] Notify a user when a transaction is taking longer than expected

## Gas Estimation

- [ ] Give users a choice in plain english for what their gas price should be in terms of how long the transaction will take
- [ ] Warn users if their gas is set much higher than needed (i.e. helping prevent against a developer bug that adds a few zeros to the gas price by accident, for example)
- [ ] Warn users if their gas is set super low during times of high network congestion (i.e. so that future, higher nonce, transactions are not blocked)

## Error Handling

- [ ] Catch & parse MetaMask errors, and alert users what is happening in easy to understand language

## Mobile Support

- [ ] If your dapp supports mobile, make sure you don't tell people to install MetaMask

## Network Status

- [ ] Tell users the overall state of the network (e.g. red/yellow/green notificaton)

# Resources

- Ryan Angilly's slides on Dapp Usability from ETHDenver 2019: https://docs.google.com/presentation/d/1vHNpSVCDwIbdpjA-zlBvSvsCjK7uikcLvaCcz3PglqQ/edit?usp=sharing


# Contributions

Have ideas? Please send us a pull request!
