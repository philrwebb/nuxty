<template>
  <section class="container">
    <h1>How we Make Nuxt</h1>
    <p class="subheading">There is method in our madness.</p>
    <div class="textContainer">
      <div>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ipsa quo sed tenetur excepturi suscipit sunt aut rem, id placeat nulla asperiores laudantium accusantium neque natus. Inventore excepturi laboriosam quo eius odio, consectetur nostrum quaerat! Ratione eligendi quas veritatis provident! Magni, totam? Earum nulla rem doloribus sapiente quis, numquam excepturi repellat fugiat voluptatibus consequatur illum ad adipisci amet veniam sed non eaque facilis aspernatur, esse perferendis incidunt, dolores ipsum. Ipsam placeat aut laborum distinctio porro iusto quis odio voluptatibus, corporis hic vel quasi, tempora dolore nam! Numquam sapiente ipsum magnam voluptate consequatur. Reprehenderit iusto blanditiis quia. Assumenda, accusamus dolores numquam necessitatibus ipsum minus molestias iusto molestiae nostrum maxime, dignissimos aliquid repellat, quaerat a ex fuga vel distinctio labore aliquam. Ad, in id? Excepturi porro ullam quae aspernatur aliquam, neque quidem tenetur soluta doloribus vel ex? Hic impedit eligendi totam, corrupti dolore odio error dolorem. Suscipit tempora accusamus sint non reiciendis officia nam iste dicta sed debitis illo natus fuga facilis ea cum, atque, consectetur modi explicabo! Nobis aliquid, facilis iusto, debitis repellendus quidem animi perspiciatis ullam ea exercitationem blanditiis sint obcaecati vitae rerum mollitia? Illo deserunt alias, mollitia ipsa sint, nam autem suscipit, laboriosam natus quod quo temporibus minima beatae blanditiis?
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
