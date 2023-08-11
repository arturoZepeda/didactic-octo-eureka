<script>
import { reactive } from 'vue';

const puesto = reactive ({
    puesto: 'Desarrollador Web',
    empresa: 'Empresa',
    ubicacion: 'Remoto',
    fechaInicio: '2015',
    fechaFin: 'Presente',
    descripcion: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin nec mi ante. Etiam odio eros, placerat eu metus id, gravida eleifend odio. Vestibulum dapibus pharetra odio, egestas ullamcorper ipsum congue ac. Maecenas viverra tortor eget convallis vestibulum. Donec pulvinar venenatis est, non sollicitudin metus laoreet sed. Fusce tincidunt felis nec neque aliquet porttitor',
    puntosClabe:'lorem impsum'
})

</script>
<template>
    <section
    v-for="puesto in puestos"
    class="blocks">
          <div class="date">
            <span>{{ puesto.fechaInicio }}</span><span>{{ puesto.fechaFin}}</span>
          </div>
          <div class="decorator">
          </div>
          <div class="details">
            <header>
              <h3>{{ puesto.puesto }}</h3>
              <span class="place">{{ puesto.empresa}}</span>
              <span class="location">{{ubicacion}}</span>
            </header>
            <div>
              <ul>
                <li>{{ puesto.puntosClabe }}</li>
                <li>{{ puesto.descripcion }}</li>
              </ul>
              </div>
          </div>
        </section>
        
</template>