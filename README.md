# Proyecto Cloud Computing ACOES

![badget](https://travis-ci.org/jmrodriguez90/ProyectoCCACOES.svg?branch=master)

Este proyecto, a efecto de ser evaluado en la clase de CC, servirá para gestionar las donaciones entre una entidad benéfica y un donante.

[*ACOES,*](http://www.acoes.org) es una iniciativa del padre Patricio Larrosa, sacerdote granadino que tiene alrededor de 46 proyectos de promoción social en Honduras, uno de ellos, las becas de niños de escasos recursos en el cual se basa este proyecto de desarrollo.
La situación de los donantes está en que los abonos que realizan, se envían por medio de la contraparte local de [*ACOES*](http://www.acoes.org) en España, según lalocalidad en que se encuentre el donante y este, no recibe mayor retroalimentación de lo que ha otorgado a su becario.

El proyecto va enfocado en presentar de manera equilibrada las ayudas que diversos donantes  envían a sus becarios en Honduras mediante el registro en una aplicación web que va alimentando una base de datos, y a la vez, existirá una retroalimentación de la administración general de [*ACOES Honduras*](http://www.acoes.org) donde indican haber recibido y otorgado la donación recibida.

El lenguaje a utilizar será Java y se intentará manejar la base de datos en Azure y a lo largo del curso se irán trabajando diversas herramientas de Cloud para maximizar el potencial del proyecto con dichas herramientas.

Este proyecto trabaja bajo licencia GPL, además, está inscrito en el [*Certamen de Proyectos Libres de la UGR 2015-2016*](http://osl.ugr.es/2015/10/01/certamen-de-proyectos-libres-de-la-universidad-de-granada-2015-2016/), pueden verse [aquí](https://docs.google.com/document/d/16UsdUV_XXuPUh-Imz4PSgh-2ES_YaAJpZ8fNrbTVpMA/edit) las bases del [Certamen](http://osl.ugr.es/2015/10/01/certamen-de-proyectos-libres-de-la-universidad-de-granada-2015-2016/)

#**Segundo hito del proyecto CC ACOES**

##**Justificación de uso de Test e Integración Continua**
para efectos de test, se ha decido utilizar [*Mocha*](http://mochajs.org/) por ser, como su slogan lo menciona; simple y muy flexible, el proyecto es trabaja con lenguaje Java y la Integración Continua se realiza en Travis-CI, el cual es un entorno estable y muy confiable para la realización de esto. La integración se realizó a través del archivo .travis.yml, en el que se indica el entorno de programación a utilizar y un archivo build.xml en el que se indican los directorios a integrar.

En el inicio de este README, aparece el [*Badge*](https://travis-ci.org/jmrodriguez90/ProyectoCCACOES.svg?branch=master) correspondiente a la correcta funcionalidad de la integración continua.

[*Desde aquí podrán acceder directamente a la web del proyecto*](http://jmrodriguez90.github.io/ProyectoCCACOES/)
