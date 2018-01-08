### How can I access the Parity Wallet?

Open your favorite browser and navigate to `localhost` on port `:8180`: http://127.0.0.1:8180/

You can change the port with the `--ui-port` flag. To disable the UI, use `--no-ui`.

### Can I use Mist with Parity?

Yes, run `parity --geth` in Geth-compatibility mode. This sets the IPC path to be the same as Geth's and allows Mist to connect to Parity. See also [Using Parity with Mist](Using Parity with Mist).

### Can I send Bitcoin to my Parity wallet?

No, sending Bitcoin directly to an Ethereum address does not work. However, you can use the Shapeshift integration. Open an account on your wallet and click the blue fox icon.

![Parity Shapeshift Integration](https://i.imgur.com/C7cAYeb.png)

### Can I create multi-signature wallets with Parity?

Yes, open your wallet on the _A'ccounts'_ view and click _'New Wallet'_. This will deploy a multi-signature contract on the selected chain.

### How can I compile and deploy contracts with Parity?

Open your Parity UI and navigate to the _'Contracts'_ tab, it allows you to write, compile and directly deploy contracts on the selected chain.

![Parity Solidity Contracts](https://i.imgur.com/2xjUkiI.png)

### What DApps are available for Parity?

Parity comes with a couple of builtin DApps:

- **Web 2.0 browser**: A Web 2.0 hosted pseudo-dapps browser.
- **Method registry**: A registry of method signatures for lookups on transactions.
- **Parity/Web3 console**: A Javascript development console complete with web3 and parity objects.
- **Registry**: A global registry of addresses on the network.
- **Token Deployment**: Deploy new basic tokens that you are able to send around.
- **Token Registry**: A registry of transactable tokens on the network.
- **TX-Queue Viewer**: Have a peak on internals of transaction queue of your node.

Additional DApps can be added, see [Writing Dapps for Parity](Writing Dapps for Parity).

### How can I write a DApp for Parity?

Head over to the excellent [DApp Tutorial](https://github.com/paritytech/parity/wiki/Tutorial-Part-I) documentation. It walks you through making a simple Ethereum-powered, distributed app. By the end of it, you'll be able to head in to Parity, select your Dapp and see it in action.

### Does Parity support the Swarm and Whisper sub-protocols?

Currently, Parity does neither support Swarm nor Whisper sub-protocols. However, [Whisper Support](https://github.com/paritytech/parity/issues/4685) is on the road-map.
