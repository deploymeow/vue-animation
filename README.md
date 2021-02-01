# vue-animation

+ aos (animation on scroller) 설치
```
yarn add aos
```

+ aos script 추가 및 initialize offset 및 duration 설정 @ App.vue <script>
```
import AOS from "aos";
import "aos/dist/aos.css";

export default {
  created() {
    AOS.init({
      offset: 600,
      duration: 1500,
    });
  },
}
```

+ template 에서 애니메이션이 필요한 부분에 data-aos prop 추가 @ Home.vue <template>
```
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

```

