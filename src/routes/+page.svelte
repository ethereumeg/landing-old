<script>

  import SvelteMarkdown from 'svelte-markdown'

  const manifesto = `
In the sprawling landscape of *[The Infinite Garden](https://ethereum.foundation/infinitegarden)*, we stand as a group of nonconformist, working to cultivate and nurture the Ethereum community. We are a diverse assembly of individuals from different fields and backgrounds, united by our passion for decentralized technologies and human coordination.

Our mission is to promote and support community events and gatherings, and to foster a culture of inclusivity, diversity, and open participation. Embrace the unique local characteristics of every corner of the world, and celebrate the voluntary work that is done with meaning and purpose.

We stand in opposition to commercialization and unification, rejecting the notion that our community should be homogenized and commoditized. Instead, we strive to create a decentralized and grassroots movement that highlights the differences and diversity of our global community.

As a group of people with cypherpunk in the hearth, we cherish the basic principles of freedom and collaboration that underlie Ethereum. Our diverse membership, comprising both solarpunks and lunarpunks, brings a range of perspectives and energies to our mission. 

Let us sow the seeds of a vibrant and inclusive community, one that will bloom and flourish for generations to come.

*Your Ethereum Event Gardeners*
`

</script>

<svelte:head>
  <title>ETHevents.club</title>
</svelte:head>

<div class="grid m-6 justify-center">
  <div class="max-w-5xl mt-5 grid justify-center mb-16">
    <h1 class="text-5xl">Ethereum Event Gardeners</h1>

    <h2 class="head2 !mb-0">Manifesto</h2>
    <div class="manifesto mt-2 p-6 bg-black/5">
      <SvelteMarkdown source={manifesto} />
    </div>

    <h2 class="head2">Our projects</h2>
    <div class="text-lg">
      <ul class="list-disc projects">
        <li><a href="https://chronicle.ethevents.club">chronicle</a> ⎯ historical archive of community ETH events (in development)</li>
        <li><a href="https://github.com/ethevents-club/confeth">confeth</a> ⎯ state-of-the-art conference/hackathon planning and managing tool (draft)</li>
        <li><i class="italic">"The Etherevent Field Guide"</i> ⎯ knowledge-base with best practices for ETH event organisers (idea)</li>     
      </ul>
    </div>

    <h2 class="head2">Roadmap</h2>
    <div class="text-lg">
      The initiative will be widely discussed within Q2/2023 on EthereumZurich and ETHDam, and published (genesis) within ETHPrague, in early June 2023.
    </div>


    <h2 class="head2">Join our community</h2>
    <div class="text-lg ml-2">
      → <a href="https://t.me/+J8yr3DY0xPg2ZWFk">Telegram group</a>
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
  .list-disc {
    @apply ml-7;
  }

  a {
    @apply underline hover:no-underline;
  }

</style>