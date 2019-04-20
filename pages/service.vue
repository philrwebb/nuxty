<template>
  <section class="container">
    <h1>How we Make Nuxt</h1>
    <p class="subheading">There is method in our madness.</p>
    <div class="textContainer">
      <div>
        <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.
        </p>
      </div>
      <div><p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.</p></div>
      <div><p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.</p></div>
      <div><p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.</p></div>
      <div><p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.</p></div>
      <div><p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae culpa vero soluta, voluptatibus quasi ipsa saepe repudiandae harum qui voluptate laudantium, doloremque hic repellat mollitia temporibus sit voluptates praesentium. Labore consequatur ipsam quia ipsum! Quas, saepe voluptatibus exercitationem at iste a excepturi, neque laboriosam mollitia nostrum delectus quod deserunt impedit.</p></div>
    </div>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: "Nuxt Services",
      meta: [
        {
          name: "description",
          content: "This is my services description here."
        },
        { name: "keywords", content: "services nuxt" }
      ]
    };
  }
};
</script>

<style scoped>
@media only screen and (min-width: 501px) {
  .textContainer {
    display: grid;
    grid-template-columns: 1fr 1fr;
  }
  .textContainer  p {
    padding: 1.5em;
    border: 1px solid grey;
    font-size: 1rem;
    line-height: 1.5em;
  }
}

@media only screen and (max-width: 500px) {
  .textContainer {
    display: grid;
    grid-template-columns: 1fr;
  }
  .textContainer p {
    padding: 0.5em;
    border: 1px solid grey;
    font-size: 0.8em;
    line-height: 1.4em;
  }
}
</style>
