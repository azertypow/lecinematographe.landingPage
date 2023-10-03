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
                        <div class="inf-input inf-input-text">
                            <input
                                type="text"
                                name="inf[1]"
                                data-inf-meta="1"
                                data-inf-error="Merci de renseigner une adresse email"
                                required="required"
                                placeholder="Email"
                            >
                        </div>
                        <div class="inf-submit">
                            <input type="submit"
                                   name=""
                                   value="Envoyer"
                            >
                        </div>
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
}
</style>
