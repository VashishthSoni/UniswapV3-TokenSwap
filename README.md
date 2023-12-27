To use this Repository install <a href="https://book.getfoundry.sh/getting-started/installation"> Foundry </a> testing Framework.<br>
Then create API key to interect with blockchain. To get API keys use <a href="https://www.alchemy.com/">Alchemy</a>, <a href="https://www.infura.io/">Infura</a>

After getting Key execute the Following Commands
<ul> 
  <li>FORK_URL=YOUR_API_KEY </li>
  <li>forge test -vv --gas-report --fork-url $FORK_URL --match-path test/UniswapV3Swap.t.sol  </li>
</ul>
