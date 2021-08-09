<script>
  let exampleText = "Hello world";
  // Note: it works if we use
  // exampleText = "<span>Hello world</span>"
</script>

<h1>Bug reproduction</h1>
<p>We expect the `exampleText` to be displayed below:</p>
<p>
  {#if false}hello{/if}
  {#if false}hello{/if}
  {@html exampleText}
</p>
