<script lang="ts">
    // import { Hamburger } from 'svelte-hamburgers'
    // import { copy } from 'svelte-copy'

    import clickOutside from "@svackages/click-outside-action";
    const awesomeCallback = () => console.log('AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHhh');
</script>

<!-- <Hamburger /> -->

<!-- <button use:copy={"something or other"}>
    Copy something -->
<!-- </button> -->

<div use:clickOutside={awesomeCallback}>
    AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHh
</div>