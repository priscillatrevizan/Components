<script>
export default {
  name: "Content",
};
</script>

<template>
  <div class="card-content">
    <img src="../assets/img/image-qr-code.png" alt="qr-code" class="img-code">
    <div class="text-content">
      <h1>Improve your front-end skills by building projects</h1>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level </p>
    </div>

  </div>
</template>

<style>
.card-content {
  display: flex;
  justify-content: center;
  flex-direction: column;
  padding: 16px;
  justify-content: center;
  align-items: center;
  border-radius: 20px;
  background: var(--color-white);
  box-shadow: 0px 25px 25px 0px rgba(0, 0, 0, 0.05);
  width: 320px;
  height: 499px;
  margin: 0 auto;
  margin-top: 65px;
}

.img-code {
  width: 288px;
  height: 288px;
  margin: 0 auto;
  border-radius: 10px;
}

.text-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  align-self: stretch;
  padding: 0px 22px;
  gap: 16px;
  font-family: var(--font-family);
  text-align: center;
}

.text-content h1 {
  font-size: var(--font-size-title);
  font-weight: var(--font-weight-bold);
  color: var(--color-slate-900);
  margin: 24px 0 0 0;
}

.text-content p {
  font-size: var(--font-size-paragraphy);
  font-weight: var(--font-weight-regular);
  color: var(--color-slate-500);
  box-sizing: border-box;
}

@media (min-width: 360px) {
  .card-content {
    max-width: 300px;
    max-height: 460px;
    align-items: center;
    margin: 0;
  }

  .img-code {
    width: 288px;
    height: 288px;
  }

  .text-content h2 {
    font-size: 20px;
  }
}
</style>
