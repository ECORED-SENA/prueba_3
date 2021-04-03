<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(titulo="1. Usuarios servicios turísticos")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    figure
      img(src="@/assets/curso/tema1/tema1-main.jpg")

    p Los usuarios turísticos son aquellas personas físicas que utilizan los establecimientos, instalaciones y recursos turísticos, o reciben los bienes y servicios que ofrecen las empresas y profesionales del sector. 

    p Los usuarios turísticos tienen una serie de derechos y obligaciones reguladas por ley. 

    h2.h3#t_1_1.mt-5.pt-3 1.1 Tipos
    p Podemos clasificar los usuarios turísticos de la siguiente manera

    h3.h5.mt-5 1.1.1 Clientes 
    .row.justify-content-between
      .col-12.col-md-6
        p Un cliente es toda persona que tiene una necesidad latente o sentida, que busca un producto o servicio con ciertos requisitos y condiciones para poder satisfacerla totalmente.

        p Un cliente, desde el punto de vista de la economía, es una persona que utiliza o adquiere, de manera frecuente u ocasional, los servicios o productos que pone a su disposición un profesional, un comercio o una empresa.

        p A la hora de reservar un hotel hay varios perfiles de usuarios. <strong>Cada uno de ellos reserva un hotel movido por unas razones y busca algo que no es, necesariamente</strong>, lo que buscan los demás. 

        p El turista, viaja con un itinerario, con cierto nivel de seguridad debe realizar su viaje en un periodo con fecha de inicio y final establecidos; <strong>sale con todo previsto y perfectamente organizado desde casa. Reservas de hoteles y  transporte confirmadas, visitas a realizar</strong>;  intenta gozar de un área de confort durante el viaje que no lo separe demasiado de sus hábitos. El turista tiene una expectativa alta por la nueva experiencia y un bajo nivel de involucramiento en la comunidad local.
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/clientes.jpg")

    h3.h5.mt-5 1.1.2  Viajeros
    .row.justify-content-between
      .col-12.col-md-6
        p Viajar es trasladarse de un lugar a otro utilizando cualquier medio de transporte y hacer turismo es realizar la actividad viajera por placer.

        p Un viaje puede hacerse por muchas circunstancias, mientras que el turismo está siempre asociado al ocio y a la diversión.  El viajero, aunque haga cierta planificación de su viaje, se preocupará menos de estas certidumbres con la expectativa  que hará lo que los acontecimientos viajeros le traigan día a día, ya que sabe que para vivir su experiencia ha de salir de su rutina diaria.

        p El viajero maneja la más alta expectativa por lo desconocido, lo exótico y lo nuevo; generalmente busca involucrarse en la comunidad local y entender otras formas de vida; el viajero no lleva un itinerario específico o un plan trazado. 
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/viajeros.jpg")

    .tarjeta--color-curso-h.fs-5.fw-bold.my-5.px-3.px-md-5.py-4
      .row.align-items-center
        .col-12.col-sm.text-center.text-md-start
          span Entorno turístico (2020/10) Diferencias entre un turista y un viajero. 
        .col-12.col-md.text-center.text-md-end
          a.boton--color-sistema-a.rounded-pill.px-5.mt-4.mt-md-0
            span.fw-bold Ebooks aquí

    h3.h5.mt-5.pt-4 1.1.3 Pasajeros
    .row.justify-content-between
      .col-12.col-md-6
        p Término que se refiere a una persona que realiza un viaje en algún tipo de medio de transporte, sin ser quien lo conduce y sin formar parte de la tripulación. Los  turistas suelen convertirse en pasajeros al comienzo y al final de sus vacaciones ya que, para llegar al destino elegido, lo normal es que se trasladen en un vehículo contratado.
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/pasajeros.jpg").

    h2.h3#t_1_2 1.2 Características
    p En todo el mundo la mayor cantidad de viajeros provienen de las ciudades, con el deseo de salir fuera de la ciudad durante sus periodos de vacaciones, <strong>en beneficio del individuo y por diferentes motivaciones: culturales, de salud, deseo de cambio, de compras, descanso, práctica de deporte, conocer, o pasarla bien en todo sentido.</strong>

    p El turista experimenta una variación en su conducta habitual, sin alterar su carácter o forma de ser , el viajar predispone en forma especial a todo lo que pueda experimentar, <strong>esto reside en la curiosidad</strong>, incrementándose la sensibilidad y la capacidad de recepción.

    //- Tarjeta Naranja
    .custom-alert.container.tarjeta.tarjeta__template--naranja.px-3.pt-4.pb-2.px-sm-5.mt-5
      .float-image.d-none.d-lg-block
        img.auto(src="@/assets/curso/tema1/advertir.png")
      .ms-lg-5.ps-lg-5 
        span.d-block.h3.lh-sm.ms-lg-5 En turismo la promoción solo es realmente efectiva al ofrecer alternativas de un mismo viaje.

    h2.h3#t_1_3 1.3 Teoría de las necesidades
    .row.justify-content-between
      .col-12.col-md-6
        p El psicólogo Abraham H. Maslow (1983)  afirmó que todos los seres humanos están perpetuamente deseando y que sus necesidades son psicológicas y sociales. Estableció una jerarquía de las necesidades y determinó que a medida que les de un orden inferior se satisfacen, surgen otras de rango superior. Esto se justifica porque la percepción de los deseos no es absoluta, es decir, cuanto mayor es la satisfacción de un deseo, menor es la necesidad de satisfacerlo.

        p Al identificar cinco grupos de necesidades básicas, Maslow construyó una pirámide ordenando jerárquicamente según las necesidades.
      
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/teoria.jpg")

    .tarjeta--color-curso-l.py-2.px-4.m-3.mt-5
      p <strong>Necesidades básicas o fisiológicas:</strong><br/>busca crear y mantener una situación de orden y seguridad física (salud), económica (ingresos), necesidad de vivienda, etc.
    .tarjeta--color-curso-l.py-2.px-4.m-3
      p <strong>Necesidades de seguridad:</strong><br/>son las únicas inherentes en toda persona, básicas para la supervivencia del ser humano como respirar, alimentarse, vestirse, sexo, etc.
    .tarjeta--color-curso-l.py-2.px-4.m-3
      p <strong>Necesidades sociales:</strong><br/>implica el sentido de pertenencia a un grupo social, familiar, de amigos, pareja, etc.
    .tarjeta--color-curso-l.py-2.px-4.m-3
      p <strong>Necesidades de estima o reconocimiento::</strong><br/>como la confianza, la independencia personal, las metas financieras, la reputación.
    .tarjeta--color-curso-l.py-2.px-4.m-3
      p <strong>Necesidades de autorrealización:</strong><br/>sólo puede ser satisfecho una vez cuando todas las demás necesidades han sido alcanzadas de manera suficiente. Es la sensación de haber llegado al éxito personal.

    p Utilizando este modelo de pirámide las empresas conocen los comportamientos de los individuos y por lo tanto lo que motiva a los clientes a comprar, así se utiliza como instrumento para que compren lo que se vende cubriendo y satisfaciendo una necesidad y no vayan a la competencia.

    .row.mt-5.justify-content-between
      .col-12.col-lg-5
        blockquote.p-3.bg-color-curso-h
          p.fs-3 Philip Kotler (1983) define las necesidades como <strong>"una sensación de carencia de algo, un estado fisiológico o psicológico"</strong>. 

          p.fs-3 Necesidad, deseo y la demanda turística. 
      .col-12.col-lg-6
        p Ya entendemos a que se refiere <strong>"la necesidad"</strong>, el deseo se conoce como la forma en que una persona expresa la manera de satisfacer una necesidad en la que inciden varios factores como las características personales, su educación y creencias, entorno cultural social y ambiental, los estímulos de marketing y su capacidad adquisitiva.

        p Un deseo se convierte en demanda cuando una persona, canaliza el deseo para realizar una petición concreta de un producto.

        p La demanda turística <strong>es el conjunto de bienes y servicios que los turistas están dispuesto a adquirir en un determinado destino, incluye el consumo y la experiencia de lugares</strong>, su motivación principal recae en el destino turístico, entre los factores que influyen en esta demanda son el poder económico, disponibilidad de tiempo y otros factores que le motiven.

    .row.mt-5
      .col-10.mx-auto.my-5
        figure
          img(src="@/assets/curso/tema1/mapa-necesidades.jpg")

    p La variación de los precios en relación con destinos y servicios similares, la falta de opciones de transporte y la diversidad de productos turísticos, entre otros, pueden afectar la demanda turística por un determinado destino.

    p Schnarch Kirberg, Alejandro. (2017) Marketing de Fidelización. 

    h2.h3#t_1_4 1.4 Requerimientos y solicitudes especiales
    p El personal en los alojamientos siempre está dispuesto a enfrentar determinadas situaciones especiales en las cuales sus decisiones son la clave para resolver eficientemente los problemas generados.

    .row
      .col-12.col-md-6
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos1.png")
          .col
            p Algunas posibles situaciones, entre otras.
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos2.png")
          .col
            p Flexibilidad en los horarios de entrada y salida.
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos3.png")
          .col
            p Salas de juntas para optimizar las reuniones de negocios.
      .col-12.col-md-6
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos4.png")
          .col
            p Trato personalizado con el huésped.
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos5.png")
          .col
            p Ubicación del establecimiento y fácil reserva.
        .row.my-4
          .col-2
            img.auto(src="@/assets/curso/tema1/requerimientos6.png")
          .col
            p Conectividad inalámbrica o wifi.

    p El establecimiento siempre estará en disposición de cumplir los requerimientos pero dentro de medidas y políticas establecidas que permitan al huésped recibir lo que requiere y que al mismo tiempo no implique inversiones extraordinarias.

    h2.h3#t_1_5.mt-5.mb-4 1.5 Motivaciones de compra
    .row.justify-content-between.align-items-end
      .col-12.col-md-6
        p Los consumidores se ven influidos por una serie de factores y de condicionantes a la hora de elegir su destino para hacer turismo.  

        p La demanda se ve afectada por los valores del individuo y su clase social. La mentalidad y el comportamiento van a marcar y definir los productos turísticos: <strong>el placer de viajar, los negocios, las condiciones de vida, el tiempo de ocio, los recursos financieros, el acceso a nuevas tecnologías</strong>, etc. 

        p El producto turístico enmarca un espacio de satisfacción de necesidades, <strong>los turistas llegan con una serie de expectativas sobre lo que pueden hacer por ellos</strong> (Ford 2001), por otro lado, el turista juzga los servicios a través de lo que percibe y cómo percibe.
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/motivaciones.jpg")


    h2.h3#t_1_6.mt-5.pt-4.mb-4 1.6 Hábitos y tendencias de consumo
    figure.mb-5
      img(src="@/assets/curso/tema1/habitos.jpg")
    
    p El objetivo final de la industria hotelera tiene que ser conocer las expectativas y necesidades de cada turista y buscar mecanismos que permitan cubrirlas e intentar superarlas.

    p El problema al que se enfrentan los hoteles, <strong>es que estas expectativas de los clientes van evolucionando, por lo cual tienen que analizar constantemente las tendencias y nuevas necesidades</strong>.  Para esto hay que realizar un análisis del comportamiento de los clientes, no como turistas sino como consumidores, esto permite identificar sus patrones de comportamiento y permitirá definir qué productos y experiencias les satisfacen.

    p Cuanto más se conozca el cliente más fácil será:

    ul
      li Cubrir sus expectativas o deseos, intentado superarlos.
      li Ofrecerle productos que se adapten a su perfil y aumentar su gasto dentro de la industria turística.
      li Fidelizarlo a la empresa.

    p Seis megatendencias en la industria hotelera, como son las demandas del turista

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 1
        .col-12.col-md.px-5
          p Si la reserva se confirma, se marca la casilla correspondiente (OK).

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 2
        .col-12.col-md.px-5
          p La experiencia recibiendo <strong>el servicio en áreas como reservas, recepción y dentro del mismo hotel sea sencilla, cómoda y rápida</strong>. También se puede hacer uso de la geolocalización para enviarles información o notificaciones sobre productos basados en el lugar donde se encuentre el cliente.

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 3
        .col-12.col-md.px-5
          p Los consumidores buscan <strong>marcas que se identifiquen con ellos de una manera emocional</strong>, que genere sentimientos con cualidades que les generen seguridad.  El toque personal ayuda al establecimiento a posicionarse.

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 4
        .col-12.col-md.px-5
          p La tecnología se ha vuelto universal y afecta directamente la hotelería en diversas formas, <strong>los turistas se sienten muy bien con la variedad que esta le ofrece como información instantánea</strong>, herramientas de compra, canales de venta, opciones de productos y variedad de precios.

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 5
        .col-12.col-md.px-5
          p Los hoteles tienen que ser creativos con las políticas de precios, no necesariamente bajando los precios sino ofreciendo valor añadido.

    .tarjeta--color-curso-m.my-3
      .row
        .col-12.col-md-3.col-lg-2.d-flex.align-items-stretch
          div.bg-color-curso-g.px-5.py-1.d-flex.align-items-center.border-left-radius-20
            span.h1.my-0 5
        .col-12.col-md.px-5
          p No se puede centrar en ofrecer un producto por las características específicas del cliente como su nivel cultural entre otros, sino enfocarlo a sus deseos y motivaciones concretas.


    .tarjeta--color-curso-h.fs-5.fw-bold.my-5.px-3.px-md-5.py-4
      .row.align-items-center
        .col-12.col-sm.text-center.text-md-start
          span Sabre publica en el siguiente enlace
        .col-12.col-md.text-center.text-md-end
          a.boton--color-sistema-a.rounded-pill.px-5.mt-4.mt-md-0
            span.fw-bold Enlace aquí


    h2.h3#t_1_7.mt-5 1.7 Incidencia de la cultura en el comportamiento
    p En gran parte, las decisiones de consumo y la forma de procesar la información se ven afectadas por la cultura. La cultura se refiere a las conductas típicas o esperadas, las normas e ideas que caracterizan a un grupo de personas; puede ser una poderosa influencia en todos los aspectos del comportamiento humano.
    .row.justify-content-between
      .col-12.col-md-6
        p Cuando se observan grupos que se perciben similares a sus propios gustos se les considera como grupos de referencia, es decir, personas cuyos valores y opiniones comparten y respetan.

        p Su edad, su género y  formación académica pueden afectar, ejemplo, en lo que pueden ser unas buenas vacaciones.  Otros factores como la clase social y composición familiar, aun sus valores, personalidad y estilo de vida tiene un efecto en la toma de decisiones en el momento de realizar turismo o utilizar los establecimientos de servicios hoteleros.
      .col-12.col-md-5
        img(src="@/assets/curso/tema1/incidencia.jpg").
</template>

<script>
import { mapActions } from 'vuex'
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema1',
  components: {
    BannerInterno,
  },
  mounted() {
    this.increment()
    setTimeout(() => {
      this.decrease()
    }, 3000)
  },
  methods: {
    ...mapActions(['increment', 'decrease']),
  },
}
</script>

<style lang="sass" scoped></style>
