<template>
  <footer>
    <nav class="navbar-dark bg-dark footerNav">
        <div>
            <input type="number" value="5" min="1" max="100000">
        </div>
    </nav>
  </footer>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>

<style>
.footerNav {
  padding: 20px;
  display: flex;
  justify-content: center;
}
</style>
