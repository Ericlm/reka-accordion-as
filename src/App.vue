<script setup lang="ts">
import { AccordionContent, AccordionHeader, AccordionItem, AccordionRoot, AccordionTrigger } from 'reka-ui';
</script>

<template>
  <AccordionRoot class="root" collapsible>
    <AccordionItem value="1">
      <AccordionHeader class="header">
        HEADER

        <AccordionTrigger>
          AccordionTrigger
        </AccordionTrigger>
      </AccordionHeader>

      <AccordionContent class="content" as="ul">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur soluta cum natus. Veritatis, exercitationem
        omnis quae cumque explicabo illum necessitatibus tenetur quam repellendus suscipit quos ipsam repudiandae qui
        reprehenderit eum provident adipisci enim sit nemo. Sed possimus exercitationem consequatur odio amet ullam
        maiores omnis. Quasi ea optio tempore ex, excepturi libero, possimus architecto ut, debitis doloribus
        necessitatibus dolor. Autem saepe, laboriosam odit animi obcaecati repudiandae numquam neque atque aspernatur,
        exercitationem culpa error quae earum iusto cumque sapiente. Pariatur error quae modi possimus in rerum, quos,
        beatae placeat minima incidunt eveniet natus! Cum, ab, a nihil harum praesentium, maiores deleniti quisquam
        cumque earum dignissimos ducimus laudantium. Et recusandae commodi ipsum quae, nisi, porro iste illum doloremque
        vel impedit cupiditate laudantium quo fuga! Cum amet, obcaecati veniam necessitatibus assumenda quo est eius
        culpa inventore numquam ea, unde delectus laboriosam maxime? Nisi, quis sapiente? Suscipit, amet aperiam,
        dignissimos quo nulla adipisci nihil, laborum totam accusamus maiores illo quam saepe tenetur. Consectetur illum
        voluptate perspiciatis cupiditate, officiis cum? Placeat ullam ipsum aperiam modi harum tempore! Consequatur at
        temporibus libero quas dolor exercitationem dicta assumenda quis ullam atque. Neque, id natus. Unde, sint
        voluptatem perspiciatis illum nobis voluptatum fuga. Impedit explicabo ad, doloremque nostrum quas aperiam
        magnam assumenda, aut laboriosam omnis optio hic, quidem saepe sequi fugit sint est possimus. Velit, voluptates
        repudiandae. Atque neque ducimus nisi, unde alias totam delectus rem, corrupti nihil illo, explicabo soluta
        reiciendis! Nam consequuntur praesentium tempora eius aperiam incidunt impedit id quam quaerat ex. Tempora
        perferendis cumque placeat libero quibusdam. Delectus modi ducimus hic, perferendis inventore adipisci quam
        animi ratione eligendi, impedit, cupiditate recusandae at autem? Neque mollitia possimus eveniet porro dolores
        dignissimos, ipsam molestias quod cumque atque veritatis vel eligendi illo. Similique est expedita voluptas
        quas, fugiat ad, vitae rerum delectus voluptates consequatur debitis. Quod illum vel maiores.
      </AccordionContent>
    </AccordionItem>
  </AccordionRoot>
</template>

<style scoped>
.root {
  width: 60%;
}

.header {
  background-color: pink;
  width: 100%;
  display: flex;
  justify-content: space-between;
  margin: 0;
}

.content {
  background-color: yellow;
}
</style>
