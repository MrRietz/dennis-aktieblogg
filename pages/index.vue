<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">Välkommen till Dennis aktieblogg</h1>
      <h2 class="subtitle text-center">
        En ekonomiblogg som fokuserar på att ge inspiration och tips kring aktier, fonder & ETF:er. Let's get rich
        together!
      </h2>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>