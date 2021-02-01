<template>
  <main class="container">
    <section class="card">
      <img src="../assets/1.jpeg" alt="" />
      <div>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ex
          tempora? Doloribus ipsum corrupti iusto necessitatibus culpa mollitia
          in omnis consequatur, eligendi beatae. Alias laboriosam optio amet
          cupiditate, harum, nisi rerum fuga commodi molestiae reprehenderit
          ipsum labore reiciendis, neque sed doloremque officiis quae eius
          dolores quaerat corrupti. Ipsa, voluptatibus debitis!
        </p>
        <button>Watch Now</button>
      </div>
    </section>
    <section class="card" data-aos="fade-left">
      <img src="../assets/2.jpeg" alt="" />
      <div>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ex
          tempora? Doloribus ipsum corrupti iusto necessitatibus culpa mollitia
          in omnis consequatur, eligendi beatae. Alias laboriosam optio amet
          cupiditate, harum, nisi rerum fuga commodi molestiae reprehenderit
          ipsum labore reiciendis, neque sed doloremque officiis quae eius
          dolores quaerat corrupti. Ipsa, voluptatibus debitis!
        </p>
        <button>Watch Now</button>
      </div>
    </section>
    <section class="card" data-aos="fade-right">
      <img src="../assets/3.jpeg" alt="" />
      <div>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ex
          tempora? Doloribus ipsum corrupti iusto necessitatibus culpa mollitia
          in omnis consequatur, eligendi beatae. Alias laboriosam optio amet
          cupiditate, harum, nisi rerum fuga commodi molestiae reprehenderit
          ipsum labore reiciendis, neque sed doloremque officiis quae eius
          dolores quaerat corrupti. Ipsa, voluptatibus debitis!
        </p>
        <button>Watch Now</button>
      </div>
    </section>
    <section class="card" data-aos="fade-left">
      <img src="../assets/4.jpeg" alt="" />
      <div>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ex
          tempora? Doloribus ipsum corrupti iusto necessitatibus culpa mollitia
          in omnis consequatur, eligendi beatae. Alias laboriosam optio amet
          cupiditate, harum, nisi rerum fuga commodi molestiae reprehenderit
          ipsum labore reiciendis, neque sed doloremque officiis quae eius
          dolores quaerat corrupti. Ipsa, voluptatibus debitis!
        </p>
        <button>Watch Now</button>
      </div>
    </section>
    <section class="card" data-aos="fade-right">
      <img src="../assets/5.jpeg" alt="" />
      <div>
        <h3>Lorem ipsum dolor sit amet.</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, ex
          tempora? Doloribus ipsum corrupti iusto necessitatibus culpa mollitia
          in omnis consequatur, eligendi beatae. Alias laboriosam optio amet
          cupiditate, harum, nisi rerum fuga commodi molestiae reprehenderit
          ipsum labore reiciendis, neque sed doloremque officiis quae eius
          dolores quaerat corrupti. Ipsa, voluptatibus debitis!
        </p>
        <button>Watch Now</button>
      </div>
    </section>
  </main>
</template>

<script>
import AOS from "aos";
import "aos/dist/aos.css";

export default {
  created() {
    AOS.init({
      offset: 600,
      duration: 1500,
    });
  },
};
</script>

<style>
.container {
  max-width: 800px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
img {
  width: 100%;
}
.card {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  background: #f1f1f1;
  margin-bottom: 2rem;
}
.card h3 {
  margin-bottom: 2rem;
}
.card div {
  margin: auto auto;
  padding: 2rem;
}
.card:nth-child(even) img {
  order: 2;
}
button {
  margin-top: 1rem;
  background-color: #000;
  color: #fff;
  padding: 0.8rem 1.8rem;
  cursor: pointer;
  border-radius: 0.5rem;  
}

button:hover {
  opacity: 0.45;
}

@media (max-width: 768px) {
  .card {
    display: block;
  }
}
</style>
