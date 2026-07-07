<!-- <template>
  <h1>Contact Book</h1>
</template> -->

<ContactCard :contact="activeContact" />
<router-link
  :to="{
    name: 'contact.edit',
    params: { id: activeContact._id },
  }"
>
<span class="mt-2 badge badge-warning">
<i class="fas fa-edit"></i> Hiệu chỉnh</span>

</router-link>

<!-- <script setup></script> -->
