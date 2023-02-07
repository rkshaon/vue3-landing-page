<template>
  <div class="container">
    <div class="row">
      <div class="col-md-7">
        <img src="https://picsum.photos/id/237/600/400" alt="">
      </div>
      <div class="col-md-5">
        <h1 class="font-weight-light">Tagline</h1>
        <p class="mt-4">Paragraphs are the building blocks of papers. Many students define paragraphs in terms of length: a paragraph is a group of at least five sentences, a paragraph is half a page long, etc. In reality, though, the unity and coherence of ideas among sentences is what constitutes a paragraph. A paragraph is defined as “a group of sentences or a single sentence that forms a unit” (Lunsford and Connors 116). Length and appearance do not determine whether a section in a paper is a paragraph. For instance, in some styles of writing, particularly journalistic styles, a paragraph can be just one sentence long. Ultimately, a paragraph is a sentence or group of sentences that support one main idea. In this handout, we will refer to this as the “controlling idea,” because it controls what happens in the rest of the paragraph.</p>
        <button class="btn btn-primary">Call to action!</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'JumbotronComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
