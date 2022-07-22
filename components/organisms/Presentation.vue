<template>
  <div class="presentation">
  <p>
    Vivamus suscipit tortor eget felis porttitor volutpat. Quisque velit nisi, pretium ut lacinia in,
    elementum id enim. Curabitur non nulla sit amet nisl tempus convallis quis ac lectus. Pellentesque
    in ipsum id orci porta dapibus. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus.
    Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur non nulla sit amet nisl tempus convallis
    quis ac lectus. Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Proin eget tortor risus.
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  </p>
    <img src="@/assets/img/presentation.svg" alt="Apresentação do iBook"/>
  </div>
</template>


<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
@include screen('small', 'medium') {
  grid-template-columns: 1fr;
}
p {
  line-height: 26px;
}
img {
  max-width: 100%;
}
}
</style>
