<script>

</script>

<article class="article">
    <h2 class="article-header">
        Projects
    </h2>
    <section class="section">
        <div class="list">
            <div class="list-item">
                <p>
                    pulsehub
                </p>
                <span>
                    ->
                </span>
            </div>
        </div>
    </section>
</article>


<style lang="scss">
    .article {
        padding: 1rem;
        background-color: $first;
        border-radius: $radius;
        display: flex;
        flex-direction: row;
        gap: 1rem;
        .section {
            .list {
                list-style: none;
                .list-item {
                    display: flex;
                    align-items: end;
                    justify-content: space-between;
                    height: 100px;
                    padding: 1rem;
                    color: $bg;
                    text-decoration: underline;
                    text-align: end;
                    background-color: $second;
                    width: 200px;
                    border-radius: $radius;
                }
            }
        }
    }

</style>
