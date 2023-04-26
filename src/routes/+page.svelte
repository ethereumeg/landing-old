<script>

  import SvelteMarkdown from 'svelte-markdown'

  const manifesto = `
In the sprawling landscape of *[the Infinite Garden](https://ethereum.foundation/infinitegarden)*, we stand as a group of nonconformist, working to cultivate and nurture the Ethereum community. We are a diverse assembly of individuals from different fields and backgrounds, united by our passion for decentralized technologies and human coordination.

Our mission is to promote and support community events and gatherings, and to foster a culture of inclusivity, diversity, and open participation. Embrace the unique local characteristics of every corner of the world, and celebrate the voluntary work that is done with meaning and purpose.

We stand in opposition to commercialization and unification, rejecting the notion that our community should be homogenized and commoditized. Instead, we strive to create a decentralized and grassroots movement that highlights the differences and diversity of our global community.

As a group of people with cypherpunk in our hearths, we cherish the basic principles of freedom and collaboration that underlie Ethereum. Our diverse membership, comprising both solarpunks and lunarpunks, brings a range of perspectives and energies to our mission. 

Let us sow the seeds of a vibrant and inclusive community, one that will bloom and flourish for generations to come.

*Your Ethereum Event Gardeners*
`

</script>

<svelte:head>
  <title>Ethereum Event Gardeners (ETHevents.club)</title>
</svelte:head>

