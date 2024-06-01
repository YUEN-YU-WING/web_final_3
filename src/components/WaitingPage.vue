<template>
  <div>
    <p>
      由於空間發生異常，憑空出現大量金人，
    </p>
    <p>
      把你的網路控到動不了。
    </p>
    <p>
      請耐心等待我們的專業團隊把它們清理掉
    </p>
    <section>
      <div class="enemys">
          <img src="/enemy.png" alt="enemy" style="width:22%">
          <img src="/enemy.png" alt="enemy" style="width:22%">
          <img src="/enemy.png" alt="enemy" style="width:22%">
      </div>
    </section>
    <section>
        <div>

        </div>
        <div class="people">
          <h2>
            你的網路  ⭣
          </h2>
          <img src="/imprisoned.png" alt="imprisoned" style="width:30%">
        </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style scoped>
p {
  text-align: center;
  font-size: 2rem;
  color: #f4f805dc;
  line-height: 1.5rem;
}
h2 {
  text-align: center; /* 修改此處 */
  font-size: 2rem;
  color: #f4f805dc;
}

.enemys {
  text-align: center;
}

.people {
  text-align: center;
}
</style>