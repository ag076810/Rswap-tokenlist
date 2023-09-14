# Rswap-tokenlist

Rswap - Token list

Please note the current information in this repo is based on RTH launch

### Whitelisting

- Fork this repo
  ```
  gh repo clone raydex-tokenlist
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
      "chainId": 622277
  }
  ```
- Make a Pull Request to this repo including all of the above.

<br>

More info about pull requests:

- [Creating a pull request from a fork](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
