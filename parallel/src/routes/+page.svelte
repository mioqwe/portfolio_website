<script>
    import Second from "$lib/components/second.svelte";
</script>



<article>
    <h1 class="article-header">
        <div class="info-div">
            <img src="/hiro.webp" alt="avatar">

            <div class="info">
                <p>yO 21</p>
                <p>devExp 2</p>
            </div>
        </div>
        Storozhyk Egor
    </h1>

    <section class="section">
        <h2 class="article-header">
            Skills
        </h2>  
        <ul class="section-content">
            <li>
                Front 1 svelte 
            </li>
            <li>
                Beckend 1 django, celery, redis, postgres, nginx
            </li>
            <li>
                Languages 1 ENG BG UA 
            </li>
            <li>
                something
            </li>
        </ul>

    </section>
</article>

<Second>
</Second>


<style lang="scss">
    article {
        margin-block: 1rem;
        display: flex;
        @media screen and (max-width: 600px) {
            flex-direction: column;
        }
        @media screen and (min-width: 600px) {
            flex-direction: row;
        }
        justify-content: space-between;
        gap: 1rem;
        .article-header {
            font-size: 2.5rem;
            display: flex;
            align-items: start;
            gap: 1rem;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            .info-div {
                display: flex;
                flex-direction: row;
                justify-content: space-between;
                width: 100%;
                gap: 0.5rem;
                img {
                    width: 100px;
                    height: 100px;
                    border-radius: 50%;
                }
                .info {
                    display: flex;
                    flex-direction: column;
                    gap: 1.2rem;
                    box-sizing: border-box;
                    background-color: $first;
                    
                    @media screen and (max-width: 600px) {
                        border-top-left-radius: $radius;
                        border-bottom-left-radius: $radius;
                    }
                    @media screen and (min-width: 600px) {
                        border-radius: $radius;
                
                    }
                    padding: 0.4rem;
                    width: 60%;
                    font-size: 1rem;
                    p {
                        margin: 0;
                        padding: 0;
                    }
                }
            }
        }
        section {
            @media screen and (max-width: 600px) {
                border-radius: 0;
            }
            @media screen and (min-width: 600px) {
                border-radius: $radius;
                
            }
            background-color: $second;
            padding: 20px;
            display: flex;
            gap: 1rem;
            flex-direction: row;
            .section-content {
                display: flex;
                width: 100%;
                height: 100%;
                flex-direction: column;
                gap: 1rem;
                font-size: 1.4rem;
                list-style: none;
            }
        }
    }


</style>