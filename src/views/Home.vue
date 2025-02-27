<template>
    <div class="home">
        
        <h5>What is Kaspa?</h5>
        <p>
            <a href="https://hashdag.medium.com/in-which-i-run-with-the-ghosts-of-my-hometown-95ad503c88c" target="_blank">The story of Kaspa</a>
        </p>
        
        <p>
            Kaspa is a proof-of-work cryptocurrency which implements <a href="https://eprint.iacr.org/2018/104.pdf" target="_blank">the GHOSTDAG protocol</a>. Unlike traditional blockchains, GHOSTDAG does not orphan blocks created in parallel, rather allows them to coexist and orders them in concensus. Whereby our blockchain is actually a block<i>DAG</i>; you can see GHOSTDAG in action in a real time <a href="http://kgi.Kaspanet.org/" target="_blank">blockDAG visualizer</a>). This generalization of Nakamoto consensus allows for secure operation while maintaining very high block rates (currently one block per second, aiming for 10/sec, dreaming of 100/sec) and minusucule confirmation times domianated by internet latency (cf. chapter 6 of the <a href="https://eprint.iacr.org/2018/104.pdf" target="_blank">the paper</a> for some initial benchmarks). The Kaspa implementation includes a lot of cool features and subprotocols including Reachability to query the DAG's topology, <a href="        https://research.kas.pa/t/some-of-the-intuition-behind-the-design-of-the-invalidation-rules-for-pruning/95
" target="_blank">Block data pruning</a> (with <a href="https://github.com/kaspanet/research/issues/3" target="_blank">near-future palns for block header pruning</a>), SPV proofs, and later subnetwork support which will make future implementation of layer 2 solutions much easier. 
        </p>
        <p>
            Kaspa is a community project, completely open source, no central governance, no biz model. Think Bitcoin, Litecoin, Monero, Grin, Kaspa. The mainnet was openly launched without premining or any other preallocation of coins.
        </p>
        


        <p>
            <a href="https://github.com/kaspanet/docs/blob/main/About%20Kaspa/Overview.md" target="_blank">Kaspa overview</a>
        </p>

<p>
            <a href="https://github.com/kaspanet/docs/blob/main/About%20Kaspa/Vision.md" target="_blank">Kaspa vision</a>
        </p>

        <p>
            <a href="https://hashdag.medium.com/kaspa-launch-plan-9a63f4d754a6" target="_blank">Kaspa growing pains I</a>
        </p>
        
        <p>
            <a href="https://hashdag.medium.com/Kaspa-launch-plan-responding-to-reality-6b4bec449037" target="_blank">Kaspa growing pains II</a>
        </p>


        <br>
        
        <h5>OK, but what <i>is</i> Kaspa? Can I understand it without reading a long research paper?</h5>
        
        <p>
        For a friendly overview of the core ideas of Kaspa, you can start with <a href="https://medium.com/@shai.wyborski/kaspa-what-are-we-actually-doing-here-fd7b2e420ad1" target="_blank">this post</a>.
        </p><p>
        For a more in-depth (but still not technical) account, you can proceed to these posts: <a href="https://someone235.medium.com/how-increasing-the-throughput-harms-bitcoins-security-76ed62313227" target="_blank">part 1</a> <a href="https://someone235.medium.com/scaling-bitcoin-with-blockdag-d785174a3402" target="_blank">part 2</a>.
        </p>
        <h5>Sounds interesting, how can I engage the Kaspa community?</h5>
        <p>
            The central hub of the community is currently the <a href="https://discord.gg/kS3SK5F36R" target="_blank">Discord server</a>. Other than that you are welcome to join our <a href="https://t.me/Kaspaenglish" target="_blank">Telegram channel</a> and <a href="https://www.reddit.com/r/Kaspa/" target="_blank">subreddit</a>. Please also follow this <a href="https://twitter.com/CurrencyKaspa" target="_blank">Twitter account</a>.
        </p>
        
        <h5>How can I get Kaspa?</h5>
        <p>
            There are currently three ways to obtain Kaspa:
            <ul>
                <li><strong>Mining</strong>: You can join the efforts by setting up a mining node, see instructions <a href="https://github.com/Kaspanet/docs/blob/main/Getting%20Started/Full%20Node%20Installation.md" target="_blank">here</a> and more detailed instruction for Windows users <a href="https://steemit.com/crypto/@Kaspa/Kaspa-quick-start-guide" target="_blank">here</a>.</li>
                <li><strong>Bounties</strong>: A lot of community members offer bounties for people who contribute to the Kaspa community and ecosphere by running servers, writing toturials, etc.. Check out the bounties channel in our <a href="https://discord.gg/kS3SK5F36R" target="_blank">Discord server</a>.</li>
                <li><strong>Trading</strong>: Kaspa has not been listed on any exchanges yet, however, there is a trading channel in our <a href="https://discord.gg/kS3SK5F36R" target="_blank">Discord server</a>.</li>
            </ul>
        </p>

        <br>
        
        
        <h5>Is there a Kaspa wallet?</h5>
        <p>
            At the moment, Kaspa does not have a GUI wallet. The Kaspa codebase contains a CLI wallet which requires a full node to operate. Want to help us create a GUI wallet? Contact us on our <a href="https://discord.gg/kS3SK5F36R" target="_blank">Discord server</a>! You might even gain some bounties.
        </p>
        
        <h5>Useful Links</h5>
        <p>
            <ul>
                <li>Community hubs: <a href="https://discord.gg/kS3SK5F36R" target="_blank">Discord server</a>, <a href="https://t.me/Kaspaenglish" target="_blank">Telegram channel</a>, <a href="https://www.reddit.com/r/Kaspa/" target="_blank">subreddit</a>, <a href="https://twitter.com/CurrencyKaspa" target="_blank">Twitter account</a>.</li>
                <li>Getting started guides: <a href="https://github.com/Kaspanet/docs/blob/main/Getting%20Started/Full%20Node%20Installation.md" target="_blank">the "official" guide</a>,  <a href="https://steemit.com/crypto/@Kaspa/Kaspa-quick-start-guide" target="_blank">screenshot guide for Windows users</a>.</li>
                <li>Diagnostic tools: <a href="http://katnip.Kaspanet.org/" target="_blank">Katnip block explorer</a> (<a href="http://blockexplorer.Kaspanet.org/" target="_blank">Mirror</a>), <a href="http://kgi.Kaspanet.org/" target="_blank">KGI blockDAG visualizer</a>, <a href="http://kasboard.Kaspanet.org/" target="_blank">Kaspa board</a>.</li>
                <li><a href="https://github.com/elichai/Kaspa-miner/releases/latest" target="_blank">Elichai's miner</a>.</li>

            </ul>
        </p>

        <br>

    </div>
</template>
