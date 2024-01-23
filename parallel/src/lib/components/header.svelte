<script>


</script>


<header>
    <div class="content">
        <p>
            Portfolio
        </p>
        <button type="button" name="contact" class="contact-us">
            contact me 
        </button>
    </div>
</header>


<style lang="scss">
    header {
        // background-color: ($first-rgb / 75%);
        border-bottom-left-radius: $radius;
        border-bottom-right-radius: $radius;
        background-color: $first-rgb-opacity;
        .content {
            padding: 20px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            .contact-us {
               background-color: $second; 
               outline: none;
               padding-inline: 14px;
               padding-block: 8px;
               border: none;
               border-radius: $radius*2;
            }

        }


    }


</style>
