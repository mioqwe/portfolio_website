<script>

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

    <section>
        <h2>
            Skills
        </h2>  
        <ul>
            <li>
                something
            </li>
            <li>
                something
            </li>
            <li>
                something
            </li>
            <li>
                something
            </li>
        </ul>

    </section>
</article>

<style lang="scss">
    article {
        margin-block: 1rem;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        gap: 1rem;
        .article-header {
            font-size: 3.5rem;
            display: flex;
            flex-direction: column;
            align-items: start;
            gap: 0.4rem;
            text-align: center;
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
                    border-radius: $radius;
                    padding: 0.4rem;
                    height: 100%;
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
            width: 100%;
            background-color: $second;
            border-radius: $radius;
            padding: 20px;
        }
    }


</style>