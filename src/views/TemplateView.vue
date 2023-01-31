<template>
    <div>
        <header>
          <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#" @click.prevent="$router.push({ name:'home' })">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" @click.prevent="$router.push({name:'about'})">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" @click.prevent="$router.push({name:'donar'})">Donar</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"  @click.prevent="$router.push({name:'donate'})">Donate</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"  @click.prevent="$router.push({name:'team'})">Team</a>
            </li>
           
            
          </ul>
        </div>
      </div>
          </nav>
        </header>

           <slot></slot>

        <footer-component></footer-component>
    </div>
  </template>

  <script>
  import FooterComponent from '@/components/FooterComponent.vue' 
  export default {
    name:'TemplateView',
    components:{FooterComponent}
  }
  </script>

  

  