<div class="grid m-6 justify-center">
  <div class="max-w-5xl mt-5 grid justify-center mb-16">
    <h1 class="text-5xl">Ethereum Event Gardeners <span class="text-teal-500">⟠</span></h1>

    <div class="mt-5 text-lg">Organizing diversity against commercialization in Ethereum community</div>

    <h2 class="head2 !mb-0">Manifesto</h2>
    <div class="manifesto mt-2 p-6 bg-black/5">
      <SvelteMarkdown source={manifesto} />
    </div>

    <h2 class="head2">Goals</h2>
    <div class="text-lg">
      <ul class="list">
        <li>Collect, archive and publish information about Ethereum community events, like hackathons or conferences</li>
        <li>Improve the culture of these events by promoting diversity, inclusivity and open participation</li>
        <li>Support organisers by providing communication space & resources, tools and best practice guidance</li>
        <li>Coordinate with other Ethereum groups such as <a href="https://hudsonjameson.com/2020-06-22-what-is-an-ethereum-core-developer/">AllCoreDevs</a>/<a href="https://www.ethereumcatherders.com/">Ethereum Cat Herders</a>, <a href="https://ethereum-magicians.org/">Ethereum Magicians</a>, <a href="http://ethereum.foundation/">EF</a> etc.</li>
      </ul>
    </div>

    <h2 class="head2">Projects</h2>
    <div class="text-lg">
      <ul class="list">
        <li><a href="https://chronicle.ethevents.club">chronicle</a> ⎯ historical archive of community ETH events (in development)</li>
        <li><a href="https://github.com/ethereumeg/confeth">confeth</a> ⎯ state-of-the-art conference/hackathon planning and managing tool (draft)</li>
        <li><i class="italic">"The Etherevent Field Guide"</i> ⎯ knowledge-base with best practices for ETH event organisers (idea)</li>
        <li><i class="italic">"Live from ETH event!"</i> ⎯ web3 platform for remote participation based on StreamETH (idea)</li>
        <li><i class="italic">"ETHEUnite"</i> ⎯ sub-community & Twitter Spaces hosted by European Ethereum organizers</li>
      </ul>
    </div>

    <h2 class="head2">Roadmap</h2>
    <div class="text-lg">
      Nothing is certain yet, we are still in the ideation phase. 
      
      The initiative will be widely discussed within Q2/2023 on <a href="https://ethereumzuri.ch/">EthereumZurich</a> and <a href="https://www.ethdam.com/">ETHDam</a>, and hopefully published on <a href="https://ethprague.com/">ETHPrague</a>, early June 2023 (genesis).
    </div>
    <div class="text-lg mt-5">
      At the moment, we are mainly addressing the following areas:
    </div>
    <div class="text-lg mt-3">
      <ul class="list-number">
        <li>Inviting the founding gardeners</li>
        <li>Defining the key objectives</li>
        <li>Finalisation of our Manifesto</li>
        <li>Setting up basic communication tools</li>
      </ul>
    </div>

    <h2 class="head2">Founding gardeners</h2>
    <div class="text-lg">
      <ul class="list">
        <li><a href="https://twitter.com/treecz">Tree</a> ⎯ ETHBrno (Gwei.cz)</li>
        <li><a href="https://twitter.com/q9fcc">Afri Schoedon</a> ⎯ ETHBerlin, Protocol Berg (Department of Decentralization)</li>
        <li><a href="https://twitter.com/hyperalchemy">Limone</a> ⎯ ETHRome (urbe.eth)</li>
        <li><a href="https://twitter.com/hyperalchemy">Ceci</a> ⎯ ETHPrague</li>
        <li><a href="https://twitter.com/chrishobcroft">Chris Hobcroft</a></li>
        <li><a href="https://twitter.com/blockblanc">Eléonore Blanc</a> ⎯ ETHDam (CryptoCanal)</li>
        <li><a href="https://twitter.com/juandaveth">Juan David Reyes</a> ⎯ Devcon (Ethereum Foundation)</li>
      </ul>
    </div>
    <div class="mt-5 text-lg">The full ensemble will be announced on <a href="https://ethprague.com/">ETHPrague</a> during <a href="http://prgblockweek.com/">Prague Blockchain Week 2023</a>.</div>


    <h2 class="head2">Proposed founding gardeners</h2>
    <div class="mb-5 text-lg">
      People we respect and want to have on board:
    </div>

    <div class="text-lg">
      <ul class="list">
        <li><a href="https://twitter.com/JosefJ_">Josef Je</a> ⎯ Devcon, ETHPrague, EthereumZurich (Paralelní Polis)</li>
        <li><a href="https://twitter.com/TMIYChao">Mario Havel</a> ⎯ (Ethereum Foundation/Paralelní Polis)</li>
        <li><a href="https://twitter.com/_franzihei">Franzi</a> ⎯ ETHBerlin, Protocol Berg (Department of Decentralization)</li>       
        <li><a href="https://twitter.com/manualzuru">Manu Alzuru</a> ⎯ ETHBarcelona (DoinGud)</li>
        <li><a href="https://twitter.com/JBSchweitzer">Joseph Schweitzer</a> ⎯ (Ethereum Foundation)</li>
        <li><span class="italic">Add your nominee!</span></li>
      </ul>
    </div>

    <h2 class="head2">History</h2>
    <div class="text-lg">
      <ul class="list">
        <li><span class="italic">April 2, 2023</span> - first draft of the Manifesto</li>
        <li><span class="italic">April 5, 2023</span> - this website has been created</li>
        <li><span class="italic">April 6, 2023</span> - Twitter account <a href="https://twitter.com/EthereumEG">@EthereumEG</a> was born</li>
        <li><span class="italic">April 22, 2023</span> - Forum deployed at <a href="https://ethevents.club">ethevents.club</a></li>
      </ul>
    </div>

    <h2 class="head2">Funding</h2>
    <div class="text-lg">
      We are a non-profit, donation-backed collective.
    </div>

    <h2 class="head2">Join our community</h2>
    <div class="text-lg">
      We would be very grateful for any support or any feedback - everyone is welcome in our community. Join us and let's create a better future for Ethereum events together!
    </div>
    <div class="text-lg mt-3">
      Our Forum: <a href="https://ethevents.club">ethevents.club</a>
    </div>
    <div class="text-lg mt-3">
      Our public Telegram group: <a href="https://t.me/EthereumEG">t.me/EthereumEG</a>
    </div>
    <div class="text-lg mt-3">
      Our Twitter: <a href="https://twitter.com/EthereumEG">@EthereumEG</a>
    </div>
    <div class="text-lg mt-3">
      If you would like to become a founding gardener in this pre-genesis phase, please ask one of the current gardeners for an invitation.
    </div>

    <div class="mt-16 border border-x-0 border-t-1 border-b-0 pt-6 border-black/10 text-black/50">
      The source code of this website: <a href="https://github.com/ethereumeg/web">https://github.com/ethereumeg/web</a>
    </div>

  </div>
</div>

<style lang="postcss">

  .projects li a, .projects li i {
    @apply text-xl;
  }

  .head2 {
    @apply text-2xl italic mt-10 mb-5;
  }
  .list {
    @apply ml-2;
  }
  .list li, .list-number li {
    @apply pl-3 mb-2.5;
  }
  .list-number {
    @apply ml-9;
    list-style-type: decimal;
  }
  .list li:before {
    content: '⟠';
    @apply pr-2.5 text-teal-500;
  }

  a {
    @apply underline hover:no-underline;
  }

</style>
