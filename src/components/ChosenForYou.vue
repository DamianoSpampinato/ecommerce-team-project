<script>
    export default{
        name: 'ChosenForYou',
        data(){
            return{
                chosenCard: [
                    {
                        heading: 'Articoli moda consigliati per te',
                        firstImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                        secondImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                    },
                    {
                        heading: 'Ottimi prezzi sulla moda donna',
                        firstImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                        secondImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                    },
                    {
                        heading: 'Made in italy',
                        firstImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                        secondImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                    },
                    {
                        heading: 'Riprendi da dove hai lasciato',
                        firstImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                        secondImg: 'https://img01.ztat.net/article/spp-media-p1/ce04c37cdd77453188f507568b09edde/925de377f0f34cffb533586d0855ea4c.jpg?imwidth=762',
                    },
                ]
            }
        },
    }

</script>

<template>
    <section>
        <!-- Single card template -->
        <div class="ms-container my-3">
            <div v-for="card in chosenCard" class="card">
                <h5>{{ card.heading }}</h5>
                <div class="img-wrapper">
                    <img :src="card.firstImg" alt="product image">
                    <img :src="card.secondImg" alt="product image">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
.ms-container{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    .card{
        border-radius: 0;
        h5{
            padding-left: 5px;
            font-weight: bold;
        }
        width: calc((100% / 4) - 15px);
        padding: 10px;
        .img-wrapper{
            display: flex;
            img{
            width: 50%;
            padding: 5px;
            }
        }
    }
}
</style>