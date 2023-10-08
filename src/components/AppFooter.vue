<template>
    <footer class="v-app-footer" >
        <div
            class="v-app-footer__newsletter-container"
        >
            <form
                    method="post"
                    action="https://newsletter.infomaniak.com/external/submit"
                    class="v-app-footer__newsletter-container__form"
                    target="_blank"
            >
                <input
                        type="email"
                        name="email"
                        style="display:none"
                />
                <input type="hidden"
                       name="key"
                       value="eyJpdiI6ImxEQmYwMU52ZkM0OGl4TlBVQWs4YmJtb1wvZ2Q0MkpIcGlZY3RPblZGeUxZPSIsInZhbHVlIjoiVEpHXC93ZVwvcCtPMTFnMGNTclpuU1RRMzNLZ1pKdUV2dVF4bjVnV05HUW1JPSIsIm1hYyI6IjE4NjNiNjNhYzY2MTE4YmFlNmQ0NmQ2ZDg3MWE1ZmY0YTEyYzFhZDU4NTQzZjNiMzdjY2I5ZGUzMTVkYTk3MWMifQ=="
                >
                <input
                        type="hidden"
                        name="webform_id"
                        value="15422"
                >

                <div class="inf-main_76f376382a50bd4859e50a81e701da10">
                    <h4>Newsletter</h4>
                    <div class="inf-success" style="display:none"><h4>C'est tout bon, merci !</h4>
                        <p><a href="#" class="inf-btn">&laquo;</a></p>
                    </div>
                    <div class="inf-content">
                        <input
                            type="text"
                            name="inf[1]"
                            data-inf-meta="1"
                            data-inf-error="Merci de renseigner une adresse email"
                            required="required"
                            placeholder="Votre Email"
                        >
                        <input type="submit"
                               name=""
                               value="Envoyer"
                        >
                    </div>
                </div>
            </form>
        </div>
    </footer>
</template>





<script lang="ts" setup>
defineProps<{
}>()

</script>





<style lang="scss" scoped >
.v-app-footer {
    background: var(--lc-color);
}

.inf-main_76f376382a50bd4859e50a81e701da10 {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding: 1rem .5rem;
    box-sizing: border-box;
    height: 2rem;
}

.inf-content {
    display: flex;
    align-items: center;

    > input {
        font-family: "DIN Dong", Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
        box-sizing: border-box;
        border: none;
        display: block;
        font-size: inherit;
        line-height: inherit;
        height: 1rem;
    }

    [type="text"] {
        background: transparent;
        border-bottom: solid 2px white;
        color: white;

        &::placeholder {
            color: white;
        }

        &:focus-visible {
            outline: none;
        }
    }
}
</style>
