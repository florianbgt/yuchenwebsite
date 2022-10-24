<template>
    <div class="mx-auto" style="max-width: 150px">
        <b-carousel :interval="3000" class="w-100">
            <b-carousel-slide v-for="image in images" :key="image.path">
                <template v-slot:img>
                    <nuxt-img :src="image.path" :alt="image.alt" style="width: 100%; height: 100px; object-fit: contain"/>
                </template>
            </b-carousel-slide>
        </b-carousel>
    </div>
</template>

<script>
export default {
    data() {
        return {
            images: [
                {path: '/python.png', alt: 'python'},
                {path: '/tensorflow.png', alt: 'tensorflow'},
                {path: '/numpy.png', alt: 'numpy'},
                {path: '/tableau.png', alt: 'tableau'},
                {path: '/scikit.png', alt: 'scikit'},
                {path: '/R.png', alt: 'R'},
                {path: '/google_cloud_platform.png', alt: 'google cloud platform'},
                {path: '/django.png', alt: 'django'},
                {path: '/postgres.png', alt: 'postgres'},
            ]
        }
    }
}
</script>