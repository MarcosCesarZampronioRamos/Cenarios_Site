<title>Librelato</title>
<body>
  <div class="logo">
    <img src="Librelato - Cromada - Horizontal.png" alt="LBT" />
  </div>
</body>
<div class="carousel">
  <div class="carousel">
    <div class="carousel__item carousel__item--left">
      <img
        src="file:///C:/Users/marcos.ramos/Downloads/cenario.webp"
        alt="Dashboard Armazenamento"
      />
      <div class="carousel__text">
        <h3>Dashboard Cenários</h3>
        <p class="read-more">
          <a
            href="file:///C:/Users/marcos.ramos/Desktop/INTELIGENCIA%20COMERCIAL/PROFISSIONAIS/MARCOS%20CESAR/LIBRELATO/HTMLL&CSS/INTRODU%C3%87%C3%83O%20AO%20HTML/Cenarios.html"
            ><button class="btn">Acessar</button></a
          >
        </p>
      </div>
    </div>
    <div class="carousel">
      <div class="carousel">
        <div class="carousel__item carousel__item--left">
          <img src="Armazans.PNG" alt="Dashboard Armazenamento" />
          <div class="carousel__text">
            <h3>Dashboard Capacidade Armazenagem</h3>
            <p class="read-more">
              <a
                href="file:///C:/Users/marcos.ramos/Desktop/INTELIGENCIA%20COMERCIAL/PROFISSIONAIS/MARCOS%20CESAR/LIBRELATO/HTMLL&CSS/INTRODU%C3%87%C3%83O%20AO%20HTML/Capacidade_Armazens.html"
                ><button class="btn">Acessar</button></a
              >
            </p>
          </div>
        </div>
        <div class="carousel__item carousel__item--main">
          <img src="Safra.PNG" alt="Dashboard Safra" />
          <div class="carousel__text">
            <h3>Dashboard Safra</h3>
            <p class="read-more">
              <a
                href="https://app.powerbi.com/Redirect?action=OpenReport&appId=27f3bf23-2bf9-4683-8c52-1519105e9107&reportObjectId=001a798b-c3d7-41f8-a3de-68e1f168ce70&ctid=5e152adc-3bf6-4e07-a817-98fed9142abd&reportPage=c0429ff7216ebb1a60d3&pbi_source=appShareLink&portalSessionId=e599f8cc-e91b-4b65-be74-4f1ade558d71"
                ><button class="btn">Acessar</button></a
              >
            </p>
          </div>
        </div>
        <div class="carousel__item carousel__item--right">
          <img src="Cotação.PNG" alt="dog" />
          <div class="carousel__text">
            <h3>Dashboard Cotações</h3>
            <p class="read-more">
              <a
                href="https://oespecialista.com.br/safrapay-rio-grande-do-sul-analise-banco-safra/"
                ><button class="btn">Acessar</button></a
              >
            </p>
          </div>
        </div>
        <div class="carousel__item carousel__item--right">
          <img src="Esportação.PNG" alt="dog" />
          <div class="carousel__text">
            <h3>Dashboard Exportação/Importção</h3>
            <p class="read-more">
              <a
                href="https://app.powerbi.com/Redirect?action=OpenReport&appId=27f3bf23-2bf9-4683-8c52-1519105e9107&reportObjectId=66f99eb8-96e0-49ee-b4d2-c4807fec4e94&ctid=5e152adc-3bf6-4e07-a817-98fed9142abd&reportPage=d8b86eb78028089880a5&pbi_source=appShareLink&portalSessionId=e599f8cc-e91b-4b65-be74-4f1ade558d71"
                ><button class="btn">Acessar</button></a
              >
            </p>
          </div>
        </div>
        <div class="carousel__btns">
          <button class="carousel__btn" id="leftBtn">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                fill-rule="evenodd"
                d="m15 4l2 2l-6 6l6 6l-2 2l-8-8z"
              />
            </svg>
          </button>
          <button class="carousel__btn" id="rightBtn">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                fill-rule="evenodd"
                d="m9.005 4l8 8l-8 8L7 18l6.005-6L7 6z"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>
    <style>
      *,
      *::after,
      *::before {
        margin: 0;
        padding: 0;
        box-sizing: inherit;
        font-family: "Montserrat", sans-serif;
      }
      html {
        font-size: 62.5%;
      }
      body {
        box-sizing: border-box;
        font-size: 1.6rem;
        background-color: rgb(24, 27, 30);
        color: #fff;
        display: grid;
        place-items: center;
        min-height: 100vh;
      }

      .logo {
        position: absolute;
        top: 20px;
        left: 20px;
      }

      .logo img {
        height: 50px;
      }

      .carousel {
        position: relative;
      }
      .carousel__item {
        position: relative;
        height: 30rem;
        width: 45rem;
        border-radius: 3px;
        overflow: hidden;
        box-shadow: 0 1rem 4rem rgba(0, 0, 0, 0.5);
        position: absolute;
        transform: translate(-50%, -50%) scale(0.1);
        z-index: 0;
        transition: all 0.2s linear;
      }
      .carousel__item img {
        width: 100%;
        min-height: 100%;
        object-fit: cover;
      }

      .carousel__item--main {
        transform: translate(-50%, -50%) scale(1);
        z-index: 2;
        cursor: pointer;
      }

      .carousel__item--left {
        transform: translate(-110%, -50%) scale(0.9);
        z-index: 1;
      }
      .carousel__item--right {
        transform: translate(10%, -50%) scale(0.9);
        z-index: 1;
      }
      .carousel__item--left img,
      .carousel__item--right img {
        filter: grayscale(80%);
      }

      .carousel__item--right:hover {
        transform: translate(10%, -50%) scale(1.2);
        z-index: 3;
        cursor: pointer;
      }
      .carousel__item--left:hover {
        transform: translate(-110%, -50%) scale(1.2);
        z-index: 3;
        cursor: pointer;
      }
      .carousel__item--main:hover {
        transform: translate(-50%, -50%) scale(1.2);
      }
      .carousel__item:hover > .carousel__text {
        opacity: 1;
      }
      .carousel__item:hover img {
        filter: grayscale(0%);
      }

      .carousel__text {
        position: absolute;
        bottom: 0;
        z-index: 4;
        opacity: 0;
        transition: opacity 0.2s;
        width: 100%;
        text-align: center;
        background-color: rgba(0, 0, 0, 0.5);
        padding: 2rem 1rem;
        color: #fff;
      }

      .carousel__btns {
        position: absolute;
        transform: translate(-50%, 22rem);
        display: flex;
        gap: 2rem;
      }
      .carousel__btn {
        background-color: transparent;
        height: 5rem;
        width: 5rem;
        border-radius: 50%;
        border: 1px solid currentColor;
        color: #fff;
        cursor: pointer;
      }
      .carousel__btn svg {
        height: 1.8rem;
        width: 1.8rem;
      }
      .carousel__btn:hover {
        color: #aaa;
      }
    </style>
    <script>
      "use strict";

      const carouselItems = document.querySelectorAll(".carousel__item");
      console.log(carouselItems);
      let currentItem = document.querySelector(".carousel__item--main");
      const leftBtn = document.querySelector("#leftBtn");
      const rightBtn = document.querySelector("#rightBtn");

      rightBtn.addEventListener("click", function () {
        currentItem = document.querySelector(".carousel__item--right");
        const leftItem = document.querySelector(".carousel__item--main");
        carouselItems.forEach((item, i) => {
          item.classList = "carousel__item";
        });
        currentItem.classList.add("carousel__item--main");
        leftItem.classList.add("carousel__item--left");
        const currentId = Array.from(carouselItems).indexOf(currentItem);
        const rightItem =
          currentId === carouselItems.length - 1
            ? carouselItems[0]
            : carouselItems[currentId + 1];
        rightItem.classList.add("carousel__item--right");
      });

      leftBtn.addEventListener("click", function () {
        currentItem = document.querySelector(".carousel__item--left");
        const rightItem = document.querySelector(".carousel__item--main");
        carouselItems.forEach((item, i) => {
          item.classList = "carousel__item";
        });
        currentItem.classList.add("carousel__item--main");
        rightItem.classList.add("carousel__item--right");
        const currentId = Array.from(carouselItems).indexOf(currentItem);
        const leftItem =
          currentId === 0
            ? carouselItems[carouselItems.length - 1]
            : carouselItems[currentId - 1];
        leftItem.classList.add("carousel__item--left");
      });
    </script>
  </div>
</div>
