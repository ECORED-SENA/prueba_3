<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(titulo="3. Comunicación")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    h2.h3#t_3_1 3.1 Definición
    p La comunicación es un proceso que consiste en la transmisión e intercambio de mensajes entre un emisor y un receptor. La palabra deriva del latín comunicación que significa compartir, participar en algo o poner en común.
    p Los elementos que participan son los siguientes:

    //- Tarjetas definicion
    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/emisor.png")
          .col
            p <strong>Emisor:</strong> Es quien transmite el mensaje.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/receptor.png")
          .col
            p <strong>Receptor:</strong> Es el que recibe el mensaje.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/codigo.png")
          .col
            p <strong>Código:</strong> es el conjunto de signos que serán utilizados para crear el mensaje (palabras, gestos, símbolos).

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/mensaje.png")
          .col
            p <strong>Mensaje:</strong> es la información o conjunto de datos que se transmiten.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/canal.png")
          .col
            p <strong>Canal de comunicación:</strong>  es el medio físico que se utiliza para enviar el mensaje.  Ejemplo : teléfono, televisión, internet, el propio aire, etc.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/ruido.png")
          .col
            p <strong>Ruido:</strong>  son todas las distorsiones que pueden influir en la recepción del mensaje original, y pueden ser tanto del emisor, como del canal o del receptor.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3.align-items-center
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/retroalimentacion.png")
          .col
            p <strong>Retroalimentación o feedback:</strong>  en una primera instancia, es la respuesta del receptor hacia el mensaje recibido. Si posteriormente el emisor responde a lo enviado por el receptor, también se considera retroalimentación.

    .tarjeta--color-curso-i.px-4.pt-4.pt-md-1.mb-4
        .row.py-md-3
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema3/contexto.png")
          .col
            p <strong>Contexto:</strong>  son las circunstancias en las que se desarrolla el proceso de comunicación. Tienen influencia directa en la interpretación del mensaje (el lugar en donde se desarrolla la comunicación, la motivación de la comunicación, contexto social, etc.)
    p El proceso comunicativo es esencial para la vida en sociedad: permite que los seres humanos se expresen y compartan información entre sí, establezcan relaciones, lleguen a acuerdos y sean capaces de organizarse.

    .tarjeta--color-curso-h.fs-5.fw-bold.my-5.px-3.px-md-5.py-4
      .row.align-items-center
        .col-12.col-sm.text-center.text-md-start
          span Raúl Villanueva López (2017) Comunicación y atención al cliente en hostelería y turismo.
        .col-12.col-md.text-center.text-md-end
          a.boton--color-sistema-a.rounded-pill.px-5.mt-4.mt-md-0
            span.fw-bold Ebooks aquí

    h2.h3.pt-5#t_3_2 3.2. Tipos de comunicación.
    .tarjeta.tipos-background.p-5.my-4
      .row
        .col-12.col-lg-6
          p.fs-4 La comunicación puede llevarse a cabo de diferentes maneras:<br><strong>Verbal</strong> utiliza un lenguaje o idioma.<br><strong>No verbal</strong> se vale de gestos, lenguaje corporal o signo no lingüísticos.

    h3.h5 3.2.1. Lenguaje verbal
    p Se refiere a la comunicación que se vale de la palabra para dar el mensaje, es la principal forma de comunicación que se utiliza. Puede ser oral o escrita

    .row
      .col-12.col-lg.me-lg-5
        h4.h5 3.2.1.1. Comunicación oral:
        figure.my-4
          img(src="@/assets/curso/tema3/oral.jpg")
        p es el intercambio de mensajes a través del habla. La voz juega un papel muy importante en nuestro contacto con el cliente.  Debemos ser directos al hablar. Evitar <strong>"muletillas o gaguear"</strong> Y sobre todo, evitar la voz postiza o fingida. La presentación personal, el espacio adecuado para atender al cliente y mantener un contacto visual.
      .col-12.col-lg.ms-lg-5
        h4.h5 3.2.1.2. Comunicación escrita:
        figure.my-4
          img(src="@/assets/curso/tema3/escrita.jpg")
        p en este caso, el proceso comunicacional ocurre a través del lenguaje escrito.

        p Ejemplo : carta, mensajes de texto, correos electrónicos. 

        p El contenido del mensaje es  riguroso y preciso, lógico y claro aplicando  normas gramaticales y reglas de acentuación.

    h3.h5 3.2.2. Lenguaje no verbal
      p Son todos los gestos que consciente e inconscientemente transmitimos en nuestras relaciones interpersonales y que dan cuenta de nuestras posiciones acerca de lo que el otro dice o hace.  <strong>Se expresa a través del lenguaje corporal, la proximidad, signos no lingüísticos y sonidos sin palabras.</strong>

    h2.h3#t_3_3 3.3. Técnicas

    Tabs
      div(titulo="Generar confianza")
        .row.align-items-center.p-3.pd-lg-5
          .col-12.col-lg-6.p-md-5.text-center.p-3
            img(src="@/assets/curso/tema3/tab1.jpg")
          .col-12.col-lg-6.p-md-5
            .h2 A 
            p Para que se dé una buena comunicación y generar confianza con el oyente se debe tener convicción, el emisor debe estar convencido y creer lo que está diciendo, de no ser así es posible que el mensaje no llegue al receptor como se piensa y de lo contrario sea interpretado de manera errónea, y no se logrará el objetivo.

      div(titulo="Actitud de escucha")
        .row.align-items-center.p-3.pd-lg-5
          .col-12.col-lg-6.p-md-5.text-center.p-3
            img(src="@/assets/curso/tema3/tab2.jpg")
          .col-12.col-lg-6.p-md-5
            .h2 B
            p Actitud de escucha, es la principal herramienta.  La escucha activa consiste en una forma de comunicación, que demuestra al hablante, que el oyente le está entendiendo.

      div(titulo="Postura y movimientos")
        .row.align-items-center.p-3.pd-lg-5
          .col-12.col-lg-6.p-md-5.text-center.p-3
            img(src="@/assets/curso/tema3/tab3.jpg")
          .col-12.col-lg-6.p-md-5
            .h2 C
            p Postura y movimientos.  La posición física del cuerpo es un reflejo de la  condición mental y del estado de ánimo en el que se encuentra, por esto  influye en la percepción que el o los oyentes pueden tener.
            ul
              li Aprender a moverse con naturalidad y moderadamente.
              li Tener una postura recta y a la vez armoniosa.
              li Las manos deben usarse con movimientos moderados reforzando el contenido del mensaje.
              li Cada gesto o movimiento debe apoyar el significado de lo que se está comunicando, guardar concordancia entre lo que se expresa y lo que hace el cuerpo.

      div(titulo="Los gestos faciales")
        .row.align-items-center.p-3.pd-lg-5
          .col-12.col-lg-6.p-md-5.text-center.p-3
            img(src="@/assets/curso/tema3/tab4.jpg")
          .col-12.col-lg-6.p-md-5
            .h2 D
            p Los gestos faciales generan gran impacto al momento de comunicar, se debe aprender a apoyar el mensaje con la expresión facial.
            ul
              li Mostrar una expresión cordial.
              li Controlar gestos negativos como inseguridad o nerviosismo.
              li Ser moderados con la expresividad.
              li Es importante sonreír, de lo contrario el cliente puede percibir hostilidad.
              li Evitar fingir porque se puede mostrar con el lenguaje no verbal y perderá credibilidad.
              li Se debe establecer contacto visual y la mirada debe reflejar convicción y entusiasmo, esto traslada credibilidad al mensaje.
            p La expresión debe reflejar: cortesía, amabilidad, interés, confianza.

</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
import Tabs from '../../components/Tabs'
export default {
  name: 'Tema3',
  components: {
    BannerInterno,
    Tabs,
  },
}
</script>

<style lang="sass" scoped>
.tipos-background
  background: url("../../assets/curso/tema3/tipos-background.jpg") no-repeat top right
  background-size: cover

@media (max-width: $bp-max-md)
  .tipos-background
    background-image: none
    background-color: #5CD8F1 // Se quema el color en código porque no se usara más
</style>
