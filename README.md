# solarbeam-tokenlist

PulseChain Swap DEX - Token list

Please note the current information in this repo is based on PulseChain testnet launch

### Whitelisting

- Fork this repo
  ```
  gh repo clone pulsechainswap-tokenlist
  ```
- Create a folder under _assets/{blockchainName}/{tokenAddress}_
- Add token's icon (logo.png) under the folder created in the previous step
- Add token's info in the _community.tokenlist.json_ file, in this format:
  ```
  {
      "name": [token_name],
      "address": [token_address],
      "symbol": [token_symbol],
      "decimals": [token_decimals],
      "chainId": 940
  }
  ```
- Make a Pull Request to this repo including all of the above.

<br>

More info about pull requests:

- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
