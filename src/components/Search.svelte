<script>
  export let item;
</script>

<div class="name">
  {item.toUpperCase()}
  <img src={`https://sozluk.gov.tr/assets/img/isaret/${item.toLowerCase()}.gif`} alt="" />
</div>
