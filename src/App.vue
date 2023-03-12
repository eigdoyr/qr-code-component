<template>
  <main>
    <div class="container">
      <div class="card">
        <img
          class="img-qr-code"
          src="./assets/image-qr-code.png"
          alt="qrcode"
        />
        <div class="lead-text-container">
          <h1 class="title">
            Improve your front-end skills by building projects
          </h1>
          <p class="lead-text">
            Scan the QR code to visit Frontend Mentor and take your coding
            skills to the next level
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.container {
  max-width: 1440px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 0 auto;
  height: 100vh;
}

.card {
  background-color: var(--dark);
  max-width: 19.5rem;
  justify-content: center;
  border-radius: 1.35rem;
  padding: 1rem;
  box-shadow: 12px 12px 52px #afaeae31, -12px -12px 52px #faf9f905;
}
.img-qr-code {
  border-radius: 0.625rem;
}

.lead-text-container {
  padding: 1.75rem 1rem;
}

.title {
  color: var(--light-blue);
  font-size: 1.35rem;
  font-weight: 700;
  line-height: 1.65rem;
}

.lead-text {
  color: var(--light-gray);
  font-size: 1rem;
  font-weight: 400;
  padding-top: 1rem;
  line-height: 1.25rem;
}
</style>
