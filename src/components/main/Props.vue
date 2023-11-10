<template>
    <div class="col-2">
        <div>
            <img :src="img" :alt="title"/>
            <div>
                <h6 class="title text-light">{{ title }}</h6>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    nome: 'Props',
    props: {
        img: String,
        title: String
    }

}
</script>

<style lang="scss" scoped>
img {
  width: 200px;
  height: 200px;
}
.title {
  width: 90%;
  padding: 5px 0;
}
</style>