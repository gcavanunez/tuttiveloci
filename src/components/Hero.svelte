<script>
  import Button from './ui/Button.svelte';
  let src = 'images/tutti-veloci-logo.png';
	let name = 'Tutti Veloci';
</script>

<section id="inicio" class="h-screen bg-bottom bg-cover 
  bg-no-repeat flex flex-col p-2 justify-center items-center bg-hero">
  <!-- TODO: Parallax, chevron hacia siguiente sección, línea al hacer click al botón. RNF: animación ingreso -->
  <img {src} alt={name} class="w-3/4 lg:w-1/2 mb-16 sm:mb-0" />
  <Button text="Hacer Pedido" type="button" />

</section>
