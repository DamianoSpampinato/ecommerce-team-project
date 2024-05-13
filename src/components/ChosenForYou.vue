<script>
    export default{
        name: 'ChosenForYou',
        data(){
            return{
                chosenCard: [
                    {
                        heading: 'Articoli moda consigliati per te',
                        firstImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                        secondImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                    },
                    {
                        heading: 'Ottimi prezzi sulla moda donna',
                        firstImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                        secondImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                    },
                    {
                        heading: 'Made in italy',
                        firstImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                        secondImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                    },
                    {
                        heading: 'Riprendi da dove hai lasciato',
                        firstImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                        secondImg: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zalando.it%2Fnike-performance-free-rn-50-2021-scarpe-running-neutre-blackwhitedark-smoke-grey-n1242a27o-q12.html&psig=AOvVaw14lEFWm3M-NOVNhEcSFYUk&ust=1715699319679000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOj865n0ioYDFQAAAAAdAAAAABAJ',
                    },
                ]
            }
        },
    }

</script>

<template>
    <section>
        <!-- Single card template -->
        <div class="ms-container">
            <div v-for="card in chosenCard" class="card">
                <h5>{{ chosenCard.heading }}</h5>
                <img :src="{{ chosenCard.firstImg }}" alt="product image">
                <img :src="{{ chosenCard.secondImg }}" alt="product image">
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
.ms-container{
    display: flex;
    justify-content: space-between;
    .card{
        width: calc((100 / 4) -15px);
    }
}
</style>