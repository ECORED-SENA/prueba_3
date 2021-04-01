<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(titulo="2. Servicio al Cliente")

  .container.tarjeta.tarjeta--blanca.py-4.p-md-5
    figure
      img(src="@/assets/curso/tema2/principal.jpg")

    //- Los titulos de segundo nivel se usan en h2 por semántica
    h2.h3#t_2_1 2.1 Concepto
    .row.align-items-end
      .col-12.col-lg-6
        p Se entiende por servicio al cliente el conjunto de acciones, procesos y ejecuciones que el cliente espera, además del producto básico, como consecuencia del precio y la imagen. Son las actividades que buscan satisfacer las necesidades, deseos y expectativas  de un cliente.
        p En consecuencia, el objetivo institucional no es solo vender, sino ganar y mantener clientes satisfechos.
        p.mb-0 La experta en calidad del servicio Lisa Ford (2013) dice:
      .col-12.col-lg-6.text-end
        blockquote.fs-2.p-2.ps-3.mt-lg-0.mt-5.fw-light “si no se cuida lo básico,<br> de nada servirán los<br> detalles y los extras”

    //- Los titulos de tercer nivel se usan en h3 por semántica pero .h5 para seguir el estilo planteado en adobe xd
    h3.h5.mt-5.pt-5 2.1.1 Importancia
    .row
      .col-12
        p La atención al cliente se refiere al trato que le damos al cliente cuando interactuamos con él, se trata de una relación con cortesía, rapidez, confiabilidad, información, simpatía, empatía y sensibilidad.
      .col-12.col-lg-6
        p El servicio al cliente, en cambio, es la articulación sistemática y armoniosa de los procesos y acciones que buscan lograr la satisfacción del cliente. El servicio es más que amabilidad y gentileza, es disposición a servir con efectividad.
        p El personal es clave, es necesario que las personas que trabajan para la empresa, entiendan los objetivos del servicio y el por qué se debe alcanzar.

    
    h2.h3#t_2_2 2.2 Características
    .row
      .col-12
        p Las características fundamentales que diferencian a los servicios de los bienes y que debe tener en cuenta.
      .col-12.col-md-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta.tarjeta--color-curso-g.text-center.px-4.py-4
          img.normal(src="@/assets/curso/tema2/bombilla.png")
          span.d-block.fw-bold.mt-3 Intangible.
      .col-12.col-md-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta.tarjeta--color-curso-g.text-center.px-4.py-4
          img.normal(src="@/assets/curso/tema2/cadena.png")
          span.d-block.fw-bold.mt-3 Inseparabilidad.
      .col-12.col-md-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta.tarjeta--color-curso-g.text-center.px-4.py-4
          img.normal(src="@/assets/curso/tema2/feliz.png")
          span.d-block.fw-bold.mt-3 Heterogeneidad.
      .col-12.col-md-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta.tarjeta--color-curso-g.text-center.px-4.py-4
          img.normal(src="@/assets/curso/tema2/dano.png")
          span.d-block.fw-bold.mt-3 Carácter perecedero.

      p.pt-3 Componentes básicos del buen servicio.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/shield.png")
          .col
            p.h6 Seguridad:
            p sólo está bien cubierta cuando podemos decir que brindamos al cliente cero riesgos, cero peligros y cero dudas en el servicio.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/credibilidad.png")
          .col
            p.h6 Credibilidad:
            p va de la mano de la seguridad, hay que demostrar seguridad absoluta para crear un ambiente de confianza, además hay que ser veraces y honestos, no sobre prometer o mentir con tal de realizar la venta.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/charla.png")
          .col
            p.h6 Comunicación:
            p se debe mantener bien informado al cliente utilizando un lenguaje oral y corporal sencillo que pueda entender, si ya hemos cubierto los aspectos de seguridad y credibilidad, seguramente será más sencillo mantener abierto el canal de comunicación cliente – empresa.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/person.png")
          .col
            p.h6 Comprensión del cliente:
            p no se trata de sonreírle en todo momento a los clientes sino de mantener una buena comunicación que permita saber qué desea, cuándo lo desea y cómo lo desea en un esfuerzo por ponerse en su lugar.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/accesibilidad.png")
          .col
            p.h6 Accesibilidad:
            p para dar un excelente servicio debemos tener varias vías de contacto con el cliente, buzones de sugerencias, quejas y reclamos, tanto físicamente como en el sitio web (si se cuenta con él), línea 800 además, hay que establecer un conducto regular dentro de la organización para este tipo de observaciones.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/amabilidad.png")
          .col
            p.h6 Cortesía:
            p atención, simpatía, respeto y amabilidad del personal, como dicen por ahí, la educación y las buenas maneras no pelean con nadie. Es más fácil cautivar a los  clientes si se les da un excelente trato y brinda una gran atención.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/licencia.png")
          .col
            p.h6 Profesionalismo:
            p posesión de las destrezas necesarias y conocimiento de la ejecución del servicio, de parte de todos los miembros de la organización, recuerda que no sólo las personas que se encuentran en el Front line hacen el servicio.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/brain.png")
          .col
            p.h6 Capacidad de respuesta:
            p disposición de ayudar a los clientes y proveerlos de un servicio rápido y oportuno.  Los clientes no tienen por qué rogar para ser atendidos, ni para que sus dificultades o problemas sean solucionados, se debe estar al tanto de las dificultades, para estar un paso adelante de ellas y una buena forma de hacerlo es retro alimentándose con las observaciones de los clientes.
          
      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/fiabilidad.png")
          .col
            p.h6 Fiabilidad:
            p es la capacidad de la organización de ejecutar el servicio de forma fiable, sin contratiempos ni problemas, este componente se ata directamente a la seguridad y a la credibilidad.

      .tarjeta.tarjeta__template--azul-claro.px-4.pt-4.pt-md-1.mb-4
        .row
          .col-12.col-md-3.col-lg-2.d-flex.align-items-center
            img.normal(src="@/assets/curso/tema2/book.png")
          .col
            p.h6 Elementos intangibles:
            p se trata de mantener en buenas condiciones las instalaciones físicas, los equipos, contar con el personal adecuado y los materiales de comunicación que permitan acercarse al cliente.

      h2.h3#t_2_3.mt-5 2.3 Tipos

      p No todos los clientes son iguales cada cliente es único y requiere un trato individualizado y personalizado  sin embargo si existen características comunes que permiten clasificarlos en distintos grupos. Se pueden clasificar por su <strong>origen, nacionalidad, idioma, edad, sexo, la actividad a la que se dedican</strong>, etc. No es una clasificación estricta pero ayuda para <strong>conocer sus necesidades y permitir tratarlo según sus expectativas</strong>, así como ampliar la oferta para ofrecer distintos servicios según su clasificación.

      h3.h5.mb-4 2.3.1 Tipología según la personalidad
      
      .row
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/happy-couple-greeting-financial-consultant.jpg")
            figcaption.position-absolute.bottom-0.text-center Amigable
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/serious-female-model-standing-against-lay-figure-and-rack-of-clothes-holding-hangers-with-clothes-in-one-hand-and-smart-phone-reading-about-discounts-in-clothes-shop.jpg")
            figcaption.position-absolute.bottom-0.text-center Frívolo o mundano
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/happy-woman-in-trendy-red-dress-waving-hand-outdoor-shot-of-positive-beautiful-girl-walking-by-street-cafe.jpg")
            figcaption.position-absolute.bottom-0.text-center Sociales
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/outside-portrait-in-profile-of-model-with-lush-eyelashes-pretty-girl-drinks-cappuccino-and-smiles-shyly.jpg")
            figcaption.position-absolute.bottom-0.text-center Tímidos
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/young-blond-woman-in-clothing-store-back-view-difficult-choice.jpg")
            figcaption.position-absolute.bottom-0.text-center Difícil o exigente
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/beautiful-smart-asian-young-entrepreneur-business-woman-owner-sme-online-checking-product-stock-save-computer-working-home.jpg")
            figcaption.position-absolute.bottom-0.text-center Independiente
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/woman-have-argument-in-cafe.jpg")
            figcaption.position-absolute.bottom-0.text-center Impaciente
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/lady-sitting-on-couch-looking-in-her-shopping-bags.jpg")
            figcaption.position-absolute.bottom-0.text-center Curioso

      h3.h5.mb-4 2.3.2 Tipología según la actitudes

      .row
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/disagreement-between-waiter-and-customer.jpg")
            figcaption.position-absolute.bottom-0.text-center Enfado
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/boss-worrying-because-of-company-bad-annual-report.jpg")
            figcaption.position-absolute.bottom-0.text-center Desconfiado
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/positive-and-smileful-man-stand-and-point-on-black-car-he-looks-at-young-woman-she-is-listening-to-him-model-is-calm-and-peaceful.jpg")
            figcaption.position-absolute.bottom-0.text-center Tranquilo
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/young-beautiful-woman-using-her-smart-watch-while-shopping-at-the-mall-copy-space.jpg")
            figcaption.position-absolute.bottom-0.text-center Con prisa
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/man-choosing-car-and-talking-with-salesperson.jpg")
            figcaption.position-absolute.bottom-0.text-center Introspectivo o metódico
        .col-12.col-md-6.col-lg-4.my-3
          figure.position-relative
            img(src="@/assets/curso/tema2/real-estate-agent-showing-modern-house-to-attractive-couple.jpg")
            figcaption.position-absolute.bottom-0.text-center Elocuente o explosivo

      h2.h3#t_2_4.mt-5.pt-3 2.4 Estándares
        p Se puede definir como un modelo o regla de los requisitos mínimos aceptados para ejecutar un proceso específico, con el fin de asegurar la calidad en la prestación de los servicios. Señalan de una manera clara el comportamiento esperado de los empleados y se utilizan como guías para evaluar su correcto procedimiento y lograr el mejoramiento continuo de los servicios.
        p Requieren que se establezcan con el fin de utilizarlos como parámetros y permite identificar oportunamente las variaciones que se presentan en el desarrollo de los procesos y se apliquen las medidas correctivas de una manera eficaz.

        p manuales de funciones y procedimientos así como los formatos, son herramientas útiles para el establecimiento de los estándares en el hotel.

      h2.h3#t_2_5.mt-5.pt-3 2.5 Protocolos
      h3.h5.mt-1.mb-5 2.5.1 Definición

      Acordeon(claseTarjeta="border-bottom px-4 pb-3" claseTarjetaSelected="tarjeta tarjeta__template--azul-claro px-4 pb-3" iconClose="fa-chevron-down" iconOpen="fa-chevron-up" iconClass="badge rounded-circle border border-gray fs-6" isRowReverse=true)

        div(titulo='1. SALUDE A SU CLIENTE "HAGA QUE ME SIENTA CÓMODO Y A GUSTO"')
          p Recuerde siempre que cuando usted saluda a un cliente y le da la bienvenida, usted está hablando a nombre de la organización para la cual trabaja. Es la empresa quien está saludando al cliente. Usted es la imagen de su empresa. Una persona se forma impresiones de otra en los primeros siete segundos de contacto. Al saludar a su cliente, muéstrele que su presencia es importante para usted. No lo mire como a un estorbo, sino como alguien que es importante. Establezca contacto visual, dele las gracias por haberlo visitado o por haberlo llamado y préstele toda su atención.

        div(titulo='2. CONCÉDALE VALOR A LOS CLIENTES HÁGAME SABER POR QUE PIENSA QUE YO SOY IMPORTANTE"')
          p Cada persona es única e irrepetible. Concédales a las personas el valor que se merecen. Esto se logra siendo consciente del valor que usted se atribuye a sí mismo. A usted le gusta recibir un buen trato. Pues bien, trate a su cliente exactamente de la misma manera como a usted le gustaría ser tratado. Recuerde que gracias a su cliente usted recibe un salario y que su empleo, en última instancia, existe gracias a los clientes.
          p Recuerde que usted no está en su empresa para vender u ofrecer productos o servicios, está allí para ayudar a las personas a obtener los beneficios finales que ofrecen esos productos o servicios. Lograr que se sientan a gusto y hacerles saber que se han dirigido al mejor lugar que podrían haber elegido
          p Al realizar actividades que se centran en otros, usted obtiene grandes recompensas personales, una de ellas es un mayor respeto por sí mismo.
          
        div(titulo='3. PREGUNTE A SU CLIENTE EN QUE LE PUEDE SERVIR, "AVERIGÜE LO QUE QUIERO"')
          p Recuerde siempre que las personas en realidad no necesitan un producto o un servicio. Lo que realmente necesitan es lo que les producirá ese producto o ese servicio, es decir, los beneficios finales que le proporcionará. Los clientes no compran automóviles con el sólo propósito de conducir un vehículo. Lo compran para agradar a sus familias, estar a la altura de sus vecinos u obtener un mayor estatus o mayor comodidad.
          p Por lo tanto, una parte muy importante de su contacto con el cliente debe consistir en averiguar qué necesita, teniendo presente más allá de las cosas que busca satisfacer.
          p Averigüe qué necesita la persona que lo ha llamado o que ha llegado y pregúntele: “En qué puedo servirle?”

        div(titulo='4. ESCUCHE AL CLIENTE "POR FAVOR, ESCÚCHEME Y ENTIÉNDAME"')
          p Son muy pocas las personas que saben escuchar. La mayoría de las personas aparentan escuchar al otro, pero en realidad están procesando internamente la frase que van a pronunciar cuando el otro haga una pausa. Y de esa manera la conversación se convierte en un monólogo compartido.
          p Centre toda su atención en su cliente, escuche sus palabras, escuche su tono de voz y “escuche” su lenguaje corporal. Tenga presente además que su lenguaje corporal sirve de modelo al otro. La mayoría de las personas adoptan inconscientemente el lenguaje corporal de su interlocutor. 
          p Haga el siguiente experimento: la próxima vez que esté con alguien (que no sea un cliente) independientemente de lo que la otra persona esté haciendo con sus brazos, cruce usted los suyos bien apretados. Después observe lo que hace su interlocutor. Lo más probable es que él también cruce los suyos. Pero, ¿qué tiene que ver esto con escuchar?
          p Todo!! <br> Escuchar no se limita sólo a oír las palabras. También consiste en entender qué siente. Es establecer un contacto emocional con la otra persona. Fíjese en su propio lenguaje.

        div(titulo='5. AYUDE AL CLIENTE "AYÚDEME A OBTENER LO QUE QUIERO"')
          p Ya que ha recibido bien al cliente, le ha concedido valor, le ha preguntado en qué puede servirle y le ha escuchado para conocer sus necesidades, llegó el momento de satisfacerlas.
          p Al hacerlo, tenga presente que una persona no compra su producto o servicio por lo que es, sino por la necesidad que le permitirá satisfacer. La persona compra por los beneficios finales. Centre su comunicación en torno de los beneficios que obtendrá el cliente. 
          p Recuerde que gran parte de su trabajo consiste en ayudar a la gente a resolver sus problemas. Llegó el momento de hacerlo. Satisfaga sus necesidades, ayúdele a resolver su problema.

        div(titulo='6. INVITE AL CLIENTE A QUE REGRESE "DIGAME QUE SIEMPRE SERÉ BIENVENIDO"')
          p Un verdadero cliente no es el que le compra un producto o utiliza sus servicios, sino el que lo hace de nuevo, el que regresa. Cuando haya atendido a su cliente, asegúrese de que se lleve una grata última impresión. 
          p Hágase las siguientes preguntas:

          ul
            li ¿Cómo quiere que se sienta alguien después de haber estado en contacto con usted?
            li ¿Qué quiere que diga de usted?
            li ¿Cómo quiere que describa su experiencia con usted?
            li Para lograr una buena última impresión a su cliente
            li Dele las gracias por haber utilizado sus servicios.
            li Invitarlo a regresar pronto.
            li Despierte las ganas de volver.

          p Recuerde que el buen trato influye en la satisfacción del cliente. Las personas van a lugares donde son apreciadas, donde se sienten bienvenidas y valoradas y vuelven a los lugares cuando se les invita a que regresen.

      .tarjeta--color-curso-h.fs-5.fw-bold.my-5.px-3.px-md-5.py-4
        .row.align-items-center
          .col-12.col-sm.text-center.text-md-start
            span SCRIBD (2020/10) Atención al cliente
          .col-12.col-md.text-center.text-md-end
            a.boton--color-sistema-a.rounded-pill.px-5.mt-4.mt-md-0
              span.fw-bold Enlace aquí

      h3.h5  2.5.2 Tipos de protocolo
      p El protocolo <strong>se puede aplicar en distintos campos y sectores de actividad, tanto es así que ello da lugar a la clasificación del mismo atendiendo a las características de la actividad a la que se aplica</strong>, ya que cada precisará de determinados usos, reglas y costumbres (e incluso leyes) específicos. <br/>De acuerdo al entorno en donde se encuentre se presentan  diferentes Protocolos entre ellos:

      .row
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/oficial.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>oficial
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/diplomatico.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>diplomático
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/social.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>social
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/empresarial.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>empresarial
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/universitario.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>universitario
        .col-12.col-md-3.col-lg.mb-4.mb-lg-0
          .text-center.px-4.py-4
            img(src="@/assets/curso/tema2/militar.png")
            span.d-block.fw-bold.mt-3 Protocolo<br>militar

      p <strong>Protocolo empresarial</strong><br/>La estructura organizacional establece los protocolos a utilizar en cada una de las áreas respaldando con manuales de funciones y procedimientos.

      h2.h3#t_2_6 2.6 Cadena de valor
      .row.justify-content-between
        .col-12.col-lg-7
          p Es una herramienta estratégica que se usa para analizar las actividades de una empresa, de esta manera identifica las fuentes para establecer una ventaja competitiva.  <strong>La empresa debe crear valor en los productos y servicios</strong> que ofrece a sus clientes.
          p El concepto se comienza a popularizar hacia 1985 a partir de la publicación del libro <strong>The competitive advantage: creating and sustaining superior performance</strong>, del profesor Michael Porter; quien indica que desde el punto de vista de la competencia el valor es lo que la gente está dispuesta a pagar por lo que se le ofrece. 
          p El valor se mide por los ingresos totales, reflejado por el precio que se cobra del producto y las unidades que logra vender, <strong>una empresa es rentable si su valor sobrepasa los costos que se generan al crear el producto</strong>, y debe analizarse de acuerdo a la posición con respecto a la competencia.
        .col-12.col-lg-4
          figure
            img(src="@/assets/curso/tema2/cadena-de-valor.jpg")
      

      h2.h3#t_2_6 2.7 Momentos de verdad
      figure
        img.momentos.mx-auto.mt-5(src="@/assets/curso/tema2/momentos.jpg")

      .row.mt-5
        .col-12.col-md
          p.fs-3.fw-light <strong>Concepto</strong>: un momento de verdad <strong>es ese preciso instante en que el cliente se pone en contacto con el establecimiento</strong>, y sobre la base de ese contacto se forma una opinión acerca de la calidad del servicio y virtualmente de la calidad del producto.
        .col-12.col-md
          p En la industria hotelera el cliente entra en contacto en cualquier momento, de cualquier forma: <strong>porque visita las instalaciones, recibe la visita de un empleado para ofrecerle los servicios, porque hace una llamada telefónica, o ve su publicidad, ingresa a su página web, remite un correo electrónico</strong>, recibe una comunicación del establecimiento de múltiples maneras.
          p De acuerdo con la calidad de ese contacto el cliente califica el servicio de la entidad, existen muchas posibilidades de que el cliente tenga constantes <strong>"momentos de verdad"</strong>, por esto se debe estar preparado para conseguir que todos y cada uno de ellos sean  agradables para el cliente.
          p <strong>Es en donde se hacen o se pierden clientes</strong>. Es una oportunidad única para fidelizar los clientes y aun acrecentar la base de clientes.

      h2.h3#t_2_6 2.8 Ciclo de servicio
        p Se inicia desde el mismo momento en que el usuario hace la solicitud de un servicio y continua a través de una serie de contactos entre este y el proveedor. El ciclo se cierra cuando el usuario queda satisfecho y dispuesto a regresar.

        p Para determinar el ciclo del servicio, las empresas u organizaciones elaboran un mapa con la secuencia de las etapas y los momentos de la verdad que ocurren durante la prestación de un servicio.

        p <strong>Ciclo del servicio en un hotel</strong><br/> El ciclo de servicio de un huésped en un hotel es un proceso que comienza en el momento en que este decide hospedarse y llama al hotel para hacer la reservación. Este ciclo finaliza cuando el huésped abandona el establecimiento hotelero.

        p Las etapas del ciclo de servicio de hospedaje son las siguientes:

      Acordeon(claseTarjeta="tarjeta tarjeta__template--azul-claro px-4 pb-3" claseTarjetaSelected="tarjeta tarjeta--azul px-4 pb-3" iconClass="badge rounded-circle shadow-sm fs-6 bg-white")

        div(titulo='1.  Reservación.')
          p Puede que la venta se realice o no. Esto  dependerá de la disponibilidad de habitaciones, el tipo de habitaciones, los servicios que se ofrecen, las tarifas y por supuesto la atención al cliente al momento de realizar la reserva.

        div(titulo='2.  Transporte.')
          p Luego viene el servicio de transfer si el hotel lo ofrece. Este es un momento de la verdad crítico porque es el primer contacto directo entre el cliente y el personal del hotel.
          p Este consiste en la búsqueda en el aeropuerto o terminal terrestre al huésped para su mayor comodidad. La información de la hora de llegada, empresa de transporte y demás datos son ofrecidos por el cliente al hotel.

        div(titulo='3. Registro y alojamiento.')
          p Al llegar al hotel, el cliente entra en una nueva fase (otro momento de verdad) para su registro y alojamiento. Durante el momento de la bienvenida el cliente tendrá la primera impresión directa del servicio hotelero.  Es recibido inicialmente por el botones quien lo acompaña a la recepción.
          p La forma como es recibido, el trato, la atención que se presta, el tiempo de espera, etc., también cuentan. <br>Esta etapa comienza con el check-in que verifica y determina las condiciones de la reserva. También incluye la compra concretamente, en caso de que el cliente no posea reserva. Es el llamado front desk, donde también vende el hotel.
          p Una vez el cliente llena la tarjeta de registro, se le asigna la habitación solicitada por el huésped. Se establece la forma de pago, si no se ha hecho el pago previo, y otras garantías.
          p Aquí entran en juego aspectos como la calidad de la habitación, para que el cliente determine la relación costo – beneficio.

        div(titulo='4. Estadía.')
          p Luego viene la etapa de la estadía propiamente, donde el huésped experimentará muchos momentos de verdad con los empleados del hotel: camareras, meseros, botones, empleados administrativos, entre otros. <br>El cliente hace uso de las instalaciones del hotel y comprueba la calidad del servicio que compró. Esta fase comprende todo lo que hace el huésped dentro del hotel: dormir, comer, recrearse, solicitar información y satisfacer o no sus expectativas de compra.

        div(titulo='5.Salida.')
          p El check–out es la última etapa del ciclo del cliente en el hotel. Es cuando se le presenta al huésped su estado de cuenta para su pago final. Esta etapa representa otro momento crítico, pues el cliente verificará que le hayan cargado y cobrado correctamente sus consumos, de acuerdo a lo ofrecido por el establecimiento.  Aquí juega un papel muy importante no solo el cobro correcto sino también el tiempo de espera del cliente.

</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
import Acordeon from '../../components/Acordion'
export default {
  name: 'Tema2',
  components: {
    Acordeon,
    BannerInterno,
  },
}
</script>

<style lang="sass" scoped>
.row
  img
    &.normal
      margin: 0 auto
      height: auto
      width: 50%

    &.momentos
      width: 80%

  figure
    figcaption
      background-color: $color-curso-e
      width: 100%
      border-bottom-left-radius: 10px
      border-bottom-right-radius: 10px
</style>
