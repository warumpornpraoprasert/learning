<script>
  import Await from "$lib/Await.svelte";
  import BindInstance from "$lib/BindInstance.svelte";
  import BindThisCanvas from "$lib/BindThisCanvas.svelte";
  import Counter from "$lib/Counter.svelte";
  import Each from "$lib/Each.svelte";
  import Keyed from "$lib/Keyed.svelte";
import OnMountPhoto from "$lib/OnMountPhoto.svelte";
</script>

<svelte:head>
  <link
    rel="stylesheet"
    href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css"
  />
  <!-- <base href="/learning/"> -->
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
<br /><br />

<Counter msg="Hello" notmsg="CodeSandBox" />

<Each />

<Keyed />

<Await />

<i class="las la-battery-three-quarters" />
<i class="lab la-accessible-icon" />

<br />

<BindThisCanvas />

<br />

<BindInstance />

<OnMountPhoto />
