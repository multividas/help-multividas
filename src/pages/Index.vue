<template>
  <MainLayout>
    <header class="mv-header mv-header-bg px-3 px-sm-4">
      <h1 class="fw-bold text-primary">How can we help?</h1>
      <div class="col-md-4 offset-md-4 my-2">
        <form class="position-relative" role="search">
          <input
            class="form-control"
            type="search"
            placeholder="Search for a topic"
            aria-label="Search"
          />
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="icon icon-tabler icon-tabler-search position-absolute"
            width="20"
            height="20"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M10 10m-7 0a7 7 0 1 0 14 0a7 7 0 1 0 -14 0"></path>
            <path d="M21 21l-6 -6"></path>
          </svg>
        </form>
      </div>
    </header>
    <main class="container px-4 py-2 my-4 py-md-5 my-md-2">
      <div class="card">
        <div class="card-body">
          <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ut
            repudiandae fuga quo tenetur deserunt ad culpa, odio eaque
            consectetur laudantium vero quia veniam provident at architecto
            debitis molestiae perferendis aut sapiente incidunt consequuntur
            quae sequi dolore rem. Nulla sint, facilis ut laudantium praesentium
            vero eum accusamus quo perspiciatis nam sapiente molestias amet quam
            nihil doloribus ea, modi quia suscipit similique possimus molestiae
            quis, reprehenderit optio temporibus? Earum dolorem incidunt
            possimus impedit maiores, eaque atque error necessitatibus nesciunt
            adipisci odit aliquam quidem molestias itaque. Maiores laborum quod
            sed dolore dolorum aspernatur autem sint eligendi voluptatibus,
            cupiditate deserunt corrupti facere quos asperiores!
          </p>
        </div>
      </div>
    </main>
  </MainLayout>
</template>

<script>
export default {
  metaInfo: {
    title: "Help Center",
  },
};
</script>

<style>
</style>

<style scoped>
input[type="search"] {
  padding-right: 35px;
}

svg.icon-tabler-search {
  top: 10px;
  right: 10px;
  color: rgb(162, 162, 162);
}

input[type="search"]::placeholder {
  color: rgb(162, 162, 162);
}
</style>
