---
title: Destilación del conocimiento 
subtitle: Tópicos Avanzados en Inteligencia Artificial 
layout: page
hero_image: /curso-2021-2/img/rectoria2_muse.jpg
hero_darken: true
show_sidebar: false
---

# Tema

Una de las razones por las cuales las Redes neuronales funcionan es que dado una cantidad suficiente de neuronas, estas pueden funcionar como un aproximador universal. Para asegurar que la red sea capaz de generalizar se necesita una cantidad importante de datos. Por lo mismo, muchas de las redes que muestran mejor desempeño requieren de bastante computación para ser entrenadas o ejecutadas y muchas veces son incapaces de funcionar en un tiempo razonable si no se cuenta con cómputo de alto rendimiento.

La destilación de conocimiento permite busca reproducir las salidas de una red compleja, usando menos recursos. Pero, abre toda una discusión sobre la certeza que se puede esperar de un modelo entrenado ya no directamente sobre datos ordenados, si no sobre la interpretación que un modelo hace sobre esos datos.

## Material para el aprendizaje

1. [Un tutorial indroductorio del tema.](https://neptune.ai/blog/knowledge-distillation)
2. [Otro tutorial bastante amable](https://www.v7labs.com/blog/knowledge-distillation-guide) aunque con muchos anuncios insertados.
3. [El artículo seminal sobre destilación del conocimiento.](https://arxiv.org/pdf/1503.02531v1.pdf) 
4. [Una revisión de 2021](https://arxiv.org/pdf/2006.05525.pdf) que se ve bastante completa.
5. [Destilación del conocimiento en `papers with code`](https://paperswithcode.com/task/knowledge-distillation)
6. Una [presentación](http://xcfeng.net/res/presentation/Knowledge%20Distillation.pdf) algo rara pero muy completa.

## Actividades de aprendizaje

1. Destilación del conocimiento [en Keras](https://keras.io/examples/vision/knowledge_distillation/) (tambien [esta receta](https://keras.io/examples/keras_recipes/better_knowledge_distillation/)) y un proyectito en [pyTorch](https://github.com/haitongli/knowledge-distillation-pytorch) con su respectivo [reporte](https://cs230.stanford.edu/files_winter_2018/projects/6940224.pdf). 
2. Un [modulo de pythorch](https://github.com/yoshitomo-matsubara/torchdistill) en etapa mas o menos experimental.

## Proyecto

Vamos a usar un modelo grande proveniente del CERN para destilar un modelo con la menor pérdida posible.

