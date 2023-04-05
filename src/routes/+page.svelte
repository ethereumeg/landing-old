<script>

  import SvelteMarkdown from 'svelte-markdown'

  const manifesto = `
In the sprawling landscape of the Infinite Garden, we stand as a group of nonconformist, working to cultivate and nurture the Ethereum community and their events. We are a diverse assembly of individuals from different fields and backgrounds, united by our passion for decentralized technologies and human coordination.

Our mission is to promote and support community events, and to foster a culture of inclusivity, diversity, and open participation. Embrace the unique local characteristics of every corner of the world, and celebrate the voluntary work that is done with meaning and purpose.

We stand in opposition to commercialization and unification, rejecting the notion that our community should be homogenized and commoditized. Instead, we strive to create a decentralized and grassroots movement that highlights the differences and diversity of our global community.

As a group of cypherpunks, we cherish the basic principles of freedom and collaboration that underlie Ethereum. Our diverse membership, comprising both solarpunks and lunarpunks, brings a range of perspectives and energies to our mission. 

Let us join hands and hearts. Let us sow the seeds of a vibrant and inclusive community, one that will bloom and flourish for generations to come.

*Your Ethereum Gardeners*
`

</script>

<svelte:head>
  <title>ETHevents.club</title>
</svelte:head>

<div class="grid m-6 justify-center">
  <div class="max-w-5xl mt-5 grid justify-center">
    <h1 class="max-w-3xl text-5xl mb-5">ETHevents.club</h1>
    <h2 class="text-2xl">Manifesto</h2>
    <div class="manifesto mb-5">
      <SvelteMarkdown source={manifesto} />
    </div>
  </div>
  <div class="text-xl">
    → <a href="https://t.me/+J8yr3DY0xPg2ZWFk" class="underline hover:no-underline">Telegram group</a>
  </div>
</div>

<style lang="postcss">
</style>