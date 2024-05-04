---
title: 'detail-1'
layout: '../../layouts/Layout.astro'
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/img8.jpg" alt="Kid completo" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Proximamente</h2>
   <h4>Proximamente en nuestra pagina kid completo.</h4>
   <p class='max-w-md'>Próximamente en nuestra página: Kit Completo. Prepárate para descubrir el conjunto definitivo que reúne todo lo que necesitas para crear looks impresionantes. Nuestro Kit Completo incluye una selección cuidadosa de productos de alta calidad, desde sombras de ojos hasta labiales y accesorios de maquillaje. Ideal para maquilladores profesionales y entusiastas del maquillaje, este kit te permitirá experimentar y reinventar tu estilo con facilidad. Mantente atento para obtener información exclusiva y sé el primero en tener en tus manos este kit imprescindible para llevar tu maquillaje al siguiente nivel.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'>Comprar</button>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }
</style>
